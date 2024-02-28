# Google Fiber Project

Google Fiber provides people and businesses with fiber optic internet. It has a customer call center, where Fiber uses business intelligence to monitor and improve customer satisfaction.

## Project Background

Google Fiber needs to understand how often customers call customer support again after their first inquiry; this will help leaders understand whether the team is able to answer customer questions the first time. Further, leaders want to explore trends in repeat calls to identify why customers are having to call more than once, as well as how to improve the overall customer experience.

### Dataset Includes
- Number of calls
- Number of repeat calls after first contact
- Call type
- Market city
- Date

## Goal
The ultimate goal is to reduce call volume by increasing customer satisfaction and improving operational optimization.

## Data Prep
Since the tables were already cleaned and the columns matched, a target table was created using BigQuery to consolidate and store the Google Fiber datasets for the final dashboard.

## Tableau Dashboard
[Link to Tableau Dashboard]([https://public.tableau.com/app/profile/syed.taha.ahmed/vizzes](https://public.tableau.com/views/GoogleFiberProject_17091398711100/RepeatCalls?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link))

### Repeats by Month
The first tab of the dashboard includes two bar charts: the first chart visualizes the number of repeat calls the customer service team received each month. Contacts_N represents the first date a customer called– then, one can explore how often the customer called again that week. For example, 1,636 customers called again one day after their initial call, but only 575 customers called again seven days later in January. 

The second chart visualized the percentage of first contact calls by day of the week; in January, only 8.71% of customers made first contact on Sunday. The majority of customers reached out for the first time on Monday in January!

### Tables
The second tab of the dashboard includes two tables: Repeat Calls by First Call Date and Calls by Market and Type.

The first table allows stakeholders to explore the number of different types of calls by date. The second table then separates calls into market and problem type to provide more specific information about what markets experience the most calls and the problems customers have that seem to prompt repeat calls.

### Market and Type for First Repeat Calls
The Market and Type for First Repeat Calls uses the data from the previous tabs table in order to further visualize the problem types that seem to generate the most repeat calls for different markets.

### Calls Across Q1
The final dashboard tab includes two charts to visualize the number of Day 0 calls across markets and problem types and the first repeat calls across markets and problem types. This helps users gain insight into what markets and problems are generating calls in the first quarter of the year, as well as which ones are prompting customers to call again after the first contact.
