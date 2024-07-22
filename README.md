# Project 2 Movie Analysis
Flatiron Data Science Project: Movie Data Analysis
## Overview
Starting a Movie Studio is an important decision that follows with informed statistics and analytics. By analyzing various factors such as, genres, runtime, and directors, we will be able to identify trends that can contribute to the box office success that we are seeking. 

### Interactive Dashboard Link:
##### Below is the link to my Tableau which will show the different factors that would help in choosing the right movie.
   * 

### Presentation Link
##### Below is the link to my Google Slides on my Non-Technical Presentation
   * 

## Business Understanding
In order to ensure success of this new venture, my goal is to indetify potential issues so you the Movie Studio can make informed decisions as well as position yourself in a great place in the industry.
1. What film genres are performing best at the box office?

2. What is the optimal runtime for movies to maximize box office success?

3. Which directors are associated with the highest box office success?


## Data Understanding and Analysis

#### Source of Data
Files: `im.db` and `bom.movie_gross.csv.gz`

* IMDB: Contains information on movies, including titles, genres, directors, runtimes, and box office ratings.

* Box Office Mojo: Included movie titles, domestic gross, and foreign gross.

#### Data Visualization

   Top Performing Genres
    ![download](https://github.com/user-attachments/assets/7baefc30-8508-4f03-9395-c71bb11ed1da)

- The left chart is a representation of the top performing Genres by the Weighted Rating. Weighted rating was calculated using the number of votes and the average rating, equaling a Weighted Rating that can be graphed.
- The right chart shows the Average Gross that a genre makes. The Average Gross is the average of the domestic and foreign gross.


 Optimal Runtime
![download](https://github.com/user-attachments/assets/7610c512-e28d-405f-b870-b253d6fd7d11)

- Both graphs follow the same basis. We are using the Runtime as the variable, and we check the Weighted Rating and Average Gross depending on the Runtime of the movie.


Top Directors
![download](https://github.com/user-attachments/assets/9f210733-9868-4fb7-91c9-6a998f4d8c4d)
- This table shows the Directors with the heighest Weighted Rating, also how many movies they have done and what genres they specialize in.


![download](https://github.com/user-attachments/assets/d8faeb8c-ff8d-43ce-a194-6647df437553)
- This table shows the Directors with the highest Average Gross, also how many movies they have done and what genres they specialize in


## Conclusion
1. Sci-Fi and Animation both have the highest Weighted Rating and Average Gross
2. The best Runtime is 165-179 minutes because it has the highest Weighted Rating and Average Gross
3. The Russo Brothers have the highest Average Gross and Weighted Rating, but Christopher Nolan is the most consistent Director.

Recommending collaborating with directors that specializes in Sci-Fi to replicate their success. For example, an optimal choice would be Christopher Nolan. Mr. Nolan has 4 movies that specialized in Sci-Fi while all receiving the highest Weighted Rating. Limit him to about 170 minutes that engages the audience enough to receive the most box office returns.
