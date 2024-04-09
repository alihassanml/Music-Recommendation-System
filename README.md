# Music Recommendation System with Flask

This project is a music recommendation system built using machine learning techniques and deployed with Flask. The system recommends songs based on their similarity to the user's preferences, utilizing natural language processing (NLP) and cosine similarity.

## Overview

The recommendation system employs a collaborative filtering approach, where it analyzes the similarities between songs based on their features and user interactions. The dataset used for training and testing the model consists of music metadata, including song titles, artists, genres, and user ratings.

## Technologies Used

- Python
- Flask
- Pandas
- Scikit-learn
- NLTK
- Seaborn
- Matplotlib

## Features

- **User Preference Analysis**: The system analyzes user preferences by considering their interaction history, such as liked songs, listened duration, and genre preferences.

- **Cosine Similarity**: It computes the cosine similarity between songs' feature vectors to determine their similarity and recommend songs that are most similar to the user's preferences.

- **Flask Deployment**: The recommendation system is deployed using Flask, allowing users to interact with it through a web interface.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/alihassanml/music-recommendation-system.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:

   ```bash
   python app.py
   ```

4. Access the application through the web interface.

## Usage

1. Visit the deployed application URL.
2. Provide your preferences or select from pre-defined options.
3. Get personalized song recommendations based on your preferences.
4. Enjoy listening to recommended songs!

## Contribution

Contributions are welcome! If you have any suggestions or feature requests, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the README according to your project's specifics and add any additional sections or information as needed.
