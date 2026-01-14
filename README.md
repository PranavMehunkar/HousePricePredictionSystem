<h1>HousePrice Prediction System</h1>
HousePrice Prediction System is a machine learning project that predicts the market price of a house automatically based on its physicalfeatures, location, and condition.The goal is to analyse the dataset, perform data preprocessing, train a LinearRegression model, and evaluate its performance.

<h2>Project Structure</h2>
<ul><li>house_price.ipynb – Model for training and evaluation</li></ul>
<ul><li>HousePricePrediction.csv – Dataset used for training and evaluation</li></ul>

<h2>Model Used</h2>
<ul><li>Linear Regression</li></ul>
Model performance was compared using R2 Score, Mean Absolute Error, Root Mean Squared Error and Mean Absolute Percentage Error.

<h2>Model Performance</h2>
<table>
<tr><th>Model</th><th>R2 Score (%)</th>	<th>Mean Absolute Error</th><th>Root Mean Squared Error</th>	<th>Mean Absolute Percentage Error (%)</th></tr>
<tr><td>Linear Regression</td>	<td><b>37.41</b></td>	<td>30829.93</td>	<td><b>41138.55</b></td>	<td><b>18.74</b></td></tr>
</table>

<h2>Technologies Used</h2>
<ul><li>Python</li></ul>
<ul><li>Pandas, NumPy</li></ul>
<ul><li>Scikit-learn</li></ul>
<ul><li>Jupyter Lab</li></ul>

<h2>Future Work</h2>
<ul><li>Deploy the final model using Streamlit</li></ul>
<ul><li>Improve feature engineering</li></ul>
<ul><li>Add model interpretability and UI enhancements</li></ul>

<h2>Key Learnings</h2>
During this project, I learned and applied several important machine learning and data preprocessing concepts, including:
<ul><li>Handling missing values using <b>SimpleImputer</b> with appropriate strategies for numerical and categorical features</li></ul>
<ul><li>Building a regression model that can accurately predict the house price using historical property data.</li></ul>
<ul><li>Analysing the dataset, perform data preprocessing, train a LinearRegression model, and evaluate its performance.</li></ul>
<ul><li>Understanding the impact of feature scaling using <b>StandardScaler</b></li></ul>
