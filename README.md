
# KNN Iris Classifier

This project demonstrates a K-Nearest Neighbors (KNN) classifier for the Iris dataset. The application allows users to:
1. Tune the hyperparameter `k` (number of neighbors).
2. Evaluate the model's performance (accuracy and balanced accuracy).
3. Predict the iris species based on user-provided input.

## Features
- Hyperparameter tuning for KNN (`k` selection).
- Model training and evaluation.
- Console-based user input for custom predictions.
- Performance metrics: Accuracy and Balanced Accuracy.

## Requirements
Ensure you have the following installed:
- Python 3.x
- pandas
- scikit-learn

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CAU-AID-Class.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CAU-AID-Class
   ```

## Usage
1. Run the script:
   ```bash
   python knn_iris-classifier.py
   ```
2. Entere the number of neighbors (`k`) when prompted.
3. View the models accuracy and balanced accuracy in the concole.
4. Input `sepal.length` and `petal.length` in the format `value1, value2` to predict the iris species.


## Example
**Console Interaction:**
   ```bash
   Enter the number of neighbors (k) for KNN: 3
   Model Accuracy: 0.95
   Balanced Accuracy: 0.96
   Enter the sepal.length and petal.length for the iris in                        
   theformat'sepal_length,petal_length': 5.1,1.8
   Predicted Label:  Setosa
   ```
## Notes
- Ensure that the input for predictions is numeric and follows the correct format (`value1,value2`).
- Modify the dataset loading path in the script if necessary.

## License
This project is licensed under the [MIT License](https://streamlit.io/cloud)
   ```bash
   ```

**Author**

Developed by [Joonho](https://streamlit.io/cloud)
