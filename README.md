![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Mini Project | Data - Create a Machine Learning dashboard using Streamlit

## Mini Project Overview

This is a 2-day hands-on mini project where you need to create a streamlit application for the Sakila database. This application must contain three pages:

- Home
- EDA
- Prediction

## Instructions

### Dataset

In this project, you will be using the [Sakila](https://dev.mysql.com/doc/sakila/en/) database of movie rentals. You can follow the steps listed here to get the data locally: [Sakila sample database - installation](https://dev.mysql.com/doc/sakila/en/sakila-installation.html). You can work with two sql query files - `sakila-schema.sql` (creates the schema) + `sakila-data.sql` which inserts the data.

The ERD is pictured below - not all tables are shown, but many of the key fields you will be using are visible:

<br>

![DB schema](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/database-sakila-schema.png)

<br><br>

## Requirements

### Home page

Must contain a title and an image of your choice.

### EDA page

Must contain the following plots:

- A line plot of daily rentals by each store in 2005
- A bar plot with the total benefit by each store
- A dataframe with the top five most rented movies by each store in 2005. Hint: use `st.dataframe(df)`

### Prediction page

Must contain a `st.text_area()` that will allow the user to input a movie description and get a prediction from the movie rating prediction model created yesterday.
It also must contain an `st.button("Get Your Prediction")` button.


## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.