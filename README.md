# filter-expensive-products
# What I Built
A simple Java program that reads product data from a CSV file, filters items with a price greater than 10000, and writes those products into a new CSV file.
# Why I Built It
## This project was created to practice file handling in Java, focusing on:
Reading text files line by line.
Parsing CSV data.
Converting string data into numeric types.
Filtering records based on conditions.
Writing results into a new file.
# How It Works
Input file: products.csv (contains product names and prices).
The program uses BufferedReader to read the CSV line by line.
Each line is split by , to separate name and price.
The price is converted to double, and only products priced above 1000 are kept.
Matching products are written into expensive_products.csv using FileWriter.
The program prints a success message when done.
