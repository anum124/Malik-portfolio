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

### Step 4: Test the Solution

 **Can you tell me what you think this is?**
 *Response 1:
 *Response 2:

**Can you describe to me what this is telling you**
*Response 1:
*Response 2:

**Is there anything you find surprising or confusing**
*Response 1:
*Response 2:

**Who do you think is the intended audience for this?**
*Response 1:
*Response 2:

**Is there anything you would change or do differently?**
*Response 1:
*Response 2:

then look across all interviews for similarities and differences. What patterns in the feedback emerge?  What did you learn from the feedback?  Finally, document what you expect to change heading into step five based on this feedback. 

### Step 5: Build Your Own Solution

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/7760832"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


