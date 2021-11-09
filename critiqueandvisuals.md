## Assignment 3 and 4

### Step 1: Find a Data Visualization
The pandemic has been a critical topic of discussion since its devastating start in December 2019; and it has fueled a movement around active data collection on a global scale. Data tracking has transitioned from number of cases and deaths to now include vaccination trends across countries. With winter approaching and stringent enforcements of lockdowns continuing to be lifted, I became more curious to see any subsequent changes in the number of cases globally. Given the myriad of resources, dashboards and trackers, I was certain that I would find exactly what I was looking for but soon discovered that it was not as easy as I had assumed. Pretty much all the sources I tapped into, including but not restricted to the NY Times, CNN and WHO, had chosen to visualize total cases on a map of the world; followed by a huge table of countries that listed more COVID-19 statistics. This was a lot of information but nothing that I could absorb easily or possibly critique. After almost a three hour long search, I found an article on Bloomberg which focused solely on coronavirus cases around the world and zoomed in on a visual that intended to display how the outbreak spread in countries via number of cases from Feb 2020 to date. I chose this visual because it presented exactly the content I needed to see in an intuitive format; but in its attempt to make the data more succinct and visually compact, it took away crucial elements of informativity, made illogical comparisons between 'Asia' and 'Other' and was visually unappealing with the trendlines stacked together at the bottom of the chart. 'This could be an exciting re-design!', I thought to myself.          

![image](https://user-images.githubusercontent.com/75527838/140686999-61c373af-54ea-4785-bb6a-bc01ff842f9f.png)

Visual Source: https://www.bloomberg.com/graphics/2020-coronavirus-cases-world-map/

Even though Bloomberg has maintained a Covid tracker on their website, the data was not available on their github public page. However, I was able to track down the their source as The John Hopkins Center of Systems Science and Engineering Covid -19 repository. This situational time-series dataset maintains data daily from 3rd January 2020 to date; for new cases, new deaths and the cumulative of both across 194 countries and 6 regions split according to the World Health Organization categorizations. This was not going to be an easy dataset to sift through but the critique of the visual would allow me to filter through to the values required to meet the audience's needs and communicate the content effectively.  

Data Source: https://github.com/CSSEGISandData/COVID-19/tree/master/who_covid_19_situation_reports

### Step 2: Critique the Data Visualization
I like that the chart type chosen is intuitive and easy to absorb while keeping in mind the global audience it is meant for. I can easily discern that the United States is currently reporting the highest number of cases of the virus and that the number of cases in ‘Asia’ peaked around May 2021. However, this visual intended to show ‘How the Outbreak Spread Country by Country’ is not completely truthful to its title. At first look, I assumed it was an interactive graph that would allow me to select countries using the hand icon placed next to the title; however, on scanning the graph further, I spotted a note below the visual (in a smaller, unnoticeable text), that mentioned that the visual depicted the 15 countries with the highest totals of new confirmed cases, as of November 6. In addition to this, with the provided context of the resurgence of infections as countries loosened lockdowns following May 2021, the usefulness to the audience suffers since the timeline of the visual covers the entire pandemic. 

Perceptibility is a problem because the trendlines are scattered towards the bottom right of the chart and it is difficult to pinpoint which line represents a certain country. Furthermore, illogical comparisons between ‘Asia’ and ‘Other countries’ in the context does not make sense as the only country displayed that even falls in the Asian region is India. Despite being a simple chart, the graph is not visually appealing; the axis labels are layered on top of each other, and the colors do not represent much information. The visualization is not engaging and does not invoke much of a response with the audience except for a little frustration about being unable to decipher the axis or demarcate the countries trends for new cases. To communicate significant stories in the data to the audience, it is important to make use of the context provided and evaluate design choices that reinforce the point being made. The critique allowed me to consider the following design and content changes: 

1. Change the title to ‘New Cases by Day Since Lock-Down Measures were Eased’ to improve truthfulness.
2. Add a subtitle to convey that the countries profiled are those that had the highest cases as per the latest available data.
3. The x-axis can be restricted to daily cases from May 2021; when lockdown lifts began to the current date to make the graph more relevant to the context.
4. A color icon to represent more regions can be added to derive more value and insights from the visual instead of just two categorizations of ‘Asia’ and ‘Other’ for usefulness and completeness.
5. Change the layout to a heatmap or a bar chart across the countries for number of cases for improved perceptibility and aesthetics.

### Step 3: Wireframe a Solution
I thought of three ideas to follow a heatmap, a grid of lines and a bar chart. The heat map did not allow me to visualize the regions as I had originally intended and defining a scale for the number of cases was tough because all the data sources had a different reference point fo good or worse. Furthermore, it was restricting in terms of the timeline; i would only be able to use the average for the month instead of the daily number of cases. I wrote down all the design decisions and thoughts I faced while I sketched and outline as below:






### Step 4: Test the Solutions
Two people were kind enough to review all three of my sketches and provide quick but useful feedback. Some of the responses to the questions are below:

 **Can you tell me what you think this is?**
 *Response 1: i can see that the all three charts are showing me the number of covid cases for a few countries from May to November 2021.*
 *Response 2: the increase in the number of covid cases across countries post ease of lockdown measures. That's what the title says for each visual.*

**Can you describe to me what this is telling you**
*Response 1: 
*Response 2:

**Is there anything you find confusing**
*Response 1: The grid of line charts and bar chart is pretty clear in its description but the heat map is confusing. I do not understand the color gradient and i do not really get what the 'scale of new daily cases means'; is it a range? How did you define what was a good range to be in in terms of Covid cases, what was in the middle and what was the absolute worse? It's not really something I can pick up on easily from the visual for a measure as easy as 'number of cases'.* 

*Response 2: the heat map is very confusing! I can see why you would want to use that to describe the movement but in this case the fluctuations are so vast that the spread of color on the grid is not letting me conclude anything from the visual. Did it increase for the Italy, decrease what happened in the middle; i really cannnot tell. The grid of line charts and bar chart is easy to understand in that aspect. I can easily follow trends.* 

**Who do you think is the intended audience for this?**
*Response 1: the countries that have the highest number of covid cases probably.* 
*Response 2: anyone who would want to look at the COVID-19 data or keep up with the current COVID situation.*

**Which of the three visuals should I choose as my final solution?**
*Response 1: the heat map is confusing and I immediately want to look away from it because the colors are hurting my brain. Honestly, I would not use that as a layout for the final piece. I think the animated bar chart would be cool to see once you implement the design.*

*Response 2: the grid of lines is interesting so you could use that; but it's boring. The bar chart is a nice visual; the animated look will probably be like the LinkedIn visual that became famous showing the growth of giants like Apple, Microsoft and Google. Though if you cannot animate it, then go for the grid of line chart instead because otherwise I don't think you will be able to include the time element* 

**Is there anything you would add to the final solution you mentioned?**
*Response 1: add a flag for the countries! I think flourish has a bar chart race you can use for this animated visual and you can add images on for it too. It would be good to identify the country when the bars are moving rapidly even if you cannot pick up on the name. You have already added the colors to represent regions and not countries, so this would make things easier. Move the country names somewhere else too and add abbreviations maybe? Looks too cluttered on top of the chart* 

*Response 2: if you can get the animation, i think it would be a great final solution. Maybe you can also add a small title that displays the total number of cases across all the countries as the chart moves, and also move the day from the middle to the side of the chart - it is distracting there.*

The assessment for the worst and best options were unanimous. Both responders were highly critical of the heat map and encouraged me to use the animated bar chart. The differences arose from their interpretations of the intended audience and what the data was meant to visualize. 

then look across all interviews for similarities and differences. What patterns in the feedback emerge?  What did you learn from the feedback?  Finally, document what you expect to change heading into step five based on this feedback. 

### Step 5: Build Your Own Solution

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/7760832"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


