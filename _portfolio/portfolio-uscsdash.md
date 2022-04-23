---
title: "US Computer Science Faculty Pipeline Dashboard"
excerpt: "In this project for CS 725: Information Visualization, I used Vega-Lite and D3 to visualize data about graduate computer science programs (topics: gender, computing)<br/><img src='/images/uscsdashsm.png'>"
collection: portfolio
---

In my final project for [CS 725: Information Visualization](https://weiglemc.github.io/teaching/2022-spr-cs725825), I produced an interactive dashboard
to show insights about gender diversity in graduate computer science programs in the US. The user can investigate the percentage of PhD students by gender,
professors employed and professors from an alma mater by gender, see the gender breakdown of CS PhD students over time, and explore the regional hiring preferences
of tenure track computer science professors. I used Vega-Lite and D3 to create my dashboard. 
[The dashboard is available on Observable](https://observablehq.com/d/01313a4a164aeb21).

![US Computer Science Faculty Pipeline Dashboard](/images/uscsdashsm.png)

I used two data sets for this project. The first data set is the Integrated Postsecondary Education Data System, Completions, 1984-2011. This data
set includes CS PhDs awarded per year per institution, by gender and is located at
[nces.ed.gov](https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx?year=2011&surveyNumber=3), one file per year.
The second data set is the 2012 Computer Science Faculty Hiring Network (Tenure-Track). This data set includes
CS tenure-track faculty, by gender, job title, alma mater name and region, employing institution name and region and is located at
[science.org](https://www.science.org/doi/10.1126/sciadv.1400005). I used Wikidata to align the two data sets.
