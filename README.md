# Phase 1 Project
 
This project makes use of datasets in order to provide an analysis on what movies to make. 

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data Used
* `bom.movie_gross.csv.`
* `movie_buget.csv.`
* `movie_info.tsv.`
* `movie.csv.`

## Approach to analysis

   #### Problem Statement:
   
   You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

   #### Research questions:
   
   what are the movies with the highest earnings?, 
   what are their genres?, 
   who made them(studio) ? 
   what were the budgets to profit comparison over studio and years?

   #### Sart by understanding the content in the different Dataset provides
  
   import the pandas library, numpy and matplotlib as the analysis uses the following libraries to explore the data 

    import pandas as pd
    import matplotlib.pyplot as plt
    import numpy as np
​     
   ##### Unpack datasets 
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/Movies_info.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">
      
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/Movies.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">
      
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/Movies_budget.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">
      
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/Movies_gross.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">
   
   #### Explore to find meaningful data
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/Genres.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">
      image.png
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/Worldwide_gross.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">
      image.png
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/Total_gross.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">
      image.png
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/Overall%20profit.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">
      
   <img
      src="https://github.com/Kelta153/Phase-1-Project/blob/main/Project_images/BV.png"
      style="display: inline-block; margin: 0 auto; max-width: 300px">

## Conclusion
Buena Vista (BV) is the market leader as of the data and the previous analysis back this. They make movies movies with the highest popularity based on the most polpular genre from Toy Story 3,Alice in Wonderland (2010) to The Marvel Franchise all in the Action, Superhero, Science Fiction, Adventure and Fantasy.There is also Avatar although not being from BV falls under that genre. Also although the decrease in the worldwide gross and total profit which may in turn be the reason for no relation with production budget, the fact that worldwide/foreign_gross still weild more profits for the movies may lead me to assume the Production Budget are still kept high to produce something that attracts a wider audience. Whether The 2020 pandemic is the major role at play for decrease of profits or it an underlining factor that has gone unseen, it is currently no in the dataset and may need further extensive research.

