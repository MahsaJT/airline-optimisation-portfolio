# Airline Network Optimisation Project 

##  Project Overview
This project demonstrates **mathematical optimisation** techniques applied to airline route planning. Using **Gurobi Optimizer**, I model a real-world scenario where limited aircraft resources must be allocated across multiple routes to maximize passenger capacity.

##  Problem Statement
- **Limited fleet size** with operational constraints
- Each aircraft has maximum daily flights due to maintenance and crew rest requirements
- Multiple routes between different cities need to be covered
- **Objective:** Maximize total passengers carried within operational limits

##  Data Collection
- Real-time flight data collected from **Aviation Stack API**
- Focus on domestic routes between major airports
- Data cleaning and preprocessing: handled missing values (only 0.67% of data)
- Time period analysis: 40-hour window showing flight distribution patterns

##  Technologies & Tools
- **Python** - Core programming language
  - pandas & numpy: Data manipulation
  - matplotlib & seaborn: Data visualization
- **Gurobi Optimizer** - Industry-standard optimisation solver
- **Jupyter Notebook** - Interactive development environment
- **GitHub** - Version control and project portfolio

##  Key Results & Insights
- Successfully modelled a fleet of **15 aircrafts** with **4 flights per day** capacity
- Optimised flight allocation across **10 busiest routes**
- Achieved **7,200 passengers** daily capacity with optimal route distribution
- Data-driven decision making: resources concentrated on high-demand routes
- Maintained minimum service levels on all routes (2 flights per route)

## 🚀 How to Run This Project

### Prerequisites
- Python 3.8 or higher
- Gurobi license (academic licenses available for free)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/airline-optimisation.git
   cd airline-optimisation

Install required packages:

bash
pip install -r requirements.txt
Run the Jupyter notebook:

bash
jupyter notebook notebooks/optimisation_model.ipynb

Contact
Mahsa Javadzadeh Tatabatabaee

Email: tatabatabae.mhs@gmail.com

LinkedIn: linkedin.com/in/mahsa-javadzade-tatabatabae

License
This project is created for educational and portfolio purposes.

If you find this project interesting or have suggestions for improvement, feel free to reach out!
