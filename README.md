# Mars Weather Data Analysis - Data-Collection

## Background

This project focuses on analyzing weather data for Mars. The analysis involves querying and visualizing the data, and creating a detailed report based on these queries.

## Project Structure

### Files

- `part_1_mars_news.ipynb`: Jupyter Notebook containing the Mars news data analysis.
- `part_2_mars_weather.ipynb`: Jupyter Notebook containing the Mars weather data analysis.
- `mars_weather_data.csv`: CSV file with Mars weather data.
- `daily_minimum_temperature.png`: PNG file showing the daily minimum temperature on Mars.
- `average_pressure_by_month.png`: PNG file showing the average pressure by month on Mars.
- `average_low_temperature_by_month.png`: PNG file showing the average low temperature by month on Mars.
- `average_low_temperature_by_month_sorted.png`: PNG file showing the average low temperature by month on Mars, sorted by temperature.

### Data Analysis

#### Mars News Analysis

The Mars news analysis involves:
- Scraping the latest Mars news titles and preview texts.
- Storing the scraped data in a structured format.

#### Mars Weather Analysis

The Mars weather analysis involves:
- Retrieving the weather data for Mars from the CSV file.
- Analyzing the data to find trends and patterns.
- Plotting the results.

### Analysis Summary

1. **Average Low Temperature by Month on Mars**:
   - The average low temperature varies across different months on Mars.
   - Coldest months: Identified the coldest months to be around the middle of the Martian year.
   - Hottest months: The temperatures tend to be higher at the beginning and end of the year.

2. **Average Low Temperature by Month on Mars (Sorted by Temperature)**:
   - Sorted analysis shows clear distinctions between the coldest and warmest months.
   - Coldest month: Month 3 (approximately -80°C).
   - Warmest month: Month 8 (approximately -60°C).

3. **Average Pressure by Month on Mars**:
   - The atmospheric pressure also varies by month.
   - Highest pressure observed in Month 9.
   - Lowest pressure observed in Month 6.

4. **Daily Minimum Temperature on Mars**:
   - Daily variations in temperature over the Martian year.
   - Notable cycles and patterns in the temperature data, reflecting seasonal changes.

#### Visualizations

1. **Average Low Temperature by Month on Mars**
   - ![Average Low Temperature by Month on Mars](Mars_Scraping/Chart_Visuals/average_low_temperature_by_month.png)

2. **Average Low Temperature by Month on Mars (Sorted by Temperature)**
   - ![Average Low Temperature by Month on Mars (Sorted by Temperature)](Mars_Scraping/Chart_Visuals/average_low_temperature_by_month_sorted.png)

3. **Average Pressure by Month on Mars**
   - ![Average Pressure by Month on Mars](Mars_Scraping/Chart_Visuals/average_pressure_by_month.png)

4. **Daily Minimum Temperature on Mars**
   - ![Daily Minimum Temperature on Mars](Mars_Scraping/Chart_Visuals/daily_minimum_temperature.png)

## Analysis Steps

1. **Mars News Analysis**
   - Scraped the latest Mars news titles and preview texts using BeautifulSoup.
   - Stored the data in a structured format for further analysis.

2. **Mars Weather Analysis**
   - Loaded the weather data from the CSV file.
   - Analyzed the data to calculate average low temperatures and pressures by month.
   - Visualized the data using Matplotlib to identify trends and patterns.

## Sources

- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
