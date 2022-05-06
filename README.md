# guesstheelo_sl

In the game of chess, there is a chess rating system that estimates the strength of a player based on their performance in previous games. The higher a player's rating, the better the player typically is. Ratings on the site Lichess.org range from about 800 to 3000. An 800 rating is extremely bad and a rating of 3000 is world-class elite level.

On the popular chess YouTube channel GothamChess, there is a series called "Guess The Elo" where he watches a game of chess being played without seeing the ratings of the players. After the game is completed, he attempts to guess the rating of both players. The first episode of his series can be seen here for an example: https://www.youtube.com/watch?v=0baCL9wwJTA

The goal of this module is to do exactly the same as the "Guess The Elo" series, except with data. It will use data from completed chess games to predict a player's rating. For simplicity sake, this module will guess the rating of the player who plays with the white pieces. We can expect the model to guess the rating of the player who plays with the black pieces to be nearly identical.

After a game of online chess is played, a number of stats about the game are saved. Some example stats are numbers of mistakes made by each player, number of blunders (aka very bad mistakes) made by each player, and so on. These are the stats that will be used to try to predict the player's rating.

The data is pulled from https://www.kaggle.com/ahmedalghafri/lichess-chess-games-statistics?select=Chess+games+stats.csv, which was pulled from the chess website Lichess.org. The dataset includes the ratings of each players for the target variable. For potential feature variables, the dataset includes all relevant statistics from individual chess games.

The final model ended up not being very strong.

While it may be fun to predict the rating of a chess player after viewing one game, it is certainly not accurate. Thinking back on this, the fact that it is difficult to predict a player's rating after viewing one of his or her games definitely adds to the fun of the "Guess The Elo" YouTube series. It can provide a lot of "I never would have guessed that" moments. It can also provide moments where you are amazed at how well a low-level rating player can play and provide moments where you are amazed at how poorly a high-level rating player can play. If it was easy to predict, it would be doubtful the YouTube series has as much success as it has now.

As it stands now, there are no future plans for this project.
