# Sunburst Plot Project

This project is about creating a sunburst plot using Matplotlib. A sunburst plot is a circular chart that shows hierarchical data, where each level of the hierarchy is represented by a ring or a circle. The innermost circle represents the root node, and the outer circles represent the sub-nodes. The arc length of each wedge is proportional to the value of the node.

## Data Description

The data used for this project is a CSV file containing the information about the video game consoles sold by Nintendo, Microsoft and Sony. The file has five columns: Platform, Type, Company, Released and Units sold. The Platform column contains the name of the console, the Type column indicates whether it is a home console, a handheld console or a dedicated console, the Company column shows the manufacturer of the console, the Released column gives the year of release, and the Units sold column shows the number of units sold in millions.

## Project Objective

The objective of this project is to recreate the sunburst plot shown below, using Matplotlib. The plot shows the total number of video game consoles sold by Nintendo, Microsoft and Sony. The inner ring shows the total number of consoles sold per company, and the outer ring refines each company into their individual consoles. The consoles on the outer ring are ordered from largest number of units sold to smallest number of units sold in a clockwise fashion. The four consoles with the smallest number of units sold for Nintendo are not displayed (since that would create visual clutter). The colours of the inner ring are [#156eaf, #db2018, #56b45b] for Microsoft, Nintendo and Sony, and [#5599cc, #ea6727, #83c143] for the outer ring. The edge colours of the wedges are white. The labels of the inner ring are white in colour and on the interior, and the labels of the outer ring on the exterior.

![Sunburst plot](/images/example_1.png)

## Project Steps

The project steps are as follows:

- Load the CSV file using pandas and select the columns for each level of the circle plot.
- Define a function to create a sunburst plot using Matplotlib. The function takes a list of nodes, a dictionary of colours, and other parameters such as the total angle, the offset, the level, and the axis. The function uses a recursive approach to draw the wedges and the labels for each level of the hierarchy.
- Define a function to get the data list for the sunburst plot. The function takes two arrays, one for the first level and one for the second level, and returns a nested list of tuples containing the label, the value, and the sub-nodes for each node.
- Define a dictionary of colours for the nodes, using the hexadecimal codes given in the project objective.
- Call the sunburst function with the data list and the colour dictionary, and display the plot.

## Result

![result_1](/output.png)
