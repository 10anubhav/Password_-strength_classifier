# Password_strength_classifier

Password Strength Checker

This is a simple password strength checker implemented in Python using the Tkinter library for the graphical user interface (GUI). The program uses a machine learning model trained on a dataset of passwords to classify the strength of a given password.

 Dependencies

- Python 3.x
- Tkinter
- pandas
- scikit-learn

Installation

1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Place the password dataset file (`data.csv`) in the same directory as the script.

Usage

1. Run the script: `python password_strength_checker.py`
2. The GUI window will open.
3. Enter a password in the provided entry field.
4. Click the "Check" button to check the strength of the password.
5. A message box will display the strength of the password.

 Dataset

The password dataset (`data.csv`) contains two columns: "password" and "strength". The "password" column contains the passwords, and the "strength" column contains the corresponding strength labels. The strength labels are as follows:

- 0: Very weak password
- 1: Medium password
- 2: Strong password

 Model Training

The program uses a logistic regression model trained on the password dataset to predict the strength of a given password. The dataset is preprocessed using the CountVectorizer from scikit-learn to convert the passwords into numerical features. The dataset is split into training and testing sets, and the model is trained on the training set. The trained model is then used to predict the strength of user-inputted passwords.

Acknowledgements

- The password dataset used in this project is sourced from [insert source].
- The machine learning model implementation is based on scikit-learn's logistic regression classifier.

References

- [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)


