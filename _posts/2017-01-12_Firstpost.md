---
layout: post
title: Along the Subway Line
---

Whether you are heading to work or home, whether you are going out to meet a friend or going to school, you are most likely to ride the New York City’s subway system. 

Millions of commuters ride the subway system every year, and guess what, the data of the entries and exists from each turnstiles in each of the 700 subway stations is available for free for  you to analyze.

Now, the problem at hand: WomenTechWomenYes (WTWY) will be holding an annual gala at the beginning of the summer each year. They are interested in filling the event space with people passionate about increasing the participation of women in technology and to concurrently build awareness and out-reach. They want to place their street teams at the entrances to subway stations to collect email addresses of riders and send free tickets to the gala, to those who sign up.

Now, how to optimize the placement of these street teams to maximize the goal of WTWY. Team Benson5 (with[Nikhil](https://github.com/nikhiliyengar), [Dexter](https://github.com/dextersealy), [Andrew](https://github.com/acatal3) and [Keerthi](https://github.com/KeerthiPamulaparthy) ) get to work.

We decide to use the data from Spring to Early-Summer, from the MTA website. As the gala is to be held in the beginning of Summer, it would be good if the street teams are deployed at the entries of the subway stations around mid to late Spring.

Our approach was to identify the high volume subway stations, and map it with stations located near tech hubs to identify stations that are most likely to have riders working in technology. We believe that this will be our target group, as riders working in technology will be interested in promoting the cause of not only increasing the participation of women in technology, but also build awareness of the cause. 

We used several libraries in python, like pandas, matplotlib etc to acquire, clean, analyze and graphically depict the data.

By analyzing the data for the average entries and exits for all stations, we able to identify the top stations by volume, and by combining it with the data provided by Digital NYC, we were able to narrow down the stations of interest to - 14 St Union Square station, 23 St. station, 28 St. station, Wall St. station, Fulton St. station, Spring St. station.

Our insights into the data revealed that, weekdays have more riders in the subway system in general, and also in the tech hubs. So we reached the conclusion that the street teams should be deployed on weekdays at the subway stations.

By looking at the average entries and exits across different time slots, the time frame between 4pm - 9pm has the highest number of frequency of commuters entering or exiting the subway station.

So our recommendation to WTWY, based on analysis of only the MTA and Digital NYC data is that the street teams should be located at 14 St Union Square station, 23 St. station, 28 St. station, Wall St. station, Fulton St. station and Spring St. stations between 4pm - 9pm on weekdays, targeting commuters exiting the station. 

![stations](https://github.com/KeerthiPamulaparthy/KeerthiPamulaparthy.github.io/blob/master/_posts/stations.png)



