# Car Inventory Dataset
## Project Overview
This project is focused on training my Excel skills by completing and analyzing a car inventory dataset. The dataset contains detailed information about cars available for a company's business, and the goal is to fill in missing information and perform basic analysis.

## Dataset Information
Name: Car Inventory
Source: GitHub

### Variables Description:
- Car ID: A unique identifier for each car, containing symbols with specific meanings about the car.
- Make: The producing company.
- Make (Full Name): The full name of the producing company.
- Model: The model's name.
- Model (Full Name): The model's full name.
- Manufacture Year: The year the car was produced.
- Age: The age of the car.
- Miles: The total miles driven by the car.
- Miles/Year: The average miles driven per year.
- Driver: Information about the driver.
- Warranty: The warranty period for the car.
- Warranty Covered?: Whether the car is still under warranty.
- New Car ID: A newly generated ID for each car based on its attributes.

### Key Excel Features Used:
1- Import Text Files: Import the dataset into Excel.
2- Formulas for Splitting Cells: Using =LEFT(), =MID(), and =RIGHT() to extract parts of data.
3- VLOOKUP Formula: For looking up related data.
4- CONCATENATE Formula: To combine text values from different cells.
5- Pivot Tables: To summarize and analyze data.
6- Charts: For data visualization.
7- Copy Results to Report: Generating a report in Microsoft Word or another platform.

## Project Objectives
The primary goal is to fill in the following missing columns:
`Make`, `Make (Full Name)`, `Model`, `Model (Full Name)`, `Manufacture Year`, `Age`, `Miles/Year`, `Warranty Covered?` and `New Car ID`.

## Methodology
- Make: Extracted the first two letters from the Car ID to determine the producing company.
- Make (Full Name): Created a lookup table with full company names and used VLOOKUP to populate this column.
- Model: Extracted the model from the Car ID.
- Model (Full Name):  Used a similar lookup table to fill the model's full name.
- Manufacture Year: Extracted from the Car ID.
- Age: Calculated by subtracting the Manufacture Year from the current year.
- Miles/Year: Calculated by dividing the total Miles by the Age.
- Warranty Covered?: Checked by comparing the current year with the Manufacture Year.
- New Car ID: Generated a new ID using the CONCATENATE formula, combining the Make, Manufacture Year, Model, the first three letters of the car's color, and the last three digits of the original Car ID.
- Analysis

After completing the dataset, I conducted some simple analyses on the filled columns to gain insights into the car inventory, and added the charts into word document.
