# AutoRia Data Exploration 🚗
Auto Ria porfolio project. From data scraping to cleaning and creating dashboard

## Summary of Project
#### Description: 
In this project i wanted to use my skills and knowledge to analyze the secondary market of cars in Ukraine 
based on the cars that are sold on the AutoRia website.
The project involved scraping the data from AutoRia website (216.520 rows), loading the data, cleaning and creating visualization in PowerBI.
The dataset includes: manufacturer, model_name, release_year, mileage, fuel_type, fuel, transmission, accident, price(USD), price(UAH), city, region, link.

#### Data Sources:
`auto_ria_cleaned.csv`: The primary datatset that was scraped and used in this project, dataset contains detailed information about cars.
`city_region.csv`: This dataset was scraped and used to add region names into primary dataset, because we only had city or village names and for PowerBI visualization i needed regions

#### Files:
`Auro Ria Data Scraping.ipynb`: To begin, I scraped data from the [AutoRia](https://auto.ria.com/uk/) website, which contains information about cars that are on sale and saved as `auto_ria.csv`.

`Auto Ria Cleaning.ipynb`: In this file i did data cleaning where i worked with: handling Null values; changing column names; reordering columns; changing data type; making 2 different columns from a single one; dropping unneeded columns. After cleaning up the data i saved cleaned file as a `auto_ria_cleaned.csv`.

`City&Regions Data Scraping.ipynb`: In this file i scraped city, village and regions of Ukraine from [Wikipedia](https://uk.wikipedia.org/wiki/%D0%9C%D1%96%D1%81%D1%82%D0%B0_%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D0%B8_(%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA)) and saved as a `city_region.csv` to add regions into primary dataset

#### Skills: 
Web scraping, creating dataset, data cleaning, data analysis, PowerBI visualization

#### Technologies:
Python, BeautifulSoup, requests, Pandas, PowerBI

#### Results:
PowerBI dashboard with 4 pages containig all necessary information about secondary car market in Ukraine, which will help you make certain decisions to solve problems associated with used cars
