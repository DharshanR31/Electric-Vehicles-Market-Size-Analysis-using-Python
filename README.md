# Electric-Vehicles-Market-Size-Analysis-using-Python

Market size analysis is a crucial aspect of market research that determines the potential sales volume within a given market. It helps businesses understand the magnitude of demand, assess market saturation levels, and identify growth opportunities. So, if you want to learn how to perform a market size analysis of any product, this article is for you. In this article, I’ll take you through the task of Electric Vehicles market size analysis using Python.

## Electric Vehicles Market Size Analysis: Process We Can Follow
Market size analysis for electric vehicles involves a multi-step process that includes defining the market scope, collecting and preparing data, analytical modeling, and communicating findings through visualization and reporting. Below is the process you can follow for the task of electric vehicles market size analysis:

Define whether the analysis is global, regional, or focused on specific countries.
Gather information from industry associations, market research firms (e.g., BloombergNEF, IEA), and government publications relevant to the EV market.
Use historical data to identify trends in EV sales, production, and market.
Analyze the market size and growth rates for different EV segments.
Based on the market size analysis, provide strategic recommendations for businesses looking to enter or expand in the EV market.
So, we need an appropriate dataset for the task of market size analysis of electric vehicles. I found an ideal dataset for this task. You can download the dataset from [here](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python)
## Electric Vehicles Market Size Analysis using Python
Now, let’s get started with the task of electric vehicles market size analysis by importing the necessary Python libraries and the [dataset](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python):

![head](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/ec1f955e-62a2-463a-a4b2-9c9a47e95428)

So, this data is based on the EV population in the United States.


For the task of market size of electric vehicles analysis, we can explore the following areas:

1. EV Adoption Over Time: Analyze the growth of the EV population by model year.
2. Geographical Distribution: Understand where EVs are most commonly registered (e.g., by county or city).
3 EV Types: Breakdown of the dataset by electric vehicle type (BEV, etc.).
4. Make and Model Popularity: Identify the most popular makes and models among the registered EVs.
5. Electric Range Analysis: Analyze the electric range of vehicles to see how EV technology is progressing.
6. Estimated Growth in Market Size: Analyze and find the estimated growth in the market size of electric vehicles.

Let’s start with analyzing the EV Adoption Over Time by visualizing the number of EVs registered by model year. It will give us an insight into how the EV population has grown over the years:

![image](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/0ea88ce6-a954-4827-b1c9-906300cc2f14)

From the above bar chart, it’s clear that EV adoption has been increasing over time, especially noting a significant upward trend starting around 2016. The number of vehicles registered grows modestly up until that point and then begins to rise more rapidly from 2017 onwards. The year 2023 shows a particularly sharp increase in the number of registered EVs, with the bar for 2023 being the highest on the graph, indicating a peak in EV adoption.

Now, let’s start by selecting the top 3 counties based on EV registrations and then analyze the distribution of EVs within the cities of those counties:

![image](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/05b01e42-4cd3-448d-85d9-489831a42aa7)

The above graph compares the number of electric vehicles registered in various cities within three counties: King, Snohomish, and Pierce. The horizontal bars represent cities, and their length corresponds to the number of vehicles registered, color-coded by county. Here are the key findings from the above graph:

* Seattle, which is in King County, has the highest number of EV registrations by a significant margin, far outpacing the other cities listed.
* Bellevue and Redmond, also in King County, follow Seattle with the next highest registrations, though these are considerably less than Seattle’s.
* Cities in Snohomish County, such as Kirkland and Sammamish, show moderate EV registrations.
* Tacoma and Tukwila, representing Pierce County, have the fewest EV registrations among the cities listed, with Tacoma slightly ahead of Tukwila.
* The majority of cities shown are from King County, which seems to dominate EV registrations among the three counties.
* Overall, the graph indicates that EV adoption is not uniform across the cities and is more concentrated in certain areas, particularly in King County.


Next, let’s explore the types of electric vehicles represented in this dataset. Understanding the breakdown between different EV types, such as Battery Electric Vehicles (BEV) and Plug-in Hybrid Electric Vehicles (PHEV), can provide insights into consumer preferences and the adoption patterns of purely electric vs. hybrid electric solutions. So, let’s visualize the distribution of electric vehicle types to see which categories are most popular among the registered vehicles:

![3](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/62861cf3-6917-4414-ad8d-98a4adf910da)

The above graph shows that BEVs are more popular or preferred over PHEVs among the electric vehicles registered in the United States.

Let’s now focus on the popularity of electric vehicle manufacturers and models among the registered vehicles. This analysis will help us identify which manufacturers and specific models dominate the EV market, potentially indicating consumer preferences, brand loyalty, and the success of various manufacturers’ strategies in promoting electric mobility.

So, let’s have a look at the most popular manufacturers and then drill down into the most popular models within those manufacturers:

![4](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/051de104-fabc-4b45-9190-01c98bec4114)

The above chart shows that:

* TESLA leads by a substantial margin with the highest number of vehicles registered.
* NISSAN is the second most popular manufacturer, followed by CHEVROLET, though both have significantly fewer registrations than TESLA.
* FORD, BMW, KIA, TOYOTA, VOLKSWAGEN, JEEP, and HYUNDAI follow in decreasing order of the number of registered vehicles.
  
Next, let’s drill down into the most popular models within these top manufacturers to get a more detailed understanding of consumer preferences at the model level:


![image](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/19cd2cf8-a51a-410a-b304-e0a8e7f38337)

The above graph shows the distribution of electric vehicle registrations among different models from the top three manufacturers: TESLA, NISSAN, and CHEVROLET. Here are the findings:

* TESLA’s MODEL Y and MODEL 3 are the most registered vehicles, with MODEL Y having the highest number of registrations.
* NISSAN’s LEAF is the third most registered model and the most registered non-TESLA vehicle.
* TESLA’s MODEL S and MODEL X also have a significant number of registrations.
* CHEVROLET’s BOLT EV and VOLT are the next in the ranking with considerable registrations, followed by BOLT EUV.
* NISSAN’s ARIYA and CHEVROLET’s SPARK have the least number of registrations among the models shown.
  
Next, we’ll explore the electric range of vehicles, which is a critical factor for analyzing the market size of electric vehicles. The electric range indicates how far an EV can travel on a single charge, and advancements in battery technology have been steadily increasing these ranges over the years. So, let’s look at the distribution of electric ranges in the dataset and identify any notable trends, such as improvements over time or variations between different vehicle types or manufacturers:

![6](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/a7d6fa06-101b-40a5-a11c-95c3a0ef2009)

The above graph shows the mean electric range. Key observations from the graph include:

* There is a high frequency of vehicles with a low electric range, with a significant peak occurring just before 50 miles.
* The distribution is skewed to the right, with a long tail extending towards higher ranges, although the number of vehicles with higher ranges is much less frequent.
* The mean electric range for this set of vehicles is marked at approximately 58.84 miles, which is relatively low compared to the highest ranges shown in the graph.
* Despite the presence of electric vehicles with ranges that extend up to around 350 miles, the majority of the vehicles have a range below the mean.

It suggests that while there are EVs available with high electric ranges, the average range is skewed lower due to a substantial number of vehicles with shorter ranges.

Now, let’s delve into the trend of electric ranges over model years, which can provide insights into how advancements in battery technology and vehicle design have influenced the electric range capabilities of electric vehicles over time. A positive trend in this analysis would indicate continuous improvements, offering consumers EVs with longer driving ranges and potentially addressing one of the major concerns regarding the EV market (range anxiety):

![7](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/0f7d595e-d732-4351-92ad-4cfda61e7cc0)

The above graph shows the progression of the average electric range of vehicles from around the year 2000 to 2024. Key findings from the graph:

* There is a general upward trend in the average electric range of EVs over the years, indicating improvements in technology and battery efficiency.
* There is a noticeable peak around the year 2020 when the average range reaches its highest point.
* Following 2020, there’s a significant drop in the average range, which could indicate that data for the following years might be incomplete or reflect the introduction of several lower-range models.
* After the sharp decline, there is a slight recovery in the average range in the most recent year shown on the graph.

The data suggest that while there have been fluctuations, the overall trend over the last two decades has been toward increasing the electric range of EVs.

Next, let’s explore how electric ranges vary among the top manufacturers and models. This analysis can reveal how different manufacturers are addressing the crucial aspect of electric range and highlight which models stand out for their superior range capabilities:

![image](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/48a87da0-2f20-40d5-96ef-b49ff0d00cf0)

The TESLA ROADSTER has the highest average electric range among the models listed. TESLA’s models (ROADSTER, MODEL S, MODEL X, and MODEL 3) occupy the majority of the top positions, indicating that on average, TESLA’s vehicles have higher electric ranges. The CHEVROLET BOLT EV is an outlier among the CHEVROLET models, having a substantially higher range than the VOLT and S-10 PICKUP from the same maker. NISSAN’s LEAF and CHEVROLET’s SPARK are in the lower half of the chart, suggesting more modest average ranges.


## Estimated Market Size Analysis of Electric Vehicles in the United States

Now, let’s move forward towards finding the estimated market size of electric vehicles in the United States. I’ll first count the number of EVs registered every year:

![image](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/6d05cc04-d03e-4ee4-b609-2c9987fb1706)

The dataset provides the number of electric vehicles registered each year from 1997 through 2024. However, the data for 2024 is incomplete as it only contains the data till March. Here’s a summary of EV registrations for recent years:

* In 2021, there were 19,063 EVs registered.
* In 2022, the number increased to 27708 EVs.
* In 2023, a significant jump to 57,519 EVs was observed.
* For 2024, currently, 7,072 EVs are registered, which suggests partial data.

To forecast the total number of EVs expected to be registered in 2024, we can use a growth rate based approach from previous complete years.

We’ll calculate the Compound Annual Growth Rate (CAGR) between a recent year with complete data (2023) and an earlier year to project the 2024 figures. Additionally, using this growth rate, we can estimate the market size for the next five years. Let’s proceed with these calculations:

![image](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/51258a12-5426-4e42-bb6b-11dbe3abfddc)


Now, let’s plot the estimated market size data:

![image](https://github.com/DharshanR31/Electric-Vehicles-Market-Size-Analysis-using-Python/assets/109989995/c8c8871c-f0fd-42b9-9be0-a470e5e4054f)


From the above graph, we can see:

* The number of actual EV registrations remained relatively low and stable until around 2010, after which there was a consistent and steep upward trend, suggesting a significant increase in EV adoption.
* The forecasted EV registrations predict an even more dramatic increase in the near future, with the number of registrations expected to rise sharply in the coming years.
Given the growing trend in actual EV registrations and the projected acceleration as per the forecast data, we can conclude that the EV market size is expected to expand considerably. The steep increase in forecasted registrations suggests that consumer adoption of EVs is on the rise, and this trend is likely to continue. Overall, the data point towards a promising future for the EV industry, indicating a significant shift in consumer preferences and a potential increase in related investment and business opportunities.

# Summary
So, market size analysis is a crucial aspect of market research that determines the potential sales volume within a given market. It helps businesses understand the magnitude of demand, assess market saturation levels, and identify growth opportunities. From our market size analysis of electric vehicles, we found a promising future for the EV industry, indicating a significant shift in consumer preferences and a potential increase in related investment and business opportunities.
