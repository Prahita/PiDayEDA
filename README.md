# PiDayEDA

This project analyzes Google Trends data to explore search trends related to Pi Day from 2020 to 2024.
The goal was to see search trends around pi day, and if there were any correlations between the searches for different foods, and pi

Pi Day is celebrated the 14th day of March every year, and typically restaurants take advantage of this holiday to offer special discounts on pizzas and pies as an ode to the mathematical constant. 


## Google Trends Search Interest

The search interest values displayed in this analysis are derived from Google Trends. It's important to understand that these values are **not absolute search counts**. Instead, they represent the relative popularity of a search term over time and within a specified region.

Google Trends normalizes search data on a scale from 0 to 100, where:

* **100:** Indicates the peak popularity of a search term during the selected time period.
* **0:** Indicates that there was not enough data for the term.
* **Values between 0 and 100:** Show the relative popularity of the term compared to its peak.

Essentially, Google Trends provides a way to compare the relative popularity of different search terms or to track the change in popularity of a single term over time. It's a valuable tool for identifying trends, but it doesn't provide the actual number of searches.



# The questions I aimed to answer in this small analysis were: 
- What are the general search trends for Pi Day, pizza, and pie over the past 5 years?
- What are the relative search interests of Pi, Pie, and Pizza specifically on Pi Day?
- What were the most popular days for searches for pi, pizza, and pie, for each year?

# Methodology
I utilized the google search API to collect and measure data on search trends for the terms "pi" and related food terms like "pizza" and "pie", and aimed to analyze whether there was a spike in search interest for these food related terms on pi day.

Python libraries, specifically pandas, matplotlib, seaborn, and pytrends were used for data processing and visualization.

# Limitations and Future Improvements
It would have been interesting to look at sales data of pizzas and pies on every pi day in the years past and in the week following up to pi day to see what the correlation between pizza and pie sale were on pi day. Finding granular data on restaurant and QSR sales on these specific days was difficult to acquire upon researching data sources to collect this information. 
I think that finding this data and incorporating this into a future analysis on this project would be an interesting and fruitful project.

# Running the code
All code here was used on the google colab workbook, and can be accessed via this repository under the name "". The Google search trends API is available for all to access so you will be able to download and run the code on this notebook and see the visualizations generated to support this small analysis as well.


# Key Findings:
I found a few major trends within the search data for Pi, pi day and related food terms

* **Relative Search Popularity:**
  - Across the years 2020-2024, the search term "Pizza" consistently exhibited the highest relative search interest, followed by "Pie," "Pi," and then "Pi Day," which showed the lowest overall relative search interest across the year.

* **Pi Day Search Interest Distribution:**
  - On each Pi Day from 2020 to 2024, "Pizza" consistently held the largest share of relative search interest, while "Pi," despite being the day's namesake, showed the lowest relative interest.

* **Pi Day Spikes:**
  - There were noticeable spikes in the relative search interest for "Pi," "Pi Day," and "Pie" specifically on Pi Day across the years 2020-2024, indicating a strong correlation between the date and increased search activity.

* **"Pi" Peak on Pi Day:**
  - Within each year from 2020 to 2024, Pi Day was the date on which the term "Pi" generated the highest relative search interest.

* **"Pie" Peaks Around Thanksgiving and Pi Day:**
  - Across 2020-2024, the term "Pie" showed its highest relative search interest during the week leading up to Thanksgiving, reflecting a seasonal trend. Additionally, there were also noticeable spikes in "Pie" search interest on Pi Day.

* **"Pizza" Peaks Around Holidays and Specific Dates:**
  - For the years 2021, 2022, and 2024, the term "Pizza" had its highest relative search interest during the days between Christmas and New Year's. In 2020 and 2023, the highest relative search interest for "Pizza" occurred on April 12th and September 24th, respectively.
  



