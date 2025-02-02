# ModelDeployment
 
# Disaster Tweet Prediction

Natural Language Processing with Disaster Tweets aims to classify messages on Twitter that describe actual emergencies versus non-emergencies, even when they use disaster-related language. Using natural language processing (NLP) and machine learning, this project processes and analyzes text data to effectively distinguish between true disaster-related tweets and non-disaster tweets.

## Features

- **Predict Disaster Tweets** Using tweets about real and disaster events.
- **Interactive web form** to input the necessary data and get the tweet prediction in real-time.
- Uses a trained **Bert and LSTM model** for predicting wether the Tweet is real or not.

## Tech Stack

- **Backend**: FastAPI (Python)
- **Frontend**: HTML, JavaScript (Vanilla)
- **Machine Learning**: LSTM and Bert model
- **Deployment**: Can be deployed on Heroku or any server supporting FastAPI.

## Requirements

- Python 3.7+
- FastAPI
- Pandas
- Uvicorn (for running the FastAPI server)
- Scikit-learn
- Python-multipart
- Pydantic
- Tensorflow
- Starlette
- Nlkt
- Torch
- Transformers

## Setup
Open your Windows Terminal and follow the next steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Esteebaan23/LSTM_Bert_Deployment.git
   
2. Create Viirtual environments
   ```bash
   python -m venv myenv
   myenv\Scripts\activate
3. Replace the data file path in app.py according to your local file path
   ```bash
   cd + "Your path"
4. Install dependencies
    ```bash
    pip install -r requirements.txt

5. If for some reason scikit-learn, uvicorn and python-multipart don't get installed try:
   ```bash
   pip install scikit-learn uvicorn python-multipart

6. Then, in your cmd paste:
   ```bash
   uvicorn app:app --reload
   
7. Open the deployment at: http://127.0.0.1:8000
