# Flight Price Data Preprocessing & Feature Engineering

A complete Jupyter Notebook demonstrating exploratory data analysis (EDA), data cleaning, feature extraction, and categorical encoding on the Flight Price dataset using Python, Pandas, and Scikit-Learn.

## 📊 What's Inside?
- **Data Loading & Inspection**: Exploring the dataset using `pandas` (`head()`, `info()`, `describe()`).
- **Feature Extraction**: Extracting Date, Month, and Year from `Date_of_Journey`.
- **Time Feature Engineering**: Splitting `Dep_Time` and `Arrival_Time` into distinct hour and minute numerical features.
- **Handling Missing Values**: Imputing missing values in `Total_Stops` using mapping and `fillna()`.
- **Duration Parsing**: Cleaning and splitting flight `Duration` into hours and minutes.
- **Categorical Encoding**: Applying `OneHotEncoder` from `scikit-learn` to categorical features like `Airline`, `Source`, and `Destination`.

## 🛠️ Technologies Used
- Python 3.14
- Pandas & NumPy
- Scikit-Learn (Preprocessing)
- Matplotlib & Seaborn

## 🚀 How to Run
Clone the repository and open `flight_price.ipynb` in Jupyter Notebook or JupyterLab to execute the steps interactively.
