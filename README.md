# 🛍️ E-Commerce File Handling Project

This project demonstrates structured file handling techniques in Python for managing and analyzing e-commerce product data. It includes operations such as reading, modifying, and saving data across JSON, CSV, and TXT formats, organized within a consistent file system.

## 📁 Project Structure

```
mainfolder/
├── descriptions/
│   ├── <product_sku>.txt
├── products/
│   ├── <product_sku>.json
├── sales/
│   ├── sales_data.csv
```

## 📘 Features

- **JSON Parsing**: Loads and manages product details from JSON files.
- **CSV Handling**: Parses sales data, storing quantities sold for each product SKU.
- **TXT Reading/Writing**: Handles product descriptions in plain text format.
- **File System Navigation**: Dynamically loads data from a structured directory.

## 🔧 Functions Overview

### `load_data(main_folder)`
Loads product details, sales data, and product descriptions from the specified directory.

Returns:
- `product_details`: Dictionary of product information from JSON files.
- `sales_data`: Dictionary of sales quantities from CSV.
- `product_descriptions`: Dictionary of descriptions from TXT files.

### `update_product_description(product_descriptions, sku, new_description)`
Updates the description for a specific product SKU.

### `save_data(main_folder, product_details, sales_data, product_descriptions)`
Writes the updated data back to the appropriate files in the directory structure.

## 🧪 How to Run

1. Ensure the `mainfolder` directory is unzipped and placed in your working directory.
2. Run the `fileHandling.ipynb` notebook in a Jupyter environment (e.g., JupyterLab or Google Colab).
3. Use the provided functions to explore and manipulate the product dataset.

## 🛠️ Requirements

- Python 3.10+
- Packages:
  - `os`
  - `json`
  - `csv`

## 📈 Use Case

This project is ideal for entry-level developers and data analysts who want to:
- Understand how to work with file systems in Python.
- Learn practical file I/O operations with real-world data.
- Manage structured data formats in a scalable way.

## Contact
[Linkedin](https://www.linkedin.com/in/pawarom14/) | [E-mail](pawarom14112002@gmail.com)
