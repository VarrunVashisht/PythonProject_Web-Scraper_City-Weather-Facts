## 🎯 “City Weather & Facts Scraper” — a beginner-friendly data science web scraping project.

## 🌤️ City Weather & Facts Scraper

A fun and beginner-friendly Python project that scrapes real-time weather information 🌦️ and interesting facts 🏙️ about cities from the web — all in one place!
This project demonstrates how to use web scraping and data handling tools like BeautifulSoup, Requests, and Pandas to collect and organize useful information from websites.

## 🌍 Introduction

Web scraping allows us to automatically extract data from websites and turn it into structured datasets.
In this project, you’ll:

Collect live weather data for selected cities from wttr.in
Retrieve city facts from Wikipedia
Combine and save them neatly in a CSV file using Pandas

## This project is a great starting point for anyone learning:

Web scraping 🕸️
Data manipulation with Pandas 🧩
Automation and data collection in Python ⚙️

## ✨ Features

✅ Fetches real-time weather updates for multiple cities
✅ Scrapes first-paragraph facts from each city’s Wikipedia page
✅ Stores the data in a structured CSV file
✅ Fully beginner-friendly and easy to modify
✅ Encourages ethical and responsible scraping practices

## 🧰 Technologies Used
Library	Purpose
requests	To send HTTP requests to websites
beautifulsoup4	To parse and extract HTML content
pandas	To structure and store data in a CSV
time	To control scraping frequency (be polite to servers!)

## ⚙️ How It Works

The script fetches weather data for each city using requests from wttr.in.
It then scrapes the first paragraph of the city’s Wikipedia page using BeautifulSoup.

## 🚀 Usage

Run the Python script:
python scraper.py


## Output:
🔎 Scraping data for London...
🔎 Scraping data for New York...
🔎 Scraping data for Tokyo...
✅ Data scraping complete!

A CSV file named city_weather_facts.csv will be created in your project folder.

## 📊 Example Output
City	Weather	Fact
| City     | Weather             | Fact                                                                                        |
| -------- | ------------------- | ------------------------------------------------------------------------------------------- |
| London   | Partly cloudy +13°C | London is the capital and largest city of England and the UK.                               |
| New York | Clear +19°C         | New York City comprises 5 boroughs sitting where the Hudson River meets the Atlantic Ocean. |
| Tokyo    | Rain +16°C          | Tokyo is Japan’s busy capital, blending the ultramodern and traditional.                    |
| Delhi    | Sunny +28°C         | Delhi is the capital of India, known for its rich history and culture.                      |
| Paris    | Cloudy +15°C        | Paris, France's capital, is known for art, fashion, gastronomy, and culture.                |


All the collected data (city name, weather, and facts) are stored in a Pandas DataFrame.
Finally, the DataFrame is exported to a CSV file (city_weather_facts.csv).

## 💡 Future Improvements
Here are some cool ideas to take this project further:

🌎 Add more cities dynamically using user input
📊 Visualize temperature data using Matplotlib or Seaborn
🕒 Automate the scraper to run daily using Cron jobs or Task Scheduler
🌐 Build a Streamlit web app to display results interactively

## ⚖️ Ethical Scraping Note
Please scrape responsibly! 🧑‍💻
Always check a website’s robots.txt before scraping.
Don’t overload a server — add small delays between requests.
Use scraped data only for educational or ethical purposes.


## 👨‍💻 Author
Varrun Vashisht

