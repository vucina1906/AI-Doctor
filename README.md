- Project inspiration was found in scientific article "Disease prognosis using machine learning algorithms based on new clinical dataset", link of article https://dergipark.org.tr/en/download/article-file/2818524. 

- The project began with recognizing a common issue: people often experience symptoms and want quick answers about their health concerns. It can be challenging to differentiate between various diseases, especially when symptoms overlap. My goal was to provide a convenient solution for users to input their symptoms and receive potential diagnoses.

- I developed a web app that allows users to enter a list of symptoms they are experiencing. The app then uses a pre-trained Support Vector Machine Classifier model to predict the most likely disease based on the provided symptoms. Here's how it works:

- The Solution
* Symptom Input: Users enter their symptoms through a user-friendly interface (chose one or more symptoms from the dropdown menu). The web app supports a wide range of symptoms, making it versatile for different scenarios.
* Machine Learning Model: I trained a Support Vector Machine Classifier using a dataset containing symptoms and corresponding diseases. The model is capable of predicting diseases based on input symptoms.
* Prediction: The app uses the model to predict the most likely disease, providing users with instant information about potential health concerns.
* Additional Information: To enhance user experience, the app also provides additional information about the predicted disease. This includes a description of the disease, recommended precautions, medications, dietary advice, and workout tips.

- Key Features
* User-Friendly Interface: The web app boasts an intuitive and easy-to-navigate interface, ensuring that users can input their symptoms without any hassle using dropdown menu that includes list of 132 symptoms.
* Accurate Predictions: Leveraging machine learning, model provides accurate disease predictions based on the symptoms provided by the user.
* Comprehensive Information: In addition to predictions, the app offers comprehensive information about the predicted disease, including descriptions, precautions, medications, diet recommendations, and workout tips.
* Educational Content: To empower users with knowledge, the app includes informative blog posts about various health topics.

- link for dataset https://www.kaggle.com/kaushil268/disease-prediction-using-machine-learning 
- link for symptoms https://people.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html 