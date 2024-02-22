# Real-Estate-Market-Analysis

**Background** :  The real estate market is a complex and dynamic entity of great interest for professionals in the field, investors, policymakers, and data analysts 
that wish to thoroughly understand the market conditions and customer behavior and make informed decisions. 
In this Real Estate Market Analysis project, the client—a leading company in the industry—has collected data on properties and their customers and wishes you to help them with the real estate analysis.

## Project Objective
This Real Estate Market Analysis project aims to preprocess, analyze, 
and visualize the real estate property data, thereby generating meaningful insights about property transactions and customer profiles.

## Data
The data in this Real Estate Market Analysis with Python project is divided into two main tables. 
The first dataset contains details about the properties, including ID, building details, sale date, etc. 
The second dataset comprises customer details, such as customer ID, entity, name, surname, and more.

## Data Analysis (Finding)

### Sales Performance by Building and Type

![1](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/Real%20Estate%20Sold%20each%20Type.png?raw=true)
![2](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/Total%20Sales%20Price%20each%20Building.png?raw=true)
![3](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/total%20price%20percentage.png?raw=true)

**REPORT:**
- Almost all residences sold are apartment types. This indicates that apartments are much more popular than offices.
- Total sales of type 2 buildings are the highest. The lowest is building type 5. Building types 2, 3, and 1 have a total sales price that is not too far compared to buildings types 4 and 5.
- All office type residences sold are type 1 buildings. This means the building type with the total sales price is in 3rd place. For apartment-type residences, the highest total sales prices were for buildings of types 2, 3, 1, 4 and 5. Total sales of type 2 buildings accounted for 29% of the total sales.

### Sales Performance by Country and State

![4](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/country%20contribution.png?raw=true)

- The country with the highest total sales price is the USA. This country accounts for 90% of the total sales price overall. Sales in the USA, Canada and Russia have reached more than 95% of total sales overall.

### Breakdown by Building

![5](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/by%20building.png?raw=true)

### Breakdown by Customer Age

![6](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/properties%20sold%20customer%20age.png?raw=true)
![7](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/percent%20purpose.png?raw=true)

- The customers who buy the most houses are aged 36-42 years, followed by those aged 42-48 years. 65% of customers who buy at the age of 36-42 years are for residence.
- Almost all age ranges of customers buy houses to use as a place to live, except for the age range 65-71 years. At that age, 63% of homes sold are for investment.

### Deal Satisfaction

![8](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/average%20deal%20satisfaction.png?raw=true)

### Revenue Over Time

![9](https://github.com/AnnurAfgoni/Real-Estate-Market-Analysis/blob/master/assets/revenue%20over%20time.png?raw=true)

- In the period March 2004 to January 2008, residential sales performance based on price experienced ups and downs. However, overall sales performance could be said to have increased until it peaked in November 2007. After that, sales performance somehow dropped and there were no transactions for several months. In fact, during 2009 there were no sales at all.

## Project Requirements

* pandas
* NumPy
* Matplotlib
* datetime
* seaborn (optional)