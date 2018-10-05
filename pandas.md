# Pandas

### DataFrame locations (.loc vs .iloc): select by position

[.loc](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.loc.html) vs 
[.iloc](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.iloc.html#pandas.DataFrame.iloc) are essentially 
the same concept; you are trying to pull specific data segments out of a dataframe. 

`.loc` uses `labels`

`.iloc` uses integer position; `0 to length-1`

if you are tyring to pull a specific segment of data out and you are not using these, you are perhaps doing something wrong.
