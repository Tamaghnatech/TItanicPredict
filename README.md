# Titanic Survival Prediction

![Project Logo](titanic.png)

This project by Tamaghna Nag aims to predict the survival of passengers on the Titanic using machine learning techniques. The dataset consists of passenger information including features such as age, fare, class, gender, and more. The goal is to build a model that accurately predicts whether a passenger survived or not.

## Project Overview

- **Data**: The project utilizes the Titanic dataset containing train and test data in CSV format. The train data is used for model training, while the test data is used for predictions.
- **Preprocessing**: Data preprocessing steps include handling missing values, feature engineering, and scaling numerical features.
- **Model Selection**: Different classifiers are evaluated, including Random Forest, Support Vector Machine, K-Nearest Neighbors, and Logistic Regression.
- **Hyperparameter Tuning**: The Random Forest classifier is tuned using GridSearchCV to find the best set of hyperparameters.
- **Cross-Validation**: Cross-validation is performed to assess the model's performance more reliably.
- **Submission**: The best model is used to predict survival on the test dataset, and the results are saved in a submission CSV file.

## Code Files

- `train.csv`: Training dataset containing passenger information and survival labels.
- `test.csv`: Test dataset containing passenger information for predictions.
- `submission_random_forest.csv`: CSV file containing predicted survival for the test dataset.
- `titanic_project.ipynb`: Jupyter Notebook containing the project code, including data exploration, preprocessing, model training, evaluation, and submission.

## Requirements

- Python 3.x
- Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Instructions

1. Install the required libraries using `pip install pandas numpy scikit-learn matplotlib seaborn`.
2. Download the `train.csv` and `test.csv` files and place them in the project directory.
3. Open the `titanic_project.ipynb` notebook in a Jupyter environment.
4. Follow the notebook's step-by-step instructions to explore the data, preprocess it, train the model, evaluate performance, and generate predictions.
5. The final predictions will be saved in the `submission_random_forest.csv` file.

## License

This project is licensed under the MIT License.

## Author

Tamaghna Nag

Feel free to use, modify, and distribute this project according to the terms of the MIT license. If you have any questions or suggestions, please feel free to reach out.

Happy coding! 🚢🔍📊
