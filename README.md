# Movies-ETL 


# PURPOSE OF ANALYSIS

Amazing Prime Video wants to create an algorithm that determines which low budget movies being released will be popular so they can buy the streaming rights of those films at a bargain price. 

To figure this out, they have decided to have a Hackathon, where contestants are given a clean dataset of movie data, participants predict the popular movies. 

Brita and I were tasked with creating this clean dataset by: 
 - doing a scrape of wikipedia of all movies realeased since 1990
 - doing a scrape of rating data from MovieLand website 
 - utilize a SQL database for sharing the data in the hackathon
 - include ratings data


After completing this task, Amazing Prime loved the dataset and wants to keep it updated on a dailybasis. 

We were then tasked with creating an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 

Resources 
    - movies_metadata.csv
    - ratings.csv
    -wikipedia-movies.json
    
Software 
    - Python 3.8.3
    - Pandas 
    - pgAdmin 4, version 4.26
