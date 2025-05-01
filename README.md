
![Meat Pie Review Power BI Image](https://github.com/GEdnieLockett/DataScraper_MeatPieReview/blob/main/InstagramMeatPieRaterPBI.jpg)

**PBI PUBLIC** - Check it out:

##h/ttps://public.tableau.com/app/profile/kevin.killion/viz/Guinness_Advisor_Dark/DashboardDark

# **Instagram Meat Pie Review Data Extraction, Geocoding & Power BI Visualisation** 
This is a project that demonstrates how to scrape and analyse Instagram data using Apify, Python, and Google Maps API, and then visualize it using Power BI. The project involves scraping Instagram data from a specific profile, data cleansing, data enriching, geocoding and data visualisation.

# Prerequisites 💻
To run the this project, you will need to have the following software installed:

- Excel
- Apify account
- Google Maps API key
- Power BI Desktop


# Getting Started 🛠
To run the Python files in this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python libraries using pip.
3. Place the Apify output file (instagram_guinnessadvisor.xlsx) in the project directory.
4. Run the following command to clean the resulting data:

    **main.py**

5. Run the following command to geocode the address field

     **geocode.py**

6. Run the following command to join the cleaned data with the geocode data and produce a geocoded output file:

    **join.py**

The resulting file (final_instagram_guinnessadvisor_geocoded.xlsx) can be used for data visualization in Tableau or other similar visualtion tools.

# Data Extraction 🔑
The Apify application was used to extract Instagram posts exporting Intragram users PieReivewAu and PieReviewGuy posts. The extracted data included the post's caption, date, and location, as well as the number of likes and comments.

A second extract was taken from Instragram tagged users from post to extract location of the Pies.

![image](https://github.com/user-attachments/assets/37c4fe9f-c08c-4a58-be1c-f5e910a3482e)

# Data Cleaning 🧼
The extracted data was cleaned using Excel to remove any duplicate posts, and to reformat the date and time columns for easier analysis.


# Data Analysis 📊
The cleaned data was then loaded into PowerBI, where a dashboard was created to analyze the data. The dashboard included visualizations of the total number of posts, likes, and comments, as well as the top ratings and locations.


# Files
The following files were used in this project:

- README.md: Description file outlining the project
- final_instagram_guinnessadvisor.xlsx: The cleaned data file
- geocode_addresses.xlsx: The geocoded addresses file
- final_instagram_guinnessadvisor_geocoded.xlsx: The final cleaned, geocoded data file 
- InstagramMeatPieRaterDashboard.jpg: The PowerBI dashboard file

# Conclusion
This project demonstrates the power of Data scrapers, Excel and PowerBI in extracting, clensing and analyzing data from popular media platfroms. By using these tools, I was able to present information from Instagram in a dynamic, fun and visually aesthetic dashboard.

