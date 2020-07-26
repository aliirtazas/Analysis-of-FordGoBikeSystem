# Communicate-Data-Findings
Udacity's Data Analyst Nanodegree - Project 5

### Overview About the Project
Data visualization is an important skill that is used in many parts of the data analysis process. 
> *Exploratory* information representation by and large happens during and after the information wrangling process, and is the principle strategy that you will use to comprehend the examples and connections present in your information. This understanding will assist you with moving toward any factual examinations and will assist you with building ends and discoveries. This procedure may likewise light up extra information cleaning assignments to be performed.  

> *Explanatory* information perception strategies are utilized in the wake of creating your discoveries, and are utilized to help convey your outcomes to other people. Understanding structure contemplations will ensure that your message is clear and successful. Notwithstanding being a decent maker of representations, experiencing this venture will likewise assist you with being a decent buyer of perceptions that are introduced to you by others.

### Project Details

1. Dataset: [Ford GoBike](https://www.fordgobike.com/system-data)
2. Explore the data: Feel free to explore the jupyter notebook where the dataset is visually, and programatically explored. 
3. Document the story: organized findings convey a story to present to an audience.
4. Communicate the findings - a slide deck with my findings is prepared for a curious audience.

### Project Findings
Following is the short summary that we can summarize from this project:

>The Ford GoBike Sytem is a Naturally neighborly, spending benevolent, and lifetsyle agreeable.

>The user type subscribers are those who use this daily is a benefit from a healthy life.

>The second user type is Customers, they have a maintained and very flexible and better option for touring the city according to there availability.

>The system is very affordable and convenient for all types of classes

>Leasing a bicycle from theFord GoBike System is a fabulous (solid and ecologically inviting) method of moving around in the city, both for pleasure and work.

There are two sorts of customers utilizing the framework: Subscribers and Customers. Supporters are principally day by day suburbanites, having short excursions to and from work, who lease a bicycle on weekdays at 8-9am and 5-6pm. Clients are generally sightseers or occassional riders who utilize the framework fundamentally on ends of the week to investigate the Bay Area.

The most interesting interaction between features were the Customers and Subscribers,where there was major difference between their time duration and Day of the Week they use the bike.

### Files
- readme.md - This Markdown file contains sections that you should fill out as you select your dataset, complete your exploration, and plan your explanatory analysis. 

- CommunicateDataFinding-FordGoBike.ipynb - This Jupyter Notebook contains section templates to help you organize your exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration. 

- slide_deck_template.ipynb - This Jupyter Notebook contains starter cells to help you organize your slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.

To view the slide deck, you will need to use the expression (all one line):
jupyter nbconvert Example_Project_Diamonds_Part2.ipynb --to slides --post serve --template output_toggle

- output_toggle.tpl - This template file can be used with nbconvert to export your slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project). 

## Help
I've taken help from the following repositories and links
1.https://github.com/chelseymarie6/Communicate-Data-Findings/blob/master/Communicate_Data_Slide_Deck.ipynb
2.https://github.com/huiyinglu/Communicate-Data-Findings/blob/master/exploration.ipynb
3.https://matplotlib.org/contents.html
4.https://seaborn.pydata.org/