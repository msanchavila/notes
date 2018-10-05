# Pandas

### DataFrame locations (.loc vs .iloc): select by position

[.loc](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.loc.html) vs 
[.iloc](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.iloc.html#pandas.DataFrame.iloc) are essentially 
the same concept; you are trying to pull specific data segments out of a dataframe. 

`.loc` uses `labels`

`.iloc` uses integer position; `0 to length-1`

if you are tyring to pull a specific segment of data out and you are not using these, you are perhaps doing something wrong.

### Cool Tools

[pandas.cut](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.cut.html)

super cool tool to use, helps with turning continuous values into categorical values; basically put values into bins. 

[pandas.Series.str.extract](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.str.extract.html)

sweet tool to apply a regex to a Series and create columns out of the match groups.
