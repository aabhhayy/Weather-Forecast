☁️ Live Weather Forecast Dashboard – Power BI
🧩 Project Overview
This interactive dashboard provides real-time weather updates for multiple Indian cities.
It pulls data from a live weather API and translates complex climate stats into easy-to-understand
visuals — making it usable for any user, technical or non-technical.

🎯 Purpose
To create a real-time weather monitoring tool that:

Helps users track chance of rain, UV index, visibility, and temperature at a glance.
Converts raw API weather metrics into plain, readable language like “Rain”, “No Rain”, “Moderate UV”, or “Unavailable”.
Provides a user-friendly view for quick daily planning or travel decision-making.

⭐ Key Features
🌦️ Rain Chance Logic:

When API returns 0% → shows “No Rain”
Any value > 0 → shows “Rain”

☀️ UV Index Logic:

Converts numeric UV values into categories like "Low", "Moderate", "High"
If no value → shows "Unavailable"

📍 City-wise Weather Cards:

Display temperature, humidity, pressure, wind, and visibility using simple cards

🕒 Last Updated Time:

Displays the last time the API was refreshed (so users know how current the data is)

🔁 Live API Integration:

Connected via Power Query to fetch real-time data in each refresh

📈 Interactive Visuals:

Use of slicers (like Chance of Rain), bar charts, KPI cards for an intuitive experience

🛠️ Skills & Tools Used

.Power BI
.Power Query (M Language)
.DAX (Data Analysis Expressions)
.JSON API Integration
.Data Modeling
.Custom Conditional Formatting

📚 What I Learned

1. How to handle cyclic references & relationship errors in Power BI
2. Advanced DAX logic building to display conditional weather summaries
3. API-based real-time dashboards using external JSON
4. Creating a user-first UI, where even a non-technical user can instantly understand data like UV Index or rainfall

👀 Preview
Check Out this Dashboard Link:- 

🧭 How to Use:-

Select a city (optional slicer).
Check the Chance of Rain and UV Index cards.
View detailed visualizations for daily weather patterns.
Refresh data for the most up-to-date weather info.

#Thinking Behind the Dashboard:-

🧠 "Weather isn’t just data, it’s a daily decision driver. Built this tool so anyone — from a traveler to a shopkeeper — can understand it at a glance."
— Made with passion for simplicity and clarity ❤️

