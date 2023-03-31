# bikesharing

## NYC Citibike Analysis
This project analyzes data from NYC Citibike, a bike-sharing program in New York City, to gain insights into bike usage patterns. The analysis includes visualizations created in Tableau that show trip durations, trip frequency by hour and day of the week, and user behavior by gender and user type.
### Deliverable 1:
is locsted in the folder 
### Deliverable 2: Create Visualizations for the Trip Analysis (50 points)
Using Tableau, we created the following visualizations:
#### Checkout Times for Users Viz

This visualization shows the length of time that bikes are checked out for all riders. We added the number of records and the "tripduration" column to the Rows and Columns, respectively, and filtered the "More" option by "Hour" and "Minute". We also added the "tripduration" column that shows the "Hour" to the Filters field and selected "Show Filter". The resulting visualization shows the checkout durations by the minute for each hour for all users.

#### Checkout Times by Gender Viz
This visualization shows the length of time that bikes are checked out for each gender. We repeated the steps of the previous visualization and added the converted column for gender as a color to the Marks field and to the Filters field, and selected "Show Filter". The resulting visualization shows the checkout times by the minute for each hour for each gender.

####Trips by Weekday for Each Hour Viz

This visualization shows the number of bike trips by weekday for each hour of the day as a heatmap. We added the "Starttime" column to the Rows and filtered the "More" option by "Hour", and added the "Stoptime" column to the Columns and filtered it by "Weekday". We also added the number of records to the Marks field as a color and formatted the Y axis of the Starttime by Hour to show the 12-hour format. The resulting visualization shows the number of trips by weekday for each hour of the day.

#### Trips by Gender (Weekday per Hour) Viz

This visualization shows the number of bike trips by gender for each hour of each day of the week as a heatmap. We repeated the steps of the previous visualization and added the converted column for "Gender" to the Columns and to the Filters field, and selected "Show Filter". The resulting visualization shows the number of trips by gender for each hour of each day of the week.

#### User Trips by Gender by Weekday Viz
This visualization shows the number of bike trips broken down by gender for each day of the week by each user type. We added the converted column for "Gender" and the "Usertype" column to the Columns and Filters field, respectively, and selected "Show Filter". We also added the "Starttime" column to the Rows and filtered it by "Weekday", and added the number of records to the Marks field as a color. The resulting visualization shows the number of trips for each user type by gender by each day of the week.
#### Deliverable 3: Create a Story and Report for the Final Presentation (30 points)
We created a Tableau Story that includes the four visualizations we created in Deliverable 2, as well as two additional visualizations created in this module. The Story is designed to highlight key findings and insights from the analysis.

### Overview of the analysis
The purpose of this analysis is to gain insights into bike usage patterns in NYC Citibike. We analyzed trip durations, trip frequency by hour and day of the week, and user behavior by gender and user type.

### Results
The Checkout Times for Users visualization shows that the majority of bike checkouts last less than 20 minutes, with
link to the tableau we page https://public.tableau.com/app/profile/samuel.aboma/viz/NYCCityBike_16802944127760/NYCstory?publish=yes
