# 1mg-analysis-project








![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/9f31e58a-29b2-47c8-9885-5f255a2a1296)











## Project Description:
In the era of data-driven decision-making, harnessing valuable insights from web data can be a game-changer for businesses. This project exemplifies the power of data acquisition, analysis, and visualization by leveraging web scraping techniques. Using the Python programming language and the BeautifulSoup library, we embarked on a journey to extract essential information from the 1mg website, a prominent online pharmaceutical and healthcare platform. Our objective was to transform raw web data into actionable insights that could drive informed decisions and bolster profitability.




## 🛠 Tools used


BeautifullSoup,Excel,Python




## Project Highlights:
#### 1) Web Scraping and Data Extraction:
We initiated the project by employing BeautifulSoup to scrape crucial data from the 1mg website. This encompassed extracting data from tables, ensuring data integrity, and structuring it for further analysis.

#### 2) Data Transformation and Export:
To facilitate in-depth analysis, we seamlessly transformed the extracted data into an Excel spreadsheet. This step involved organizing columns, handling data types, and preparing the dataset for insightful exploration.

#### 3) Data Analysis and Visualization:
With the cleaned and structured dataset in hand, we delved into a comprehensive analysis. Employing data visualization libraries, such as Matplotlib and Seaborn, we crafted a series of informative charts, graphs, and visualizations. These visual representations unearthed trends, patterns, and correlations within the data, providing a deeper understanding of the pharmaceutical landscape.

#### 4) Dashboard Creation:
The pinnacle of our project was the creation of an interactive dashboard. Leveraging tools like Tableau or Power BI, we designed a user-friendly dashboard that encapsulated key findings, trends, and actionable insights derived from the data. This dashboard served as a one-stop hub for decision-makers to access critical information and make informed choices swiftly.

#### 5) Strategic Insights for Profitability:
Our analysis culminated in the generation of strategic insights. These insights encompassed market trends, product performance, pricing strategies, and customer behavior. By presenting these insights in a digestible format through our interactive dashboard, we equipped stakeholders with the tools needed to make data-driven decisions aimed at enhancing profitability and optimizing business operations.

This project exemplifies the fusion of web scraping, data analysis, and data visualization to convert raw web data into a valuable asset for decision-makers. By distilling complex information into actionable insights, we empower businesses to thrive in a competitive market landscape.


## Aim:
To harness the power of web scraping, data analysis, and data visualization techniques to transform raw data from the 1mg website into actionable insights and an interactive dashboard. The aim is to equip decision-makers in the pharmaceutical and healthcare domain with the tools and information needed to make informed choices, optimize pricing strategies, enhance product offerings, and ultimately increase profitability.


## Web scrapping 


#### This Python script scrapes product URLs from 1mg's homeopathy category, mimicking a web browser's behavior. It gathers these URLs for subsequent data collection and analysis.





![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/f646d163-fba6-45de-9585-0c358db02a72)






#### This Python script sets a time limit for web scraping requests and initializes empty lists to store data such as product names, brand names, key benefits, key ingredients, product ratings, and the number of ratings. It iterates through a list of product URLs, sending HTTP GET requests to each product page and parsing the HTML content using BeautifulSoup. The script then extracts and stores information for each product, including its name, brand, key benefits, key ingredients, rating, and the number of ratings. It introduces a small delay between requests. Finally, it organizes the scraped data into a DataFrame for further analysis.




![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/d18ba068-b9e9-47fb-85d9-2bacb53c1c87)







![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/40913278-0ace-4319-9863-2e630951b290)














## Visualizations:


#### Most popular Brands

![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/8a040730-5ef3-4aab-b5de-85bbd7d74454)






#### Relationship between average rating and price 


![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/3d723806-ad02-4a2b-bb07-747f4050923f)






#### Distrbitution of customer ratings 







![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/4d7f6976-fa80-418f-8c44-3825bc3d575f)







#### Top 10 Highest rated brands  









![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/756ce5ca-5a24-4a89-b50a-d87257e25670)









#### Key incredients in top 5 rated brands 






![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/ac3f5b1a-50e3-473a-a1b0-dbfcae547db9)








#### Top 5 most expensive Key benefit Areas 





![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/ae3590c9-6e5b-48d6-a65b-b0cca23959d5)








#### Bottom 5 Key Benefits Acc. To   Total Prodcuts Ordered  




 


![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/4b03a88f-f547-400d-b36a-5f200e5dcee7)









## Dashboard 






![image](https://github.com/aayushkataria123/1-mg-data-anlytics-project/assets/137820574/ce08123c-9426-4cd9-b088-6c9771c711ab)











## Suggestions:
1) Capitalize on the popularity of SBL Pvt Ltd. by prominently featuring its products and offering special promotions to attract more customers and boost sales.

2) Consider reviewing and optimizing the pricing strategy, especially for products with lower ratings, to improve customer satisfaction and potentially increase average ratings.

3) Analyze the distribution of customer ratings to identify areas for improvement, focusing on enhancing products with lower ratings to enhance overall customer satisfaction.


4) Leverage the high rating of Similia Homeo Laboratory to build trust with customers. Highlight this brand's positive reviews in marketing materials and on the website.

5) Promote Phenolphthalein 1x as it was the most popular product among the top 5 highest-rated brands. Consider bundling it with other products to cross-promote and increase sales.

6) Evaluate the pricing strategy for products in the "Hair" key benefit area to ensure it aligns with market expectations while maintaining product quality.

7) Diversify the product range in the "Hair" section to cater to a broader audience. Introduce budget-friendly options to capture a wider customer base.

## Challenges faced:
1) Navigating and scraping data from dynamically changing webpages on the 1mg website, where content could vary across pages.

2) Identifying the most suitable chart types that not only effectively convey insights but are also visually appealing.

3)  Creating an interactive dashboard that seamlessly integrates data, insights, and user-friendly functionality.
