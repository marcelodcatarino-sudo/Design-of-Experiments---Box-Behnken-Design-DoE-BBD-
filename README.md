# Design of Experiments - Box-Behnken Design (DoE-BBD)
This Jupyter notebook (DOE_BB.ipynb) is an interactive tool for generating a Box-Behnken Design (BBD), allowing users to define the number of factors and center points. Its primary purpose is to convert the coded variables (-1, 0, 1) of the statistical design into the actual experimental values (scaled) that will be used in the laboratory, and to export the final result to Excel.

---

# Key Features
- *Interactive BBD Generation*: Creates the design matrix using the bbdesign function from the pyDOE3 library.
- *Factor Naming*: Allows the user to define the names of the factors (e.g., Temperature, Time, Solvent).
- *Scale Conversion*: Converts the coded design values (-1, 0, 1) into the real experimental values, based on the lower and upper limits provided by the user.
- *Export*: Exports the final experimental design (with real values) to an Excel file (Box_Behnken_Design.xlsx).

