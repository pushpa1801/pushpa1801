import pandas as pd
data = pd.read_csv('D:\\s3vp\\auto_mpg.csv')
print(data)
cylinders = data[data['cylinder'] ==8]
print(cylinders)
year = data.groupby('my').size()
print(year)
