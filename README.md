# Berlin Summer 2022 Activity Recommender

**Authors:** Francesca Logiacco and Hilal Işık  
*This project is created and shared by the mentioned authors, with each joint author enjoying an equal interest in the undivided whole.*

---

## Project Goal

The goal of this project is to **find the best fitting activity for a summer day in Berlin (May–August 2022)**.  
The recommendations are **based entirely on user preferences and budget**, using rule-based logic and conditional statements rather than machine learning. The system guides users to activities that match their interests, time, and budget constraints.

---

## Data Sources

1. **Eventbrite**
   - Web scraping was used to collect both free and paid event information in Berlin.  

2. **Gratis-in-Berlin**
   - Web scraping to collect local free event listings.  

3. **Parks and Lakes in Berlin**
   - Prepared CSV files with information sourced from **Berlin Bezirksamt** and **Visit Berlin** websites.  

All datasets were cleaned and standardized for use in the recommendation system.

---

## Recommender System

The Jupyter Notebook contains a **rule-based recommender system** that:

- Combines events, free activities, and park visits  
- Filters activities based on **user-selected interests** and **maximum budget**  
- Uses **conditional logic and if-else statements** to match users with the most suitable options  
- Outputs a curated list of **best activities for a summer day in Berlin**  

> **Note:** This is **not a machine learning model** — it relies on explicit rules defined in Python to make recommendations.

---

## Libraries Used

- **Web Scraping:** `requests`, `BeautifulSoup`  
- **Data Manipulation:** `pandas`, `numpy`  
- **Persistence & Randomness:** `pickle`, `random`

