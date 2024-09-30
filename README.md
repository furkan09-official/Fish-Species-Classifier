# Fish Species Classifier

A machine learning-based web application that predicts fish species based on user input features (length, weight, and weight-length ratio) using a pre-trained model. The app also displays an image of the predicted fish species.


## Features
- Takes fish features (length, weight, and weight-length ratio) as input.
- Predicts the species of the fish using a machine learning model.
- Displays an image of the predicted fish species if available.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [File Structure](#file-structure)
4. [Model](#model)
5. [Contributing](#contributing)
6. [License](#license)

## Installation

### Prerequisites
- Python 3.x
- scikit-learn
- pandas
- numpy
- streamlit
  
##Usage
1. Train or Use Pre-Trained Model
You can train your model using a dataset of fish species or use the pre-trained model provided(model.pkl)
2. Run the Streamlit Application
   streamlit run App.py
   
3. Interact with the Application
Enter the length, weight, and weight-length ratio of a fish.
Click the Predict button to get the species prediction and its corresponding image.

## File Structure
├── App.py                        # The main Streamlit app
├── model.pkl                     # Pre-trained machine learning model
├── scaler.pkl                    # Pre-trained data scaler
├── images/                       # Folder containing fish species images
│   ├── Anabas testudineus.jpeg
│   ├── Puntius lateristriga.jfif
│   └── ...
├── README.md                     # Project documentation


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

### Key Sections:
1. **Installation**: Lists dependencies and instructions to set up the project.
2. **Usage**: Shows how to run the Streamlit app.
3. **File Structure**: Outlines the project's folder and file structure.
4. **Model**: Describes the machine learning model used.
5. **Contributing**: Provides guidelines for contributing to the project.

Let me know if you'd like further customization!
