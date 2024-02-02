# Power-BI-Flight-Analysis

Using data from https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018 selection year 2009 to 2011.

Before the report review, the query editor had to be used to ETL the data. As three years were used, all of the tables were anexed before this cleaning went through. This list includes a brief analysis on some steps: 
- Data types. Most columns used integer values to represent variables that would be suitable on text. Such as Cancelled Status, Arrival Status or Departure Status.
- Data cleaning. While importing the data to Power BI, some data switches from integer to decimal, gaining an additional 0 on the process (this is just one example of all this process)
- New columns. Some columns hold information valuable to divide into new columns. Date on the original file is DD/MM/YY, while a column for each value is quicker and easier to manipulate.
- Data preparation. Renaming columns to make the understanding easier, or deleting columns that now became obsolete.

  
This report contains two pages. The first one being a general Overview with basic and overall information (total flights, time spent on air, distance, total airports, etc). Also, it contains three buttons to switch information quicker for a deeper understanding. The first button applies filters to select years, while the second and third allow to switch from Destination information to Origin information (regarding Airports). Lastly, a top button can be pressed to switch easily to a Delay Analysis.

On the second page, the delay analysis shows all the relevant information about this topic. Also, it allows to filter Airlines, years (as the previous page, with the same filter) and two buttons to switch between Arrival and Departure information aswell.
