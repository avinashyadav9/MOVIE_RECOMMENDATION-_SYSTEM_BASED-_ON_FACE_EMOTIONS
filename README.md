# # Movie Recommendation System Using Facial Emotions

## Overview
This project is a deep learning-based movie recommendation system that suggests movies based on detected facial expressions, genres, ratings, and user input. The system captures facial expressions via a laptop camera, analyzes them using an NLP model, and provides personalized movie recommendations.

## Features
- **Facial Emotion Recognition**: Detects user emotions using a webcam and classifies them (e.g., angry, happy, sad, neutral, etc.).
- **NLP-based Recommendation**: Analyzes user input such as movie names and ratings to refine suggestions.
- **Genre & Rating-Based Suggestions**: Provides recommendations by considering preferred genres and user ratings.
- **User-Friendly Interface**: Built with Flask and Streamlit for an interactive experience.
- **Music Integration**: Supports an emotion-based music player using OpenCV and FisherFaceRecognizer.

## Technologies Used
### Backend:
- **Python** (Flask, Pandas, Scikit-learn, Pickle)
- **Deep Learning** (Facial emotion recognition model)
- **OpenCV** (For face detection and recognition)
- **Eel** (For interactive GUI development)
- **TMDB Dataset** (For movie information)

### Frontend:
- **Flask** (For web-based interaction)
- **Streamlit** (For easy UI implementation)
- **Tkinter** (For local GUI-based emotion detection and music integration)

## Installation & Setup
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. **Create a Virtual Environment:**
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the Flask Application:**
   ```sh
   python app.py
   ```
5. **Run the Eel GUI for Emotion-based Music Player:**
   ```sh
   python eel_app.py
   ```

## How It Works
1. The system captures the user's facial expression via the webcam.
2. The deep learning model classifies the detected emotion.
3. User inputs preferences like favorite movie names or ratings.
4. The system analyzes both the emotion and user input to generate relevant recommendations.
5. The recommended movies are displayed on the Flask/Streamlit interface.
6. The emotion detection module also integrates with a music player to play emotion-based music.

## Dataset
The system uses **The Movie Database (TMDB) dataset**, which contains extensive details about movies, including genres, ratings, and descriptions.

## Future Enhancements
- **Integration with Streaming Platforms** to check availability.
- **Improved NLP Model** for enhanced recommendation accuracy.
- **Support for Multiple Users** with personalized profiles.
- **Enhanced Emotion-based Music Suggestions**

## Contributing
If you’d like to contribute, feel free to fork the repository and submit a pull request.

## License
This project is open-source under the MIT License.


