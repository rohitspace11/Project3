# codsoft_task3
internship task of codsoft (CUSTOMER CHURN PREDICTION)

# Customer Churn Prediction

This repository contains the code and resources for a Customer Churn Prediction project. The goal of this project is to predict which customers are likely to churn (stop using a service) using machine learning algorithms.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Algorithms Used](#algorithms-used)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Customer churn prediction is essential for businesses to retain their customers. By identifying potential churners, companies can take proactive measures to retain these customers, thereby reducing the cost of acquiring new customers. This project employs various machine learning algorithms to predict customer churn accurately.

## Dataset
The dataset used in this project is publicly available and contains customer information such as demographics, services subscribed, and account information. 

- **Number of records:** 10000
- **Number of features:** 14(RowNumber	CustomerId	Surname	CreditScore	Geography	Gender	Age	Tenure	Balance	NumOfProducts	HasCrCard	IsActiveMember	 
                             EstimatedSalary	Exited)
- **Target variable:** 'Exited' (0/1)

## Algorithms Used
- **Logistic Regression**
- **Gradient Boosting**
- **Random Forest**


## Results
The Random Forest model achieved the highest accuracy on the test data. Here are the evaluation metrics for each model:

- **Logistic Regression**
  - Accuracy: 80.05%

- **Gradient Boosting**
  - Accuracy: 86.55%

- **Random Forest**
  - Accuracy: 86.70%
 

## Installation
To run this project locally, please follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/customer-churn-prediction.git
    ```

2. Navigate to the project directory:
    ```bash
    cd customer-churn-prediction
    ```

3. Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Preprocess the data:
    ```bash
    python preprocess_data.py
    ```

2. Train the models:
    ```bash
    python train_models.py
    ```

3. Evaluate the models:
    ```bash
    python evaluate_models.py
    ```

4. Predict churn on new data:
    ```bash
    python predict.py --input data/new_customers.csv
    ```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or new features.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
