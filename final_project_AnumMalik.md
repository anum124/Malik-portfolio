## Overview
Pakistan's air pollution almost doubled from 1998 to 2019. If this continues at the current level, residents are expected to have their lives reduced by 4.3 years compared to places that adhere to the air quality standards of the World Health Organization (W.H.O). 

## Outline
**Introduction**
- Depict an overview map that shows latest data across all countries on the world-map with metrics such as population, pollutant levels, gain in life expectancy 
- Particulate air pollution shortens lives globally, even more than smoking, alcohol and road injuries.
- The average life expectancy lost; globally, is 2.2 years for poor air quality regions below the W.H.O maximum standard of 10 micrograms per cubic meters of particulate matter 2.5 (PM 2.5).
- Pakistan is the fourth most polluted country in the world. 

**Focus on Pakistan**
- Pakistan has 221 million inhabitants, making it the fifth most populous country in the world (The World Bank). 
- Lahore, Pakistan is one of the most polluted cities in the world. 
- Air pollution shortens the average Pakistani's life expectancy by 4.3 years as per University of Chicago Air Quality Life Index.
- According to W.H.O Global Update of Risk assessment,  PM 2.5 estimates in Pakistan are 58 micrograms per cubic meter; which is almost 6 times that of the safety guidelines. 

**Sources of Air Pollution**
- Air quality reaches hazardous levels from the months of October to February. 
- The number of vehicles in Pakistan has jumped from 7 million in 14 million in 12 years (2008 to 2019). 
- Industrial facilities, particularly those consuming fossil fuels, emit significant amounts of air pollutants. Emissions from large-scale facilities, such as cement, fertilizer, sugar, steel, and power plants—many of which use furnace oil that is high in sulfur content—are a major contributor to poor air quality (Ghauri, Lodhi, and Mansha 2007; Khan 2011)
- More than 54,000 tons of solid waste are generated daily, most of which is burned (Cleaning Pakistan's Air, World Bank Report).  
- Farmers in Pakistan burn cane fields to ease harvesting. Harvesting begins in October in Sindh, November in Punjab and the NWFP, and continues until April or May (Food and Agriculture Organization of the UN in Pakistan, FAO). 

**Policies for Reduction**
- Introduction of Low-Sulphur fuels and adopting Euro-II standards for vehicular emissions.
- A complete solid waste management system needs to be adopted in all major cities that includes both the collection of waste and its environmental friendly disposal.
- Agriculture Department needs to launch a systematic campaign for educating farmers on the harmful impacts of burning of crop residues and introduce alternative technologies for environmentally safe disposal of crop residue such as converting it into compost or mulch. 
- Green Industrial processes with resource efficiencies and emission reduction should be implemented in cement manufacturing plants, steel mills and thermal power plants.

Source: [Report of the Smog Commission by the Government of Punjab](https://epd.punjab.gov.pk/system/files/Smog%20commission%20report.pdf) 

## Initial Sketches 

![IMG_0019](https://user-images.githubusercontent.com/75527838/141739526-2568417d-2a75-4298-aaca-069276a2d8e8.PNG)

## Data 
The main data source is the Air Quality Life index calculations which is an initiative of the Energy Policy institute at the University of Chicago. This dataset shows the population, PM 2.5 pollutant measures in micrograms per cubic meters, and the loss in life expectancy given the degrading air quality for 243 regions from 1998 to 2019. Both the global data for world estimates and the regional, country level data for Pakistan will be extracted from this source. 

[Dataset 1](/aqli_global_data.csv)
[Dataset 2](/aqli_regional_data_PAK.csv)

To get more granular data, I will extract the daily air quality data from the [IQ Air](https://www.iqair.com/us/pakistan) and the [Open Data Pakistan](https://opendata.com.pk/dataset/air-quality-index-may-2019-april-2020/resource/decb72cb-1d47-4c2b-8414-33fb01f763d5/) websites. 

The sources of air pollution are tailled from the [Food and Agricultural Organization of the United Nations in Pakistan](https://www.fao.org/pakistan/news/detail-events/en/c/1179183/).

The data for the increase in number of vehicles will be extracted for all modes of transportation from [here](https://www.ceicdata.com/en/pakistan/motor-vehicle-production-ministry-of-finance-annual)

The percentage removal of pollutant with respective dollar value against pollutant type will be taken from the research report on [Air pollution removal by urban trees and shrubs in the United States](https://www.itreetools.org/documents/55/UFUG_Air_Pollution_Removal.pdf). This will be used as a research case to prove of one the points from the policy recommendations section; an initiative which can be implemented in the short term but has a huge impact in the long term. 

**Data Sources for Literature Review**
- [Pakistan: Hazardous air puts lives at risk](https://www.amnesty.org/en/latest/news/2019/10/pakistan-hazardous-air/)
- [Report of the Smog Commission](https://epd.punjab.gov.pk/system/files/Smog%20commission%20report.pdf)
- [Cleaning Pakistan's Air](https://documents1.worldbank.org/curated/en/701891468285328404/pdf/890650PUB0Clea00Box385269B00PUBLIC0.pdf)
- [The World Bank Report](https://www.worldbank.org/en/news/press-release/2016/09/08/air-pollution-deaths-cost-global-economy-225-billion)

## Method and Medium 
The story will be presented through a mixture of visualizations using the collected datasets, open images and interactive or pop-up charts to convey the message to the audience effectively. The sketched visualization will be rendered using tools such as Tableau and Flourish. Both platforms are very user-friendly and allow one to create complex graphs, like maps across an extended timeline, easily post manipulation of the data-set at hand. The final website will be completed using Shorthand because it allows for an immersive digital experience for the audience and removes the technical complexities of story-telling, i.e the need for web developers or coders, for the content creators. 

[Back to Main Page](/README.md)
