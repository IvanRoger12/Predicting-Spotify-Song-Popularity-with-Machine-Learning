# Predicting-Spotify-Song-Popularity-with-Machine-Learning

## Project Overview

This project aims to predict the popularity of Spotify songs using linear regression. By analyzing various features of the songs, we aim to build a model that can predict the number of streams a song might get.

## Project Steps

1. **Data Exploration and Preparation**
    - Loaded the dataset and explored the initial data.
    - Selected relevant features for the analysis.
    - Cleaned and prepared the data by converting non-numeric values and handling missing values.

2. **Modeling with Linear Regression**
    - Split the data into training and testing sets.
    - Trained a linear regression model on the training data.
    - Evaluated the model's performance using Mean Squared Error (MSE) and R-squared (R²) metrics.

3. **Performance Evaluation**
    - Assessed the model's predictions on the test data.
    - Calculated the MSE and R² to determine the model's accuracy.

4. **Results Visualization**
    - Created scatter plots to show the relationship between each feature and the number of streams.
    - Generated box plots to display the distribution of each feature.
    - Constructed a heatmap to visualize the correlation between different features.

## Results

- **R²**: -0.00
- **MSE**: 244937092343747552.00

The visualizations demonstrate the accuracy of the predictions and the distribution of the residuals. Additionally, scatter plots and box plots help understand the relationships between features and the target variable.

## Visualizations

### Predictions vs Actual Values
![Predictions vs Actual Values](images/predictions_vs_actual.png)

### Residuals Distribution
![Residuals Distribution](images/residuals_distribution.png)

### Scatter Plots
![Scatter Plots](images/scatter_plots.png)

### Box Plots
![Box Plots](images/box_plots.png)

### Correlation Matrix
![Correlation Matrix](images/correlation_matrix.png)

## How to Run the Code

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/spotify-song-popularity-prediction.git
    cd spotify-song-popularity-prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
    Open `spotify_song_popularity_prediction.ipynb` in your Jupyter environment and run all cells.


