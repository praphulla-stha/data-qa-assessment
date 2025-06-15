# Junior Data QA Analyst Assessment Submission

This repository contains my deliverables for the Junior Data QA Analyst assessment, consisting of three tasks. Below is an overview of each task, file descriptions, and instructions for running and viewing the outputs.

## Task 1: Data Cleaning
- **Files**:
  - `Task 1.ipynb`: Jupyter notebook with Python code for cleaning the dataset (e.g., removing duplicates, validating fields like `dob`, `post_code`).
  - `manifest.txt`: Output file listing processed fields or metadata.
- **Description**: Cleans the dataset by handling missing values, duplicates, and invalid entries.
- **Run Instructions**:
  1. Open `Task 1.ipynb` in Google Colab or Jupyter Notebook.
  2. Place `dataset.csv` in the same directory.
  3. Install dependencies: `pip install pandas`
  4. Run all cells to generate `manifest.txt`.

## Task 2: Data Analysis
- **Files**:
  - `Task 2.ipynb`: Jupyter notebook with Python code for analyzing the dataset.
  - CSV files (e.g., `dataset_9320.csv`): Output files with aggregated data.
- **Description**: Spilts the data by postal codes.
- **Run Instructions**:
  1. Open `Task 2.ipynb` in Google Colab or Jupyter Notebook.
  2. Place `dataset.csv` or Task 1’s output in the same directory.
  3. Install dependencies: `pip install pandas`
  4. Run all cells to generate CSV files.

## Task 3: Data Quality Report
- **Files**:
  - `Task 3.ipynb`: Jupyter notebook with Python code to generate an HTML report.
  - `visualization.html`: Interactive HTML report with tables (e.g., provider counts, field summary) and charts (postcodes, missing values).
- **Description**: Visualizes data quality issues (missing values, uneven distributions, duplicates) using styled tables and Plotly charts, with a navigation bar for easy access.
- **View Report**:
  - Open `Task 3/visualization.html` in a browser (e.g., Chrome) to view the report.
  - Alternatively, visit [GitHub Pages link](https://YourUsername.github.io/data-qa-assessment/Task%203/visualization.html) for an online view.
- **Run Instructions**:
  1. Open `Task 3.ipynb` in Google Colab.
  2. Place `dataset.csv` in the same directory.
  3. Install dependencies: `pip install pandas plotly`
  4. Run all cells to generate `visualization.html`.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/praphulla-stha/data-qa-assessment.git
2. Install Python dependencies:
   pip install pandas plotly
3. Place dataset.csv in the appropriate task folders.
4. Follow task-specific run instructions above.
5. For Task 3, view Task 3/visualization.html directly or via GitHub Pages.
