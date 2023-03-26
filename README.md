# PurePrognosis - DiseasePrediction

This is a Streamlit app for a multiple disease prediction system. The app has three prediction pages: Diabetes Prediction, Heart Disease Prediction, and Parkinson's Prediction. It loads pre-trained machine learning models from saved pickle files, takes user inputs, and predicts the likelihood of having a particular disease using the loaded models.

For the Diabetes Prediction page, the app takes the number of pregnancies, glucose level, blood pressure value, skin thickness value, insulin level, BMI value, diabetes pedigree function value, and age of the person as inputs. After pressing the Diabetes Test Result button, the app displays whether the person is diabetic or not.

For the Heart Disease Prediction page, the app takes age, sex, chest pain types, resting blood pressure, serum cholestoral in mg/dl, fasting blood sugar > 120 mg/dl, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, slope of the peak exercise ST segment, major vessels colored by flourosopy, and thal as inputs. After pressing the Heart Disease Test Result button, the app displays whether the person is having heart disease or not.

For the Parkinson's Prediction page, the app takes MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, and Jitter:DDP as inputs. After pressing the Parkinson's Disease Test Result button, the app displays whether the person has Parkinson's disease or not.

The app uses the option_menu function from the streamlit_option_menu package to create a navigation sidebar with icons to switch between pages. It also uses the streamlit columns function to organize the inputs into three columns for each page.


# Tech Stack
* Streamlit
* Pandas
* Numpy
* Pickle
* Firebase and Google Drive

# Diabetes Prediction 

![WhatsApp Image 2023-03-27 at 12 40 15 AM](https://user-images.githubusercontent.com/93329536/227798599-f725dd87-61a0-4c34-a6ed-387255195729.jpeg)


# Heart Disease Prediction

![WhatsApp Image 2023-03-27 at 12 18 47 AM](https://user-images.githubusercontent.com/93329536/227798358-f3b0fb90-9747-4f18-b9b5-45c21aa23a43.jpeg)


# Parkinson's Disease Prediction

![WhatsApp Image 2023-03-27 at 12 19 25 AM](https://user-images.githubusercontent.com/93329536/227798407-04c97eed-b372-4233-a4c9-5245bbacf288.jpeg)


