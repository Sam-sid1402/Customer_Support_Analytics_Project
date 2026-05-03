# Customer Support Analytics Project
## Overview

This project analyzes customer support operations using multiple datasets (tickets, agents, reviews) to identify inefficiencies, improve response time, and better understand customer satisfaction drivers.

## Business Problem

Customer support teams often struggle with:

- Long response times
- Uneven workload distribution between agents
- Lack of visibility into performance metrics

The goal of this project is to analyze support data and provide actionable insights to improve efficiency and customer experience.

## Dataset

The project uses 3 datasets:

Tickets — customer requests, timestamps, status
Agents — agent information and assignments
Reviews — customer feedback and ratings

The data includes inconsistencies (missing values, formatting issues), simulating a real-world scenario.

## Process

1. Data Cleaning

- Handled missing values
- Standardized formats (dates, categories)
- Removed duplicates

2. Data Transformation

- Merged datasets using keys
- Created new features (e.g., response time, resolution time)

3. Analysis (EDA)

- Response time distribution
- Agent workload analysis
- Rating vs response time relationship

4. KPIs

- Average response time
- Resolution time
- Customer satisfaction (rating)
- Agent performance

## Key Insights

- Higher response times are associated with lower customer ratings
- Some agents are significantly overloaded compared to others
- Negative reviews are more frequent when response time exceeds a certain threshold

## Business Recommendations

- Redistribute tickets more evenly between agents
- Set internal SLA targets for response time
- Prioritize tickets based on urgency and sentiment

## Tools Used

- Python (pandas, numpy, matplotlib)
- SQL
- Jupyter Notebook

## Future Improvements

- Build a machine learning model to predict customer dissatisfaction
- Implement automated ticket prioritization