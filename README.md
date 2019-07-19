# hello-world-
add dataset in csv file 
import csv
import pands as pd
df=pd.read_csv('nithyaa.csv')
print(df)
mean1 = df['Byte'].mean()
sum1 = df['Byte'].sum()
max1 = df['Byte'].max()
min1 = df['Byte'].min()
count1 = df['Byte'].count()
meadian1 = df['Byte'].neadian()
std1 = df['Byte'].std()
var1 = df['Byte'].var()

# block 2 - group by
groupby_sum1 = df.groupby(['country'].sum()
groupby_count1 = df.groupby(['country']).count()

#print block 1
print ('Threshold Byte: ' + str(mean1))
print ('sum of Byte: ' + str(sum1))
print ('Max Byte: ' + str(max1))
print ('Min Byte: ' + str(min1))
print ('count of Bytes: ' + str(count1))
print (Median Bytes: ' + str(median1))
print ('std of Bytes: ' + str(std))
print (var of Bytes: ' + str(var))

#print block 2
print ('sum of values, grouped by the country: ' + str(groupby_sum))
print ('count of values, grouped by the country: ' + str(groupby_count))
