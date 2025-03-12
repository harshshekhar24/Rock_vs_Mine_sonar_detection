# Rock vs Mine Sonar Detection

This project uses Logistic Regression to classify sonar signals as either rocks or mines.

## Project Structure

```
Logistic_Regression.ipynb
sonar data.csv
```

- `Logistic_Regression.ipynb`: Jupyter notebook containing the implementation of the Logistic Regression model.
- `sonar data.csv`: Dataset containing sonar signals data.

## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/harshshekhar/rock-vs-mine-sonar-detection.git
    cd rock-vs-mine-sonar-detection
    ```

2. Install the required packages:
    ```sh
    pip install numpy pandas scikit-learn jupyter
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook Logistic_Regression.ipynb
    ```

2. Run the cells in the notebook to train and evaluate the Logistic Regression model.

## Dataset

The dataset `sonar data.csv` contains sonar signals data with the following columns:
- 60 numerical features representing the energy of the sonar signal at different frequencies.
- 1 target column indicating whether the signal is from a rock or a mine.

## Model

The Logistic Regression model is implemented using Scikit-learn's `LogisticRegression` class. The model is trained on a subset of the data and evaluated using accuracy score.
