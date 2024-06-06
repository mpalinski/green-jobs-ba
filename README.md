Bosnian Job Title Similarity Matrices

This repository contains two spreadsheets that facilitate the analysis of job title similarities within the Bosnian ISCO-08 classification system. These matrices enable users to view similar job titles for any given job title at both the 4-digit and 6-digit levels.
Contents
Files

    4-Digit Level Similarity Matrix (423x423)
        Description: This matrix represents the similarity between 423 categories at the 4-digit level of Bosnian ISCO-08.
        Purpose: Allows users to view and analyze job title similarities at a broader category level.

    6-Digit Level Similarity Matrix (4264x4264)
        Description: This matrix represents the similarity between 4264 job titles at the 6-digit level.
        Purpose: Provides a detailed view of job title similarities, treating all 6-digit job titles within the same 4-digit category equally.
        Note: The larger matrix is too large to be viewed in Excel and should be accessed via Python, R, Stata, etc.

Additional Information

    Green/Non-Green Status and Routine Task Index: Both spreadsheets contain a separate sheet with columns informing about the green/non-green status and Routine Task Index score of all job titles.

Usage
Viewing Similar Job Titles

The spreadsheets are designed to enable users to view similar job titles for any given job title from Bosnian ISCO-08 by sorting columns in descending order. Follow these steps to use the spreadsheets:

    Download the Spreadsheets:
        Download both the 4-digit and 6-digit similarity matrices from this repository.

    Open in Spreadsheet Software:
        Open the 4-digit matrix in your preferred software (e.g., Microsoft Excel, Google Sheets).
        Open the 6-digit matrix using software capable of handling large datasets (e.g., Python, R, Stata).

    Sorting Columns:
        Sort the columns in descending order to explore and analyze job title similarities.

Data Source
    Job descriptions and tasks for 4-digit level categories were accessed from the Bosnian job classifications at http://klasifikacije.bhas.gov.ba/.

Methodology
We have embedded job titles along with their descriptions as high-dimensional vectors (3072 dimensions) and calculated cosine similarity scores to identify best matches. 
