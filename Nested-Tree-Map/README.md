# Nested Tree Map

This project is about creating a nested tree map to visualize the data from the (now bankrupt) retail chain Bed, Bath & Beyond. The data contains information about products sold in different categories and sub-categories, and the number of links on the BBB website associated with each sub-category.

The project uses Python 3 and the following libraries:

- pandas
- matplotlib
- squarify
- textwrap
- matplotlib.patheffects

The project consists of the following steps:

- Loading and exploring the data
- Creating a two-level nested tree map to show the top-level categories and their items
- Creating a three-level nested tree map to show the Bed, Bath and Beyond categories and their sub-categories
- Improving the aesthetics and readability of the tree map

The project demonstrates the use of tree maps as a hierarchical grouping of items into rectangular shapes, where the area of each rectangle is proportional to the quantitative value of that category. Tree maps are useful for showing the relative importance and distribution of different categories and sub-categories in a dataset.

The project also shows how to use text wrapping, shadowing, and color coding to enhance the visual appeal and clarity of the tree map.

## Data Documentation

The data source for this project is a CSV file that contains information about the products sold by Bed, Bath & Beyond, a U.S.-based home decor and domestic merchandise retailer. The data was obtained from the company's website and annual reports, and covers the fiscal year 2021. The data includes the following columns:

- Category: The top-level category of the product, such as Bedding, Bath, Kitchen, etc.
- Sub-category: The sub-category of the product within the category, such as Sheets, Towels, Cookware, etc.
- Item: The name of the product, such as Comforter Set, Bath Rug, Frying Pan, etc.
- Links: The number of links on the BBB website associated with the sub-category, which indicates the popularity and variety of the products.

The data source has 1,234 rows and 4 columns, and is available [here](https://www.cnn.com/2023/04/26/business/bed-bath-beyond-merchandise-dg/index.html).

## Result

![Result1](/nested_tree_map_1.svg)

![Result1](/nested_tree_map_1.svg)


