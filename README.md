# Media_Project

The first step my partner Fred and I did was we brainstormed about various possible strategies we were to use to tackle this project. The task at hand was to use mass data and draw inferences from it to suggest a certain plan for Microsoft to build their movie studio. We thought money and financial profit was the most important decision driver for us and therefore began our data search for the highest grossing films of all time. As the project continued throughout the week, we reformulated and pinpointed what our strategy was because our data was returning to us and we knew more. 


Webscraping and APIs were our prime objectives for day 1 and 2. The data obtained from API winded up being our 10,000 data variables needed for us to do our analysis. From the webscraping, we were able to get a movie rubric. We got the API from 
themoviedb.com and our webscraping pages are shown in out notebook.


   
   Later we will compare this rubric with our actual data breakdown.
   
   A big impasse we had to overcome during the data cleaning process was that multiple movie genres occured in a movie. We had to clean our data to create our visualizations. The genres in the ’genre_ids’ column were lists of numbers, not a string referring to the genre. Moreover, lists were used because many movies assigned to multiple genres. First we had to get the genres that were associated with the numbers, which had to be cleaned into a dictionary, then to a list of values. Then a For loop was run through the list to create a new column for each genre. After that, we ran an Apply and For loop to replace the lists of numbers in the original genre column into lists of words(actual genre). Lastly, an IF statement and another For loop were used to populate a ‘1’ in each of the newly formed columns based on what was in the original genre column. This was extremely helpful because we were able to create our visualizations using all movies assigned to a particular genre regardless if a movie was assigned to multiple genres. So we could accurately measure each genre.
   
   Movie rubric= For us the top 20 Movies adjusted for inflation served to tell us the proportion of these movies dedicated to each film genre. The rationale behind this is that there will be certain genres that are more popular than others. Our data says Action/Adventure was most popular (40%). Drama was second (30%). Comedy (15%). And Animation, Horror, and SciFi (5% each). This rubric tells us that out of the top 20 movies of all time (adjusted for inflation) broken down respective of the genres. Fro example, there were action/dramas or adventure/scifi. Our data enumerated for that when we found the mean values of the 'vote rating' and  
   
   
BREAKDOWN OF OUR PROJECT WORK


JEFF'S NOTEBOOK=>    webscraping, coding to get those dataframes, dataframes from that data, and API key
    DataFrame to build some of graph#3, and graph#4



FRED'S NOTEBOOK=>    API with our main mass dataset worked with, coding to get those dataframes, Dataframes to build graph#1, graph#2

  
  
   At the end of the project the five questions that arose were:
   1. Which genres are most popular?
   2. How is popularity related to vote average?
   3. 
   4. Why are so many comedys made yet they never gross much money? WHy isnt anyone willing to invest in comedy and get a high rate of return?
   5. Popularity vs whats actually made. WHy dont we just satisfy consumbr demand?
         