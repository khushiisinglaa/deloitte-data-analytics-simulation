# Deloitte Data Analytics Job Simulation

Virtual job simulation completed on Forage (Deloitte Australia). I worked on data for a client called Daikibo, which runs 4 factories in Tokyo, Osaka, Berlin, and Shenzhen.

## What I did

**Task 1: Analysed machine telemetry data in Tableau**
The client collected one month of machine data (May 2021) and wanted to know:
1. In which location did machines break the most?
2. Which machines broke most often in that location?

Steps I followed:
- Imported the JSON telemetry file into Tableau with all schema levels selected
- Created a calculated field called **"Unhealthy"** with a value of 10 for every unhealthy status (10 minutes of possible down time)
- Built a bar chart called **"Down Time per Factory"**
- Built a second bar chart called **"Down Time per Device Type"**
- Combined both charts in a **dashboard**, with the first chart working as a filter for the second
- Selected the factory with the most down time and took a screenshot of the dashboard

**Task 2: Classified employee pay equality in Excel**
I added a 4th column called **Equality Class** to the Equality Table. It sorts each equality score (from -100 to +100, where 0 is ideal) into one of three groups:
- **Fair**
- **Unfair**
- **Highly Discriminative**

## Key insights
- The dashboard shows which factory has the most down time and which machine types cause it
- The equality table shows which factory and job role combinations have unfair or highly discriminative pay

## Tools
Tableau

## Skills
Data analysis, data visualisation, calculated fields, dashboards, Excel formulas, attention to detail

## Certificate
[View my certificate](Deloitte.pdf)
