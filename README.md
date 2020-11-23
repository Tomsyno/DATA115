# DATA115
DATA Analytics 115 repository

Data Analysis: Disease Rating of the pathogen Cercospora chenopodii on spinach.  

Pathogen attack on crops in the world has always been a big issue causing as high as 40% lost on some crops. Severity will depend on multiple aspect but the easiest way to fight a pathogen is with a resistant cultivar that are immune or can tolerate the pathogen. My work started by classifying an unknown pathogen (Cercospora chenopodii) that was infecting a spinach field in New Jersey. I conducted a pathogenicity test on 8 different plants 4 of which were spinach cultivars. The test showed disease on only spinach and ratings were recorded for three time periods. Which spinach cultivar was most resistant/tolerated to the pathogen in hope to diminish crop lost to this new pathogen of spinach? The Data was uploaded to Excel and then converted into a .CSV and uploaded to this repository. 

Data: The data contains data in columns the corresponding data: replication number, plot number in each replication, unique number code, host (plant cultivar), the isolate number to the pathogen, 4 DAI (DAY AFTER INOCULATION), 9DAI, 14DAI. 

Data Cleaning:  The Data in excel consisted of the four spinach cultivar data, and 4 beet cultivars data. I used Jupyter books, and perl to removed data from the beet cultivar because no indication of disease was reported on the beet cultivars. The Host cultivars used to compare where put into their own data frame to separate cultivars that showed disease and ones that did not. The four cultivars of spinach used were Viroflay, SV2157VB, Mandolin, and Unipack-151.



The following is a boxplot of 4 different varity of spinach showing disease progression over 14 days. The different varity of spinach are compared to each other at 4 days after inoculation/pressence of pathogen (DAI), 9 DAI, and 14 DAI. The graph show that disease progression and servity is different over the four cultivars of spinach. 

![Percent Infected Leaf Are](https://raw.githubusercontent.com/Tomsyno/DATA115/master/Boxplot_Spinach_Path_Test_Cercospora_chenopodii_2019.png)
