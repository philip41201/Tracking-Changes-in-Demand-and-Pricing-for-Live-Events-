## Name
Tracking Changes in Demand and Pricing for Live Events

## Objective
The goal of this project is to capture data on live events that can be used to make better informed decisions in the future regarding the buying and selling of tickets. This project tracks demand and pricing for shows over time on Vividseats.com to gauge demand, and also utilizes event information from Ticketmaster to predict the profitability of future events.

## Description
The job posting I selected was for a data analyst role at Live Nation Entertainment. The role would be working with the Sales Enablement team to help measure the value Ticketmaster's tools and services bring to its customers. Ticketmaster and Live Nation merged in 2010 to create Live Nation Entertainment. The job responsibiltiies include working with transactional and web data sets to analyze ticket sales among other things. This role would also analyze and translate data sets in order to provide actionable insights. A qualified candidate would need to have the ability to write and run SQL queries.

A lot of the job responsibilities parallel what I attempted to do with this project. In a way I am tracking ticket sales by pulling changes in ticket count on Vividseats over time. I also gain experience analyzing data sets and providing recommendations based on the questions I proposed. I also get the chance to showcase my SQL skills by writing complex queries.

## Data
I sourced my data from 3 places: Ticketmaster, Vividseats, and Google. I utilized Ticketmaster's API to pull specific event details such as artist name, genre, venue, event date, minimum price, and maximum price. I had to perform web scraping to grab data off Vividseats. 

## Notebooks
Ticketmaster: https://github.com/philip41201/Tracking-Changes-in-Demand-and-Pricing-for-Live-Events-/blob/main/ticketmaster_data_collection.ipynb
    - Utilizes Ticketmaster's API to grab event details.
Vividseats: https://github.com/philip41201/Tracking-Changes-in-Demand-and-Pricing-for-Live-Events-/blob/main/vividseats_data_collection.ipynb\
    - Web scrape Vividseats.com to grab important listing details, such as minimum/maximum price and listing/ticket count.
Venue: https://github.com/philip41201/Tracking-Changes-in-Demand-and-Pricing-for-Live-Events-/blob/main/venue_data_collection.ipynb
    - Web scrape Google searches on venues to grab the address and capacity.
SQL Analysis: https://github.com/philip41201/Tracking-Changes-in-Demand-and-Pricing-for-Live-Events-/blob/main/sql_analysis.ipynb
    - SQL queries to answer business questions and provide recommendations.
Presentation: https://github.com/philip41201/Tracking-Changes-in-Demand-and-Pricing-for-Live-Events-/blob/main/presentation.ipynb
    - Combination of all the other notebooks.

## Future Improvements
One thing I would do differently is to be more consistent in my data collection. Some of my queries were not as useful or reliable as they could've been had I collected data more consistently. Possibly finding a way to automate the execution of my Python scripts.
I would also want to ask questions that utilize location/regional data.