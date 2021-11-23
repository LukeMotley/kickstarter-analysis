# Kickstarting with Excel

## Overview of Project

   This repository uses a data set of kickstarter information to examine and visualize trends, specifically outcomes based on their launch dates and funding goals of various kickstarters.

### Purpose
   Client Louise, after fundraising her own play, wanted to see how other plays fared in their own kickstarters. This repository uses the data provided to visualize the clients needs and gain insight of her own projects.

## Analysis and Challenges
First Pivot Table showing successful, failed, and canceled.

![image](https://user-images.githubusercontent.com/85656361/143129337-078ed7c5-1fad-4717-8286-247731f0807d.png)


### Analysis of Outcomes Based on Launch Date
   As the chart below shows, there is a natural rise and fall throughout the calendar year, seeing the most productions in the late spring to early summer. There are small increases in theatrical productions in the months of February and October. October also has a spike in failed kickstarters. By far, the most successful month is May.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85656361/124357990-32718f80-dbec-11eb-9cf3-371e0150f537.png)

### Analysis of Outcomes Based on Goals
   As the chart indicates below, there is no linear divide in the relationship between outcome and monetary goal overall. Starting from the lowest goal amount, the success rate is at its highest. As the goal gets bigger, the success rate drops. This remains the general rule until 35k-40k goal. From the range of 35k-45k there is a spike that almost rivals the highest success rate. After that, there is a sharp drop to 0% percent before sizing slightly to 13%.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85656361/124358001-3e5d5180-dbec-11eb-842b-c39856c79a33.png)

### Challenges and Difficulties Encountered

The one challenge I had with this project was creating the table for the "Outcomes Based on Goals" sheet. it took some time to figure out how the COUNTIFS function can be used to filter the information. It was mainly a syntax error that I had to troubleshoot until I got it correctly. Luckily, after I solved the first few, I was able to recreate the formulas for the rest easily. I did accidentally forget to create the "plays" filter so my results were incorrect and I did have to go back after the fact and fix that as well.

Note: At the beginning, I also did not realize there is a difference between COUNTIF and COUNTIFS. I realized that after doing some of my own research.

## Results
#### Conclusions of Outcomes based on Launch Date
There is a much higher volume and success rate of theatrical productions in the summer months, peaking in May. Months September through March do substantially worse than other months.

#### What can you conclude about the Outcomes based on Goals?
   Minus the potential skew towards the 35k to 45k range, the lower the goal, the more likely the goal is to be reached.

#### What are some limitations of this dataset?
   One big limitation of this dataset is the lack of kickstarters in the larger goal ranges. The majority of data is found on the lower end (<1k to 10k) so while the smaller goal ranges have sufficient data to represent those ranges, the larger goals lack the kickstarters to factor into the success of kickstarters at that range. If the percentages could be weighted, it would give a more accurate representation of actual success rates.
   It would also be beneficial to view the central tendency of this data to determine the degree of variation between launch dates and goal amount.
   Although not a limitation of the dataset, one potential problem could be how the two graphs display their data. They could cause confusion if one were to try to use these graphs together to make conclusions. On the graph of "Outcomes Based on Goals", the Y-Axis metric is percentages. Meanwhile, the graph of "Theater Outcomes by Launch Date" uses the volume of total projects as its Y-Axis metric. The differences in metrics do not allow these graphs to be used effectively with one another and can be an obstacle when making data-driven decisions.

#### What are some other possible tables and/or graphs that we could create?
   To correct this problem described in the previous section, there should be two more graphs created. Each table should have a second graph, one with number of projects on the y axis and one with percentages on the y axis. This way, it is possible to gain a more accurate understanding and not fall into some of the pitfalls in this data. 
