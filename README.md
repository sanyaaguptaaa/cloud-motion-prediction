# cloud-motion-prediction
This project predicts the next cloud image frame in a short time-series using a ConvLSTM-based spatio-temporal model built in PyTorch.
It is designed as a compact ML + Earth Observation demo for internships and portfolio use.
Project Features:
Generates cloud-motion sequences (synthetic dataset for demo)
Uses a ConvLSTM architecture for temporal prediction
Trained with L1 + SSIM loss for better structure retention
Outputs predicted vs actual next frames
Fully reproducible in Google Colab
Beginner-friendly but technically solid ML project
| File                         | Description                                           |
| ---------------------------- | ----------------------------------------------------- |
| `cloud_motion_project.ipynb` | Full Colab notebook (training, model, visualizations) |
| `predicted_final.png`        | Model’s predicted next cloud frame                    |
| `real_final.png`             | Actual next frame                                     |
| `cloud_mini_improved.pth`    | Saved trained model weights                           |
Tools Used:
Python
PyTorch
Matplotlib
NumPy
Google Colab
Author
Sanya Gupta
B.Tech Geoinformatics, NSUT
Email: guptasanya840@gmail.com
