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

## 📂 Dataset

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

## 🔧 Getting Started

1. **Download or Clone the Repository**  
   - git clone https://github.com/rafi0020/Smart_Dining_Caloric_Display.git
   - cd Smart_Dining_Caloric_Display

2. **Install Dependencies**  
   Install the required Python packages using the `requirements.txt` file.

3. **Prepare the Dataset**  
   - Store the dataset files in the `data/` folder.

4. **Run the Notebook**  
   Open the `Developing_a_Smart_Restaurant_Menu_for_Caloric_Calculation.ipynb` notebook in Jupyter or Google Colab.

---

## 📊 Results

- **Best Model**: Random Forest Regressor
- **Performance**:
  - **MSE**: 15.75
  - **R²**: 0.9999
- **Visualizations**:
  - Error distributions
 
    ![image](https://github.com/user-attachments/assets/002e0d9f-a8dd-48d6-9247-535bedd6b41e)


  - feature importance

    ![image](https://github.com/user-attachments/assets/00a91444-2631-4188-93d2-c742f3ffebd2)


  - model performance plots

    ![image](https://github.com/user-attachments/assets/2e5aa2c0-14e1-4d56-b244-2bed46c568c0)


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
