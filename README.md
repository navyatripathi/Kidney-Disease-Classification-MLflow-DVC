# Kidney Disease Classification 🔬

An end-to-end deep learning project for classifying kidney tumors using transfer learning with VGG-16. This project integrates MLflow for experiment tracking and uses Docker for containerized deployment on AWS, delivering a scalable, secure, and cloud-ready solution.

---

##  Key Features

- **High Accuracy Model**: Achieved 97% prediction accuracy using a pre-trained VGG-16 architecture fine-tuned for medical imaging.
-  **Transfer Learning**: Leveraged VGG-16 for efficient feature extraction and robust classification.
-  **MLflow Integration**: Tracked experiments, hyperparameters, metrics, and model versions for reproducibility and performance tuning.
-  **Dockerized Deployment**: Packaged the entire pipeline using Docker for seamless deployment.
-  **AWS Deployment**: Hosted the containerized solution on AWS to ensure scalability and reliability.

---

##  Tech Stack

- **Frameworks**: TensorFlow / Keras, Scikit-learn
- **Experiment Tracking**: MLflow
- **Deployment**: Docker, AWS EC2
- **Languages**: Python
- 
---

## Project Structure

```bash
├── data/                  # Dataset and preprocessing scripts
├── models/                # Trained models and checkpoints
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── src/                   # Source code: training, evaluation, utils
├── Dockerfile             # Docker configuration
├── requirements.txt       # Python dependencies
├── mlruns/                # MLflow tracking directory
├── app.py                 # Flask API for serving the model (optional)
└── README.md              # Project documentation
