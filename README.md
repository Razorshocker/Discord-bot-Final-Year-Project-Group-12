# Discord-bot-Final-Year-Project-Group-12
Discord bot for gamers, gets information from website using web scraping. Functionalities: get information of game, check game updates

Bot setup: uses the prefix: "g/"

Database: automatically connects/create a new database if not present in the directory of this code.

# functions:
log_user_behaviour: inserts the values of input and output into database

update_user_stats: inserts/update values in database

get_user_info: fetches info from database

detele_user_info: deletes user info based on the id

update_favourite: updates favourite game in database

# commands:
g/help: displays all commands
g/list_games: displays all games available

g/game_info: checks game name and get information from website link. stores data into database using update_user_stats and log_user_behaviour.

g/check_updates: accepts a game name and channel id to check for game updates from website every 5 minutes and post in the channel id.

g/searchInfo: accepts a game name followed by keyword to search for in the websites.

Discord Bot's Token is not given.

