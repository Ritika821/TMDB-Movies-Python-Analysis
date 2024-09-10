# TMDB-Movies-Python-Analysis


## Introduction :

TMDB stands for The Movie Database. In this project we will be investigating the TMDB Dataset which is providing us with various useful information regarding movies and how good or bad they performed both qualitatively and quantitatively. In this dataset there is movies from the year 1960 to 2015. Our aim is to get some insight into what makes movies get better reviews and get more viewers and hence make more revenues. This can give you an idea of how other viewers feel about the show.

<p align="center">
<a><img src="" width="700" height="300">
</a></p>

--------------------------------------------------------------------------------------------------------------------------------------------------------


## About Dataset :

1. imdb_id: It represents imdb_id of the movie in the IMDB Database.
2. popularity: It represents the popularity score of the movie.
3. budget: It represents the budget of the movie in dollars.
4. revenue: It represents the total revenue collected by the movie in dollars.
5. original_title: It represents the title of the movie.
6. cast: It tells the actors who acted in that movie.
7. director: It tells the director of the movie.
8. overview: It tells the overview of the plot of the movie.
9. runtime: It tells the overall runtime of the movie in minutes
10. gehres: It represents the genres the movie represents.
11. release_date: It tells the date of release of the movie.
12. release_year: It tells the year in which the movie was released.

--------------------------------------------------------------------------------------------------------------------------------------------------------


## This Project includes :

- **Import Libraries :** The first step to import libraries that are required like numby, matplotlib, seaborn and pandas by writing code.
- **Load Dataset :** Loaded TMDB Dataset through pandas read_csv code.
- **Data Wrangling :** Ensured accuracy and consistency by removing null values and dublicate values, then derived significant columns for analysis.
- **Data Analysis :** Inserted additional profit column and then splited one column to more columns.
- **Data Interpretation :** Drag various qualitative informations through interpreting data.
- **Data Visualization :** Through Seaborn library, constructed various visuals for clear understanding.

----------------------------------------------------------------------------------------------------------------------------------------------------------


## Important Questions derived from the Project :

1. Which movie has a maximum budget and how much ?
2. Which movie has a maximum profit and how much ?
3. Which movie has a maximum popularity and how much ?
4. Which movie has a maximum vote and how much ?
5. Which movie has least profit and how much ?
6. Which movie has least popularity and how much ?
7. Which genre has gained the maximum profit ?
8. Which genre has gained the maximum popularity ?
9. Which genre has gained the maximum mean budget ?
10. Which genre has gained the maximum mean revenue ?
11. Which genre is most common between 1960-2015 ? 
12. In which year movies with the maximum mean budget has made ?
13. In which year movies with the maximum mean profit has made ?
14. In which year movies with the maximum mean revenue has made ?
15. Which year we have more movies released ?

----------------------------------------------------------------------------------------------------------------------------------------------------------


## ## Based on the report Insights, here are the outcomes :

1. "The Warrior's Way" movie has 425000000 budget which is the maximum budget than others.

   <p align="centre">
   <a img src="" height="250" width="400">
   </a></p>

2. "Avatar" movie has 2544505847 profit which is the maximum profit than others.

   <p align="centre">
   <a img src="" height="250" width="400">
   </a></p>

3. "Jurassic World" movie has 32.985763 popularity which is the maximum popularity than others.

   <p align="centre">
   <a img src="" height="250" width="400">
   </a></p>

4. 'Inception' movie has 9767 votes which the maximum votes than others.

   <p align="centre">
   <a img src="" height="250" width="400">
   </a></p>

5. "The Warrior's Way" movie has -413912431 loss, that means its revenue doesn't touch the total budget also and has suffered from greater loss.

   <p align="centre">
   <a img src="" height="250" width="400">
   </a></p>

6. 'North and South, Book I' movie has got 6.5e-05 popularity only, which is the least popularity than others.

   <p align="centre">
   <a img src="" height="250" width="400">
   </a></p>

7. Adventure genre has gained the maximum profit i.e. 7.559417e+07.

8. Adventure genre has the maximum populalirty i.e. 1.154259.

9. Adventure genre has the maximum mean budget i.e. 3.754369e+07.

10. Adventure genre has gained maximum mean revenue i.e. 1.131379e+08.

11. Drama genre has made maximum movies i.e. 4672.

12. Movies with the maximum mean budget were made in year 1999.

13. Movies had the maximum mean profit in year 2015.

14. Movies had the maximum mean revenue in year 2015.

15. Maximum Movies were made in the year 2014.

----------------------------------------------------------------------------------------------------------------------------------------------------------


## Conclusion :

This Report is helpful in gaining knowledge about the generation of movies after 1960, how film industry has developed itself that over time more and more movies were made per year. Starting at just 32 movies in 1960 up to 627 per year in 2015 with a max of 699 movies in 2014. From the given graphs in the project we can observe that revenue and profit developed almost in parallel untill the early 1980s. In the 1980s budget is increasing more sharply. Probably as a consequence the gap between revenue and profit is starting to emerge. At the end of the 1990s budget starts decreasing, probably due to technological progress, and therefore profit starts to increase again. We also found that Drama is the most common genre (17.6%) followed by Comedy (14.2%) and then Thriller (10.7%). Through the Scatterplot between budget and profit we find evidence for a moderate linear relationship with a coefficient of ~0.570. Hence we can gather more information about the movies from this Report.

----------------------------------------------------------------------------------------------------------------------------------------------------------


## Author :

- ![@Ritika821](https://github.com/Ritika821)
- Ritika : Data Analyst

----------------------------------------------------------------------------------------------------------------------------------------------------------
