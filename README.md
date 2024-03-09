# New-York-Motor-Vehicle-Collisions
Overview : 
This project focuses on analyzing motor vehicle collision data from New York City. Additionally, it integrates data from GCB Google Cloud to enrich the analysis. The primary goal is to explore patterns, trends, and factors contributing to motor vehicle collisions in New York City. The project utilizes ETL (Extract, Transform, Load) techniques to process the data. It starts with the creation of a dimensional model using ER Studio, followed by data integration, preparation, cleaning, transformation, and visualization using Alteryx, Talend, Power BI, and Tableau.

Datasets : 

1. New York Motor Vehicle Collisions: This dataset contains information about motor vehicle collisions in New York City, including collision dates, locations, severity, contributing factors, and more.
2. GCB Google Cloud: This dataset from GCB Google Cloud enriches the analysis by providing additional relevant information for the motor vehicle collisions dataset.

Process : 

1. Dimensional Model Creation: The project initiated with the creation of a dimensional model using ER Studio. This model organized and structured the data for efficient analysis and querying. The model was then converted into SQL scripts to establish a new database on Azure.

2. Data Integration, Preparation, and Profiling with Alteryx: Following the dimensional model creation, the datasets underwent integration, preparation, and profiling using Alteryx. This stage involved merging datasets, handling inconsistencies, and profiling the data to understand its characteristics.

3. Data Cleaning, Transforming, and Staging with Talend: Post data integration, the dataset underwent cleaning, transforming, and staging processes using Talend. Tasks included handling missing values, standardizing formats, and preparing the data for analysis. The cleaned and transformed data was then staged for loading into the Azure database.

4. Database Storage: The cleaned and transformed data was stored in the newly created database on Azure. This facilitated organized and accessible data for further analysis and querying, allowing for combined analysis of motor vehicle collision data from different sources.

5. Visualization with Power BI and Tableau: The final step involved visualizing insights derived from the combined datasets using Power BI and Tableau. Various visualizations such as charts, graphs, and dashboards were created to showcase key trends and patterns in motor vehicle collisions within New York City.
