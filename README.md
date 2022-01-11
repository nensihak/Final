# Dash app

Dash apps are built off of a set of simple but powerful principles: declarative UIs that are customizable through reactive and functional Python callbacks.
Every element attribute of the declarative components can be updated through a callback and a subset of the attributes, like the value properties of the dcc.Dropdown, are editable by the user in the interface.

In the Python file, I have created a Dashboard taking data from [Eurostat, GDP and main components (output, expenditure and income)](http://ec.europa.eu/eurostat/web/products-datasets/-/nama_10_gdp). 
The dashboard has two graphs: 

- The first one is a scatterplot with two DropDown boxes for the different indicators. Also, it has a slider for different years in the data. 
- The other graph is a line chart with two DropDown boxes, one for the country and the other for selecting one of the indicators.

The final implementation is deployed on Heroku: https://nensihakobjanyan.herokuapp.com
 
