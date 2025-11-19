# WeatherWatch-Dashboard
Recommended Structure and Order
1. Project Title / Headline
🌤️ WeatherWatch Dashboard: Real-Time City Weather & Climate Insights
A dynamic, real-time Power BI dashboard that connects to a live weather API to monitor current conditions, hourly trends, and short-term forecasts for selected cities. It helps users quickly understand temperature patterns, humidity, wind conditions, and overall weather health in a visually rich and interactive way.

2. Short Description / Purpose
The WeatherWatch Dashboard is a real-time, API-driven Power BI report designed to display and analyze current weather conditions across multiple cities. The dashboard focuses on live temperature, humidity, wind speed, sunrise/sunset, and forecast data, enabling users to monitor and compare weather patterns for decision-making and planning.
This tool is intended for travel planners, outdoor event organizers, logistics teams, and data enthusiasts who want an at-a-glance view of real-time weather and short-term trends.

3. Tech Stack
The dashboard was built using the following tools and technologies:
📊 Power BI Desktop – Primary platform for building interactive visuals and reports.
🔄 Power Query – Used to call the weather API, transform JSON responses, and shape the data into structured tables.
🧮 DAX (Data Analysis Expressions) – For calculated measures (e.g., average temperature, feels-like index), time formatting (sunrise/sunset), and dynamic titles.
🧱 Data Modeling – Relationships created between city/master tables, current weather, and forecast tables for cross-filtering.
🌐 Weather API – (e.g., WeatherAPI / OpenWeather / similar) used to pull live temperature, humidity, wind, and forecast data in JSON format.
📁 File Format – .pbix for the dashboard file and .png/.jpg images for static previews.

5. Data Source
Source: Public Weather API (e.g., WeatherAPI.com or similar).
The dataset is generated in real time using API calls and includes:
Current Weather Data – temperature (°C), feels-like temperature, humidity, wind speed, wind direction, cloud cover, UV index, visibility, pressure.
Location Data – city name, region/state, country, timezone, latitude & longitude.
Astronomy Data – sunrise time, sunset time, moonrise, moonset (where available).
Forecast Data – hourly or daily forecast including expected temperature, condition (sunny, cloudy, rain), chance of rain, and max/min values.

6. Features / Highlights
• Business Problem
Weather affects travel, events, logistics, agriculture, and daily life, but many people rely on generic apps that don’t provide analytical views.
Key questions such as:
How does today’s weather compare to yesterday or last few hours?
Which city is currently experiencing extreme heat, cold, or high humidity?
What is the best time of day for outdoor activities based on temperature and wind?
How does weather vary between selected cities?

• Goal of the Dashboard
To create an interactive, real-time weather analytics tool that:
Shows live weather data from an API in a clean, dashboard format.
Helps users compare multiple cities on key weather metrics.
Provides short-term trend insights using hourly/forecast data.
Supports decisions such as trip planning, delivery scheduling, event timing, or simple weather monitoring.

• Walkthrough of Key Visuals
You can adapt exact visuals depending on what you built, but a strong structure could be:
1. Key KPIs (Top Section)
Card visuals showing:
🌡️ Current Temperature (°C) – selected city
🤒 Feels Like Temperature (°C)
💧 Humidity (%)
🍃 Wind Speed (km/h or m/s)
🌅 Sunrise Time
🌇 Sunset Time
🌍 Selected City & Country
These KPIs give a quick snapshot of “what’s the weather right now?”.

2. City / Location Filter Panel
A slicer for City and optionally Country or Region allowing users to switch between locations.
All visuals update dynamically when a different city is selected.
Example filters:
City name (e.g., Mumbai, Lucknow, Agra, Ajmer,hyderabad,Noida)
Country

3. Hourly Temperature Trend (Line Chart)
X-axis: Time (hourly – e.g., next 12–24 hours).
Y-axis: Temperature (°C).
This visual helps users see:
How the temperature will rise or fall through the day.
Peak heat/cool times.

4. Hourly Feels-Like vs Actual Temperature (Dual Line Chart)
One line for Actual Temperature
One line for Feels-Like Temperature
This helps identify times when humidity/wind makes it feel hotter or colder than actual.

5. Weather Condition Summary (Bar / Column / Donut Charts)
Examples:
Weather Condition Count (Donut / Pie Chart): Sunny vs Cloudy vs Rainy hours.
Humidity Range Distribution (Column Chart): Hours with low, medium, high humidity.
These visuals show the composition of weather conditions over the selected forecast period.

6. Wind & Visibility Panel
Bar/Column Chart – Wind speed by hour.
Card or Gauge – Current visibility and pressure.
Useful for driving conditions, aviation, marine, or outdoor planning.

7. Current vs Historical Comparison (Optional if you store history)
If you are storing past API calls in a database or using parameters:
Line Chart: Today’s temperature vs yesterday’s or last week’s same time.
This highlights anomalies or unusual weather days.

• Business Impact & Insights
Travel & Outdoor Planning:
Users can quickly decide the best time for outdoor activities, travel, or events by checking temperature and wind patterns over the day.
Operations & Logistics:
Delivery and transport teams can plan operations around extreme heat, rain, or low visibility, reducing risk and delays.
Decision Support:
Event managers and organizers can avoid bad weather time slots, improving user experience and safety.
Learning & Analytics Skill Showcase:
For you as a data analyst, this project demonstrates:
Working with APIs (JSON)
Data transformation in Power Query
DAX measures for time formatting and calculations
Real-time / near real-time dashboarding
Practical use of Power BI for live external data integration

8.Screenshots / Demos
Show what the dashboard looks like:-
Example: ![WeatherWatch Dashboard](https://github.com/KartikRathod2003/WeatherWatch-Dashboard/blob/main/project%20ss.png)



