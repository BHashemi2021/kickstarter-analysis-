# Kickstarting with Excel - # Kickstarter Statistical Analysis 

## Overview of Project

A huge New York-based public benefit corporation, [Kickstarter]: https://www.kickstarter.com/ , is a huge global crowdfunding platform that focuses on creativity and they strive to "help bring creative projects to life". By December 2019, the company has received more than $4.6 billion in pledges from more than 17 million backers to fund 445,000 projects, including but not limited to films, music, theater plays, comedy shows, journalism, video games, technology, publishing, inventions, and food-related projects (1). To get funded by Kickstarter, the applicants need to meet their initial campaign goals. Therefore, analyzing Kickstarter data, especially those of previous projects can provide the market trends and one may need to tailor their business plans and strategy.

### Purpose

In this section, we try to analyze part of the Kickstarter data to analyse the results of 4114 crowdfunding campaigns with a pledged amount of $46,173,741.66 that took place across different countries in Northern America, parts of Asia and Europe with different launching and closing dates during May 2009 to April 2017. The purpose of the analysis was to find out trends in the crowdfunding projects focusing on theater shows - specifically plays. To briefly review the results of the campaigns, we analysed the outcomes of the projects based on goals and launching dates.


## Analysis and Challenges

The analysis was performed by the use of Microsoft Excel 2016 and use of COUNTIFS and ROUND functions to calculate and populate the variables columns based on the data retrieved from the sample Kickstarter dataset described above. 

Possible challenges could arise from interpreting the way the second deliverable is to be performed. For instance, the way it has been instructed to "'create' the dollar-ranges" in the Goal column. This could lead the learners to spend noticeable time "creating" the ranges through the use of Analyze tab and then the Group, Ungroup tabs repeatedly and finally having difficulty filling the last row by ">50000".  The instructions could simply be "write down these dollar-amount ranges in the Goal column". 



### Analysis of Outcomes Based on Launch Date

The number of successful projects in the parent category namely "Theaters" launched during the campaign seem to be greater than the ones failed or cancelled (Diagram 1). The greatest number of successful projects seems to be the ones launched in May that have well exceeded their goals (110%) and the lowest ones to be in December. The projects launched during mid-April to end of June have fared well with attaining nearly 80% of their goals. The cancelled projects have followed a low but steady pattern all through the campaign life except an interruption during the months September and October.


### Analysis of Outcomes Based on Goals

The successful projects and the ones which failed during the campaign seem to follow a mirror image of each other or in other words they have a negative correlation (Diagram 2). The projects with a campaign goals of below $1000 seem to have been relatively successful (~ 70%) but greater campaign goals seem to fail, especially goals set at 25-30 thousand dollars (the highest failure). Interestingly, the diagram shows a growing success rate between the $35k-$45K campaign goals. There have been no cancelled campaigns throughout the time interval. 

### Challenges and Difficulties Encountered

Comparing the outcomes based on their launch dates and their goals and their goals seem to be two different entities by now and they do not talk to each other. In other words, one could not completely base their campaign based on these two results. Drawing a solid correlation between the two could better show when and how to start a campaign to attain highest success. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. The first conclusion to draw about the outcomes based on their launch date is that starting a campaign during April to end of June could bring about a successful result with the highest yield in May.

2. As the failed campaigns seem to follow the same pattern of the successful campaigns (Figure 1) this could indicate that the failure rate increases as the campaign goals increase and they decrease when campaign goals decrease. Figure 1 also shows a reduced number of campaigns starting late during the year (November and December).


- What can you conclude about the Outcomes based on Goals?

1. For the subcategory of campaigns, plays, there is an inverse or negative correlation with the outcome throughout the curves and the failure rate increase as the goal amounts decrease, except the $25000-$35000 goal range in which the failure rates decrease in relation to an increase in the amount of campaign goals. This discrepancy is unexplainable with the amount of data provided here. 

2. While the successful campaigns for the subcategory of plays constitute nearly 54% of the campaigns, their median goal is at $3500 (versus 8000 and 15000 for the failed and cancelled ones, respectively), indicating greater success rates for goals set at this value range. Mode also follows nearly the same pattern, 2000 vs. 5000 and 10,000 respectively.
 

- What are some limitations of this dataset?

The dataset falls short in providing proof for the discrepancy between successful goals and failure rates at the $25000 - $35000 range. In fact, when the goals are climbing the failure rates are decreasing. Could these be outliers or some other factors could have caused the discrepancy is worth mentioning here as this data range would be rather misleading to interpret. If the pattern holds for other campaign types and subtypes, adding another variable that could help explain the cause may be warranted.


- What are some other possible tables and/or graphs that we could create?

A descriptive summary table using the Data Analysis tab, could clarify and give more information on the differences among the three sets of campaigns and whether they have had a realistic goal setting.


##References

1-	Kickstarter, Accessed 2021, 05, 02. Wikipedia. https://en.wikipedia.org/wiki/Kickstarter 

