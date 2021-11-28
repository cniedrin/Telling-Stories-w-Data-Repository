# Visualization Assignment #2

## Part I: Working with web-based visualization tools and data

This visualization shows a visualization created directly on the OECD website. 

General Government Debt to GDP Ratio for 2020

<iframe src="https://data.oecd.org/chart/6vdk" width="800" height="600" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6vdk" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

## Part II: Flourish

### 1.
This first Flourish visualization is a grid of charts showing the changes over time in the debt-to-GDP ratio from 1995 - 2020 for countries around the world. 

Debt to GDP Ratio 1995-2020

<div class="flourish-embed flourish-chart" data-src="visualisation/7654970"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### 2. 
This second Flourish visualization is a population pyramid showing the change in debt-to-GDP ratios from 1995 to 2020 for countries around the world. It also highlights the U.S. change in ratios to point out how our ratio compares to the other countries. 

<div class="flourish-embed flourish-chart" data-src="visualisation/7677265"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Analysis

Between these three visualizations, there are particular pros and cons. To begin with the original visualization from OECD, their simple bar chart quickly shows comparable information between a large number of countries.[1] It gives the viewer a quick look at the raw ratios for any given year. There are also neat interactive features that allow you to highlight certain countries of interest or look at a different year.[2] There is even an option to look at the trends over time, but this is a bit overwhelming and creates a different kind of visualization (a line graph, specifically). The downside is that the current organization caused you to automatically see a trend analysis. The information is listed from smallest ratio to largest, making it seem as though the ratios are increasing over time when in reality they are just ordered that way by country. Additionally, it's a very large set of information to work with for a simple bar chart, and without highlights, it's very difficult to parse out individual country information. 

In contrast, the first grid of charts visualization in Flourish makes it easy to see each country and all the data over time on separate graphs. In this way, one can compare the various shapes of lines to compare the trend with other countries. However, this has limited use. It is very hard to directly compare data from chart to chart as they are all separate and there are 30+ tiny charts to analyze. Although the author of *Good Charts* states that our visual systems are very good at math,[3] it takes a while to compare any two charts that aren't directly next to one another. While it may not overwhelm the viewer in the same way a line chart with all that information might, it leaves very few options to call out and highlight information. Color can be used, or not used to call out certain information,[4] but this chart isn't easily manipulated to tell such stories. However, to see general trends for specific countries, it's very helpful. 

With my third visualization, I wanted to explore the change in value between 1995 and 2020 in the debt-to-GDP ratio, specifically calling out the US. I did this by cleaning the dataset to remove any countries that lacked 1995 and 2020 data and calculated the value change using the following formula: 2020 value - 1995 value. I chose to utilize a population pyramid because it could clearly show which countries increased their debt-to-GDP ratios and which ones decreased their ratios during that time frame. I greyed all the lines except for the U.S. to draw attention to it. I also chose to utilize the value labels on each bar to help the audience accurately compare the value changes rather than just see the general trend; I feel that this provides context. Finally, I added a title and subtitle to clearly explain to the audience what the chart shows.  As per *Good Charts*, there are five things to know about how we perceive visualizations: we don't view things in order, we see what stands out first, we only see a few things at once, we seek meaning and make connections, and we rely on conventions and metaphors. [5] My goal with this visualization was to make the U.S. stand out to the viewer using color and also make the connection with the red that the U.S. isn't in the best position. Additionally, I created a large, bold title in the top left corner to hopefully draw the audience's eye there first to gain context.

I had initially tried several other visualizations that wouldn't allow me to manipulate the data and colors the way I liked, so I landed on this one. Overall, I'm happy with this visualization as it allowed me to communicate my story. Hopefully, it conveys that the U.S. does not have the largest positive change in the debt-to-GDP ratio (with a higher ratio being negative for the country), but it also is not doing much better than most other countries either. 

Sources:

[1] “General Government - General Government Debt - OECD Data.” theOECD. Accessed October 30, 2021. https://data.oecd.org/gga/general-government-debt.htm. 

[2] Ibid.

[3] Berinato, Scott. Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations. Boston, MA: Harvard Business Review Press, 2016. 

[4] Ibid.

[5] Ibid.

### Navigation ###
[Home](README.md)

[Visualization Class Examples](class_examples.md)

[Visualization & Critique Assignment #3 & 4](visualization2.md)

[Final Project Part I](final_project1_cniedrin.md)

[Final Project Part II](final_project2_cniedrin.md)

[Final Project Part III](final_project3_cniedrin.md)
