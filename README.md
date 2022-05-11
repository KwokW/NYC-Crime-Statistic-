# Cis-9440-Group-12

 NYC Crime Statistics
- author(s): Jordan Wong, Sihan Lin,Xiaodie Zhao,Jie Qu
- date created: 5/5/2022
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: 
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:

NYC's crime rate has been climbing these years and the high crime rate has a huge impact on people’s lives. We want to have a deeper insight into the NYC crime statistic and provide a transparency report to expand awareness of crimes in NYC.


Description of the issues or opportunities the project will address:

Find the crime rate for the major crime category
Improve the procedure and training for certain crimes

Project Business or Organization Value:
Reduce crime
Effectively use police resources.
Provide transparency to the public

Data Sources:
1. NYPD Arrest Data (Year to Date)
2. NYPD Criminal Court Summons Incident Level Data (Year To Date)
...





### Business Requirements Definition

List of Data Warehouse KPI's:
1. Monthly Arrest case by borough
2. Monthly arrest cases by age group
3. Arrest case by type
4. Total arrest case per weekday
5. Percentage of arrest cases over criminal court cases by borough 
...

### Dimensional Model

This project's Dimensional Model consists of (x) Facts and (y) Dimensions

Use correct file path here to show picture of dimensional model...
![Alt text](https://github.com/barrypangteng/Cis-9440-Group-12/blob/e791915a1f6fe88415de57fef32fe8f20d5a29c6/Dimensional%20Model.png)

This project's Kimball Bus Matrix:

Use correct file path here to show picture of dimensional model...
![Alt text](https://github.com/barrypangteng/Cis-9440-Group-12/blob/ceedfd3a88581fa366967017719f0155852156ec/Kimball%20BUS%20Matrix.jpg)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. We use a horizontal bar chart for the first KPI because we want to make a comparison across different subgroups of our data. From a horizontal bar chart, we can easily identify which group has the highest values.
2. We use a pie chart for the second KPI because it shows the relationship of parts to the whole for different categories.
3. We use a treemap for the third type because we have too many subgroups for the crime type. By using the heat map, the highest value will show as the biggest square inside the table. So we can easily identify which crime type has the highest value
4. We use a bar chart for the 4th and 5th KPI because we want to compare the data and there aren’t too many segments

BI Application Wireframe design:

Use correct file path here to show picture of Wireframe design...
![Alt text](https://github.com/barrypangteng/Cis-9440-Group-12/blob/09c0720207879d02bd5e3d004c23061b729a3b3c/Design.jpg)

Picture of final Dashboard:

Use correct file path here to show picture of Dashboard...
![Alt text](https://github.com/barrypangteng/Cis-9440-Group-12/blob/82fb05e55015c967db6f7aa07c19082584ffc2d8/Tableau%20Dashboard.png)






### Deployment

The project was deployed on Tableau Public: [CIS 9440 Group 12]

(https://public.tableau.com/app/profile/kwoktung.wong/viz/cis9440Group12/Dashboard1?publish=yes)
