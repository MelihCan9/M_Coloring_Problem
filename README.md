# M_Coloring_Problem

This project basicly do Choropleth Map with python.

### Know How

First, it reads the CSV file containing the list of neighbors for each country in South America. The readcsv() method in the 'Pandas' library could be used, but this is also another way of reading and there is an advantage to using this way to read graphs, this way we can also create a graph to use the color-in-neighborhood method.

In ‘paint_map’ method, I initialized all the vertices without any color. Then used nested loops and lists to return colormap as a dictionary that will be used in the ‘plot_choropleth’ method in the main. Also, in this method I used several try-except blocks to make the code maintainable and robust. In the main method I also handle the general exception just in case. 
And finally, here are some sample outputs of my code:

![image](https://user-images.githubusercontent.com/73959073/175181109-6fb5a856-dbd4-4571-a26a-6b90b20d01e4.png)

![image](https://user-images.githubusercontent.com/73959073/175181212-e057fe10-de8f-448d-bb61-bd7591193619.png)

