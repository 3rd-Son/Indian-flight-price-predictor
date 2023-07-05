# Flight Price Prediction Web Application

This is a Flight Price Prediction web application that predicts the prices of flights in India based on various features such as the takeoff point, destination, time, number of stops, and the airline. The web application utilizes the CatBoost algorithm for building the machine learning model. The backend of the application is built using Flask, while the frontend is developed using HTML and CSS.

## Features

- **Flight Price Prediction**: Users can input the relevant details of the flight, including the takeoff point, destination, time, number of stops, and the airline. The application then uses the trained CatBoost model to predict the flight price.

## Prerequisites

Before running the web application, ensure that you have the following dependencies installed:

- Python 3.x
- Flask
- CatBoost
- Pandas
- NumPy
- Scikit-learn

## Getting Started

To get started with the Flight Price Prediction web application, follow these steps:

1. Clone the repository or download the source code.
2. Open a terminal or command prompt and navigate to the project directory.

### Preprocessing and Model Training

1. Explore and preprocess the flight price dataset.
2. Build a machine learning model using the CatBoost algorithm. Train the model on the preprocessed dataset.

### Running the Web Application Locally

1. In the terminal or command prompt, install the required dependencies using the following command:
2. Start the Flask development server:
- For Windows, use the command:
  ```
  set FLASK_APP=app.py
  flask run
  ```
- For macOS/Linux, use the command:
  ```
  export FLASK_APP=app.py
  flask run
  ```
3. Open a web browser and navigate to `http://localhost:5000` to access the Flight Price Prediction web application.

### Deploying the Web Application

This project includes deployment on the Render platform. To deploy the web application on Render, follow these steps:

1. Sign up for an account on [Render](https://render.com/).
2. Create a new web service and connect the repository containing the project's source code.
3. Configure the environment variables required for running the application, such as the Flask secret key.
4. Deploy the web service on Render, and wait for the deployment to complete.
5. Once the deployment is complete, access the web application using the provided URL.

## Directory Structure

The project directory is organized as follows:


- The `static` directory contains the CSS and JavaScript files for the frontend.
- The `templates` directory contains the HTML template for the web application.
- `app.py` is the Flask application file that handles the routes and predictions.
- `model.pkl` is the serialized CatBoost model file.
- `preprocessing.ipynb` is a Jupyter Notebook containing the data preprocessing steps.

## Additional Notes

- The model used for flight price prediction in this application is trained using a specific dataset and may not generalize well to other scenarios.
- It is recommended to periodically retrain the model using updated data to maintain prediction accuracy.
- The application can be enhanced by incorporating additional features, such as weather conditions, customer reviews, orhistorical flight data.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
 
