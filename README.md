# Fish Species Classifier

A machine learning-based web application that predicts fish species based on user input features (length, weight, and weight-length ratio) using a pre-trained model. The app also displays an image of the predicted fish species.


## Features
- Takes fish features (length, weight, and weight-length ratio) as input.
- Predicts the species of the fish using a machine learning model.
- Displays an image of the predicted fish species if available.



## Installation

### Prerequisites
 Python 3.x.
 scikit-learn.
 pandas.
 numpy.
 streamlit.
  
## Usage
1. Train or Use Pre-Trained Model
You can train your model using a dataset of fish species or use the pre-trained model provided(model.pkl)
2. Run the Streamlit Application
   streamlit run App.py
   
3. Interact with the Application
Enter the length, weight, and weight-length ratio of a fish.
Click the Predict button to get the species prediction and its corresponding image.


## Model
The model is trained using fish species dataset containing features like length, weight, and weight-length ratio.
The model is a classification model, and it uses a MinMaxScaler for data normalization.
The prediction outputs the species name, which is mapped to an image that is displayed in the app.

## Contributing
Contributions, issues, and feature requests are welcome!

1.Fork the repository.
2.Create a new branch (git checkout -b feature-branch).
3.Commit your changes (git commit -m 'Add some feature').
4.Push to the branch (git push origin feature-branch).
5.Create a new Pull Request.


