Cloud Motion Prediction — Mini Spatio-Temporal ML Project
This project predicts the next cloud image frame in a short sequence using a ConvLSTM-based spatio-temporal deep learning model.
It demonstrates understanding of temporal modeling, training pipelines, loss functions, and visualization, built fully in Google Colab.
Project Highlights:
Implemented a ConvLSTM architecture in PyTorch for cloud-motion forecasting
Trained using L1 + SSIM loss for sharper structure retention
Created a synthetic cloud-motion dataset for pipeline validation
Produced predicted vs actual comparison visuals
End-to-end notebook included for complete reproducibility
Beginner-friendly but demonstrates real ML/EO capability
Files in this repository:
File	Description:
cloud_motion_project.ipynb	- Full Colab notebook (data generation, model, training, inference)
predicted_final.png	- Predicted next cloud frame
real_final.png -	Ground-truth next frame
cloud_mini_improved.pth -	Trained model weights
Tech Stack:
Python
PyTorch
NumPy
Matplotlib
Google Colab
Author:
Sanya Gupta
B.Tech Geoinformatics, NSUT
Email: guptasanya840@gmail.com
