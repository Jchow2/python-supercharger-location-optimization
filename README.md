# Tesla Supercharger Location Optimization

## Data Preparation
In an era marked by an accelerating shift towards sustainable transportation, the EV industry has emerged as a vanguard for innovation and environmental consciousness. Central to the success and widespread adoption of electric vehicles is the infrastructure that supports them. How does the location of Tesla supercharger stations affect the demand for Tesla cars in the EV market? In this paper, we explore a set of selected charging stations based in the California market and optimize for newly built locations to minimize distance traveled.

Here are the following data preparations involved with extracting and analyzing information related to the dataset:
1. Selected Charging Stations: The optimization model yields a solution status and a set of selected charging stations based on the model's optimal solution.
2. Parsing Station Information: The selected charging station entries are parsed to extract relevant information, specifically the city names.
3. Handling Station Information: Some processing is applied to the extracted station information to isolate the city names. However, there might be cases where the data structure or naming conventions vary, leading to debugging challenges.
4. City Frequency Analysis: A city frequency analysis is performed using the Counter class to count the occurrences of each city in the dataset.

## What is the Objective Function?
With this question in mind, we optimize for the locations where Tesla should build new supercharger stations based on the demand for EV cars sold in that region and the demand for EV charging stalls. Diving deeper into our investigation, we have a list of sub-questions that we must answer to assist us in our understanding of what we are researching. 

1. What is the proportion of superchargers per state distributed across the USA?
2. What were the periods of dynamic growth or slowdown in the installation of superchargers?
3. Which states may require more stalls or higher power capacity?
4. What is the relationship between power capacity and number of charging stalls?
5. What areas require an expansion of their charging network to ensure adequate coverage?

## Why is this Important?
All of these questions help to address the challenges in meeting the demand for EV supercharger stations in California. 

# References
Lambert, Fred. “Tesla’s Supercharger Cost Revealed to Be Just One-Fifth of the Competition in Losing Home State Bid.” Electrek, 15 Apr. 2022, electrek.co/2022/04/15/tesla-cost-deploy-superchargers-revealed-one-fifth-competition/#:~:text=It%20would%20mean%20that%20Tesla%27s,applications%20to%20the%20TxVEMP%20program. 

Nikos, Karen Michele. “Tesla’s Advantage: EVS Cannot Succeed without Developing Parallel Supercharging Networks.” UC Davis, 10 Nov. 2021, www.ucdavis.edu/curiosity/news/tesla%E2%80%99s-advantage-evs-cannot-succeed-without-developing-parallel-supercharging-networks. 

“Tesla Charging Stations Cost in California.” Energy5, energy5.com/tesla-charging-stations-cost-in-california#anchor-1. Accessed 1 Dec. 2023. 

Tesla Sales by State 2023, worldpopulationreview.com/state-rankings/tesla-sales-by-state. Accessed 1 Dec. 2023. 

“How Much Does Electricity Cost by State?” EnergySage, www.energysage.com/local-data/electricity-cost/. Accessed 1 Dec. 2023. 

Equities, Daniel Shvartsman expertise:, and expertise: Equities. “Tesla Growth and Production Statistics: How Many Vehicles Are Sold across the Globe?” Investing.Com, 29 Nov. 2023, www.investing.com/academy/statistics/tesla-facts/. 

Market), Brand Sales (by. “Tesla Sales Figures – U.S Market.” GCBC, www.goodcarbadcar.net/tesla-us-sales-figures/. Accessed 1 Dec. 2023. 
