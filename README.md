![image](https://user-images.githubusercontent.com/123991455/235980695-c5be9af5-2b50-4cc7-8577-b54ca7fd61b8.png)

## Aim:
The project aims to predict the optimal price for a given cuisine and determine the best location to sell that cuisine with the help of scraped data from Zomato.

## Content 📋
- The Zomato dataset provides a unique opportunity to gain valuable insights into Bengaluru's vibrant restaurant scene. With over 12,000 restaurants serving diverse cuisines worldwide,
  Bengaluru is a dynamic culinary hub. This analysis aims to shed light on the factors influencing restaurant establishment and success, as well as the preferences of the city's residents.
- Bengaluru, known as the IT capital of India, witnesses a continuous influx of new restaurants to meet the growing demand for convenient dining options.
- Many people here rely on restaurant food due to time constraints. 
- Despite the increasing demand, newcomers often struggle to compete with established eateries, often offering similar menus.
- Given the overwhelming demand for restaurants, it becomes crucial to examine the demographic characteristics of different localities.
- To address these questions, we will leverage the Zomato dataset to analyze the following factors:
	- Location of the restaurant
	- Approximate price of food
	- Theme-based restaurant categorization
	- Localities with the highest concentration of specific cuisines
	- Meeting the culinary needs of residents
- We were able to scrape the Zomato website successfully and extract around 3,000 records.

## Methodology 🛠️
### Phase I,
Web Scrapping 
Scrapped the data using Beautiful soup and Selenium for scrolling

### Phase II,
Data Preprocessing
Cleaning the Raw data using Numpy, Panadas  and Excel 

### Phase III,
Model Building 
Worked on different models and Random Forest was the best suitable

### Phase IV,
Model Deployment
Deployed the model on HTML webpage


## Sections 📚
✔️ Exploratory Data Analysis\
✔️ Visualization \
✔️ Rate Prediction\
✔️ Restraurant Prediction\
✔️ Recommendation System

## Quick Summary

    1. Using Selenium And BeautifulSoup libraries of Python we Extracted data present on page and stored it in series and merging them to get DatFrame
    	a)MainPage Scrapper
	
![image](https://github.com/SaketSuhane/Recommendation_Model_Zomato/assets/123991455/bcf3804c-4734-40e8-b303-fd905eadb7c3)


![image](https://github.com/SaketSuhane/Recommendation_Model_Zomato/assets/123991455/539d66e8-cf48-4874-a548-eddbb9e4b365)

   
    	b)Restaurants info Scrapper
    
![image](https://github.com/SaketSuhane/Recommendation_Model_Zomato/assets/123991455/577b3980-c832-4306-8b92-a1974549808b)


![image](https://github.com/SaketSuhane/Recommendation_Model_Zomato/assets/123991455/ce8083e6-d33f-4974-88f4-961433711cb1)


![image](https://github.com/SaketSuhane/Recommendation_Model_Zomato/assets/123991455/05620b7e-e18c-4fff-8fd4-29dfb7d3afa8)

 
    2. After obtaining the DataFrame we performed some data cleansing operation using Power Querry Editor , Excel and obtained a single table.
    	a) Raw Data 
	
	Table 1 :
![image](https://github.com/SaketSuhane/Recommendation_Model_Zomato/assets/123991455/8a3b450c-cc24-4d73-a731-450b2a95c910)
      
      	Table 2 :
![image](https://github.com/SaketSuhane/Recommendation_Model_Zomato/assets/123991455/e6ed4bf2-f460-472e-b808-6d78a3a5b9d6)

      a) Cleaned Table and Joined Table 
      
     Final Table :
![image](https://github.com/SaketSuhane/Recommendation_Model_Zomato/assets/123991455/d79eb1bf-3fa4-4f29-83d5-5dc821c799e9)

       
    3. After joining the tables, we imported the dataset into Power BI in order to visualize the data.
    
    4. In Power Bi, we made some useful KPI's and some user friendly charts.
    
    5. Created a interactive and dynamic dashboard at the end using Power Bi and generated some useful insights.


## Dashboards
- **Excel**:

![image](https://github.com/Venkatesh-Nayk/Zomato-Bangalore-Data-Analysis/assets/129421850/44865ccd-8ef1-411d-a488-92e921245ab0)

- **PowerBI**:

![image](https://github.com/Venkatesh-Nayk/Zomato-Bangalore-Data-Analysis/assets/129421850/0dc43f71-b0cc-4b47-bd76-d97e2f292e44)

## Conclusion
- As per our analysis, if the person wants to open a remote kitchen in Bangalore he/she should prefer opening it in Shanti Nagar or Basavanagudi, since the place is having less no of restaurant which reduces the competition and it has some of the expensive restaurants in the Banglore, hence the person can deliver food at lower price which reduces the competition even further.

- The second suggestion would be sell North Indian, South Indian cuisine as they are demanded the most by the customers and they can keep the price ranging from 300 - 400 Rs for Non vegetarian category and 200 - 300 Rs for vegetarian category.

## Challenges Faced

There are several limitations and challenges that arised during the project. Some potential challenges include:
   
   - Learning web scraping with different tools was challenging due to the diversity of tools, evolving website structures, anti-scraping measures, and the need for data cleaning and 
     preprocessing.
   - Dynamic page scrolling posed an additional challenge during the data scraping process, requiring specific techniques and tools to effectively capture and extract the desired 
     information from web pages that load content dynamically as the user scrolls.
   - Data quality and consistency were compromised in the scraped data from Zomato, with errors, missing values, and inconsistencies present, thereby impacting the integrity of the raw 
     dataset.




