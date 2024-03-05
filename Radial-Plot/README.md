# Radial Plot Project

This project is about creating a radial plot using Matplotlib and Python. A radial plot is a type of visualization that uses polar coordinates to display periodic data. The project is inspired by the original visualization from Nadieh Bremer and Zan Armstrong, which shows the average number of babies born per minute in the USA for the year 2014.

## Data

The data used for this project is from the births.csv file, which contains the following columns:

- year: the year of the birth
- month: the month of the birth
- time: the time of the birth in HH:MM format

The data is filtered to only include the year 2022, and then grouped by the time in minutes. The average number of babies born per minute is computed and used as the baseline for the radial plot.

## Visualization

The visualization is created using Matplotlib's polar projection. The following elements are present in the radial plot:

- The region between the actual data and the average line is colored with a gradient, using different colors for above and below the average.
- The average line is yellow, and the dashed lines for 6 and 9 babies per minute are grey.
- The angular axis is located at a radius of 11 babies per minute, and has circles for each hour. The labels are adjusted to show the time of the day.
- The title, annotations, and legend are added to provide context and explanation.

## Result

![result_1](/Radial-Plot/output.png)