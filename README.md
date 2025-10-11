# Power Shifts: Visualizing Global Energy Transitions
This project explores how global energy consumption has evolved over time, focusing on the shift from fossil fuels (Coal, Oil, Natural gas,Nuclear) to renewable energy sources (Hydro, Wind, Solar, Biofuel,Others).

## Data  
- `data.csv`: the cleaned global energy consumption dataset  
- Derived variables, summaries, and plots are created in `Analysis.qmd`

 ## Methods & Workflow  
1. Clean and inspect the data  
2. Calculate totals by country, region, year  
3. Identify top energy-consuming countries  
4. Plot time series trends (global, regional, country-level)  
5. Compute and display year-to-year percentage change

All of the code is done using R and it's packages (readr, dplyr, tidyr, ggplot2).
## How to Run  
To reproduce the analysis locally:
1. Clone or download the repository
   “Download ZIP”, or use the command below in your terminal:
   > git clone https://github.com/pranjalts07/Power-Shifts.git

2. Open it in RStudio.
   
3. Install the required R packages.
   > install.packages(c("readr", "dplyr", "tidyr", "ggplot2"))

4. Then render the analysis.

This will execute all R code, produce the figures, and create a complete report showing the results of the analysis.
