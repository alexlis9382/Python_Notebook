# Conditional Selection
Do not use And in below condition, use &
Use | for Or
```py 
(df['W']>0) & (df['Z']>0)
```
# MultiIndex
below code selects from a multiindex DataFrame, all rows that have column index level 'Num' that equal 1.
```py 
df.xs(1,level='Num')
```
        
# Missing value
fillna
dropna

# Group by
groupby.describe()
