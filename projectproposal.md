# **Project Proposal -- Module One**

## **Question:**

New York based matcha company, Cha Cha Matcha, is rolling out a new bottled beverage and wants to roll out a series of advertisements placed in subway stations across New York. My analysis of MTA data will help the company decide the best time and place to drop rotating digital ads seen on subway platforms. 

## **Data:**

I am planning on using MTA data. Since commuting and ridership isn’t completely back to “normal” due to Covid-19, I will plan on using a 3-4 month period of data over the course of two seasons taken from 2019. 

Some features of the data I plan on using include finding the most trafficked stations, comparing weekday vs weekend traffic of those stations, looking to see what peak rush hours are. 

Particularly since my project is based around advertising a caffeinated drink, I want to see what peak morning rush hours are as opposed to the post-work rush when consumers are less likely to be interested in an energizing beverage. In addition, I am curious to see if the most trafficked weekday vs weekend stations vary or are the same and the drop off in ridership numbers. I.E. I expect that FiDi stations popular during the weekday due to work commuters will not be as popular during the weekend. Should a company advertise at a station there on weekends if there is a significant dip in foot traffic?

## **Tools:**

I plan on feeding all of my raw data into one SQL database and querying that database into Python. I am not entirely sure how much data cleaning I will be doing in SQL but may be helpful to look for any NULL values or data outliers. 

Once I query my database in Python, I expect to be able to prepare my data there by aggregating any fields necessary and look for data errors. As the data is currently seen broken down to specific turnstiles per station, I am looking to ultimately compile a total number of entries and exits per station for my research. Using matplotlib, I plan on graphing a variety of my findings that include the fluctuating ridership numbers over the course of a day, top 10 stations per total traffic, weekday vs weekend ridership. 

## **MVP:**

I expect that a MVP would be prepared and cleaned data that I have been able to run through Pandas to find at least some of the answers to the questions I have about this data set. 

