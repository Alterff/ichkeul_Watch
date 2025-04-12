🚀 ML Classification Project
-------------------------------------------
My first machine learning project presents a binary classification pipeline to assess the environmental suitability of lakes for species in the Ichkeul region, utilizing both traditional ML and deep learning techniques.

📁 Dataset
--------------------------------------------
    Sourced from center Sidi Thabet Lab , with 12 input features and 1 target column (Decision).

    Preprocessing includes cleaning unused columns and mapping target values from categorical to binary.

🔄 Workflow Overview
-------------------------------------------
    Preprocessing

        Data cleaning, encoding, splitting, and standardization to prepare for modeling.

    Modeling Approaches

        Logistic Regression: A baseline model trained using scikit-learn.

        Neural Network: A multi-layer feedforward model built using TensorFlow/Keras.

    Evaluation

        Accuracy and loss measured on test data.

        Visualization of model performance and training progress.

        Confusion matrix analysis for classification insights.

    Prediction & Inference

        Demonstrates how to preprocess and predict for new input samples.

    Model Persistence

        Model and scaler saved using pickle for future use without retraining.
