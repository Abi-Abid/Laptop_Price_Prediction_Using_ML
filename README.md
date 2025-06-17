![ales-nesetril-Im7lZjxeLhg-unsplash](https://github.com/user-attachments/assets/199c05be-3505-40aa-9a12-a08dbe309769)

# Laptop Price Predictor with ML

### "Hey, these are the specifications of the laptop I’m looking for. Can you tell me the cost of this laptop? Great! Just a minute — let me ask my ML model!”

This is a regression-based machine learning project where the primary objective is to predict the price of a laptop based on its specifications. The dataset consists of multiple rows and columns, with each row representing a laptop and each column representing a specific feature such as manufacturer, GPU, RAM, CPU, etc. The target column is ‘price’, which we aim to predict using the remaining features.

## Key Insights & Conclusion


* The dataset consists of **238 entries** and **12 features**, with each entry representing a unique laptop.

* During exploratory data analysis (EDA), the following features were found to significantly influence laptop prices:

  * `RAM_GB` (RAM size)
  * `CPU_Frequency`
  * `CPU_Core`
  * `Weight_kg`

* **General trend** observed:

  * Laptops with **higher RAM**, **faster CPUs (≥2.5 GHz)**, and **lighter weight** tend to have **higher prices**.
  * The price distribution is **right-skewed**, indicating more affordable laptops and fewer high-end ones.

* **Regression models** applied to predict laptop prices:

  * Evaluated using **R² Score**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.
  * Top-performing models:

    * **Ridge Regression**
    * **Linear Regression**
    * **Lasso Regression**

* **Why no hyperparameter tuning?**

  * Dataset is relatively small.
  * Techniques like **GridSearchCV** were avoided to prevent **overfitting** or **underfitting** due to limited data.

* **Final model chosen**:

  * **Ridge Regression** showed the **best balance** of performance and generalization.
  * It can reliably predict laptop prices based on key specifications.

* This model provides a foundation that can be **further improved** if larger or more diverse datasets become available.


Below is the **results table of all 10 models performed.**

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
