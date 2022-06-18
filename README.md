# Using KMeans Clustering to Segment Customers for a Social Entertainment App

The goal of the segmentation project is to determine optimal customers and their preferences for a company who wishes to build a “social entertainment" mobile app. The customer preference data was taken from a survey of 1800 respondents.  

The analysis uses kmeans clustering to group customers into clusters based on their responses to the survey questions.  

The A2-Segmentation html file contains the R code used to create the segmentation.

#### Customer Profiles from 3 Clusters
Distinct customer profiles were derived by analyzing the mean values from the variables with the highest contributions to Dim1 & Dim2. The variables with the highest contributions included:  
* The frequency of using social media sites like Twitter (q13r2), MySpace (q13r3)  
* Usage of music sites like AOL Radio (q13r7), Last.fm (q13r8), and Vevo (q13r5 )  
* Entertainment interests: “I like learning more about my favorite TV shows when I’m not watching them (q24r8) and”Music is an important part of my life (q24r7)  
* “It’s usually worth spending a few extra dollars to get extra app features” (q26r12)  
* “People often ask my advice when they are looking to buy technology or electronic products” (q24r2)  

The three customer segments derived were:  
* Low Engagers  
* Social Entertainers  
* Social Observers  

All three segments exhibited high usage of Facebook, so usage of other social media sites in addition to Facebook was a key differentiator between the segments.  

**Low Engagers** had low usage of other social media sites as well as low usage of music sites. While they had a medium level of interest in music, they had a low interest in paying for apps features.  

**Social Entertainers** had higher usage of Twitter and MySpace than Social Observers as well asl higher usage of music sites. This segment also had a high interest in paying for app features.  

**Social Observers** were differentiated in their higher usage of other social media sites but low usage of music sites. They did have a high interest in music, indicating that they may be potentially interested in a new music app.  

From the higher usage of social media and music sites and the highest interest in paying for app features, the Social Entertainers segment has the highest potential to be interested in the social entertainment app. The Social Observers segment also shows potential interest, but may be more casual users. The Low Engagers have low potential to be interested in the app and should not be pursued.  
