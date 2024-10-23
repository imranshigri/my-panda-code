# my-panda-code
# Day 1 
pip install pandas
pip install numpy
import pandas as pd
# This code is to add csv file
dataset = pd.read_csv("ficus1.csv")
# To upload only head  4 lines
dataset.head()
# To upload only tails  4 lines
dataset.tail()
# Second method to add variable and skip rows = 1 means you can skip row 1
df = dataset = pd.read_excel("Chitral70.xlsx", skiprows = 1)
print(df)
# In this code in place of header we can use any name ,means you can change the header name
df = dataset = pd.read_excel("Chitral70.xlsx", header = None , names = ["a" , "b" , "c" , "d" ])
print(df)
