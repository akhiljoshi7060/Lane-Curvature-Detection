# Lane Curvature Detection with BezierLaneNet

A deep learning-based **lane detection and curvature estimation system** that leverages **Bezier curve representations** for accurate and robust lane prediction. The project combines research experiments on lane curvature detection with a full PyTorch-based implementation (BezierLaneNet), providing both Jupyter notebook explorations and deployable training/inference pipelines.

---

## ✨ Features

* Lane detection using **Bezier curve regression**
* Lane **curvature estimation and metrics** from research notebooks
* Backbone models: **ResNet, Custom ResNet**
* Custom **DSD loss function** for better curve fitting
* Training and inference pipelines included (`train.py`, `inference.py`)
* Visualization tools for datasets, predictions, and curvature metrics
* Modular code structure (models, losses, utils)

---

## 📂 Project Structure

* `notebooks/` → Research notebooks for lane curvature detection and experiments

  * `Bezier_Curve_Synthetic_Dataset_Final.ipynb`
  * `Bezier_With_Metrics_TuSimple_Dataset.ipynb`
  * `ENet_With_Metrics.ipynb`
* `train.py` → Train the BezierLaneNet model on a dataset
* `inference.py` → Run inference on new images/videos
* `models/` → Model definitions (ResNet, custom backbones)
* `losses/` → Custom loss functions (Bezier curve-specific)
* `utils/` → Dataloader, visualization, and helper utilities
* `images/visualization.png` → Example output visualization
* `requirements.txt` → Project dependencies
* `README.md` → Project documentation
* `LICENSE` → MIT License

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/Lane-Curvature-Detection-BezierLaneNet.git
cd Lane-Curvature-Detection-BezierLaneNet
```

2. Create a Python environment and install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Training (BezierLaneNet)

```bash
python train.py --dataset <path_to_dataset> --epochs 50 --batch_size 16
```

### Inference (BezierLaneNet)

```bash
python inference.py --image <path_to_image> --weights <path_to_weights>
```

### Research Experiments

Open the Jupyter notebooks under `notebooks/` to explore lane curvature metrics, synthetic dataset experiments, and TuSimple dataset evaluations.

---

## 📊 Dataset

* Supports lane detection datasets like **TuSimple**
* Utilities in `utils/dataloader.py` for dataset loading
* Custom visualization scripts in `utils/visualize_dataset.py`

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
