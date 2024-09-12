# Sales-Data-Analysis
## Overview
In this project I use **Python Pandas** and  **Matplotlib** to analyse and answer bussiness questions about 12 months worth of Sales Data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I started out by cleaning the Data, Tasks include:
- Dropping the NaN Values
- Removing rows based on condition
- Change the type of columns

After Cleaning up the Data, Moved into Data exploration . Here I explored **5** High level business questions related to the data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions I have utilized many different Pandas & Matplotlib Methods.
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling the graphs
# Results
The analysis of the business questions related to the sales data is as follows 
![best month for sales](https://github.com/user-attachments/assets/9ca1e21a-7f38-45e6-a9af-3a2492650ac0)

