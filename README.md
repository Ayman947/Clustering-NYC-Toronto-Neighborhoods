# Clustering-NYC-Toronto-Neighborhoods

- This project approaches a commonly faced problem by people who have to **move** from **NYC** to **Toronto** or Vice versa.

- The problem they face is that they have to move yet they prefer to move to a **similar place** to where they were, having the same **lifestyle**. (ex: similar places, similar venues, ...etc.)

- So, we **clustered the neighborhoods** within the two cities according to their most common **venues** into **6 clusters**.

- Having clustered them, people will be able to **identify easily where to go** as simple as looking at the **clustered neighborhoods map** which has been generated and identify simmilar neighborhoods by **colors**.

- [Additional **Dashboard** for interactive exploring:](https://public.tableau.com/views/NYC-Toronto-Clustered-Neighborhoods/Dashboard5?:language=en-US&:display_count=n&:origin=viz_share_link)



# **Environment** & **Packages**


| Package Name | Functionality or Usage purpose |
|---------------|-------------------------------|
| Pandas        | Data Manipulation              |
| numpy        |  Numerical calculations and array manipulations   |
| json        | Handling Json Files       |
| BeautifulSoup        | Web scrapping              |
| requests        | Building APIs          |
| matplotlib        | Data Visualizatiom        |
| seaborn        | Data Visualizatiom         |
| Follium        | Geospatial Data Visualization   |
| sklearn        | Machine learning algorithms           |


## **Data Sources**

- [**NYC**-data from **Json** file](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/labs/newyork_data.json)

- [**Toronto-data**, web scrapped from](https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M)

- [**Geospatial data from** **Geospatial_Coordinates.csv**](https://github.com/Ayman947/Clustering-NYC-Toronto-Neighborhoods/blob/main/Data-Sources-Files/Geospatial-Coordinates.csv)


## **Data Cleaning** & **Preprocessing**

- Dropping unneeded columns.
- Filtering Canada data to get only Toronto's. 
- Adding longs and lats to Toronto's data.
- Appending both of Toronto's and NYC's data.
- One-hot-Encoding venues for further processing (i.e building K-Means clusters)


## **Insights** 

