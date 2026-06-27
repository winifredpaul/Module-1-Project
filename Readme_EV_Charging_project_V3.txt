# ⚡ EV Charging Infrastructure in Spain

## 📖 Project Overview

We are a data analytics company, and our client has asked us to identify the best locations to install new electric vehicle charging points in Spain. Our client specializes in installing small private charging points for individual users.

Spain, as a member of the European Union, is promoting the transition to more sustainable transportation through policies focused on reducing emissions and supporting renewable energy. In this context, electric vehicles have shown steady growth in recent years due to improvements in battery range, lower costs, and increasing consumer adoption.

This situation creates an opportunity to invest in charging infrastructure. Therefore, the goal of this project is to analyze the distribution of charging stations and electric vehicle adoption across Spain in order to identify regions with growth potential and evaluate the feasibility of future investments.

---

## 🎯 Research Question
Which regions in Spain offer the best opportunities for new EV charging point installations based on EV adoption, tourism demand, and existing charging infrastructure?

Hipothesis:
Some regions may have high tourism activity or high EV adoption but insufficient charging infrastructure.

---

## 📊 Objectives

- Analyze the evolution of electric vehicle adoption in Spain.
- Study the growth of charging stations for private cars across regions.
- Compare EV adoption with charging infrastructure availability.
- Identify investment opportunities by locating regions where charging infrastructure may not meet current or future demand.
- Visualize key trends through data analysis.

---

## 🗂️ Dataset Sources

### Electric Vehicle Data
Eurostats

### Charging Station Data
Openchargmap

---

## 🔌 APIs and Data Sources Used

### Open Charge Map API

Provides real-time and historical information about electric vehicle charging infrastructure, including:

* Charging station locations
* Charger types and power levels
* Number of connectors
* Operator information
* Geographic distribution of charging points

Documentation:

https://openchargemap.org/site/develop/api

---

### Eurostat API

Provides official statistical data from the European Union across a wide range of economic, demographic, and transportation indicators.

For this project, the Eurostat API is used to analyze electric vehicle adoption trends and vehicle registration statistics in Spain, allowing us to compare EV growth with the development of charging infrastructure.

Data includes:

Electric vehicle registrations
Passenger car fleet statistics
Regional and national transportation indicators
Historical vehicle adoption trends

Documentation:

https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access

---
## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Requests
- Unicode
- itertools
- Geopy
- Jupyter Notebook
- VS code
- Chat GPT
- Excel

---

## 💻 How to use:

Create the API Key. 
	.env File with the keys created 
1 Minute to charge EV Charging stations. 
Will stop y cell 46 (Geopy, all info already loaded)
Run again in cell 61
First API run until cell 73
Run again from Eurostat
Cell 130 - Is a warning not an error.

Please keep geo locator cell in raw and dont run unless you want to wait 6 hours all data is charged.


## 🔍 Methodology

The project was developed in four stages:

### 1. Data Collection

Data was collected from Eurostat and Open Charge Map APIs.

### 2. Data Cleaning

Removing duplicates
Standardizing regional names
Converting data types
Aggregating data by region
Merging datasets from different sources
Creating derived metrics for comparison

### 3. Exploratory Data Analysis

We analyzed:

EV adoption by region
Charging station distribution
Charging stations per EV
Regional infrastructure gaps

### 4. Visualization

Several charts and maps were created to identify trends and opportunities.

---

## 📈 Key Findings

Catalonia is a mature región.
Valencia and Madrid have a good amount of EV but need more charging station comparing with other cities in Europe.
Partnership with renting companies is a grat oportunitie to expand the business.

---

## 💡 Conclusions

### Investment in cities like Valencia and Madrid.
### Install EV Chargers in mediterranean corridor. 
### In the near future most of the rented cars Will be electric son the network needs to grow because on of Spains main income comes from turism.

---

## 🚀 Future Work

Future improvements could include:

Incorporating tourism statistics.
Adding population density data.
Including road traffic information.
Forecasting future charging demand using predictive models.


---

## 🔗 Useful Links
### Repository

[GitHub Repository]

### Presentation

[Google Slides]

### Kanban Board

https://trello.com/b/NeRexx5r/project

---

## Data Sources
Eurostat API
Open Charge Map API

---

## 👥 Authors
Jerónimo Cagliero
Malika Baguari
Matteo Grossi
Winifred Paul

Ironhack Data Analytics Bootcamp - 2026
