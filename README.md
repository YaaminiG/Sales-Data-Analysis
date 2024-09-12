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


                  The best month for Sales is December and 4613443.34 USD were made that month 
![best month for sales](https://github.com/user-attachments/assets/9ca1e21a-7f38-45e6-a9af-3a2492650ac0)



                The best city for Sales is San Francisco CA  and 8262203.91 USD were made in that city. 
![which city sold the most](https://github.com/user-attachments/assets/ed019c1b-f0f5-4e70-b165-b2a4a80bafc3)


                The best time to diplay the ads is slightly before 11am or 7pm
![time to display ads](https://github.com/user-attachments/assets/cf80cf46-583c-4b8e-bfdf-57f0822460b2)

                The most sold item is AAA batteries.
![most sold items](https://github.com/user-attachments/assets/a4f60c5f-205e-4150-adb4-dc8d82ea2050)


                The analysis made on why AAA batteries were sold most is due to its price range which is pretty low.
![final analysis](https://github.com/user-attachments/assets/43bb225b-58a6-4cde-b343-7580d49de588)





