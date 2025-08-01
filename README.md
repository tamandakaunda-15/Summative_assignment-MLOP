# Summative_assignment-MLOP

# ML Pipeline: Image Classification Project

###  Project Overview

This project demonstrates the **end-to-end Machine Learning process** for image classification using the CIFAR-10 dataset. It follows a full ML pipeline structure, including:
- Data acquisition and preprocessing
- Model training and evaluation
- API development for predictions and retraining
- UI integration
- Cloud deployment and performance simulation with Locust

###  Directory Structure
summative-assignment-mlops/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│
├── notebooks/
│   └── 01_model_training.ipynb
│
├── scripts/
│   ├── preprocess.py
│   ├── train.py
│   └── evaluate.py
│
├── streamlit_app/
│   └── app.py
│
├── requirements.txt
├── README.md
└── .gitignore



###  Features

-  **Image Classification** using CNN
-  Model Evaluation with accuracy, precision, recall, F1-score
-  Retraining Trigger with new data uploads
-  Predict single datapoint from image via API
   Visualization of features and model status
-  Deployed to [CLOUD PLATFORM NAME]
-  Simulated load test with Locust



###  Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/ml_pipeline_project.git
cd ml_pipeline_project


2. ** Install Dependencies

```bash
pip install -r requirements.txt
Download & Prepare Dataset

3. **Run the preprocessing script to save CIFAR-10 as image folders:

python src/preprocessing.py


4. **Train the Model

Use the notebook or model.py to train and save the model.

5. **Start the API Server

uvicorn src.prediction:app --reload

6. **Access the UI (if built) or test API using Postman/cURL

7. **Run Load Testing with Locust
locust -f locustfile.py

Then go to http://localhost:8089 and start simulation.

 Project Links
 Video Demo: [YouTube Link Here]

 Live App URL: [Deployed App URL]

 Load Testing Results: See notebook/ml_pipeline.ipynb or demo video
