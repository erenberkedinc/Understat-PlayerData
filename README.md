
# UnderStat - Detailed Player Data

We scrape player's detailed xG, goals and shots from Understat. 

On this example, We scraped Haaland's 2020-2021 attacking (xG-Goals-Shots) data. Then we visualized this data and saved the detailed data to csv file.

## Parameters
- player: Understat player id (Haaland's player id is 8260)
- playerName: Player name for the graphic title (not important)
- statsSeason: The season which we want to use (default 2020 which means 2020-2021 season)
- fbref_playerName: Player name on the fbref data. ( We use fbref data for total minutes information to calculate per90 metrics)
