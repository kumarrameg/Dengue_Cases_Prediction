# Dengue Prediction Project

## Overview

This project utilizes machine learning techniques to predict Dengue cases based on environmental and demographic features. The model is trained using synthetic data generated with the help of the Faker library.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/dengue-prediction.git
    cd dengue-prediction
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```bash
        source venv/bin/activate
        ```

4. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Train the Dengue prediction model:

    ```bash
    python train_model.py
    ```

2. Generate synthetic data for testing:

    ```bash
    python generate_synthetic_data.py
    ```

3. Make predictions on new data:

    ```bash
    python make_predictions.py
    ```

## Project Structure

- **`train_model.py`**: Script for training the Dengue prediction model.
- **`generate_synthetic_data.py`**: Script for generating synthetic data.
- **`make_predictions.py`**: Script for making predictions on new data.
- **`synthetic_dengue_data.csv`**: Generated synthetic data for testing.
- **`dengue_prediction_model.joblib`**: Trained machine learning model.
- **`requirements.txt`**: File containing the required libraries.

## Results

- The trained model's performance is evaluated using Mean Squared Error (MSE) and R-squared metrics.
- Various plot styles are used to visualize the actual vs. predicted Dengue cases.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
