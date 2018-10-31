# Lab: Boolean Logic & Control Flow

<img src="https://user-images.githubusercontent.com/6586811/47810465-5b417880-dd11-11e8-9e39-6aeb7a24fac9.png" width="500">

# Lab: Pandas

<img src="https://user-images.githubusercontent.com/6586811/47810279-f5ed8780-dd10-11e8-8491-792f531cdd0a.png" width="500">


1. Import Pandas and Read a CSV file called cars.csv
2. Print out country column as Pandas Series
3. Print out country column as Pandas DataFrame
4. Print out observation for Japan
5. Print out observations for Australia and Egypt
6. Print out drives_right value of Morocco
7. Print sub-DataFrame

<details><summary>Solution!</summary>
<p>

```python
# Import pandas as pd
import pandas as pd

# Fix import by including index_col
cars = pd.read_csv('cars.csv', index_col = 0)

# Print out cars
print(cars)

# Print out country column as Pandas Series
print(cars['country'])

# Print out country column as Pandas DataFrame
print(cars[['country']])

# Print out observation for Japan
print(cars.loc['JAP'])

# Print out observations for Australia and Egypt
print(cars.loc[['AUS', 'EG']])

# Print out drives_right value of Morocco
print(cars.loc['MOR', 'drives_right'])

# Print sub-DataFrame
print(cars.loc[['RU', 'MOR'], ['country', 'drives_right']])
```

</p>
</details>
