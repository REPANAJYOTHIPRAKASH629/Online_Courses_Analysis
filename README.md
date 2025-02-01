# Power BI Dashboard for EdTech Recorded Courses Analysis

[Online_Courses_DashBoard.pdf](https://github.com/user-attachments/files/18628252/Online_Courses_DashBoard.pdf)


## Project Overview
This project leverages **Power BI** to analyze and visualize data collected from various EdTech platforms, with a specific focus on **recorded courses**. The goal is to uncover valuable insights into course offerings, viewer engagement, instructor performance, and language preferences to help the EdTech startup improve its recorded lecture services.

## Key Insights and Analysis
The analysis provides insights across several important dimensions:

1. **Distribution of Course Types Across Categories**  
   Visualizes the breakdown of course types across different categories to understand the type of content being offered.

2. **Number of Courses by Category and Sub-category**  
   Analyzes the count of courses in each category and sub-category to highlight areas with potential growth.

3. **Average Views for Categories, Sub-categories, and Languages**  
   Helps understand viewer engagement by calculating the average number of views for different categories, sub-categories, and languages.

4. **Most Commonly Taught Skills by Category**  
   Identifies key skills being taught in each category to help align course offerings with job market demands.

5. **Language Preferences and Distribution**  
   Shows the distribution of languages across courses and the viewer language preferences in the top 5 categories.

6. **Impact of Subtitles on Views**  
   Investigates how the availability of subtitles affects the number of views, helping assess the importance of subtitles in increasing accessibility.

7. **Top 3 Instructors by Category and Sub-category**  
   Identifies the highest-rated instructors within each category, helping the startup approach quality content creators.

8. **Course Duration vs. Viewer Engagement**  
   Analyzes the relationship between course duration and views to understand how the length of a course may influence learner engagement.

9. **Impact of Skill Variety on Viewership**  
   Examines whether a greater variety of skills in a course leads to higher viewership, enabling the startup to offer diverse courses in high-demand areas.

## Project Components

- **Data Source**:  
  The dataset used for this analysis comes from the Kaggle **[Online Courses Dataset](https://www.kaggle.com/datasets/khaledatef1/online-courses?select=Online_Courses.csv)**.

- **Tools Used**:  
  - Power BI Desktop (for data visualization and analysis)
  - Power Query Editor (for data cleaning and transformation)
  - DAX (for creating measures and calculated columns)

- **Files**:  
  - **Dataset**: `Online_Courses.csv` (downloaded from Kaggle)
  - **Power BI Report**: `EdTech_Analysis.pbix` (contains all the analysis and visualizations)

## Steps to Reproduce
0. **Download the Problem**  
   Download the Problem Statement [here](https://docs.google.com/document/d/1Ts4UZ3bapfSJXeGBKhIf0CKq6OFty6TrXlrCw3wsfjw/edit?tab=t.0)

1. **Download the Dataset**  
   Download the dataset from Kaggle [here](https://www.kaggle.com/datasets/khaledatef1/online-courses?select=Online_Courses.csv) and save the CSV file locally.

2. **Import Data into Power BI**  
   Open Power BI Desktop and import the dataset (`Online_Courses.csv`) into Power BI.

3. **Data Cleaning**  
   - Open the Power Query Editor and remove any irrelevant columns.
   - Convert the data types (e.g., ensure numeric columns are set as numbers, text columns as text).
   - Handle missing data, either by removing rows or filling in missing values.

4. **Create Relationships (if necessary)**  
   Set up relationships between tables if there are any reference tables (e.g., categories, instructors).

5. **Create Measures & Calculations**  
   Use DAX to create any necessary measures or calculated columns, such as:
   - Average views by category and language
   - Ranking of instructors based on ratings

6. **Design the Dashboard**  
   - Use Power BI visualizations (bar charts, donut charts, scatter plots, etc.) to present the data.
   - Add slicers for interactivity and filtering by categories, languages, or instructors.
   - Use static visuals where needed, such as the list of top instructors by category.

7. **Publish and Share**  
   - Once the dashboard is complete, publish the Power BI report to Power BI Service or share it as a .pbix file for stakeholders to explore.

## Visualizations Included
- **Stacked Column Chart**: Distribution of course types across categories
- **Tree Map/Bar Chart**: Number of courses by category and sub-category
- **Column/Bar Chart**: Average views by category, sub-category, and language
- **Word Cloud/Bar Chart**: Most commonly taught skills by category
- **Donut/Bar Chart**: Language distribution across courses
- **Scatter Plot**: Views vs. subtitle availability
- **Bar Chart/Table**: Top 3 instructors by category and sub-category
- **Scatter Plot**: Duration vs. views for courses
- **Bar/Line Chart**: Skill variety and its effect on views

## Screenshots
Include screenshots of the dashboard here to provide a preview of the visuals.

![image](https://github.com/user-attachments/assets/339f3c70-8984-4281-8387-e0d0cf7f6733)

![image](https://github.com/user-attachments/assets/5b9f9692-10e8-490a-8780-d88786ddb497)

![image](https://github.com/user-attachments/assets/c751f521-b841-4ba4-9942-b43324b104b4)

![image](https://github.com/user-attachments/assets/60debb15-2893-4f13-9894-0601cfa75276)



## Conclusions and Actionable Insights
The Power BI dashboard provides actionable insights that can help the EdTech startup:
- Identify the most popular course types and categories to prioritize.
- Understand viewer engagement and make data-driven decisions on course development.
- Approach top instructors for partnerships to improve content quality.
- Optimize language options to cater to the global audience’s preferences.
- Evaluate the impact of subtitles and course duration on learner engagement.

## Future Improvements
- **Advanced Predictive Analytics**: Use machine learning to predict which courses are likely to gain traction based on historical trends.
- **Feedback Analysis**: Integrate course ratings and user feedback to improve recommendations for course development.
- **More granular language preferences**: Delve deeper into how specific languages impact engagement by region or country.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
