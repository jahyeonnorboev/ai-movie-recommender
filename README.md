# 🎬 AI Movie Recommender System

## 📌 Overview

The **AI Movie Recommender System** is a Python-based web application that recommends movies based on users' emotions or favorite movies.

The application provides an interactive interface built with Streamlit. Users can upload an image, capture a photo using their camera, or manually select their current emotion to receive personalized movie recommendations.

The system also allows users to explore movie recommendations based on their favorite films and analyze movie data through interactive visualizations.

## ✨ Features

- **Emotion-Based Movie Recommendation:** Recommends movies according to the user's selected or detected emotion.
- **Image Upload:** Allows users to upload images in JPG, JPEG, and PNG formats.
- **Camera Input:** Enables users to capture photos directly through their webcam.
- **Manual Emotion Selection:** Users can select their current mood manually.
- **Favorite Movie Recommendation:** Suggests movies based on the emotional category of a selected movie.
- **Movie Rating System:** Displays movie ratings on a 10-point scale.
- **Data Visualization:** Provides charts for emotion-based movie distribution and rating analysis.
- **Interactive Web Interface:** Built with Streamlit for a simple and user-friendly experience.
- **Movie Database:** Includes 60 movies across different genres.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Web application interface |
| Pandas | Data management and analysis |
| NumPy | Numerical operations |
| Scikit-learn | TF-IDF vectorization and cosine similarity |
| OpenCV | Computer vision library |
| Pillow (PIL) | Image processing |
| Random | Simulated emotion prediction |

## Supported Emotions

The application supports the following emotions:

- 😊 Happy
- 😢 Sad
- 😠 Angry
- 😮 Surprise
- 😐 Neutral
- 🤩 Excited

 🎥 Movie Categories

The movie dataset includes several categories:

- Action and Superhero
- Romance and Comedy
- Drama
- Thriller and Crime
- Animation and Family
- Science Fiction and Fantasy

## 📂 Project Structure

```text
AI-Movie-Recommender/
│
├── recogin_uzbek.py
├── README.md
├── requirements.txt
└── .venv/
```

 ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Movie-Recommender.git
```

### 2. Navigate to the Project Directory

```bash
cd AI-Movie-Recommender
```

### 3. Create a Virtual Environment

```bash
python3 -m venv .venv
```

### 4. Activate the Virtual Environment

For macOS and Linux:

```bash
source .venv/bin/activate
```

For Windows:

```bash
.venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

## 📦 Requirements

Create a `requirements.txt` file with the following dependencies:

```text
streamlit
pandas
numpy
scikit-learn
opencv-python
Pillow
```

## ▶️ Run the Application

Start the Streamlit application using:

```bash
streamlit run recogin_uzbek.py
```

After launching, open the local URL displayed in the terminal, usually:

```text
http://localhost:8501
```

## 🚀 How to Use

1. Launch the application.
2. Select the Emotion-Based Recommendation tab.
3. Choose one of the available input methods:
   - Take a photo.
   - Upload an image.
   - Select an emotion manually.
4. View the emotion result and recommended movies.
5. Navigate to the Movie-Based Recommendation tab.
6. Select a favorite movie to receive additional recommendations.
7. Explore the Data Analysis tab to view movie statistics and charts.

## 🧠 Recommendation Method

The application uses a movie dataset containing:

- Movie titles
- Movie genres
- Movie ratings
- Emotion categories

TF-IDF (Term Frequency-Inverse Document Frequency) is used to transform movie genre descriptions into numerical feature vectors.

Cosine similarity is then calculated to measure similarity between movie genres.

Movie recommendations are currently selected primarily through emotion categories and movie ratings.


- Emotion recognition from uploaded images is currently simulated using random selection.
- The confidence score is generated randomly and does not represent actual model accuracy.
- The movie recommendation dataset is predefined and limited to 60 movies.
- Movie recommendations are primarily based on emotion categories and ratings rather than fully implemented cosine-similarity ranking.

Future Improvements

- Integrate a real facial emotion recognition model.
- Improve movie recommendations using cosine similarity.
- Expand the movie database.
- Add movie posters and detailed descriptions.
- Integrate an external movie database API.
- Implement user preferences and recommendation history.
- Improve personalization using machine learning techniques.

 Author

**Shohjakhon Norboev**

Software Engineering  
Kyungpook National University

📄 License

This project was developed for educational and academic purposes.
