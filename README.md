# Individual_Self_Assessment
 
 
 In First Week,We started to pick topics for final week.We had a lot of topics just like wine_weather,Covid-19,Election prediction, Amazon price tracker,Twitter sentimental but We picked to Wine_weather as per team's decision by zoom metting & discussed in slack.We divided group into different task.Based on that  for me ,Wine'api was given by team. On initial base,It was very frusruted to find wine api but Finally i got Golbal wine score  by bunch of reserch.Golbal wine api has a some input parameter just like applleation,Wine_name,Wine_score,Region,Color,Country.We decided to pick as Usa country and Red&White as Color as per team's disccussion.Red & White Api converted into csv form.
 
 
 
 
 In Second Weeek,We would required to pick common link for weather data for future Analysis.We decided to go with appellation.We assumed that Weather would be same around 50 miles zipcodes.I tried to find all appellation manual.Based on that I found that,Napa's zip code has cover a lot of appellation of wine and as well as Sonoma's zip code has cover a lot of appellation.I found 8 applleation cover all wine data's appellation.Another challenge to merging weather and wine data was that several appellations (regions) within a state straddled two different zip codes .Me&my teammate 's Shawn worked continued on connect weather & Wine.We had 2 week between week-2&week-3 project segment.That'why We had lot of days to slove complex problem but we did it by a lot of failur.
 
 
 
 In Third Week,We had a data with clean.One of Teammate had alrerady set up machine learning with Aws server.Now We were need to find best model fit for data.I was also drive into machine learning to try to get high accuray. It was very hard to get high accuary without overfitting.I contributed also tableu set up in third week.I tried to convert all project analysis into tableu and tried to find best answer for project Analysis.It was very short week for cover all things .
 
 
In Fourth and final week for Project ,We were about  to done our project but Our TA gave to us  one more challenge to add web app as part of Darshboad That'why We had a lot of frusruted. Because nobody had any type of exprience  for dump machine learning into flask app and also We had 4 days for complete webapp.Everybody tried to find way by watching video &online material to  about  how to dump machine learning into flask app.I was also drive into to find solution.Finally We got solution by a lot of experiment.I prepared also  tableau and ppt google side for presentations.It was great exprience.I learnt a lot of things from project.I was very gratefull to part of nice team member.




# Team Assessment:


For Project ,We had a powerfull team just like-Sonia , Val, Shawn, Neal,Meredith and me.Everyone have different storng background.We started to pick topics for final week.We decided to pick a Wine_weather for final project And also Soil data keep in mind.Because  of We need a storng base for project.We did split team into 3 different team's task just like-One team for Data Cleanning &Data Expolation, One Team for Machine Learning and One Team for Database,PPt,Presentations. 


Everybody did good job in project .We communicated through Slack. Everyone uploads data to their Github branch and create a pull request. One Teammate merges the data after everyone discuss the final plans.Each member of team had there own branch and makes at least 4 commits per week.

Everybody helped to each other whenever sometime stuck in problem.We did it by all team member.During project We faced some challenge like-merging weather and wine data was that several appellations (regions) within a state straddled two different zip codes and The Webapp  as  the Machine Learning model to determine if the wine is of high quality or low quality.We sloved challenge by all teammate 's support.

# Summary of Project :

#### Data Cleaning and Analysis:

First step involved importing APIs to call weather, wine and soil data. The data was collected from Global Wine Scores, NOAA, and the USGS website. It was then cleaned and finally merged together. Data was split between white wine and red wine before the weather and soil data was merged with it. The Global Wine Scores website has data for wines, the regions that they were grown in, and the scores associated with each wine. These vintages range from 1992 to 2016 and have an average score of approximately 91%. The wine data takes different wines and scores going back to 1992.Some of the challenges for finding the best weather data was to find zip codes that have reliable temperature and precipitation data. Most of the zip codes had data that originated before 1992 but the stations had missig dates for temperature, precipitation, or both of the values. The process for finding optimal stations involved an iterative process of importing different zip codes for temperature data and different zip codes for precipitation data to determine which zip codes have the best coverage of data. Another challenge to merging weather and wine data was that several appellations (regions) within a state straddled two different zip codes. One of the assumptions this study has made was that weather data would be the same for zip codes that were within 50 mile radius of one another. This allowed the group to assign zip codes for certain appellations and allowed the data to be merged together more succinctly. The wine data comes from wine that is concentrated in Washington State, Oregon, Napa Valley California, Sonoma County California, and the Santa Cruz Mountains in California as well. There were some appellations that only have one or two data points that were dropped from the study.

#### Database Storage:


The data was connected through primary keys (unique values in the main table).Once the relationship of the database was created, we used AWS to read and write data from our notebook to and from SQL. In SQL, we joined soil table to the red wine table, and soil table to the white table.

#### Model Choice, Benefits & Limitations for Machine Learning:

* Deep Learning Neural Network - The limitation of the model is that it requires a large amount of data and it's not easy to comprehend. The benefits of this model can solve complex problems.

* Random Forest Classifier - The limitation is that features need to have some predictive power to work. The benefit is handling of huge amount of data, No problem of overfitting

* Logistic Regression - The limitation of the model is that it can be easily outperformed by sturdier model like Neural Networks, also its high reliance on a proper presentation of your data. The benefits of this model are that it's easier to implement, very efficient to train and it outputs well-calibrated predicted probabilities.



We chose the Logistic Regression model as the best fit model for this analysis after trying multiple models and considering the structure of our data to help answer our questions.


#### Flask App/HTML as Dashboard:


The flask app was desgined along with the HTML to allow users to input data into our app and determine if a particular wine from a particular year is a good vintage. The app takes in inputs such as: red or white wine, vintage, and the vineyard where the wine comes from. The app then uses the Machine Learning model to determine if the wine is of high quality or low quality.link is for web app.





web app- https://groupfive-wine.herokuapp.com/

Tableau -https://public.tableau.com/profile/valencia.loyd2616#!/vizhome/Group_5_wine_16046307141490/PartnersinWine?publish=yes




