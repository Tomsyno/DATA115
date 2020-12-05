# DATA115
DATA Analytics 115 repository

Data Analysis: Disease Rating of Spinach Causal Agent Cercospora chenopodii  
Disease can have a huge impact on crops around the world, upwards to 40% crop destruction according to University of California Agriculture and Natural Resources department. This has led to endless effort in controlling pathogens that cause disease. One of the best methods of dealing with a disease is with resistance in the host plant. In the Summer of 2019, I conducted a disease rating of Cercospora Leaf Spot on four cultivars of spinach. It is important to understand how this disease interacts with spinach to give farmers the smartest option on choosing what to grow each season. This pathogen has not been known to infect spinach and is an emerging issue. The research conducted illustrated the first confirmed incident of this pathogen affecting spinach. 
	A pathogenicity test was conducted that rated infected plant leaf area over three different time intervals. Disease ratings where taken on four different cultivars of spinach. The beets in the experiment did not contract the disease. With this data I was able to show which cultivar tolerated the disease best.


DATA: The Data was uploaded to Excel and then converted into a .CSV and uploaded to this repository. The data contains columns of the corresponding data: replication number, plot number in each replication, unique number code, host (plant cultivar), the isolate number to the pathogen, 4 DAI (DAY AFTER INOCULATION), 9DAI, 14DAI. 

Data Cleaning:  The Data in excel consisted of the four spinach cultivar data, and 4 beet cultivars data. I used Jupyter books, and perl to removed data from the beet cultivar because no indication of disease was reported on the beet cultivars. The Host cultivars used to compare where put into their own data frame to separate cultivars that showed disease and ones that did not. The four cultivars of spinach used were Viroflay, SV2157VB, Mandolin, and Unipack-151. I did not consider of the different reps or block groups because of the small amount of data. The data consisted of multiple isolates which were identified later to all be the same strain. This allows all treatments to be viewed as the same. 


Analysis: Using Python I was able to use exploratory data analysis described in my Jupyter book that is uploaded to this repository. The resulting analysis of the data allowed me to recreate and show the data in the following three graphs. The first of the graphs is an overview of the experimental data. The following two graphs are snapshots of 14 days after inoculation showing the range of disease on each cultivar, and the final graph is a zoomed in view of Unipack-151 which preformed the best of the four cultivars. 

The following is a boxplot of 4 different variety of spinach showing disease progression over 14 days. The different variety of spinach are compared to each other at 4 days after inoculation/presence of pathogen (DAI), 9 DAI, and 14 DAI. The graph show that disease progression and severity is different over the four cultivars of spinach. 


![Percent Infected Leaf Are](HISTOGRAM_ALLSPINACH_FIXXED NAMES.PNG (679×650) (raw.githubusercontent.com))

The following image is a histogram showing the range of infection for each cultivar, 14 days after infection.


![Histogram 14 DAI](Histograms_All_4_Spinach_14DAI.PNG (834×527) (raw.githubusercontent.com))


This image is a close up of Unipack-151 since it tolerated the disease the best.  This histogram clearly shows most plants having 0-2% leaf area infected. That is typically one or two spots on the plant. The highest area infected was 10% of the plant leaf area and was recorded on only one plant of this cultivar. 


![Unipack-151 Histogram]( Unipack_151_Histogram_14DAI.PNG (781×497) (raw.githubusercontent.com))


Conclusion: The initial goal of this experiment was to classify this pathogen and prove that it could cause disease on spinach. The data that was generated from this experiment has allowed for other analysis. This analysis of the data has allowed us to determine which cultivar is best suited in New Jersey. Two of the cultivars Unipack-151, and SV2157VB are grown in New Jersey and where the initial crops infected. Both can be infected with SV2157VB being the most severe and Unipack-151 being the least severe. This is also backed up with field data of the Unipack-151 field not showing infection but the other was destroyed. Based off representation of the data Unipack-151 serves as a better spinach cultivar of the two, to be grown. Unipack-151  
