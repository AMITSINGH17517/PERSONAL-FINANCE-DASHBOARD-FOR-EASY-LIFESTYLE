# PERSONAL-FINANCE-DASHBOARD-FOR-EASY-LIFESTYLE

Microsoft Power BI is a data analytics tool used to provide business intelligence capabilities, including loading, modelling, and visualizing data sets. Its initial release was over 10 years ago in July 2011, and since then the Microsoft team has continued to add greater functionality and improve ease-of-use on a monthly basis. 

The program itself can be used both on a local machine (via Power BI "Desktop") and also on the cloud (via Power BI "Services"). It can be used in a similar fashion as how one may use Excel, but also provides the greater ability to more easily create interactive visualizations called 'dashboards'.

## Data Collection Methodology
![image](https://user-images.githubusercontent.com/83444670/152843999-6763c995-035b-42e8-a9b8-ef9f29e55bc8.png)


I collected this data by keeping all purchase receipts and inputting the data manually into Excel. The information I kept track of was: Date, Item Category, Price, Location, Comment.

## Data Cleaning

![image](https://user-images.githubusercontent.com/83444670/152844331-f92a94a5-6fa8-4c55-a4af-c4b9dbea3cc9.png)


There was quite a bit of data cleaning to do. I had to do some basic editing of the 'Item' category column, in order to have consistent categories. For example, I had 'hair cut', 'Hair cut', 'Hair-Cut' as separate categores, and so had to standardize this into simply a 'Hair Cut' category.

Finally, only a few rows contained null entries, so I simply chose to remove these rows from the overall dataset; This would not drastically affect the variance of the overall data.

## Measure Creation & Visualizations

![image](https://user-images.githubusercontent.com/83444670/152844434-96b059bc-a552-4545-a800-e0167789368e.png)

  
The item lookup table contained a single column of each distinct Item category. While working through the project, I realized that every month had a rental payment listed. It didn't make sense to me to have this consistently in each month, so I created a filter that can be used to manually include or exclude rental payments. To accomplish this I needed a second column in the Item Lookup table to represent the 'Rent' item as a Boolean.

## Conclusion
Using PowerBI I was able to visualize my purchases data in an interactive way. This allowed me to drill deeper into my spending behaviour and with this information I can now be more conscientious of what I choose to spend my money on.
