# Mall Customer Segmentation - Data Cleaning Project

This project involves cleaning a raw dataset called `Mall_Customers.csv` to prepare it for customer segmentation analysis. The task was completed using Python and Pandas in a Jupyter Notebook environment.

 # Files Included

- `Mall_Customers.csv`: Raw input dataset.
- `Mall_Customers_Cleaned.csv`: Cleaned and processed output dataset.
- `cleaning_script.ipynb`: Jupyter Notebook containing data cleaning code and a Markdown summary.
- `screenshots/`: (Optional) Screenshots of the process/output.
- `README.md`: Summary of the project.

# Cleaning Steps Performed

- Renamed columns to lowercase and used underscores for clarity.
- Removed duplicate rows to avoid redundancy.
- Handled missing values by dropping rows with nulls.
- Standardized the text format in the `gender` column (e.g., "female", "FEMALE" → "Female").
- Ensured the `age` column has integer type.
- Saved the final cleaned dataset as `Mall_Customers_Cleaned.csv`.

 How to Run

1. Open `cleaning_script.ipynb` in Jupyter or VS Code.
2. Make sure `Mall_Customers.csv` is in the same directory.
3. Run the notebook step-by-step.
4. The cleaned dataset will be saved in the same folder.

Tools Used

- Python 3.x
- Pandas
- Jupyter Notebook / VS Code
