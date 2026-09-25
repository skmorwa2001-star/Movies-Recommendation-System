# 🎬 Movie Recommendation System

Movie Recommendation System built with Python and Streamlit that recommends 5 similar movies based on the movie selected by the user

🔗 Live Demo: https://movies-recommendation-system-12.streamlit.app/

## 📌 Project Description

The project is a content based movie recommendation system built with Python and Streamlit deployed online that recommends 5 similar movies based on the movie selected by the user

The application helps the user to explore movies similar to his/her selected movie
The application is deployed online with the help of Streamlit.

## ✨ Features
The following are the features of the application:

🎥 Select a movie from the movie list
🤖 Get 5 similar movies recommended
🔍 Content based recommendation
⚡ Interactive Streamlit interface
💾 Movie recommendation system uses joblib
🌐 Deployed using Streamlit


## 🛠️ Technologies Used
The following are the technologies that have been used in this project:
- Python
- Pandas
- Numpy
- Scikit-learn
- Joblib
- Streamlit


## 🧠 How it works
The working of the project Movie Recommendation System can be better understood with the help of the diagram below:
 
Movie Dataset
↓
Data Preprocessing
↓
Feature Extraction
↓
Calculate Movie Similarity
↓
Save Objects using Joblib
↓
Load Objects in Streamlit
↓
User Selects Movie
↓
Find Similar Movies
↓
Display Top 5 Similar Movies

## How the application works:
1. Movie Dataset is loaded and preprocessed
2. Movie features are extracted
3. Similarity between movies is calculated using machine learning
4. Necessary objects for the recommendation system are saved using Joblib library
5. Streamlit application loads the objects saved using Joblib
6. User selects a movie from the list of movies
7. Similar movies are found based on the movie selected by the user
8. Top 5 similar movies are displayed as the movie recommendations

## 📂 Project Structure
The structure of the project is given below:
Movie-Recommendation-System/
├── app.py
├── movies.pkl
├── similarity.joblib
├── requirements.txt
└── README.md

## 🚀 How to run the project
The following are the steps to run the project locally:
### 1. Clone the repository:
git clone
### 2. Navigate to the project directory:
cd Movie-Recommendation-System
### 3. Install the required packages:
pip install -r requirements.txt
### 4. Run the Streamlit app:
streamlit run app.py

## 📦 Requirements
Add the following libraries to requirements.txt:
streamlit
pandas
numpy
scikit-learn
joblib

## 💾 Using Joblib
The joblib library is used to save and load objects that are needed for the movie recommendation system.
By using joblib, the streamlit application can load the objects without wasting resources by recomputing them every time the application runs.

## 🎯 Output
After selecting a movie, the application displays 5 recommended movies as shown below:
Selected Movie:
Avatar
Recommended Movies:
1. Movie 1
2. Movie 2
3. Movie 3
4. Movie 4
5. Movie 5

## 🔮 Future Scope
The following are the future scope of the project:
🖼️ Add movie posters
⭐ Add movie ratings
📝 Add movie descriptions
🎭 Add genre filtering
👤 Add personalized movie recommendations
📊 Add movie recommendation analytics
🤖 Improve movie recommendation accuracy
🔐 Add user authentication

## 👨‍💻 Author
Sunil Kumar
AI & Machine Learning Student
Python | Machine Learning | Data Science | Streamlit

## ⭐ Support

If you like this project, please consider giving it a star ⭐ on GitHub.