## Part I: Working with web-based visualization tools and data

This visualization shows the a visualization created directly on the OECD website. 

General Government Debt to GDP Ratio for 2020

<iframe src="https://data.oecd.org/chart/6vdk" width="800" height="600" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6vdk" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

## Part II: Flourish

This first Flourish visualization is a grid of charts showing the changes over time in debt-to-GDP ratio from 1995 - 2020 for countries around the world. 

Debt to GDP Ratio 1995-2020

<div class="flourish-embed flourish-chart" data-src="visualisation/7654970"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


This second Flourish visualization is a population pyramid showing the change in debt-to-GDP ratios from 1995 to 2020 for countries around the world. It also highlights the U.S. change in ratios to point out how our ratio compares to the other countries. 

<div class="flourish-embed flourish-chart" data-src="visualisation/7677265"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Analysis
Between these three visualizations, there are particular pros and cons. To begin with the orignial visualization from OECD, this simple bar chart quickly shows comparable information between a large number of countries. It gives the viewer a quick look at the raw ratios for any given year. There are also neat interactive features that allow you to highlight certain countries of interest or look at a different year. There is even an option to look at the trends over time, but this is a bit overwhelming and creates a different kind of visualization (a line graph, specifically). The downside is that, as it is organized, you automatically want to make a trend analysis. The information is listed from smallest ratio to largest, making it seem as though the ratios are increasing over time when in reality they are just ordered that way by country. Additionally, its a very large set of information to work with for a simple bar chart and without highlights, it's very difficult to parse out individual country information. 

In contrast, the first visualization in flourish, the grid of charts, makes it easy to see each and every country and all the data overtime on separate graphs. In this way, one can compare the various shapes of lines to compare the trend with the graphs next to it. However, this has limited use. It is very hard to directly compare data from chart to chart as they are all separate and there are 30+ tiny charts to analyze. While it may not overwhelm the viewer in the same way a line chart with all that information might, it leaves very few options to call out and highlight various information. But, to see general trends, and for specific countries, it's very helpful. 

With my third visualization, I wanted to explore the change in value between 1995 and 2020 in debt-to-GDP ratio, specifically calling out the US. I did this by cleaning the dataset to remove any countries that lacked 1995 and 2020 data, and calculated the value change using the following formula: 2020 value - 1995 value. I chose to utilize a population pyramid because it could clearly show which countries increased their debt-to-GDP ratios and which ones actually decreased their ratios during that time frame. I greyed all the lines except for the U.S. in order to draw attention to it. I also chose to utilize the value labels on each bar to help the audience accurately compare the value changes rather than just seeing the general trend; I feel that this provides context. Finally, I added a title and subtitle to clearly explain to the audience what the chart shows. Overall, I'm happy with this visualization as it allowed me to clearly communicate my story. I had inititally tried several other visualizations that wouldn't allow me to manupulate the data and oclors the way I liked, so I landed on this one. Hopefully, it clearly conveys that the U.S. does not have the largest positive change in debt-to-GDP ratio (with a higher ratio being negative for the country), but it also is not doing particularly better than other countries either. 
