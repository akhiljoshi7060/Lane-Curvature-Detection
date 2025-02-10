# Lane Curvature Detection Using Bezier Curves and ENet Segmentation

This project implements **Bezier curve-based lane detection** techniques for accurate curvature estimation in autonomous driving scenarios. It benchmarks performance against **ENet segmentation models** and utilizes the **TuSimple dataset** to improve lane detection accuracy.

## Features
- **Bezier Curve Lane Detection:** Models lane lines with cubic Bezier curves for smoother lane curvature estimation.
- **Performance Benchmarking:** Compared against ENet segmentation models to validate performance improvements.
- **Dataset:** Utilizes the TuSimple dataset, improving lane detection accuracy by 15%.
- **Real-Time Processing:** Optimized algorithms to ensure real-time performance for autonomous navigation.

## Project Structure
Lane-Curvature-Detection/ ├── notebooks/ │ ├── Bezier_Curve_Synthetic_Dataset_Final.ipynb │ ├── Bezier_With_Metrics_TuSimple_Dataset.ipynb │ └── ENet_With_Metrics.ipynb ├── presentation/ │ └── EE243_Computer_Vision_Project_Daksh_Akhil.pptx └── README.md


## How to Run

1. Clone the repository:

   git clone https://github.com/akhiljoshi7060/Lane-Curvature-Detection.git
   cd Lane-Curvature-Detection

2. Run the Jupyter notebooks:

jupyter notebook notebooks/Bezier_With_Metrics_TuSimple_Dataset.ipynb
