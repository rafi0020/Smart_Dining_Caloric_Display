# Smart Dining: A Machine Learning Approach to Caloric Display in Bangladeshi Restaurants

This repository implements a **machine learning-based caloric estimation system** for traditional Bangladeshi dishes. By integrating machine learning models with menu systems, this project aims to promote nutritional awareness and healthier eating habits.

---

## 📄 Project Overview

### Motivation
With diet-related health issues prevalent in Bangladesh, this system provides real-time caloric information for traditional dishes, empowering users to make informed dietary choices.

### Objectives
1. Compile and preprocess a dataset of Bangladeshi recipes and ingredients.
2. Train and evaluate models, including:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
3. Deploy the best-performing model for real-time caloric prediction.

---

## 📊 Dataset

### Sources
- **Food Composition Table for Bangladesh (2022)**: Nutritional information.
- **Traditional Cookbooks**: Recipes and caloric breakdowns.

### Data Preprocessing
- Extracted features: Ingredient quantities.
- Target variable: Total caloric content.

### Example Data Format:
| Recipe Name  | Ingredient_1 | Ingredient_2 | Total Calories |
|--------------|--------------|--------------|----------------|
| Chicken Curry| 100g         | 50g          | 450 kcal       |

---

## 🛠 Repository Structure

- **`notebooks/`**: Contains the Jupyter Notebook with the project implementation.
- **`src/`**: Python scripts for:
  - Data preprocessing (`data_preprocessing.py`)
  - Feature engineering (`feature_engineering.py`)
  - Model training (`model_training.py`)
  - Caloric prediction (`predict_calories.py`)
- **`data/`**: Placeholder for the dataset with a `README.md` for access instructions.
- **`results/`**: Includes evaluation metrics and visualizations.
- **`requirements.txt`**: Contains dependencies for running the project.

---

## 🔧 Getting Started

1. **Download or Clone the Repository**  
   - git clone https://github.com/rafi0020/Smart_Dining_Caloric_Display.git
   - cd Smart_Dining_Caloric_Display

2. **Install Dependencies**  
   Install the required Python packages using the `requirements.txt` file.

3. **Prepare the Dataset**  
   - Follow instructions in the `data/README.md` to access or compile the dataset.
   - Store the dataset files in the `data/` folder.

4. **Run the Notebook**  
   Open the `Developing_a_Smart_Restaurant_Menu_for_Caloric_Calculation.ipynb` notebook in Jupyter or Google Colab.

---

## 📊 Results

- **Best Model**: Random Forest Regressor
- **Performance**:
  - **MSE**: 15.75
  - **R²**: 0.9999
- **Visualizations**: Error distributions, feature importance, and model performance plots.

---

## 🤝 Contributions
Contributions are welcome! Open an issue or submit a pull request for suggestions or improvements.

---

## 📫 Contact
- **Email**: rafiulislam1921@gmail.com  
- **LinkedIn**: [Rafiul Islam](https://www.linkedin.com/in/rafi009)

---

## 📄 License
This repository is licensed under the Apache 2.0 License. See `LICENSE` for more details.
