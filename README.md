# Diabetes prediction

This repository contains code for predicting whether a person is likely to have diabetes based on certain diagnostic measurements. The data used for this prediction is from the [Pima Indians Diabetes Database]() and the machine learning model is built using Python and scikit-learn.

## Installation

To use this code, you will need to have Python 3 and scikit-learn installed on your machine. You can install scikit-learn using pip:

```cmd
pip install scikit-learn
```
If you would like to clone the repository to your local machine, you can do so using the following command:

```bash
git clone https://github.com/raniamaamer/Diabetes-prediction.git  
```

## Usage

To use the machine learning model to make predictions, run the diabetes_prediction.py script:

```sh
python diabetes_prediction.py
```

This will load the pre-trained model and use it to predict whether a person is likely to have diabetes based on input diagnostic measurements.

## Data 

The Pima Indians Diabetes Database contains diagnostic measurements for 768 women, including whether or not they have diabetes. The measurements include:

- Pregnancies: number of times pregnant
- Glucose: plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure: diastolic blood pressure (mm Hg)
- SkinThickness: triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: diabetes pedigree function
- Age: age in years

## Model

The machine learning model used in this code is a logistic regression model built using scikit-learn. The model was trained on the Pima Indians Diabetes Database and achieved an accuracy of 78% on the test set.

## Contributing

Contributions are always welcome! If you have any suggestions or find any issues, please open an issue or a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/). Feel free to use, modify, and distribute this code as you see fit.
