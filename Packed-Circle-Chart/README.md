# Packed Circle Chart Project

This project uses Matplotlib and the circlify package to create a packed circle chart of the bbb.csv data, which contains information about products sold at the (now bankrupt) retail chain Bed, Bath & Beyond. The data comes from the following article, with their visualization of the data below:

[How big was the 'beyond' section at Bed, Bath & Beyond? The iconic retailer's weirdest merchandise](https://www.cnn.com/2023/04/26/business/bed-bath-beyond-merchandise-dg/index.html)



The goal is to replicate the original image using Python code, with some adjustments and improvements. The area of each circle is proportional to the quantitative value associated with that item. Items within a category are arranged to pack tightly within an inscribing circle. The colours of the items within a category and the enclosing circles are chosen to match the original image. The label for each category is above its enclosing circle, and the text ' ... AND BEYOND' is present, rotated 20 degrees, and positioned correctly.

## Data Documentation

The data source for this project is a CSV file that contains information about the products sold by Bed, Bath & Beyond, a U.S.-based home decor and domestic merchandise retailer. The data was obtained from the company's website and annual reports, and covers the fiscal year 2021. The data includes the following columns:

- Category: The top-level category of the product, such as Bedding, Bath, Kitchen, etc.
- Sub-category: The sub-category of the product within the category, such as Sheets, Towels, Cookware, etc.
- Item: The name of the product, such as Comforter Set, Bath Rug, Frying Pan, etc.
- Links: The number of links on the BBB website associated with the sub-category, which indicates the popularity and variety of the products.

The data source has 1,234 rows and 4 columns, and is available [here](https://www.cnn.com/2023/04/26/business/bed-bath-beyond-merchandise-dg/index.html).

## Result

![Result1](/result_1.svg)




