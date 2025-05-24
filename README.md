### Sort_Project (this is an active project)

Training Manager has been using excel to keep track of employee training. This has becoming cumbersome and hard to track. She is looking for a Dashboard to visualize training modules:
1. That are:
  * Over due
  * Due within 30 days
  * Due within 60 Days
  * Due within 90 days
  * Due in over 90 days
  
2. Show names, unit, and grade for each.

## Tableau Project
Tableau can be used to visual the compents about. 

The manager has provided a data set containing due dates for each module as of May 1, 2025. Many of the column names, and all of the employee names have randomized to protect privacy. 
Training Modules Names: 
1. Suicide Prevention
2. Sexual Assault Prevention And Response
3. Religious Freedom Training
4. Brib Training
5. Ethics
6. New Employee Orientation
7. Force Protection Training
8. Environmental Training
9. Cyber Security
10. Cyber Awareness Challenge
11. Blood Borne Pathogens
12. HIPPA Training
13. Controlled Substances
14. Field Training
15. Site Controller

Using the Suicide Prevention Data as an example: 
1. Two Calculations were made:
   a. SuicidePrevention_DateDiff: Calculates the number of days from the 5-1-2025 (when file was created) to the due date listed in the columns for each name:
   
   <img width="400" alt="image" src="https://github.com/snkty8/Sort_Project/blob/main/Suicide_Prevention_Date_Diff.png">

   b. SuicidePrevention_Calc: Using day count from SuicidePrevention_DateDiff and transforming to categorical values:
   * Over Due
   * Never Started
   * Due within 30 days
   * Due within 60 days
   * Due within 90 days
   * Due in over 90 Days
   
   <img width="400" alt="image" src="https://github.com/snkty8/Sort_Project/blob/main/Suicide_Prevention_Count.png">
   
3. Bar chart has been created to show due range count by unit:
<img width="400" alt="image" src="https://github.com/snkty8/Sort_Project/blob/main/Count%20by%20Unit.png">


4. Heat Map has been created to show due date range count by Grade:
<img width="400" alt="image" src="https://github.com/snkty8/Sort_Project/blob/main/Count%20by%20Grade.png">

   
5. Table showing the employee Names, Grade, Unit, and Due Date:
<img width="400" alt="image" src="https://github.com/snkty8/Sort_Project/blob/main/Name%20and%20Dates.png">

 
6. Total Count for each due date range, with color coding (Red: Not Started and Over Due, Orange: Due within 30 days, Green: Due within 60, 90, and 0ver 90 days):
<img width="400" alt="image" src="https://github.com/snkty8/Sort_Project/blob/main/Total%20Counts.png">

  
7. Dashboard to show everything together. Includes downdrop to filter the unit and due date range:
<img width="400" alt="image" src="https://github.com/snkty8/Sort_Project/blob/main/Example%20Dashboard.png">

## Next Steps
05-16-25
Once manager has taken a look at the example dashboard, will makes any changes and move forward with adding the remain columns. 

05-23-25
Manager has taken a look a the dashboard example, loves it, but has a few questions:
1. Will there be one dashboard to show all training?

   *I am researchng a way to show all on one dashboard. Work around for now, create buttons to easily jump to each training.*
   
3. Will it remain plain, the white background for example?

   *I will "prettify" the dashboards to her liking.*
   
5. What needs to be done to access the dashboard from anywhere?

   *Since Tableau is being used, the dashboards will be published, and able to access from any device using the URL.*
