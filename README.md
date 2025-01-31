# 12-Movie Recommendation Bot

The 12-Movie Recommendation Bot is a Python-based project that recommends movies to users based on their input preferences. It uses machine learning algorithms and various data sources to offer personalized movie recommendations. This bot can filter movies by genre, ratings, and reviews, providing users with the best options to suit their mood or interests.

## Features

- **Personalized Recommendations**: Suggests movies based on user preferences (genre, rating, etc.).
- **Genre Filter**: Allows users to filter recommendations by movie genres such as Action, Comedy, Drama, etc.
- **Rating Filter**: Users can filter movies by their ratings (e.g., IMDB, Rotten Tomatoes).
- **User Review Filter**: Recommend movies based on the reviews from other users.
- **Interactive Command-Line Interface**: Simple interface for interacting with the bot.

## Installation

### Prerequisites
- Python 3.x or higher
- pip package manager

### Steps to Install

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/12-movie-recommendation-bot.git
2. **Navigate to the project directory**:
   ```bash
   cd 12-movie-recommendation-bot
3. **Install the required dependencies**: To ensure all required libraries are installed, run the following command:
   ```bash
   pip install -r requirements.txt

**Usage**

**Running the Bot**
1. After installing the dependencies, run the bot by executing the following:
   ```bash
   python movie_recommendation_bot.py
2. **Bot Interaction**:
   The bot will prompt you to choose a movie genre.
   You can also select your desired movie rating or review filters.
   The bot will then generate a list of movie recommendations based on your preferences.

**Example**
Welcome to the 12-Movie Recommendation Bot!
Please select a genre: 
1. Action
2. Comedy
3. Drama
...
Enter your choice: 1

Please select a minimum IMDB rating: 
1. 6
2. 7
3. 8
...
Enter your choice: 2

Here are your recommendations:
1. Movie A - Rating: 7.5
2. Movie B - Rating: 8.2
...


**Dependencies**

The following libraries are required for this bot to function properly:

**pandas**: For handling and processing data.
**numpy**: For numerical operations and handling arrays.
**scikit-learn**: For implementing machine learning models.
**requests**: To make API requests (if using external APIs).
**beautifulsoup4**: For scraping movie data (optional, if applicable).
To install the dependencies, run:
     ```bash
     pip install -r requirements.txt


**Acknowledgments**

Thanks to the contributors and libraries that made this project possible.
Special thanks to movie data APIs and datasets used for building the recommendation model.
