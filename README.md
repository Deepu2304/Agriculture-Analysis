# Agriculture-Analysis 
# Crop Production in India
# 1. Introduction
## Project Overview
The project focuses on analyzing crop yield, types, and agricultural areas in India. It delves into understanding the trends in crop production over time and categorizing crops based on their types and distribution across regions. Assess the impact of various factors like climate, region, and farming practices on crop productivity.Utilizing a range of data analysis and visualization tools, our objective is to extract valuable insights regarding pricing dynamics, availability patterns, and location-based trends within crop data listings.
# Objectives
The primary objectives of this project include:

1. Ensure data quality and consistency by addressing missing values, outliers, and duplicates.
2. Standardize data formats and rectify inconsistencies in column names or values.
3. Validate and clean geographic coordinates, zip codes, and other location-based data to maintain data integrity.
4. Utilize EDA techniques to grasp data distributions, trends, and interrelationships.
5. Summarize and visualize key features using descriptive statistics, histograms, scatter plot and heat map
6. Identify correlations between variables and uncover potential patterns or anomalies.
7. Analyzing geographic trends analysis to identify spatial clusters, hotspots, or patterns in Airbnb listings or amenities distribution.
8. Visualization process utilizes various tools and libraries, such as matplotlib, Seaborn, Plotly, to generate static and interactive visualizations like plots and charts.
# About Dataset
This dataset provides a huge amount of information on crop production in India ranging from several years. Based on the Information the ultimate goal would be to predict crop production using powerful machine learning techniques.The dataset covering crop production in India from 1997 to 2015 offers a rich repository of agricultural information spanning multiple years.

The provided dataset contains information on crop production in India spanning from 1997 to 2015, with entries for various states, districts, crop years, seasons, crop types, areas, and production quantities. Each entry represents the production data for a specific crop in a particular district and state for a given year and season. The dataset includes details such as the state name, district name, crop year, season, crop type, area under cultivation, and the corresponding production quantity. This sample provides a snapshot of the dataset's structure and the kind of information it contains, allowing for further exploration and analysis of crop production trends and patterns in India.

# Datasets:
## State_Name: 
This column represents the name of the Indian state where the crop production data was recorded.
## District_Name: 
It specifies the name of the district within the state where the crop production data was collected.
## Crop_Year: 
This column indicates the year in which the crop was cultivated and harvested.
## Season: 
It denotes the season during which the crop was grown, such as Kharif (monsoon season), Rabi (winter season), or Whole Year (across multiple seasons).
## Crop: 
This column specifies the type or name of the crop that was cultivated.
## Area: 
It represents the area of land (in hectares or other relevant units) used for cultivating the specified crop.
## Production: 
This column indicates the quantity or amount of the crop produced, typically measured in metric tons or other appropriate units.

# 2. Methodology
## Data Collection
Gather relevant datasets from sources such as season , Area, Production and Crop reports.

## Data Cleaning
Identify and address missing values, outliers, and inconsistencies in the datasets to ensure data integrity and accuracy.

## Exploratory Data Analysis (EDA)
Explore the datasets to understand distributions, trends, and relationships between variables using descriptive statistics and data visualization techniques.

![download](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/c5293ce6-51ea-4840-9367-1abe4de62db9)

The bar chart titled "Crop yield (by year)" illustrates the crop production trend over the years from 1997 to 2015. The x-axis is labeled as "Crop_Year," denoting the respective years, while the y-axis represents the count of crops. Notably, the visualization reveals a consistent upward trend in crop production, indicating a steady increase in the number of crops cultivated annually. Notably, the highest count of crops is observed in 2015, suggesting a peak in agricultural output during that year. Overall, the chart provides a clear depiction of the progressive growth in crop yield over the examined period, highlighting the agricultural sector's sustained development and productivity.

![download-1](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/b7422aa8-569c-4465-ae66-05dcd370c3c2)

The bar graph titled "Seasonal Count Distribution" provides a comprehensive overview of the count distribution across distinct seasons. Each bar on the graph corresponds to a specific season, namely Kharif, Whole Year, Autumn, Rabi, Summer, and Winter. The x-axis is dedicated to delineating these seasons, providing a clear visual representation of their respective counts. Notably, the count values vary significantly across the seasons, with Kharif emerging as the season with the highest count. This suggests a pronounced occurrence or activity during the Kharif season compared to others. Following Kharif, Whole Year and Autumn exhibit moderately high counts, indicating sustained activity throughout the year and a notable increase during the Autumn months. Conversely, the counts for Rabi, Summer, and Winter are noticeably lower, signifying a relatively lower occurrence or activity during these seasons. The graph thus highlights the distinct seasonal trends in the distribution of the counted entities, offering valuable insights into their temporal patterns and variations.

![newplot copy](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/854f51f4-6e2c-4973-85d2-ea15c25adbb8)

The graph shows the production per unit area of a commodity in different states of India. The x-axis of the graph shows the states, while the y-axis shows the production per unit area. The bars in the graph represent the production per unit area for each state.
From the graph, we can see that the state with the highest production per unit area is Kerala, followed by Andaman and Nicobar Islands. The states with the lowest production per unit area are Puducherry and Goa.
We can also see that there is a large variation in production per unit area between different states. For example, the production per unit area in Kerala is more than 10 times higher than the production per unit area in Puducherry.
This variation in production per unit area is likely due to a number of factors, including the climate, soil conditions, and availability of resources.

 - Kerala is the most productive state when we compare in terms of production by area.
 - We see Andaman and nikobar islands, Goa, Panduchery and many other states which are low in overall production, have high productivity when we compare with the crop areas.


![newplot](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/2d7a22c0-c743-449c-a52d-67a40fa57a7a)


The provided graph illustrates "the state-wise production distribution of a specific commodity across various regions of India". The x-axis represents the states, while the y-axis denotes the corresponding production values. Notably, the states are arranged in descending order based on their production, showcasing Kerala with the highest production and Dadra and Nagar Haveli and chandigarh with the lowest.

Delving deeper, the top 10 states contributing to production dominance include Kerala, Andhra Pradesh, Tamil Nadu, Uttar Pradesh, Assam, West Bengal, Maharashtra, Haryana, Karnataka, and the Andaman and Nicobar Islands. Conversely, the bottom 10 states in terms of production are Dadra and Nagar Haveli, Sikkim, Mizoram, Arunachal Pradesh, Nagaland, Meghalaya, Tripura, Manipur, Chandigarh, and Goa.

The graph's data offers multifaceted insights, serving various analytical purposes. Firstly, it facilitates the identification of states playing pivotal roles in commodity production, shedding light on regional productivity disparities. Secondly, it enables a comparative analysis of production levels across different states, aiding in understanding regional strengths and weaknesses in commodity production. Moreover, the graph can be instrumental in tracking production trends over time, facilitating trend analysis and forecasting. Lastly, it paves the way for identifying and investigating factors influencing production variations among different states, contributing to informed decision-making processes in commodity management and policy formulation.

 - Kerala is the highest crops producing state overall. It had produced more than 500% crop than it's runner up state Andhra Pradesh.
 - Top 3 crop producing states are from south India, which put together leave no space to compare rest states.

![newplot (1)](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/00c6724d-ebdb-45df-9051-83f336aebfa8)

The graph illustrates the trend in crop production from 1998 to 2015, with production measured in billions on the y-axis and the crop year on the x-axis. The highest production was recorded in 2011, reaching 14 billion, while the lowest production occurred in 2015, totaling 8 million. The graph provides a clear depiction of the fluctuating production levels over the years, highlighting both peak and trough periods. This information aids in understanding the variations in crop production over the specified timeframe, offering valuable insights for analysis and decision-making.

![newplot (2)](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/cff73ac8-be88-44a8-a10f-f06748f87440)

The graph depicts the correlation between crop area and crop year, with the crop year on the x-axis and crop area on the y-axis. It reveals a decreasing trend in crop area over time. Specifically, the largest crop area was observed in 1997, while the smallest crop areas were recorded in 2002 and 2003. Notably, the years 2002 and 2003 had the lowest average crop area, excluding 2015 due to limited data availability. This trend underscores a notable decline in crop area over the years, highlighting potential factors influencing agricultural practices during this period.

 - Average Crop Area has decresed over the years.
 - We had the lowest Average Crop area in Years 2002 and 2003. (We have very comparitively very less data of year 2015 so, we'll not consider that)

![newplot (3)](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/f59b4b40-9ec6-4153-b9d9-55a379d42c08)

The graph illustrates the crop production distribution across various districts within a region. District names are depicted along the x-axis, while the corresponding crop production quantities, measured in tons, are represented on the y-axis.

At one end of the spectrum, Mumbai and Namsai emerge as the least crop-producing districts, each registering a production of 0 tons. Conversely, Malappuram and Kozhikode stand out as the highest crop-producing districts, each boasting an impressive production figure of 16 billion tons.

Further analysis reveals additional districts with substantial crop production. Notably, Malappuram, Kozhikode, and Thiruvananthapuram demonstrate notable performance, yielding 14 billion, 12 billion, and 10 billion tons of crops, respectively.

On the opposite end, apart from Namsai and Mumbai, districts like Khunti, Ramgarh, and Hyderabad exhibit comparably lower crop production levels, ranging from 2000 to 5000 tons, highlighting the disparities in agricultural output across the region.


 - Mumbai and Namsai districts show minimal crop production, registering 0 tons.
 - Malappuram and Kozhikode emerge as top crop-producing districts, each boasting 16 billion tons of production.
 - Additional districts like Thiruvananthapuram also demonstrate notable performance, with 10 billion tons of crop yield.
 - Disparities in agricultural output are evident, with districts like Khunti, Ramgarh, and Hyderabad exhibiting lower production levels ranging from 2000 to 5000 tons.

![newplot (4)](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/6bcb16eb-46a3-49d1-9480-5974266a58f8)

The graph illustrates the production of five essential crops: Potato, Wheat, Rice, Sugarcane, and Coconut. Crop names are positioned along the x-axis, while the corresponding production quantities, measured in billions, are displayed on the y-axis.

Among these crops, Coconut emerges as the top producer, boasting a substantial production volume of approximately 120 billion units. Following closely behind is Sugarcane, with a production yield of approximately 6 billion units.

Conversely, Potato records the lowest production output among the featured crops, with a modest yield of around 434 million units. This disparity in production levels underscores the varying importance and contribution of each crop to the agricultural landscape.

 - Coconut tops the production chart with an impressive volume of around 120 billion units.
 - Sugarcane follows closely behind, boasting a production yield of approximately 6 billion units.
 - Potato records the lowest production output among the crops, with a modest yield of around 434 million units.

![download-2](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/8b9c79f5-bf24-444d-bb07-c0097265b0b9)

The graph depicts the production of a specific crop across various states in India spanning from 1997 to 2015. It encompasses a diverse range of states, including Andaman and Nicobar Islands, Andhra Pradesh, Arunachal Pradesh, Assam, Bihar, Chandigarh, Chhattisgarh, Dadra and Nagar Haveli, Daman and Diu, Delhi, Goa, Gujarat, Haryana, Himachal Pradesh, Jammu and Kashmir, Jharkhand, Karnataka, Kerala, Lakshadweep, Madhya Pradesh, Maharashtra, Manipur, Meghalaya, Mizoram, Nagaland, Odisha, Puducherry, Punjab, Rajasthan, Sikkim, Tamil Nadu, Telangana, Tripura, Uttar Pradesh, Uttarakhand, and West Bengal.

On the graph, the y-axis represents production in thousand tonnes, while the x-axis delineates the crop years. It illustrates the fluctuating trend in crop production over the specified period, showcasing both increases and decreases in production across different states.

The visual representation offered by the graph encapsulates the dynamic nature of crop production, providing insights into the variations observed among states over the 18-year duration. This comprehensive overview aids in understanding the agricultural landscape and production dynamics across various regions of India.

![download-3](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/d96fa081-32af-4092-8742-09ed3eca828f)

The image presents seven line graphs, each delineating the production trends of distinct crops across different geographical zones over the period from 1997 to 2014. The x-axis of each graph denotes the crop year, while the y-axis quantifies the production in thousands.

The zones represented in the graphs include Union Territory, South Zone, Northeast Zone, East Zone, North Zone, Central Zone, and West Zone. Each zone's graph illustrates the production dynamics specific to its geographical region, offering insights into how crop production has evolved over the specified timeframe.

Through these visual representations, viewers can discern the variations in crop production trends across different zones, facilitating a comprehensive understanding of agricultural dynamics within each geographical region over the seventeen-year duration.

![download-4](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/2a3075fe-b629-4362-a562-bf5b22199384)

The bar graph illustrates the aggregate production across various zones in India. The x-axis delineates the zones, while the y-axis quantifies the production in units. The zones encompass South Zone, North Zone, West Zone, Northeast (NE) Zone, East Zone, Union Territory, and Central Zone.

Notably, the South Zone boasts the highest production among all zones, with the North Zone following closely behind. Subsequently, the West Zone, NE Zone, East Zone, Union Territory, and Central Zone exhibit progressively lower production levels, showcasing a descending trend across the zones.


![download-5](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/d3a19b00-adb4-4d8f-ba01-f13f8c290194)

The graph illustrates the production of various seasonal crops, with the x-axis denoting the crop season and the y-axis representing production in units of 10^10. Specifically, it highlights three distinct crops: Kharif, Rabi, and Others.

Remarkably, the crop category "Others" exhibits the highest production levels among the three, surpassing both Kharif and Rabi. Following "Others," Kharif crops rank second in production, while Rabi crops represent the lowest production category, indicating a descending order of production across the depicted seasonal crops.


![download-6](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/13d99a03-edcc-416b-81eb-0b3cde332c25)

The graph titled "Top 10 Crops in Kharif Season: Production" showcases the leading crops cultivated during the Kharif season, emphasizing their production volumes. On the x-axis, each crop is meticulously listed, while the y-axis quantifies the production in the respective unit of measurement. The data presents a comprehensive overview of the top 10 crops, highlighting their significance in the agricultural landscape during the Kharif season. Notably, Sugarcane emerges as the dominant crop, followed closely by Rice and Cotton. Maize, Bajra, Jowar, Moth, Moong (Green Gram), Ragi, and Guar seed also feature prominently in the ranking, underlining their contribution to the seasonal agricultural output. This visualization offers valuable insights into the cropping pattern and production dynamics, aiding stakeholders in strategic decision-making and resource allocation within the agricultural sector.

 - Sugarcane emerges as the dominant crop during the Kharif season.
 - Rice and Cotton follow closely behind in terms of production volume.
 - Other prominently featured crops include Maize, Bajra, Jowar, Moth, Moong (Green Gram), Ragi, and Guar seed.
 - The visualization provides valuable insights into cropping patterns and production dynamics during the Kharif season.

![download-7](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/19428ac5-e037-4570-9445-56f5b709faa3)

The bar graph illustrates the production of sugarcane across various geographical zones. With the x-axis denoting the zones and the y-axis representing production in tons, the graph delineates seven distinct zones: North Zone, West Zone, Central Zone, East Zone, NE Zone, South Zone, and Union Territories. A discernible pattern emerges, indicating the North Zone as the primary contributor to sugarcane production, trailed closely by the West Zone and the South Zone.

Conversely, the Central Zone registers comparatively lower production figures, while the Northeast Zone records the least output. The disparity in sugarcane production among zones underscores the influence of diverse factors such as climate, soil composition, and water accessibility.

Notably, the North Zone's production outstrips that of the Union Territories by more than double, accentuating the substantial variability in production levels across regions. 

This insight underscores the multifaceted nature of agricultural dynamics, highlighting the pivotal role of environmental and geographical factors in shaping crop yields and regional agricultural economies.

![download-8](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/b3a2122e-43e9-45aa-a896-1dea42a9d956)

The graph provides a comprehensive overview of sugarcane production across key states in India. With the x-axis delineating state names and the y-axis representing production in tonnes, the focus is on four prominent sugarcane-producing states: Uttar Pradesh, Maharashtra, Tamil Nadu, and Karnataka. Uttar Pradesh emerges as the frontrunner in sugarcane production, boasting the highest output among the selected states. Following closely, Maharashtra ranks second in production, demonstrating its significant contribution to the sugarcane industry. Tamil Nadu and Karnataka trail behind, albeit still contributing substantially to the overall production landscape. 

This distribution underscores the regional diversity and significance of sugarcane cultivation in India's agricultural sector. Uttar Pradesh's dominant position in sugarcane production aligns with its status as a key agricultural hub, while Maharashtra, Tamil Nadu, and Karnataka also play pivotal roles in bolstering the nation's sugarcane output. The graph serves as a visual testament to the varied geographical distribution of sugarcane cultivation and its integral role in India's agricultural economy.

![download-9](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/12c22cee-9f41-4153-a333-17deabb461a7)


The bar graph depicts the sugarcane production distribution across various districts of Uttar Pradesh, India, with district names along the x-axis and sugarcane production area on the y-axis. Kheri emerges as the leading contributor to sugarcane cultivation, boasting the highest production area among all districts, closely followed by Muzaffarnagar and Bijnor. Conversely, Meerut and Saharanpur exhibit notably lower sugarcane production areas, indicating significant regional disparities. This variation underscores the diverse agricultural landscape of Uttar Pradesh, where factors such as soil quality, climate conditions, and agricultural practices influence production outcomes. The graph serves as a visual representation of the intricate dynamics shaping sugarcane cultivation patterns across the state, highlighting the need for targeted interventions to address regional disparities and promote agricultural sustainability.


![download-10](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/e40ae7ca-04b8-4890-815b-7b05daea5ad0)

The graph shows the production of various Rabi crops in a region. The crops are listed on the left-hand side of the graph, and their production is shown in tons on the right-hand side. The crops are listed in order of their production, with the highest-producing crop at the top.
The graph shows that the highest-producing Rabi crop is potato, followed by banana and gram. The lowest-producing crops are castor seed and barley.
The graph also shows that the production of Rabi crops varies considerably. For example, potato production is much higher than castor seed production.
This graph could be used to inform decisions about which Rabi crops to grow in a region. For example, farmers might choose to grow crops that are high-producing and in high demand.

![download-11](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/25de2b87-dea5-4ecb-8583-ed668a592a02)


The bar graph illustrates the potato production across various zones, with the x-axis denoting the zones and the y-axis representing production in thousands of tonnes. Among the zones, the East Zone emerges as the top producer, followed closely by the North and West Zones. Conversely, the South and North East Zones record the lowest potato production levels. This disparity in production highlights regional variations in potato cultivation across different zones in the country.

Notably, the graph emphasizes the dominance of the North Zone in potato production, showcasing its significance as a leading contributor to the overall output. Conversely, the South Zone exhibits comparatively lower potato production levels, indicating potential challenges or limitations in potato cultivation practices prevalent in that region. Overall, the graph provides valuable insights into the regional distribution of potato production, underscoring the need for targeted strategies to address disparities and enhance potato cultivation efficiency across various zones.

![download-12](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/b0ce506a-8d4e-40f6-8e51-85196411cc8a)

The graph depicts the potato production in four prominent states of India: Uttar Pradesh, West Bengal, Gujarat, and Bihar. Across these states, Uttar Pradesh emerges as the leading producer, showcasing its significant contribution to the overall potato output. Following Uttar Pradesh, West Bengal occupies the second position in terms of potato production, with Gujarat and Bihar trailing behind. This distribution of production underscores the agricultural prominence of these states and their respective roles in meeting the demand for potatoes across the country.

Moreover, the graph highlights the regional disparities in potato production, with Uttar Pradesh dominating the landscape as the primary potato-producing state. Meanwhile, West Bengal, Gujarat, and Bihar play crucial roles in supplementing the national potato supply, albeit to varying degrees. Overall, the graph provides valuable insights into the state-wise distribution of potato production, offering key data points for policymakers and stakeholders involved in agricultural planning and management.

![download-13](https://github.com/Deepu2304/Agriculture-Analysis/assets/86673603/28219056-8681-4c53-9ea9-3b76da173767)

The bar graph illustrates the potato production across various districts of Uttar Pradesh, a significant agricultural hub in India. With the x-axis representing the districts and the y-axis denoting potato production in quintals, the graph offers a comprehensive overview of the distribution of potato cultivation in the state. Among the districts showcased, Agra emerges as the frontrunner, leading the pack in potato production. Following closely behind are Kannauj, Firozabad, Farrukhabad, and Hathras, each contributing significantly to the state's potato output.

This depiction of potato production underscores the agricultural diversity and productivity within Uttar Pradesh, with different districts specializing in potato cultivation to varying extents. By presenting these production figures, the graph provides valuable insights into the regional dynamics of potato farming in Uttar Pradesh, offering stakeholders and policymakers a deeper understanding of the state's agricultural landscape and potential areas for development and optimization.

# Conclusion

the analysis of crop production in India offers valuable insights into the country's agricultural landscape, productivity trends, and regional disparities. Through comprehensive data collection, cleaning, and exploratory data analysis (EDA), we gained a deeper understanding of the factors influencing crop production and distribution over time.

The visualization of crop yield trends, seasonal count distribution, state-wise production distribution, and production per unit area highlighted significant patterns and variations across different regions and crop types. These insights can inform strategic decision-making processes for stakeholders, policymakers, and agricultural practitioners.

Moreover, the exploration of specific crop production across states, districts, and zones provided nuanced insights into the agricultural dynamics at various scales. Understanding the variations in crop production and distribution is crucial for optimizing resource allocation, enhancing productivity, and addressing regional disparities within the agricultural sector.

Overall, this project lays the foundation for further research and analysis aimed at leveraging data-driven approaches to enhance agricultural productivity, sustainability, and resilience in India. By harnessing the power of data analytics and visualization techniques, we can drive positive transformations in the agricultural sector, contributing to food security, economic growth, and rural development initiatives.
