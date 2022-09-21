# Introduction
ICE is a company that manages two hotels, resort and city hotel. These hotels operate throughout the year and ICE wants to know how they have been performing.
### Problem Statement
---
With the increase in competition and demand in the market, ice wants to know the following things from their hotel given the dataset of the two hotels over the last three years;
- Is the hotel revenue growing by year?
- Should the parking lot size increase?
- What other trends can be seen in the data?

## Data Analysis Process
### Data Gathering
- The data was downloaded from [kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand), then imported into excel for data cleaning.
### Data Cleaning and Preparation
- The data is a large dataset which contained three years tables, meal cost table and discount table.
- The tables were merged using excel power query.
- Deleted the agent and company columns since they contained mostly null values
- Deleted eight rows with “Na” values in the “children” column
- Deleted the “lead_time” column
- Removed rows with reservation date year “2014”
- 41223 duplicates found and removed
- Arrival date was concatenated into one column using the concatenate formula
- A new column was created with the condition of parking space to be no if it is zero and yes if not zero
### Exploratory Data Analysis And Insights
- August and July generated the highest ADR this is due to the summer period
- Online TA and Offline TA/TO had the highest numbers of bookings because they offered discount up to 30%
- BB generated the highest revenue from meal probably cause most of the guests need to go out during the day for business or some other things, so they only decide to take breakfast at the hotel before setting out
- Less than 4% of the guest are repeated guest and this implies the customers retention is low.
- More than 96% of the guests required parking spaces this shows that there is no need for the hotel to increase their parking spaces
### Recommendation
- They should increase their ads in June to target more customers against the summer periods.
- Renovation should be carried out on rooms L, P and K so that they can generate more ADR from them 
- They should work on increasing their customers retention by improving on their customers service.
- They should focus more on the Online TA and Offline TA/TO segments because that's where most of their customers come from.
- The parking lot size does not need to be increased. This is because the most of guest coming in do not require a parking space.

[See Dashboard Here]()


**Note :** This project was a team project under the Octave 20 Data analysis projects program. I was the group leader for my team.
