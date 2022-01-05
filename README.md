
# Visualizing NBA Data

### Credit where its due

This repository is forked from @DomSamangy. I will add my own work here as I experiment with different NBA data visualization techniques in R.

### My efforts so far

Most of my work so far has been exploratory, but I am currently working on a project to generate daily point total high shot charts. 
#### Daily Point Total Shot Charts
Eventually I hope to deploy this as an algorithm that can be run daily. Once working, it should display the shot chart for whichever player had the highest point total the prior day. This work can be found in the file [Previous_Day_High_Shot_Chart](Previous_Day_High_Shot_Chart.Rmd).

@christensenjo

<em>Following README from original fork:</em>
---------------------------

# R_Tutorials

To complement my R tutorials on YouTube, this repository contains the R markdown files that contain the scripts I used to produce the visualizations in the videos. Those can be found here: https://www.youtube.com/playlist?list=PL10a1_q15Hwr4H5dCXQD3htK5VGfwjrgq. 

The tutorials included are:

- NBA and NCAA basketball shot charts utilizing the NBA API and ncaahoopR package.
    - The tutorial shows how to create a court, scrape player shot data, and finally plot and customize an aesthetcially pleasing shot chart. The finished products can be seen above in png form!
![Example_NBA_Shot_Chart_Durant](https://user-images.githubusercontent.com/70119566/125554311-0ca5a6bf-707b-48f3-9d28-2d60c3f8b380.png)
- Using rvest to scrape baksetball-reference.com and fbref.com and then visualizing relationships using scatter plots.
    - The tutorial shows how to scrape indivudal tables from the aforementioned websites. We then utilizee ggplot2 to visualize the relationships between xG and xGA in the Premier League and offensive and defensive rating in the NBA.
![nba](https://user-images.githubusercontent.com/70119566/125554339-3ed4238b-96ec-461c-8a34-4ed718269889.png)
- Creating NBA shot and Soccer pass heatmaps using nbastatR and StatsBombR packages.
    - The tutorial shows how to create heatmaps for both NBA shots and Soccer/Football passes using geom_contour_2d_filled. FCrStats's SBPitch package is also used to plot a pitch and other customizable features are shown as well.
![CP3_Heatmap](https://user-images.githubusercontent.com/70119566/125554356-251b279d-da68-45a8-83cb-205e78a0eec2.png)
![Example_Soccer_Heatmap](https://user-images.githubusercontent.com/70119566/125554276-b578c3d8-b513-46ec-bd74-36e145679766.png)
- Creating NBA nd Soccer/Football poalr/pizza charts.
    - The tutorial shows how to create heatmaps for both NBA shots and Soccer/Football using a manually created data frame and scraping football reference scouting reports from the worldfootballR package.
  ![Example_Soccer_Polar](https://user-images.githubusercontent.com/70119566/142473174-cd727b32-18e6-46c7-9a00-17e182b456c1.png)
  ![Example_NBA_Polar](https://user-images.githubusercontent.com/70119566/142473196-45c56ac9-519d-4c1a-98ed-a61e4a8a115f.png)
