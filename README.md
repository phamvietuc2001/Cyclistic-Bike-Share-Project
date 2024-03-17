# Cyclistic-Bike-Share-Project

Here is another Business Intelligence project I did after taking the BI professional certificate. Specifically, it broke down into three phases corresponding with 3 courses to complete this project:
* The 1st phase (1st course) is to complete the BI documents, which include **stakeholders' requirements, project requirements, and strategy requirements**
    * **Stakeholders document** enables capturing stakeholder requests and requirements to understand their needs before planning the rest of the project details or strategy 
    * **Project document** contains the following: project's purpose, stakeholder requirements, success criteria, etc.
    * **Strategy document** deals with approaching the data and getting feedback from the stakeholders by creating data visualizations and dashboard mockups.
* The 2nd phase (2nd course) is to **consolidate** the data from **multiple sources into a target table** by using SQL and **load** it into the unified destination (Tableau in this project)
* The final phase (3rd course) is to create the **dashboard**, and the **slide-deck presentation** to present the insights to the stakeholders (here is the Tableau workbook: [Cyclistic Bike Share Project](https://public.tableau.com/app/profile/viet.pham4981/viz/Bike_17106188243660/NYCBikeTrip?publish=yes))

### Here is the scenario:

Cyclistic has partnered with the city of New York to provide shared bikes. Currently, there are bike stations located throughout Manhattan and neighboring boroughs. Customers are able to rent bikes for easy travel between stations at these locations.

Cyclistic’s Customer Growth Team is creating a business plan for next year. The team wants to understand how their customers are using their bikes; their top priority is identifying **customer demand** at different station locations.

Cyclistic has captured data points for every trip taken by their customers, including:
* Trip start time and location (station number, and its latitude/longitude)
* Trip end time and location (station number, and its latitude/longitude)
* The rented bike’s identification number
* The type of customer (either a one-time customer, or a subscriber)

Project goal: **Grow Cyclistic’s Customer Base**

* Understand what customers want, what makes a successful product, and how new stations might alleviate demand in different geographical areas
* Understand how the current line of bikes are used
* Apply customer usage insights to inform **new station growth**
* Understand how different users (**subscribers** and **non-subscribers**) use the bikes


Primary dataset: NYC Citi Bike Trips - bigquery-public-data.new_york_citibike

Secondary dataset: Census Bureau US Boundaries - bigquery-public-data.geo_us_boundaries

Third dataset: Global Surface Summary of the Day Weather Data - bigquery-public-data.noaa_gsod
