# Overview

This project focuses on analyzing subscription data related to constituents. Using Python and Pandas, the project manipulates and aggregates large datasets to generate meaningful insights about email subscriptions, including the creation and update dates of these subscriptions.

# Objectives

- To clean and process constituent and email subscription data.
- To create a 'people' file containing essential information about each subscriber.
- To generate an 'acquisition_facts' file summarizing daily acquisitions.
- To visualize the distribution of daily acquisitions.

# Technologies Used

- Python: Programming language for data analysis.
- Pandas: Library for data manipulation and analysis.
- Matplotlib: Library for creating static, animated, and interactive visualizations.
- Seaborn: Statistical data visualization library based on Matplotlib.

# Data Sources

- Constituent Information: 'cons.csv'
- Constituent Email Addresses: 'cons_email.csv'
- Constituent Subscription Status: 'cons_email_chapter_subscription.csv'

# Getting Started

# Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn

# Installation

Install the required libraries using pip:


pip install pandas matplotlib seaborn



# Usage

1. Clone this repository or download the project files.
2. Place the CSV files ('cons.csv', 'cons_email.csv', 'cons_email_chapter_subscription.csv') in the project directory.
3. Open a Jupyter Notebook or Google Colab and run the provided scripts to perform data analysis.
4. The output files 'people.csv' and 'acquisition_facts.csv' will be generated in the project directory.

# Outputs

- people.csv: Contains processed data for each subscriber, including their email, source, and subscription status.
- acquisition_facts.csv: Contains aggregated data on the number of acquisitions per day.

# Visualizations

The project includes visualizations that display the distribution of daily acquisitions, helping to identify trends and patterns in subscriber data.

# Conclusion

This project provides a structured approach to analyzing subscription data, offering insights into constituent behavior and subscription trends.
