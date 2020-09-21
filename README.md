<img src="https://raw.githubusercontent.com/codecaviar/digital_asset_management/master/assets/bingyune-and-company-logo-6400x3600.png" align="left" width="200" height="auto">

<br/><br/><br/><br/>

----------

# Here's the Kicker: What No One Tells You About Data Wrangling

**Code Caviar Story**: https://www.bingyune.com/blog/heres-the-kicker-football    

## Project Overview

Data analysis has become a necessary skill in a variety of domains where knowing how to work with data and extract insights can generate significant value. If you ask any data analysts or data scientists about which task they spend most of their time on, the answers will be data cleaning or data wrangling and data munging, and not coding or running a model that uses the data. An essential part of the role is turning messy, incomplete data or data that is too complex to gain real insights into data that is simple, clean and actionable for analysis. The key to fast tracking the entire data wrangling process is knowing which techniques to use and when to use them.

**The goal of this project is to provide a Quick Guide on the main tasks for data wrangling and exploratory data analysis.** The project makes use of the European Soccer Database on [Kaggle](https://www.kaggle.com/hugomathien/soccer). The database contains data on more than 25,000 matches for the 2008 to 2016 seasons, info on 10,000 players from 11 European Countries, players & team attributes sourced from the EA Sports' FIFA video game series, and detailed match events (e.g. goal types, possession, corner, cross, fouls, etc.). The FIFA series and all FIFA assets are the property of EA Sports.

The project also uses the open source tool Python and Pandas library to demonstrate essential data wrangling techniques. The examples deal with some of the most common data formats and their transformations.

## Summary:

The project explored the following questions with this dataset:
* Which teams are the most effective based on results?
* How do team attributes differ for the most effective teams compared to all other teams?
* How do player attributes differ for the most effective players compared to all other players?

There are typically three iterative steps that make up the data wrangling process:

**Data cleaning** is the process of detecting and/or removing corrupt or inaccurate records from a dataset. An initial round of data cleaning on our dataframe will give us the bare minimum we need to start exploring our data. Some essential data cleaning tasks include sorting the data, filtering to the desired subset of data, converting data types, deduplicating data, and addressing missing or invalid data.

**Data transformation** means organizing the data, which is necessary because raw data comes in many different shapes and sizes. We focus on changing our data's structure to facilitate our downstream analysis. For example, changes to which data goes along the rows and which goes down the columns might make for easier computation and analysis. Alternatively, a single column might be separated into several columns for future analysis.

**Data enriching** is a general term that applies to the process of enhancing, refining, and improving raw data. Here we can either merge new data with the original data (by appending new rows or columns) or use the original data to create new data. Questions asked during this data wrangling step might be: what new types of data can I derive from what I already have or what other information would better inform my decision making about this current data? For instance,

## Getting Started

Cloning the git repository and installing the provided packages will help you get a copy of the project up and running on your local machine. The analysis for this project was performed using Jupyter Notebook (.ipynb) and the packages were managed using the Anaconda platform.

```
git clone https://github.com/codecaviar/heres_the_kicker_football.git
conda env create -f environment.yml
```

File Description:
* environment.yml - packages used to perform this analysis   
* notebook_heres_the_kicker_football.ipynb - Jupyter Notebook for this project including data wrangling and exploratory data analysis
* european_football.sqlite - (original file named database.sqlite located on Kaggle) contains the following tables: Country (rows=11), League (11), Match (25,979), Player (11,060), Player_Attributes (183,978), Team (299), and Team_Attributes (1,458)

## Authors

- **BingYune Chen** - [LinkedIn](https://www.linkedin.com/in/bingyune-chen/)
- **BingYune & Co** - [GitHub](https://github.com/codecaviar)

## License

The project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

[Galvanize](https://www.galvanize.com/about) is a technology ecosystem for learners, entrepreneurs, startups, and established companies that meets the needs of the rapidly changing digital world. The organization focuses on 1) transforming individuals and teams through effective education and community programs; 2) delivering exceptional outcomes; and 3) coalescing and nurturing a community of innovators anchored by its campuses. Galvanize offers a Python-based curriculum in Data Science, which introduces students to best practice in machine learning, statistical analysis, natural language processing, and data visualization.

The project referenced the following:
* https://medium.com/analytics-vidhya/introduction-to-data-wrangling-88c1b5e747cb
* https://www.springboard.com/blog/data-wrangling/
* *Hands-On Data Analysis with Pandas* by Packt Publishing, written by Stefanie Molin

----------
The Code Caviar is a digital magazine about data science and analytics that dives deep into key topics, so you can experience the thrill of solving at scale.
