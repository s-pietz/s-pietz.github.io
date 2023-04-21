# Skylar Pietz's Webpage 

This is a page where I will share some information about myself and the work I am doing in Bioinformatics. So far, I've done some work to analyze data on Penguins and some other datasets including different species of Great Lakes Fish. 

## Work with Penguins 

I started learning how to use R code by working with the Palmer Penguins data set. We ran an analysis using a small subset of 44 penguins. If you're interested, you can view my analayis [here](https://s-pietz.github.io/BioStatisticsAnalysis/Penguins_Analysis2_1_17.html).

### More on Penguins
This data set on Penguins included 8 features measured on 44 penguins. The features included are physiological features (like bill length, bill depth, flipper length, body mass, etc) as well as other features like the year that the penguin was observed, the island the penguin was observed on, the sex of the penguin, and the species of the penguin. We were able to ask many different questions regarding the penguins. Some questions that we formulated as a class in order to better understand the data we were working with included:
+ What is the average flipper length? What about for each species?
+ Are there more male or female penguins? What about per island or species?
+ What is the average body mass? What about by island? By species? By sex?
+ What is the ratio of bill length to bill depth for a penguin? What is the overall average of this metric? Does it change by species, sex, or island?
+ Does average body mass change by year?

I ejoyed creating these questions in order to guide our analysis and facilitate our learning on how to use R code and manipulate data in this section. Specifically, we learned how to filter rows, subset columns, group data, and compute summary statistics. Remeber to check out my full analysis [here](https://s-pietz.github.io/BioStatisticsAnalysis/Penguins_Analysis2_1_17.html).

## Work with Great Lakes Fish

I then began an alaysis with a data set of various species of fish found in the Great Lakes regions. If you're also interested in this data, you can view my analysis [here](https://s-pietz.github.io/BioStatisticsAnalysis/GreatLakesFish.html). 

I liked this analysis because I was able to pick a data set, that I was interested in, and use what I learned with R and Biostatistics during our Penguins class analysis to undergo my own analyzation. 

### More on Great Lakes Fish
The first step in doing so was creating a hypothesis. The Great Lakes Fish data set comes from Great Lakes Fish Commission and includes 7 variables on 65,706 fish. Using code, I was able to split the data into exploratory and test data. My exploratory data included 7 variables of 32,853 fish. Therefore, I hypothesized that since the Lake Whitefish species is most abundant then this species will also have the greatest value (production amount). Again with this data, I was able to formulate some questions in order to gain a deeper understanding of the data on Great Lakes Fish and to determine if I could accept or reject my hypothesis. These questions include,
1. What species was observed the most throughout the lakes and regions? (overall grand total)
2. In what region were the most fish found overall?
3. Which specific lake housed the greatest amount of the most abundant species found in question 1?
4. What species yield the greatest production value?

To see more images and graphs I created to help me answer and represent these questions, don't forget to check out the full analysis [here](https://s-pietz.github.io/BioStatisticsAnalysis/GreatLakesFish.html). 

## Work with the Replication of Origin Project
I applied my knowledge using code to tackle my first real bioinformatics application. This project involved working through 4 different notbeooks called Intro to R for Bioinformatics, and Finding the Replication Origin, Parts I, II, and III. What was unique about this project was that we each were assigned a group to work with over several weeks to complete the replication origin project. I was able to colloaborate with my group-mates and connect our work to a shared GitHub repository. My group was named the Bioinformatics Finatics! 

The main purpose of these notebooks was to identify the location of the replication origin within a genome. I was able to apply the techniques I've learned from previous notebooks to help analyse the random genomes that I've generated as well as real bacterial genomes. I thought it was very interesting how I could take was I learned in my Biology classes and connect it to using code and statistics, which I have never done before! I used code to search for frequent genetic sbstrings that signal replication to DNA polymerase. Next, I learned to narrow down the area in which I was searching for the replication origin. In order to solve this, I exploited properties of genetic transcription and mutations, which I just learned about in my genetics class!

If you're interested, you can see how I worked through each notebook and view my full analayis of the Replication Origin Project [here](https://agmath.github.io/BIO4ST1_Group3/Replication_Skylar_Pietz.html). 

## Work with Volcano Eruptions!
The last portion of this project was to conduct an additional biostatistics project on another dataset. I chose to perform an analysis on a data set of volcanic eruptions. This data comes from The Smithsonian Institution and decribes volcanic activty from within the past 2,500 years. If you're interested in this data, you can view my full analysis [here](https://s-pietz.github.io/BioStatisticsAnalysis/Volcano_Eruptions.html). 

I enjoyed this analysis because I was able to pick a data set that I was interested in, and use what I learned throughout the semester with R studio, code, and biostatistics to perform my own analyzation. In the end I was able to answer some questions I had about the data.  

### More on Volcanic Eruptions

Just like the inital analysis on Great Lakes Fish, the first step in doing so was creating a hypothesis. The Volcano Eruptions data set comes from The Smithsonian Institution and includes 26 variables on 11,178 volcanoes. Using code, I was able to split the data into exploratory and test data. My exploratory data included 15 variables of 5,589 volcanoes. Therefore, I hypothesized that although volcanoes exist all over the globe, the most active volcanoes with confirmed eruptions are located close in proximity in nearby areas/regions on the map. Again with this data, I was able to formulate some interesting questions in order to gain a deeper understanding of the Volcano Eruptions data and to determine if I could accept or reject my hypothesis. These questions include,

1. Were there more confirmed or unconfirmed eruptions reported in total?
2. Which volcano recorded the highest number of confirmed eruptions?
3. In what area did the most reported eruptions occur?

The image added below represents the volcanic explosivity index (VEI). This is a relative measure of the explosiveness of volcanic eruptions. It was devised by Christopher G. Newhall of the United States Geological Survey and Stephen Self in 1982.

[Volcano Explosivity Index](https://camo.githubusercontent.com/9747c0fa7422e02bee5546dd6496ceefaac0e51d8854128f49268e124c4e62eb/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f302f30312f5645496669677572655f656e2e737667)

"Volume of products, eruption cloud height, and qualitative observations (using terms ranging from "gentle" to "mega-colossal") are used to determine the explosivity value. The scale is open-ended with the largest eruptions in history given a magnitude of 8. A value of 0 is given for non-explosive eruptions, defined as less than 10,000 m3 (350,000 cu ft) of tephra ejected; and 8 representing a mega-colossal explosive eruption that can eject 1.0×1012 m3 (240 cubic miles) of tephra and have a cloud column height of over 20 km (66,000 ft). The scale is logarithmic, with each interval on the scale representing a tenfold increase in observed ejecta criteria, with the exception of between VEI-0, VEI-1 and VEI-2, " (1). 

Once again, to see more images and tables I created to help me answer and represent these questions regarding recent and past volcanic activity, check out the full Volcano Eruptions analysis [here](https://s-pietz.github.io/BioStatisticsAnalysis/Volcano_Eruptions.html). 



References:

1. Newhall, Christopher G.; Self, Stephen (1982). "The Volcanic Explosivity Index (VEI): An Estimate of Explosive Magnitude for Historical Volcanism" (PDF). Journal of Geophysical Research. 87 (C2): 1231–1238. Bibcode:1982JGR....87.1231N. doi:10.1029/JC087iC02p01231. Archived from the original (PDF) on December 13, 2013


## THE END





