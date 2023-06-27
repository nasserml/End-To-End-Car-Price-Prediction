# End-To-End Car Price Prediction

This repository contains the code and resources for an end-to-end car price prediction project. The goal of this project is to develop a machine learning model that can predict the price of a car based on various features.

## Project Structure

The project structure is organized as follows:

- [templates/](templates/): This directory contains the HTML templates used for the web application.
- [.gitignore](.gitignore): Specifies which files and directories should be ignored by version control.
- [Car_price_Prediction.ipynb](Car_price_Prediction.ipynb): Jupyter Notebook containing the data exploration, preprocessing, and model development process.
- [LICENSE](LICENSE): The license file for the project.
- [Procfile](Procfile): Specifies the commands to run the web application on deployment.
- [README.md](README.md): The current file providing an overview of the project.
- [Untitled.ipynb](Untitled.ipynb): An additional Jupyter Notebook for any experimentation or testing purposes.
- [app.py](app.py): The main Python script that runs the web application using Flask.
- [car data.csv](car%20data.csv): The dataset used for training and testing the model.
- [car_price_prediction.py](car_price_prediction.py): The Python script containing the functions and classes related to car price prediction.
- [random_forest_regression_model.pkl](random_forest_regression_model.pkl): A trained machine learning model saved in pickle format.
- [requirements.txt](requirements.txt): Specifies the required Python libraries and their versions.

## Usage

To run the project locally, follow these steps:

1. Install the required dependencies by running `pip install -r requirements.txt`.
2. Execute the command `python app.py` to start the Flask web application.
3. Open a web browser and go to [http://localhost:5000](http://localhost:5000) to access the application.

## Deployment

The project is deployed on Render. You can access the deployed application at [https://endcarprediction.onrender.com/](https://endcarprediction.onrender.com/).

## License

This project is licensed under the [MIT License](LICENSE).

## Contribution

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

---

Please note that the information provided in this README is based on the available information from the repository. Adjustments may be needed based on the actual project requirements and contents.
