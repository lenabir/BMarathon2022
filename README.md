# BMarathon2022
**Business Requirements Documentation (BRD)Template
Requester(s): Marina 
Date: 07/01/2022
Audience (intended users): users of the Netflix application
Geographical Impact: 
Requested go live date: September 3rd 2022

**Problem Statement**
. 
Goal is to make the movie / TV show search process and decision- making easy and effective for the users of the Netflix application. We will provide a dataset that will enable search by category, genre, actor name, year of release and TMDB rating. 
What are the business questions this report will answer? 
What movie I/ family can watch based on our individual preferences? 
What are the highest rating movies in the specific category? 
In which movies my favorite actors are playing? 
**Business Justification (Benefits/ROI)**

Ultimately, this reporting will be used to drive client experience and satisfaction with the application. How many users actively utilize the Netflix service, periodically and do not use at all. Tool will help to monitor and suggest the best option based on individual preferences. Increase the Netflix application usage and profitability. 
-----------------------------------------------------------------------------------

**Data Module **
Steps for Dimentional Modeling 

Business Value: Use of Netflix application, movie selection 
Grain: 
--------------------------------------
Dimentions:
1)Production_Country (country name)
2)Movie_Discription (Title;description;Release_year;age_sertification)
3)Genres (geners_name)
4)Type (type name)
5)Actor_Info (actor_name;Character;Role)
--------------------------------------- 
Fact_Movie
id	
runtime	
seasons	
imdb_id	
imdb_score	
imdb_votes	
tmdb_popularity	
tmdb_score
person_id
