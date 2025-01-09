# CS-598-Practical-Statistical-Learning
- Course Project for CS 598 - Practical Statistical Learning.
- Project done with the help of Yusuf Khan (@ykhan21), given by course staff to build movie recommender systems based on the following:
  - System I - Recommendation Based on Genres. We were given the liberty to choose what characteristics made a movie popular. As discussed in the project, we chose:
    - Number of ratings,
    - Average rating above 3.5 stars,
    - and Minumum number of ratings to be considered.
  - We believe these criteria manage to build a list that is accurate and reflects an overall sense of what the public beleive is a popular movie. Popular movies tend to have a higher number of ratings as many it has reached
  a larger audience. Combined with the average rating above 3.5 stars, the list is narrowed to high audience films with really good feedback. The final criteria allows us to explore older films, as newer films usually have
  lower number of ratings.
  - System II - Recommendation Based on IBCF. This was straight forward, given the derivation and actual formula, we implemented the IBCF function.
- The Project also required us to build an App for both Systems. The basic requirements were:
  - System I:
    - Allow users to input their favorite movie genre.
    - Provide 10 movie recommendations based on the user’s selected genre.
    - Save your top movie recommendations for each genre (e.g., in a table) to avoid recomputing them each time.
  - System II:
    - Present users with a set of sample movies and ask them to rate them.
    - Use the ratings provided by the user as input for your myIBCF function.
    - Display 10 movie recommendations for the user based on their ratings.
- The App source code can be found under my partner's github: <https://github.com/ykhan21/MovieRecommender>
