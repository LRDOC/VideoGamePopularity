# Video Game Popularity Analysis Tool
Roux Institute at Northeastern CS5001 Intensive Foundations of CS Fall 2023 Final Project

## Requirements
- Python (3.5+)
- Pandas library
- Requests library
- Matplotlib library

## Installation
- Ensure Python is installed on your system.
- Install required Python packages using `pip install` followed by `pandas requests` or ` matplotlib`

## Usage Instructions

1) Place the games.csv file in the data/rawData directory within the project.
2) Run main.py from the scripts directory to start the tool.
3) Choose 'historical' to see historical player data or 'current' for current player count.
    1) For historical data, select from the available games listed by the program.
    2) For current data, enter the specific game ID when prompted.
4) The tool will display a graph for historical data or the current player count for the chosen game.

## Troubleshooting
Ensure the CSV file is properly formatted as per the example provided in the data/rawData directory.

Game IDs should be accurate and correspond to the correct game for current player count functionality.

#### If you encounter a FileNotFoundError, ensure the CSV file is in the correct directory.
For any issues with fetching data from the API, idk check your internet.
