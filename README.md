![Board Game Dashboard](./BoardGameGeek_Logo.svg.png){:width="300px" height="200px"}
# Board Game Dashboard

This project is a board game dashboard that allows users to explore and analyze information about board games. The dashboard provides various visualizations and statistics to help users gain insights into different aspects of board games.

## Features

The dashboard consists of the following graphs and features:

1. Area chart: Displays the distribution of games by published date.
2. Packet bubbles chart: Presents games categorized into the newly created categories.
3. Donut chart: Shows the level and quantity of games.
4. Dual lines chart: Compares user ratings and Board Game Geek (BGG) ratings.
5. Overall statistics KPI: Provides averages for complexity, user rating, BGG ratings, year published, total amount of games, age by publisher, minimum players, maximum players, minimum playtime, and maximum playtime.
6. Created bin for user rating: Generates a histogram of user ratings.
7. Scatter plot: Visualizes user ratings versus the number of players.
8. Grant view of user ratings versus playing time.
9. Bar chart: Compares user ratings versus artist.
10. Bar chart: Compares user ratings versus designer.
11. Table: Displays details of the games, including the image, name, short description, mechanic, and complexity.
12. KPI: Compares the age by publishers versus the recommended age according to users using a calculated field that determines the recommended age using the average sum of pool votes.
13. Bar chart: Displays the recommended players according to users using a calculated field that determines the percentage of votes per number of players from pool votes.

## Data Extraction

The information for this dashboard was extracted from the BoardGameGeek (BGG) website using web scraping techniques. The code used for data extraction is not included in this README file, but it can be found in the project files. The code scrapes the BGG website to obtain unique codes for each game and then retrieves detailed information about each game using the BoardGameGeek API.

## Data Cleaning and Merging

After extracting the data, it went through a cleaning process. The data from different tables was merged based on common identifiers. Additionally, new categories were assigned to the games using ChatGPT, which analyzed game details and assigned them to the desired categories. Finally, calculated fields were created to enhance the analysis.

## Usage

To use this board game dashboard, follow these steps:

1. Launch the dashboard application to visualize and explore the board game data. [Click here to access the dashboard](https://public.tableau.com/views/Project5_Dashboard_BGG/Dashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
2. Interact with the different graphs and features to drill down and obtain the desired information about board games.

Please note that the code and data files provided in this project are for demonstration purposes only and may require further customization and adaptation to suit your specific needs.

## Conclusion

This board game dashboard provides an interactive and informative way to explore and analyze board game data. By utilizing various graphs and statistics, users can gain insights into different aspects of board games, such as ratings, categories, designers, and more. The dashboard can be a valuable tool for board game enthusiasts, researchers, and industry professionals interested in understanding and exploring the world of board games.
