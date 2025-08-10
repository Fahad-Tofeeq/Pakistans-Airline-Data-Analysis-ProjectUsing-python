# Airline Data Analysis Project
## Project Overview
This repository showcases a comprehensive data analysis project focused on exploring and visualizing a large-scale airline flight dataset. The project demonstrates proficiency in data manipulation, cleaning, exploratory data analysis (EDA), and advanced data visualization using Python. By analyzing flight data, including attributes such as airline, price, duration, departure time, and class, the project uncovers actionable insights into pricing trends, flight distributions, and operational patterns, providing valuable decision-making support for stakeholders in the aviation industry.
# Key Objectives
Data Cleaning and Preprocessing: Implemented robust data cleaning techniques to handle missing values, standardize formats (e.g., converting duration strings to numeric), and remove redundant columns for optimal analysis.
Exploratory Data Analysis (EDA): Conducted in-depth EDA to summarize key statistics, identify unique values, and filter data based on conditions (e.g., high-priced Business class flights, specific destination cities like Islamabad, Lahore, and Quetta).
Advanced Visualizations: Developed a variety of visualizations, including scatter plots, boxplots, heatmaps, pairplots, violin plots, histograms, bar plots, and pie charts, to reveal trends such as price variations by airline, class, and departure time.
Feature Engineering: Created derived features (e.g., price_days as price × days_left) to enhance analysis and uncover relationships between variables
## Key Features
Data Loading: Efficiently loaded and processed a large Excel dataset (300,153 rows) using Pandas, ensuring compatibility with openpyxl.
Data Cleaning: Addressed data inconsistencies (e.g., converting duration from strings like "2.17hrs" to float, handling missing values, and dropping irrelevant columns like Unnamed: 0).
## EDA Techniques:
Grouped data by airline, class, and source_city to compute mean prices and durations.
Filtered data for specific conditions (e.g., Business class flights with prices > 10,000, Economy flights < 10,000).
Analyzed categorical variables (e.g., stops, destination_city) using unique values and value counts.
## Visualizations:
Scatter Plots: Price vs. duration with regression lines, faceted by class.
Heatmaps: Average prices by source and destination city.
Pairplots: Relationships between price, duration, and days_left, colored by class.
Violin Plots: Price distributions by airline, highlighting variability and quartiles.
Histograms: Price distribution with kernel density estimation.
Bar Plots: Flight counts by airline and class, with error bars for mean prices.
Pie Charts: Proportions of flights by airline and stops.
Palette and Hue Usage: Leveraged Seaborn’s palette and hue parameters (e.g., viridis, magma, Set2) to create visually distinct and professional plots, ensuring clarity in categorical comparisons.

# Technologies Used
Python 3.13: Core programming language for data processing and visualization.
Pandas 2.3.1: For efficient data manipulation, filtering, and aggregation.
Matplotlib 3.10.5: For customizable, high-quality visualizations.
Seaborn 0.13.2: For advanced statistical visualizations with aesthetic color palettes.
Openpyxl 3.1.5: For reading Excel data files.
NumPy 2.3.2: For numerical computations supporting data analysis.
## Repository Structure
flight_analysis_output (1).xlsx: The input dataset containing 300,153 flight records.
Airline project.ipynb: Jupyter Notebook with all data processing, analysis, and visualization code.
README.md: Project overview and setup instructions
## Key Insights
Pricing Trends: Business class flights average significantly higher prices (e.g., 52,540) than Economy (6,572), with variations by airline and route.
Flight Distribution: Shaheen Airline dominates the dataset (127,859 flights), followed by other carriers like PIA and Fly Jinnah.
Route Analysis: Heatmaps reveal price variations across source-destination pairs, with Lahore-Business routes being among the most expensive.
Time-Based Patterns: Violin and bar plots highlight price variability by airline and class, with histograms showing price distributions.
## Relevance to Industry
This project showcases skills critical for data analyst, data scientist, or business intelligence roles:

Data Wrangling: Expertise in cleaning and preparing large datasets for analysis.
Analytical Thinking: Ability to derive meaningful insights through grouping, filtering, and statistical summaries.
Visualization Proficiency: Creation of professional, publication-quality visualizations to communicate findings effectively.
Tool Mastery: Advanced use of Pandas, Matplotlib, and Seaborn for end-to-end data analysis workflows.
#Future Enhancements
Integrate machine learning models to predict flight prices based on features like duration, days_left, and class.
Add interactive visualizations using Plotly or Dash for enhanced user exploration.
Expand analysis to include temporal trends by parsing departure_time for hourly or daily patterns
## Contact
For inquiries or collaboration opportunities, please contact [Fahad Tofeeq] at [fahadtofeeq1999@gmail.com] or connect via [Fahad Tofeeq].



