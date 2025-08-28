# Airbnb Data Analysis

## Project Overview
This project explores Airbnb listing data to uncover insights about prices, room types, neighborhood distribution, pricing correlations, and review trends.

## Objectives
The analysis addresses the following questions:
1.	What is the distribution of listing prices?
2.	How are different room types distributed?
3.	How are listings distributed across different neighborhoods?
4.	What is the relationship between price and room type?
5.	How has the number of reviews changed over time?

## Dataset
The dataset contains information about Airbnb listings, including:
1.	Listing attributes such as name, host details, neighborhood, room type, price, cancellation policy, and review data.
2.	Each listing includes geographic information (latitude, longitude) and time-based review data.

## Sample columns:
1. id	name	host_id	host_name	neighbourhood	room_type	price	number_of_reviews	last_review	...
2. 10012345	Clean & Cozy	8.6E+10	Madame	Brooklyn/Kensington	Private room	45	12	2019-01-10	...
3. 10024750	Skyview Mid	5.2E+10	Jenna	Manhattan/Harlem	Private room	90	89	2018-11-17	...

## Analysis Tasks
1.	Price Distribution:
Visualize and analyze the spread and common ranges of listing prices.
2.	Room Type Distribution:
Examine proportions of room types (e.g., Entire home/apt, Private room).
3.	Neighborhood Analysis:
Explore which neighborhoods have the most listings.
4.	Price vs. Room Type:
Assess how price varies according to room type.
5.	Review Trends:
Analyze how the number of reviews for listings has changed over time.

## Getting Started
Requirements
1.	Python 3.x
2.	pandas
3.	matplotlib or seaborn (for visualizations)
4.	Jupyter Notebook (recommended for exploration)

##  Run Analysis
1.	Clone the repository:
2.	Install dependencies:
3.	Place your CSV data file in the project directory or use the provided sample.
4.	Open and run the Jupyter notebook: jupyter notebook analysis.ipynb
