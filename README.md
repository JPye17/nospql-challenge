# nospql-challenge
Module 12 KU bootcamp

Using PyMongo in Jupyter Notebook the following challenge was compelted in NoSQL by setting up a DataBase and then Using Exploritory Analysis to look further into the Data.

Intro:
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Project Overview
The purpose of this notebook is to:
* Import and interact with a MongoDB database (uk_food) containing UK food establishment data.
* Perform queries and data manipulations on the establishments collection.
* Conduct exploratory data analysis to answer specific queries about food establishments.
* Update and clean data to ensure proper formats for fields like latitude, longitude, and rating values.

# Part 1: Database and Jupyter Notebook Set Up
* Import and configure MongoDB using pymongo.
* Verify the connection to the uk_food database and the establishments collection.

# Part 2: Update the Database
* Insert a new restaurant entry into the establishments collection.
* Update data types for specific fields (e.g., latitude, longitude, RatingValue).
* Remove documents where the LocalAuthorityName is "Dover".

Part 3: Exploratory Analysis
* Explored the Data to looking into ranking primarily around Hygiene set by the local authority. Using Geo codes the analysis was to look around 'Penang Flavours' to explore resurants with varieng scores in the area, in London in general and look at establishments RatingValue. 

Queries and Operations
MongoDB queries using find, count_documents, and aggregate.
Updating documents in MongoDB using update_one and update_many.
Converting MongoDB query results into Pandas DataFrames for further analysis.

---
Resources: While using class and outside resources, challenges we overcame at section that seemed more difficult.
