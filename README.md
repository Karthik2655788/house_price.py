# house_price.py

# 🏡 House Price Prediction using Linear Regression

This project demonstrates how to predict house prices using a simple **Linear Regression** model in Python with `scikit-learn`. 
It takes into account features like house area, number of bedrooms, and number of bathrooms.
## 📁 Dataset
Make sure the dataset is available in the same directory with the filename:
house\_prices2.csv
### 📄 Expected Columns in CSV:
- `area` – Area of the house in square feet
- `bedrooms` – Number of bedrooms
- `bathrooms` – Number of bathrooms
- `price` – Actual price of the house (target variable)
## 🛠️ Technologies Used

- Python 3.x
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [scikit-learn](https://scikit-learn.org/)
- [matplotlib](https://matplotlib.org/)
## 🚀 How to Run
1. Clone the repository or copy the code into a `.py` file.
2. Make sure `house_prices2.csv` is present in the same directory.
3. Install dependencies (if not already installed):
   pip install pandas numpy scikit-learn matplotlib
4. Run the script:
   python house_price_prediction.py
## 🧠 How It Works
* **Step 1**: Load the dataset using pandas.
* **Step 2**: Select `area`, `bedrooms`, and `bathrooms` as input features and `price` as the target.
* **Step 3**: Split the data into training and test sets using `train_test_split`.
* **Step 4**: Train a `LinearRegression` model.
* **Step 5**: Predict prices for the test set.
* **Step 6**: Evaluate the model using **Root Mean Squared Error (RMSE)**.
* **Step 7**: Visualize the results using a scatter plot.
## 📈 Output
* Console:
  * Displays the first 5 rows of the dataset
  * Prints the **Root Mean Squared Error (RMSE)**
* Plot:
  * A scatter plot showing **Actual vs Predicted Prices**
## 📌 Example Output
   area  bedrooms  bathrooms   price
0  2100         3          2  500000
1  1600         2          1  300000
Root Mean Squared Error: 48023.17
