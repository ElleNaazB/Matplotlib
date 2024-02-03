# Overview
This project is about analyzing data from pharmeceuticl company that specializes in  anti-cancer medication on mice; specifically 249 mice , identified with having SCC tumors and received different drug regimens over 45 days. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.
# Analysis 
The analysis  two data sets : <a href = "https://github.com/ElleNaazB/Matplotlib/blob/main/data/Mouse_metadata.csv"> Mouse_metadata.csv </a> and <a href = "https://github.com/ElleNaazB/Matplotlib/blob/main/data/Study_results.csv">Study_results.csv</a>
<p>
The <a href = "https://github.com/ElleNaazB/Matplotlib/blob/main/pymaceuticals_analysis_script.ipynb">analysis_script</a> merges two datasets above , cleansing the data by removing missing or irrelevant entries. It then focuses on four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. The script calculates the tumor volume for each mouse under these regimens, visualizes the data with bar charts and pie charts, and computes quartiles and the Interquartile Range (IQR). By determining the lower and upper bounds using the IQR, the script identifies potential outliers. It also calculates the final tumor volume for each mouse across the selected regimens and provides visualizations of the distribution . </p>

#### Required: Base(Python 3.11.5)

# Primary Takeaways:
- Capomulin and Ramicane were more effective in reducing tumor volume, as indicated by their lower median tumor volumes and the tighter interquartile ranges.
- There's a a strong positive correlation between mouse weight and average tumor volume specifically for the Capomulin treatment group.
- There's a pssoibility that individual differences among treatments based on weight and other genetic or environmental factors, can influence the outcome.
