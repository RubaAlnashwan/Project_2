


# Project 02: Web Scraping and Linear Regression Project



#### Name: Abeer Alruwayti, Ruba Alnashwan
#### E-mail: Abeeralruwaitea@gmail.com, Ruba.Alnashwan@gmail.com

## Background
In this project, we will use data from the (Aqar) website, which provides villas for sale and their prices. Our goal from this project is to build a linear regression model that predict house prices.


## Data Description

In this project,We used data for villas offered for sale in the city of Riyadh that were scraped from a real estate website that contains the specifications and location of the villa in addition to its price.


 |Features|Description                                                                          |  Type  |
 |-------|--------------------------------------------------------------------------------------|--------|
 
 | Area |   The area of the villa land in square meters	                                  | object |
 | Price |  villa price	                                                                      | object |
 | Direction | The front of the villa, if the villa is east and west, means that it is on two streets 	                                                                                | object | 
 | bedrooms |  Number of bedrooms in the villa	                                                                                      | Int |
 | pathrooms |  Number of pathrooms in the villa	                                                                                     | float |
 | living_rooms |  The number of living rooms in the villa	                                                                                   | object |
 | streetwidth |  Width of the street on which the villa is located	                                                                             | Int |
 | oldness |   New or used villa and how many years of use	                                                                                 | Int |
 | views |   The number of users who viewed the ad of the villa	                                                                                   | object |
 | NP |   The location of the villa in the city of Riyadh (North, South, West, East, Central)	                                                                                   | Int |





  ### Scope
  
The scope of this project was the villas for sale in the areas of Riyadh, whether old or new villas.
The dataset contains 38,566 rows × 9 columns.
 

## Tools

* Technologies

  * Python
  * Jupyter Notebook
  * SQL
  * SQLite
  
* Libraries

  * Pandas
  * NumPy
  * Seaborn
  * Matplotlib
  * Requests
  * sqlalchemy
  * sklearn
  * bs4
