## Formula 1 Driver Performance Analysis

### Project Overview

This project analyzes Formula 1 driver data to explore relationships between various performance metrics and predict win rates. The dataset includes information about drivers such as their pole rates, podium rates, nationalities, and win rates.

### Project Structure

1. **Data Exploration**
   - **Libraries and Data Import**: Import necessary libraries and read the driver data from a CSV file.
   - **Basic Data Information**: Display the first and last few rows, data types, descriptive statistics, and dataset shape.
   - **Missing Values**: Check for and drop any rows with missing values.
   - **Index Reset**: Reset the data index to ensure consecutive indexing.

2. **Data Visualization**
   - **Win Rate Distribution**: Visualize the distribution of win rates using a histogram.
   - **Scatterplots**: Create scatterplots to explore relationships between pole rates and win rates, and between pole rates and podium rates.
   - **Boxplots**: Illustrate the distribution of win rates across different nationalities.

3. **Data Preprocessing**
   - **Feature Selection**: Select features for prediction, including pole rate, podium rate, and nationality.
   - **One-Hot Encoding**: Encode the nationality feature to transform categorical data into numerical features.
   - **Feature Combination**: Combine the encoded features with the remaining features.

4. **Model Training and Evaluation**
   - **Data Splitting**: Split the data into training and testing sets.
   - **Model Training**: Train a linear regression model on the training set to predict win rates based on selected features.
   - **Performance Evaluation**: Evaluate the model's performance on the testing set by calculating the root mean squared error (RMSE) and mean absolute error (MAE).
   - **Visualization**: Create a scatterplot to compare actual and predicted win rates.
   - **Model Score**: Display the model's score to assess its accuracy.

5. **Additional Analysis**
   - **Pole Position Analysis**: Visualize the relationship between actual and predicted pole positions using a scatterplot.
   - **Correlation Matrix**: Generate a correlation matrix to explore relationships between all numerical features in the dataset.

### Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn


### Conclusion

This project successfully analyzes Formula 1 driver data to identify factors influencing win rates. The visualizations provide insights into relationships between performance metrics, and the linear regression model demonstrates the ability to predict win rates based on available features. Further analysis can be conducted by incorporating additional features, exploring different machine learning models, and performing more in-depth statistical analysis.


Feel free to contribute to the project by opening issues or submitting pull requests. Happy analyzing!

---

**Author**: Raktim Kalita.
