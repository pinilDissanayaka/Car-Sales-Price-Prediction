# Car-Sales-Price-Prediction

## Main Context:-

As a vehicle salesperson, you would like to create a model that can estimate the overall amount that consumers would spend given the following characteristics:
customer name, customer email, country, gender, age, annual salary, credit card debt, and net worth

## Note:
While reading csv you will face an error UnicodeDecodeError

Just do the following step while reading csv file:-

  data = pd.read_csv("/kaggle/input/ann-car-sales-price-prediction/car_purchasing.csv",encoding='ISO-8859-1')

Dataset URL : https://www.kaggle.com/code/swathiunnikrishnan/car-sales-price-prediction-with-ann/input

