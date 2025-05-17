
# 🩺Disease Prediction web app

A Flask web app predicting diseases from user symptoms using a trained machine learning model.



## Features
- Predicts disease based on user-selected symptoms
- Responsive and clean UI using Tailwind CSS
- Trained on synthetic and noisy data to prevent overfitting
- Modular folder structure for better scalability
- Includes developer information and project credits

## Setup Instructions

1. Clone repository:-

    https://github.com/arunk0508/Disease-Prediction.git

2. Create and activate virtual environment:-

 ``` python -m venv venv ```

 ```source venv/bin/activate  # or venv\Scripts\activate on Windows```

3. Install Dependencies:-

   ``` pip install -r requirements.txt```

4. Run the app:-

 ```python app.py```

5. Access it at:-

    http://127.0.0.1:10000
## Model Info

- Model: Random Forest Classifier

- Input: One-hot encoded vector of selected symptoms

- Training: Trained on synthetic + noisy data for generalization

- Accuracy: Reduced from 98% to ~68% to reflect real-world prediction behavior
## License

[MIT](https://choosealicense.com/licenses/mit/)


##  System Architecture Overview

```
User Input (Symptoms)
        │
        ▼
 One-Hot Encoding
        │
        ▼
 ML Model (Random Forest)
        │
        ▼
  Disease Prediction
        │
        ▼
Display Result on Web UI
```
