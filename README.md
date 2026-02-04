# Table Output & Processing – Internship Assessment

## Overview
This project was developed as part of a Software Engineer Internship assessment.  
The task involved displaying a given table and processing specific values from it to generate a second table with calculated results.

## Objective
- Display **Table 1** exactly as provided in the input data  
- Perform calculations using values from Table 1  
- Display the computed results in **Table 2**  
- Ensure the output values are shown as numbers, not formulas  

## Approach

### Table 1 Display
- The data from the provided CSV file was recreated using an HTML table.
- The structure, order, and values match the original table exactly.
- This satisfies the requirement to display the table in the same format.

### Data Processing
- The required values (A5, A7, A12, A13, A15, A20) are used for calculations.
- JavaScript is used to compute the results dynamically.

The calculations are:
- **Alpha** = A5 + A20  
- **Beta** = A15 / A7  
- **Charlie** = A13 × A12  

Only the final numeric results are displayed on the webpage.

### Table 2 Display
- Table 2 is displayed at the bottom of the webpage.
- The calculated values are inserted programmatically to ensure correctness.

## Final Calculated Values
- Alpha: **30**
- Beta: **16**
- Charlie: **270**

## Technologies Used
- HTML
- CSS
- JavaScript

## Deployment
The project is hosted using a static hosting service github pages and is publicly accessible for review.

## Author
Ipshita Karmakar
Final Year in National Insitute of Technology Arunachal Pradesh, India

