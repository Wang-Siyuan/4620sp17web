###Instructions to view the data visualizer###

Launch the local server in the root directory by running:

(If you have python 2.x): python -m SimpleHTTPServer
(If you have python 3.x): python -m http.server

Then you can view the page at: http://localhost:8000/index.html

Note that it only works well on Chrome, so please test it on Chrome Only

###How to toggle dataset###
You can toggle the dataset that corresponds to the size of the bubble by
selecting from the dropdown on the top right corner. The X and Y axis still uses 
GDP per capita and Life Expectancy dataset.  

Note that the range of years change when you select a different dataset.
If the current year selection doesn't make sense when you switch dataset,
it will adjust the year selection to the closest valid year in the current data set.
