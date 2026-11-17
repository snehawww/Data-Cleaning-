Here are the 10 detailed steps and commands 1 performed for Task1:

1. Initial Data Inspection: Reviewed the raw dataset across all columns and rows to identify data types, missing fields, messy formatting, and inconsistencies before making any edits.
2. Structural Resizing & Formatting: Auto-fitted column widths using Alt + H + O + I and row heights using Alt + H + O + A to ensure all text and numbers were fully visible without truncation.
3. Text Casing Standardization: Applied Excel text functions (LOWER, UPPER, and PROPER) to standardize inconsistent capitalization across names and category fields.
4. Whitespace Removal: Wrapped text fields in the =TRIM() function to strip out hidden leading, trailing, and double spaces that could cause matching or lookup errors.
5. Parenthetical Tag Cleaning: Utilized Excel's Find & Replace tool with wildcard patterns ((*) ) to locate and remove unwanted parenthetical notes or tags from data cells.
6. Column Splitting: Separated combined multi-value fields into distinct individual columns using Data > Text to Columns with delimiter settings like commas or underscores (_).
7. Deduplication: Identified and eliminated exact duplicate rows across the dataset using Data > Remove Duplicates to prevent skewed calculations and bloated row counts.
8. Blank Cell Identification & Imputation: Located all empty data points rapidly using Home > Find & Select > Go To Special > Blanks and batch-filled them with "N/A" using Ctrl + Enter.
9. Error Handling Formulation: Wrapped division and lookup formulas inside =IFERROR(..., "N/A") to catch and suppress disruptive #DIV/0! or #N/A error outputs.
10. Final Presentation Polish: Applied bold headers, high-contrast fill colors, and disabled worksheet gridlines using Alt + W + V + G for a professional, analysis-ready finish.
<img width="32766" height="313" alt="image" src="https://github.com/user-attachments/assets/0b20a9d9-d368-4736-a929-a1d71d7c5516" />
