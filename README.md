# **NutriFit: Personalized Diet Recommendation System using Machine Learning and Content-Based Filtering**

## **Project Description**

- NutriFit is a personalized diet recommendation system that leverages machine learning and natural language processing (NLP) techniques to provide tailored dietary plans based on user-specific parameters such as age, weight, height, gender, and medical conditions. Using content-based filtering and cosine similarity, the system matches user profiles with the most suitable diet plans, promoting healthier eating habits and disease management.

## **Objectives**

- Develop a recommendation system that personalizes diet plans based on individual user health profiles.

- Utilize natural language processing (NLP) to analyze and preprocess textual data from dietary information.

- Implement machine learning techniques to enhance the accuracy of dietary recommendations.

- Improve health outcomes by promoting customized diet plans tailored to specific medical conditions.

## **Scope of Project**

- Collect and preprocess dietary datasets containing nutritional and recipe details.

- Utilize content-based filtering and cosine similarity to match user inputs with suitable diet plans.

- Implement machine learning models such as Random Forest, Support Vector Machines (SVM), and K-means clustering to enhance recommendation accuracy.

- Conduct evaluations using precision, recall, and F1-score to assess system performance.

- Provide recommendations for users with chronic conditions such as heart disease and thyroid issues.

## **Dataset Information**

- Diet Plan Recommendation Dataset: source - Kaggle 

- Healthy Diet Recipes Dataset: source - Kaggle 

- Attributes: User Information: Age, weight, height, gender, medical condition.

- Recipe Details: Ingredients, cuisine type, nutritional content (calories, protein, carbs, fat).

- Diet Preference: Vegan, Mediterranean, or other dietary restrictions.

## **Environment Setup & Dependencies**

- Requirements: Python 3.x

- Jupyter Notebook or Google Colab

- Required Libraries:
```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn tabulate
```
## **Reproducibility Guide**

- Clone the repository:

```bash
git clone https://github.com/yourusername/nutrifit_diet_recommendation.git
cd nutrifit_diet_recommendation
```
## **Results & Findings**

- The NutriFit system was tested through four test cases representing different user scenarios:

- Test Case 1: A 63-year-old male with heart disease and a vegan preference received a 100% accurate diet recommendation (Precision, Recall, and F1 Score = 1.00).

- Test Case 2: Despite the absence of an exact dataset match, the system provided a similar recommendation based on available data, demonstrating adaptability.

- Test Case 3: When an unsupported disease scenario was input, the system successfully identified the lack of suitable recommendations.

- Test Case 4: The system handled extreme input values effectively by generating appropriate error messages.

- These results validate the system's reliability in offering precise and personalized dietary guidance tailored to individual health conditions and preferences.

## **Conclusion**

- The NutriFit system provides personalized diet recommendations using machine learning and NLP techniques. It effectively tailors dietary suggestions based on health conditions and user preferences, promoting healthier lifestyles and improved disease management. The system demonstrated exceptional accuracy and reliability in testing, showing the potential for real-world applications in nutrition and wellness technology.

## **References**

- Diet Plan Recommendation Dataset - Kaggle(https://www.kaggle.com/datasets/vechoo/diet-plan-recommendation)

- Healthy Diet Recipes Dataset - Kaggle(https://www.kaggle.com/datasets/thedevastator/healthy-diet-recipes-a-comprehensive-dataset)
