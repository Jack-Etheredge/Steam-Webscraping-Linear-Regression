# Steam-Webscraping-Linear-Regression
I scraped Steam and steamDB data for every video game available for purchase through Steam and then performed linear regression to predict the number of concurrent users. This was done using Selenium and Python. Many Python packages were used including pandas, seaborn, stats models, scikitlearn, fuzzywuzzy.

I used a combination of Selenium webdriving and beautiful soup to scrape the data.

I've included the scraped data in this repo: [steam_games_dicts_selenium.json](steam_games_dicts_selenium.json) and [steam_users_table.csv](steam_users_table.csv).

# Variables collected for each videogame included:

Price

Discounted Price

Number of overall reviews

Number of recent reviews

Percentage of positive overall reviews

Percentage of positive recent reviews

ESRB Rating

User-defined tags

Genre(s)

Publisher(s)

Developer(s)

Release Date



# Linear regression:

I attempted to predict peak concurrent users scaped from SteamDB using these independent variables.

Linear regression models were made using ordinary least squares, select k-best features, and both lasso and ridge regularization.

Ultimately, ridge regularization performed the best so far.


