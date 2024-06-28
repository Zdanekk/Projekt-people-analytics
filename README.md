
# Project People Analytics
![logo](https://github.com/Zdanekk/Projekt-people-analytics/assets/169438375/70efd862-21d8-4396-a07e-8460784818f9)

## Project Overview 💡
The Team Management project aims to enhance the management of project teams within the WAIT organization. WAIT is dedicated to executing projects in the fields of Artificial Intelligence (AI), Data Science, and Business Intelligence (BI). By analyzing data regarding the competencies of team members, this project seeks to improve the processes involved in forming effective project teams. The overarching goal is to leverage data-driven insights to create well-balanced, high-performing teams.

## Business Context 🧐
WAIT undertakes projects that address real business challenges, following the Passion Based Learning (PBL) methodology. This approach encourages learning and skill acquisition among individuals connected by common interests, who learn from one another.

## Problem to Solve 🤔
Currently, WAIT has data on the declared competencies of individuals willing to work on projects, but lacks insight into how these competencies are distributed and can be effectively utilized. 

### **```The project's challenge is to extract valuable insights from the collected data, which will aid in constructing efficient project teams.```**

## Machine Learning Methods
To achieve the objectives, the project will employ machine learning techniques, including clustering, to segment WAIT members. This analysis aims to:

🔸 Identify distinct groups of users based on their competencies.

🔸 Derive interesting insights about the structure and potential of the WAIT community.

## Project Goals
➡️ Verify the existence of distinguishable user groups within the WAIT community.

➡️ Analyze available data to provide valuable insights regarding the WAIT community.

➡️ Teach participants the basics of working on a Data Science project, emphasizing quality to ensure the final product can be added to their CVs as a public repository example.


### **``` This project is carried out by students eager to develop their skills in data analysis. ```**


## Project GDescription

➡️ The chapter [_"01_datapreprocessing"_](https://github.com/Zdanekk/Projekt-people-analytics/blob/main/notebooks/01_DataPreprocessing.ipynb) deals with the initial preprocessing of data from an Excel file related to a competency survey. The process begins by loading the data from the Excel file into a DataFrame object using the pd.read_excel function. Subsequently, the ID column is converted to a string type to ensure data consistency.

The style for plots is set using the seaborn library, enhancing the aesthetics of the visualizations. A heatmap is created to visualize the missing values in the data, helping to identify patterns of missing data and aiding in decision-making for further data processing. Then, unnecessary columns are removed from the dataset, and selected columns are renamed for easier handling.

Finally, the filtered and updated data is saved to a new CSV file, enabling further stages of data analysis. This process is crucial for preparing the data for more advanced analysis and modeling, ensuring that the data is complete, consistent, and easy to manage.

➡️ The chapter [_"02_featureengineering"_](https://github.com/Zdanekk/Projekt-people-analytics/blob/main/notebooks/02_FeatureEngineering.ipynb) focuses on preprocessing and filtering data for further analysis. The process begins by determining the current file path and the parent directory path using the pathlib library. The script then defines the input file path for the CSV file containing the selected features from the previous preprocessing step.

The data is loaded from this CSV file into a DataFrame using pandas. Specific values in the "Community Participation" column, which indicate non-contributory responses, are defined and removed from the dataset. The filtered data is then saved to a new CSV file in the specified output directory, ensuring that only relevant data is retained for further analysis.

Overall, this chapter ensures that the dataset is cleaned and filtered by removing irrelevant responses, making it ready for subsequent stages of analysis and modeling.

➡️ The chapter [_"03_ExploratoryDataAnalysis"_](https://github.com/Zdanekk/Projekt-people-analytics/blob/main/notebooks/03_ExploratoryDataAnalysis.ipynb) focuses on performing exploratory data analysis (EDA) on the filtered dataset to uncover patterns, relationships, and insights. The process begins with loading the processed data from a CSV file and setting the 'Participant ID' as the index. The script then selects numerical columns for correlation analysis and creates a triangular heatmap of Spearman correlations to visualize the relationships between numerical variables.

Next, unnecessary columns are removed, and the data is sorted based on the sum of values in each row. A heatmap of individual competencies is generated, displaying different levels of engagement and competency with a custom color legend. The chapter also includes calculating the mean rating for each skill, sorting the skills by their mean ratings, and creating a stacked bar plot to show the distribution of ratings for each skill.

Overall, this chapter involves cleaning and organizing the data, performing correlation analysis, and visualizing various aspects of the data to gain deeper insights into participant competencies and relationships between different skills.








## Project Status
Project is: _in progress 🔜_  

## Contributors 😎
This project is brought to you by a dedicated team of students eager to develop their skills in data analysis. Below are the contributors to this project along with links to their GitHub profiles:

🔸 Natalia Siwiak 👉 [_click here_](https://github.com/nsiwiak)

🔸 Amanda Czechowska 👉 [_click here_](https://github.com/czeama)

🔸 Jan Zdaniewicz 👉 [_click here_](https://github.com/Zdanekk)

