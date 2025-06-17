![ales-nesetril-Im7lZjxeLhg-unsplash](https://github.com/user-attachments/assets/199c05be-3505-40aa-9a12-a08dbe309769)

# Laptop Price Predictor with ML

### "Hey, these are the specifications of the laptop I’m looking for. Can you tell me the cost of this laptop? Great! Just a minute — let me ask my ML model!”

This is a regression-based machine learning project where the primary objective is to predict the price of a laptop based on its specifications. The dataset consists of multiple rows and columns, with each row representing a laptop and each column representing a specific feature such as manufacturer, GPU, RAM, CPU, etc. The target column is ‘price’, which we aim to predict using the remaining features.

## Key Insights

The Laptop Prices dataset used in this project contains 238 entries, each representing a unique laptop with 12 features. During the exploratory data analysis phase, it was observed that certain features significantly influence the price of a laptop. Among them, RAM size (in GB), CPU frequency, CPU core, and the weight of the laptop had the most notable impact. In general, **laptops with higher RAM, faster CPUs (e.g., frequencies of 2.5 GHz or more), and lighter weight tend to be priced higher.** Additionally, the distribution of prices was found to be right-skewed, meaning that most laptops are in the affordable price range, while a smaller number fall into the high-end category.

To predict the price of a laptop, several regression models were applied and evaluated based on **R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).** Among the models tested, Ridge Regression, Linear Regression, and Lasso Regression performed the best, achieving high R² scores and low error values. These models demonstrated good predictive performance and generalization on the test data. Given the relatively small size of the dataset, hyperparameter tuning methods like GridSearchCV were intentionally avoided. Applying such techniques on limited data may lead to overfitting or underfitting, as the model could make incorrect assumptions due to insufficient variability in the dataset.

After comparing all models, **Ridge Regression** emerged as the most accurate and stable, making it the final choice for this project. It provides a reliable way to predict laptop prices based on key specifications without overfitting the data. With this model, new laptops' prices can be estimated effectively, helping consumers, retailers, or manufacturers understand pricing trends and make informed decisions. This concludes the project with a well-performing regression model that can be further refined or scaled if more data becomes available.

Below is the results table of all 10 models performed.

![image](https://github.com/user-attachments/assets/b3251ca7-947f-44f5-9666-5f4552604a1f)


### Clone this Repository

```bash
git clone https://github.com/Abi-Abid/Laptop_Price_Prediction_Using_ML.git
cd Laptop_Price_Prediction_Using_ML
```

---
## Author
**Dudekula Abid Hussain**

Email iD - dabidhussain2502@gmail.com

Kaggle - https://www.kaggle.com/abiabid
