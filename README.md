# Tesla Supercharger Location Optimization

# Introduction

The Supercharger Location Optimization project aims to optimize the placement of supercharger stations for electric vehicles. This project uses advanced data science techniques to determine the most efficient locations for these stations to maximize coverage and minimize costs. The project is based on the paper "Tesla’s Supercharger Cost Revealed to Be Just One-Fifth of the Competition in Losing Home State Bid" by Fred Lambert.

## 📝 Table of Contents

- [Project Description](#project-description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

# 📖 Project Description

With the rise in electric vehicle (EV) adoption, the need for an efficient charging infrastructure is crucial. This project focuses on optimizing the location of supercharger stations to ensure widespread coverage and convenience for EV users.

## Objective Function

The objective function used in this project aims to minimize the total distance traveled by all EV users to the nearest supercharger station. The function is formulated as follows: $$\text{Minimize} \sum_{i=1}^{n} \sum_{j=1}^{m} d_{ij} x_{ij}$$

Where: 
- \( d_{ij} \) is the distance between EV user \( i \) and supercharger station \( j \)
- \( x_{ij} \) is a binary variable indicating whether EV user \( i \) is assigned to supercharger station \( j \)

## Methodology 

This project employs advanced data science techniques, including spatial analysis and optimization algorithms, to determine the optimal locations for supercharger stations. The key steps involved are: 
- Data Collection: Gathering relevant data on existing infrastructure, EV usage patterns, and geographic factors.
- Data Preprocessing: Cleaning and preparing the data for analysis.
- Spatial Analysis: Analyzing geographic data to identify potential locations.
- Optimization: Applying optimization algorithms to select the best locations.
- Visualization: Creating interactive mapped scatter plot representing results of optimization model.

# 🌟 Requirements

- Python 3.8 or higher
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Geopandas
- NetworkX

```bash
pandas==1.3.3
matplotlib==3.4.3
seaborn==0.11.2
geopy==2.2.0
pydrive==1.3.1
plotly==5.3.1
scipy==1.7.1
numpy==1.21.2
```

# ⚙️ Installation

**1. Clone the repository and install the necessary dependencies.**
```bash
git clone https://github.com/Jchow2/python-supercharger-location-optimization.git
cd python-supercharger-location-optimization
pip install -r requirements.txt
```
**2. Change to the project directory:**
```bash
cd python-supercharger-location-optimization
```
**3. Install the required Python packages:**
```bash
pip install -r requirements.txt
```

# Usage

To start the optimization process, run the main script. Here’s how:

1. Ensure all dependencies are installed as per the requirements.txt file.
2. Execute the main script:
```bash
python main.py
```

This will begin the optimization process for supercharger locations based on the provided data.
3. The results, including visualizations and data analysis, will be generated and saved in the appropriate directories.

# Project Structure

```bash
/project-root
    ├── data                     # Directory containing data files
    ├── notebooks                # Jupyter notebooks for exploration and analysis
    ├── src                      # Source code for the project, contained in a single Python Markdown file
        ├── main_code.md         # Main Python Markdown file containing all the code
    ├── tests                    # Directory for test scripts
    ├── README.md                # This README file
    ├── requirements.txt         # List of dependencies
```

# Results
- The interactive map reveals clusters of supercharger stations in major metropolitan areas such as Los Angeles, San Francisco, and San Diego.
- The color-coded lines indicate that most supercharger stations are within a short to medium distance from their nearest neighbor, ensuring good coverage for electric vehicle drivers.
- The longest distances (red lines) highlight areas where additional supercharger stations could be beneficial to reduce travel distances for EV drivers.

# Contributing
We welcome contributions to this project! Please follow the guidelines below to contribute:

1. Fork the repository
2. Create a new branch (git checkout -b feature-xyz)
3. Commit your changes (git commit -m 'Add feature')
4. Push to the branch (git push origin feature-xyz)
5. Open a pull request

## 📜 License

This project is licensed under the MIT License.

# 👩‍💻 Author
Developed and maintained by Justin Chow.
Referenced articles to assist with developing the optimization model.

- Lambert, Fred. “Tesla’s Supercharger Cost Revealed to Be Just One-Fifth of the Competition in Losing Home State Bid.” Electrek, 15 Apr. 2022, electrek.co/2022/04/15/tesla-cost-deploy-superchargers-revealed-one-fifth-competition/#:~:text=It%20would%20mean%20that%20Tesla%27s,applications%20to%20the%20TxVEMP%20program. 

- Nikos, Karen Michele. “Tesla’s Advantage: EVS Cannot Succeed without Developing Parallel Supercharging Networks.” UC Davis, 10 Nov. 2021, www.ucdavis.edu/curiosity/news/tesla%E2%80%99s-advantage-evs-cannot-succeed-without-developing-parallel-supercharging-networks. 

- “Tesla Charging Stations Cost in California.” Energy5, energy5.com/tesla-charging-stations-cost-in-california#anchor-1. Accessed 1 Dec. 2023. 

- "Tesla Sales by State 2023", worldpopulationreview.com/state-rankings/tesla-sales-by-state. Accessed 1 Dec. 2023. 

- “How Much Does Electricity Cost by State?” EnergySage, www.energysage.com/local-data/electricity-cost/. Accessed 1 Dec. 2023. 

- Equities, Daniel Shvartsman expertise:, and expertise: Equities. “Tesla Growth and Production Statistics: How Many Vehicles Are Sold across the Globe?” Investing.Com, 29 Nov. 2023, www.investing.com/academy/statistics/tesla-facts/. 
