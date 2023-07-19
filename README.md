# Microsoft-venture-into-the-movie-industry

# <span style="color: blue; font-size: 24px;">Overview</span>

The project will primarily focus on the genres of movie films doing well in the industry at the Box Office. The goal is to provide the best recommendations to Microsoft for their new movie studio. As a result, this should guide Microsoft into making the most informed decisions through understanding of the films that are most popular in terms of performance in the industry. This will also bring in a competitive advantage into an already existing market.

# <span style="color: blue; font-size: 24px;">Business Problem</span>

Microsoft is considering venturing into the entertainment industry, specifically movie creation. However, it does not have full information necessary to enter into the industry and be successful. Therefore, the aim is to provide relevant data that enables the company to acquire insights into the popularity of various films in order to venture the market successfully.

By the end of the analysis,one will be able to answer the following:
- Most profitable genres in the industry
- Most popular production studios
- Movies making most profits
- Preferred languages to enhance inclusivity

# <span style="color: blue; font-size: 24px;">Objectives</span>

The objectives of this project are:
- Research current film trends and analyze box office success of various movie genres.
- Identify the most profitable and popular movie genres in the market.
- Develop a list of recommendations for Microsoft's new movie studio based on the research findings.
- Present a comprehensive report of the research findings and recommendations to the head of the new movie studio.

# <span style="color: blue; font-size: 24px;">Data Understanding</span>


In this project, we will work with movie datasets which will provide the following information:
1. Movie titles
2. Movie genre
3. Year of production
4. Runtime for each movie
5. Domestic and foreign gross earnings

The data is contained in fie separate csv files
1. imdb.title.basics: each record contains the movie title, genre, start year and run time
2. bom.movie_gross: each record contains the movie title, start year, studio, gross and foreign earnings
3. tn.movie_budgets.csv: each record contains movie ID, release date, movie title, production budget, domestic and foreign gross earnings in USD
4. tmdb.movies.csv: each record contains genre IDs, original language and title, level of popularity, release date, movie title, vote averages and vote counts.
5. title_ratings: each record contains the movie title, average ratings and number of votes.

# <span style="color: blue; font-size: 24px;">Load the datasets</span>


Create a dataframes title_basics and movie_gross that represent the two CSV files. Use pandas methods to inspect the shape and other attributes of these dataframes.

# <span style="color: blue; font-size: 24px;">Data Cleaning</span>

For data cleaning, I examined the structure of my dataset and dropped unnecessary columns and rows to ensure there are no missing values. Also i merged various datasets into a single one to make it easier to do analysis and correlations.

# <span style="color: blue; font-size: 24px;">Merging of Data frames</span>

Creation of joins is necessary to ease analysis of data and investigate relationships.

# <span style="color: blue; font-size: 24px;">Analysis of the movie industry competitiveness</span>

In the cells below, i am going to analyse the competitiveness of the existing movie industry based on the cleaned and merged data above. I will look into the profitability of different genres, profitability per studio, and the ratings of genres.

![image](https://github.com/EvangelineNgunjiri/Microsoft-venture-into-the-movie-industry/assets/133154189/5b355e0c-12ee-4657-a5f0-a486347f2e0b)
