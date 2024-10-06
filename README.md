# The 2nd Santai Group Assignment

## Group Members:
- Jonathan Sugijanto
- Afrah Yani
- Kevin Wiata
- Melinda Alberta

## Assignment Overview

This repository contains the solutions to the group assignment for our course. The tasks are related to plotting functions, creating shapes in the command line, generating random data, and working with Excel/CSV files. Below is a breakdown of each task and how to run the respective codes.

### Task 1: Plot Quadratic and Linear Functions
- **Objective**: Plot a quadratic function and a linear function on the same graph and display their intersection points.
- **Approach**: We used a Python plotting library (e.g., Matplotlib) to create a graph with both functions. The intersection points were calculated and marked on the graph.
- **How to Run**:
  1. Open the `task1_plot_functions.py` file.
  2. Run the script to generate the plot and display the intersection points.

### Task 2: Output Triangles in CMD
- **Objective**: Print an isosceles triangle and a right triangle to the command line based on user input for height.
- **Approach**: We implemented this in a Python script that takes the height as input and prints both triangles using `*` characters.
- **How to Run**:
  1. Open the `task2_print_triangles.py` file.
  2. Run the script and input the desired height.

### Task 3: Generate Random Variables and Export to Excel/CSV
- **Objective**: Create 100 random variables between 0 and 1, calculate their sine values, and store the results in a 100x2 table. The table is then exported to Excel or CSV format.
- **Approach**: We used NumPy to generate the random values and calculate `sin(x)` for each. The results are stored in a pandas DataFrame and exported as an Excel/CSV file.
- **How to Run**:
  1. Open the `task3_generate_data.py` file.
  2. Run the script to generate the random data and export it to `data.xlsx` or `data.csv`.

### Task 4: Read and Plot Data from Excel/CSV
- **Objective**: Read the Excel/CSV file from Task 3 and plot the data (x vs sin(x)).
- **Approach**: We used pandas to read the Excel/CSV file and Matplotlib to plot the data.
- **How to Run**:
  1. Ensure that `data.xlsx` or `data.csv` from Task 3 is in the same directory.
  2. Open the `task4_plot_data.py` file.
  3. Run the script to read the data and generate the plot.

## Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `pandas`, `openpyxl` (for Excel support)

To install the necessary libraries, run:
```bash
pip install numpy matplotlib pandas openpyxl
