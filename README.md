### ALX-Udacity-Investigate-a-Dataset
> An Udacity Data A nalyst Nanodegree project on a TMDb Dataset. The Dataset contains 10,000 rows of movie information.

### Package Installations
> The following libraries were employed for the purpose of our analysis:
- **Pandas:**: For manipulating structured data 
- **Numpy:** dealing with multi-dimensional arrays. 
- **:Matplotlib:**: for visualizations

### Project methodology
> This project aimed to generate insights on different aspects of the TMDb Dataset using Data Wrangling and Exploratory Data Analysis. Focus was on key variables, such as revenue, budget, and popularity.

### Summary of Findings
- From the analysis, ratings do not appear to significantly control the popularity of a released movie. Some highly rated movies recorded lesser popularity than lower rated movies. This means that the popularity of a movie is not heavily dependent on its ratings, and is influenced by some other factors as well. The highest rated movie (9.2) by the number of average votes, The Story of Film: An Odyssey, falls in the least popular percentile. In contrast, the most popular movie, Jurassic World, has a rating of 6.5 which is lower than many of the less popular movies.

- In the test for the relationship between ratings and revenue, the result proved low. However, ratings seem to be respected at a particular threshold. Movies with revenues of 1bn and above generally have ratings between 6.0 and above. This is an interesting point for some additional research.

### Limitations
Some limitiations that may hamper analysis include:

- The number of cleaned null values which existed in the dataset poses a limitation with respect to the accuracy of the data and the analysis that subsequently followed.
- We are also not clear on how the rating system works. Are the votes based off a general perception, or critical review, and were these done by qualified voters.
