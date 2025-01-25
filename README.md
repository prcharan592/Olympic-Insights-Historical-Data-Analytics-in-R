# Olympic-Insights-Historical-Data-Analytics-in-R
# Dataset
  https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results



# Overview:
This project analyzes 120 years of Olympic history (1896–2016), uncovering trends and insights from the data. The analysis is performed using R, leveraging two key datasets that detail athlete performance and regional information.

# Datasets:
# 1.	athlete_events.csv
	•	Rows: 271,116 | Columns: 15
	•	Each row represents an individual athlete participating in an Olympic event. Key columns include:
	•	ID: Unique identifier for each athlete
	•	Name: Athlete’s full name
	•	Sex: Gender (M/F)
	•	Age: Athlete’s age during the event
	•	Height & Weight: Physical metrics in cm and kg
	•	Team: Represented country/team
	•	NOC: National Olympic Committee 3-letter code
	•	Year & Season: Year and type of Olympics (Summer/Winter)
	•	City: Host city of the event
	•	Sport & Event: Sport and specific event details
	•	Medal: Medal won (Gold, Silver, Bronze, or NA)
# 2.	noc_regions.csv
	•	Rows: 230 | Columns: 3
	•	Provides the NOC codes along with country/region names and special notes.
	•	NOC: 3-letter National Olympic Committee code
	•	Country Name: Country/region matching map_data(“world”)
