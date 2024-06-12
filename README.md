# Indian-Cooking-Recommendation-System

Welcome to the Indian Cooking Recommendation System! This project uses machine learning to recommend Indian recipes based on user preferences. We leverage scikit-learn for machine learning models and nltk for natural language processing to create an efficient and personalized recommendation system.

**Table of Contents**
Introduction
Features
Installation
Usage
Dataset
Model
Contributing
License
Acknowledgements
Introduction
This project aims to provide personalized recipe recommendations for Indian cuisine lovers. By analyzing user preferences and recipe content, the system suggests recipes that match individual tastes and dietary requirements.

**Features**
Recipe Recommendation: Suggests Indian recipes based on user input.
User Preferences: Takes into account user preferences for ingredients, dietary restrictions, and cuisine types.
Content-Based Filtering: Utilizes natural language processing to understand and recommend recipes.
Easy to Use: Simple interface for users to get recommendations quickly.
Installation
To get started with the Indian Cooking Recommendation System, follow these steps:

**Clone the repository:**
git clone (https://github.com/Smrutir798/Indian-Cooking-Recommendation-System?tab=readme-ov-file)
cd indian-cooking-recommendation

**Create a virtual environment:**
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

**Install the required packages:**
pip install -r requirements.txt
Usage
**Prepare the Dataset:**
Ensure you have a dataset of Indian recipes in CSV format. The dataset should include columns for recipe names, ingredients, cuisine type, and other relevant information.

**Train the Model:**
Use the provided script to preprocess the data and train the recommendation model.

python train_model.py --dataset path_to_your_dataset.csv
**Get Recommendations:**
Run the recommendation script to get recipe suggestions based on user preferences.

python recommend.py --user_preferences user_prefs.json
**Dataset****
The dataset should contain Indian recipes with the following columns:**

Recipe Name: Name of the recipe.
Ingredients: List of ingredients used in the recipe.
Cuisine Type: Type of Indian cuisine (e.g., North Indian, South Indian, etc.).
Other Attributes: Additional attributes such as cooking time, difficulty level, etc.
Model
The recommendation system uses a combination of scikit-learn for machine learning algorithms and nltk for text processing. The main steps include:

Data Preprocessing: Cleaning and preparing the dataset.
Feature Extraction: Using nltk to process text data and extract relevant features.
Model Training: Implementing content-based filtering using scikit-learn.
Recommendation Generation: Providing recommendations based on the trained model and user input.
Contributing

**We welcome contributions from the community. To contribute:**

Fork the repository.
Create a new branch: git checkout -b feature/your-feature.
Make your changes and commit them: git commit -m 'Add some feature'.
Push to the branch: git push origin feature/your-feature.
Submit a pull request.

Acknowledgements
scikit-learn for the machine learning library.
nltk for natural language processing tools.
The open-source community for continuous support and inspiration.
Feel free to customize this README.md to better fit your project's needs. Happy coding and cooking!
