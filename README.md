# NBA Player Statistics and Salary Analysis

This project analyzes NBA player performance data (2021-22 season) and salary information to uncover insights such as player efficiency and team salary distributions. It leverages data visualization techniques to present these insights.

## Dataset

This analysis uses two datasets:
1. **Player Game Logs**: Contains detailed statistics for each game played in the 2021-22 season.
2. **Player Salaries**: Provides salary information for players during the 2021-22 season.

### Dataset Fields
- **Player Game Logs**:
  - `game_id`: Unique identifier for each game
  - `game_date`: Date of the game
  - `H_A`: Home or Away game indicator
  - `Team_Abbrev`: Abbreviation of the player's team
  - `Opponent_Abbrev`: Abbreviation of the opponent's team
  - `player`: Player name
  - `pts`: Points scored by the player
  - `minutes`: Minutes played by the player

- **Player Salaries**:
  - `Player`: Name of the player
  - `2021/22`: Salary for the 2021-22 season

## Methods

### Data Cleaning and Preprocessing
1. Filtered relevant columns:
   - Game logs: `game_id`, `game_date`, `player`, `pts`, `minutes`, `H_A`, etc.
   - Salaries: `Player`, `2021/22`
2. Removed duplicates and handled null values.
3. Merged datasets on the player's name.

### Analysis
1. **Player Efficiency**:
   - Calculated total points, minutes, and average salary per player.
   - Computed Points Per Game per Dollar (`PPG/$`) to identify value players.
2. **Team Salary Breakdown**:
   - Aggregated salaries by team to calculate total payrolls.
   - Created visualizations for salary distributions across teams.
3. **Lakers Salary Analysis**:
   - Analyzed the salary breakdown for top Lakers players.

### Visualizations
- **Histogram**: Distribution of total points scored per game.
  ![output (3)](https://github.com/user-attachments/assets/6fd07236-6442-469e-adc7-ce1d000cbcef)

- **Bar Chart**: Total salary paid by each team.
  ![output (4)](https://github.com/user-attachments/assets/7efa230c-4922-4431-914d-b350bb4b8f8e)

- **Horizontal Bar Chart**: Salary distribution by team.
  ![output (5)](https://github.com/user-attachments/assets/ec483b06-b141-45e4-830b-535c38373597)

- **Pie Chart**: Salary breakdown for the Lakers' top players.
  ![output (6)](https://github.com/user-attachments/assets/fb852c6c-4d43-4249-8301-62b8826ea1f5)


## Results

### Key Insights
1. **Top Players by PPG/$**:
   - Brandon Williams provided the best value in terms of points scored per salary dollar.
2. **Team Salaries**:
   - Brooklyn Nets had the highest total payroll in the league ($223.6M).
3. **Lakers' Salary Breakdown**:
   - Russell Westbrook accounted for the highest percentage of the Lakers' payroll at $44.2M (24.6%).

