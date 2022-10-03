# Notes on Assignment 05

### The following are the notes I made while working on assignment 5

- .head() is used to show first five rows of table
- .shape shows the total rows and columns in a table
- .describe() gives all the stats of the table such as mean, median, min, std
- if you want stat of a certain cloumn use  name of table["column name"].describe() same rule applies if you want to find individual stat
- .value_counts() use to count values
- 

## Notes on Ploting
- Use 'import matplotlib.pyplot as plt'
### Ploting box
- table name ['column name'].plot(kind='box', vert=False, figsize=(14,6))
### Ploting density
- table name ['column name'].plot(kind='density', vert=False, figsize=(14,6))
### Ploting histogram
- table name ['column name'].plot(kind='hist', bins=30, figsize=(14,6))
### Ploting pie
- sales['Year'].value_counts().plot(kind='pie', figsize=(6,6))

## Creating Realtionship
### Scatter plot
sales.plot(kind='scatter', x='Order_Quantity', y='Profit', figsize=(6,6))

# Notes on NumPy
### Create a numpy array
- .arange(10,50)
### Multiply Matrix
- np.ones([4,4]) * 5
### Creating diagonal Matrix 3*3
- np.identity(3)
### Create a 3*3 numpy matrix, filled with values ranging from 0 to 8
- np.arange(9).reshape(3,3)


- -1 is used to show the last element
- 0 is used to show the first element
- ::-1 is used to reverse the element
- 1:-1 is used to show all the middle elements
- ::2 used to show elements in odd poistions
- :2,:2 showing first two elements on first two rows
- 2:,2: last two elements on last two rows
- .sort() is used to sort the data 
- Adding any number to any element x + 'desired number'


