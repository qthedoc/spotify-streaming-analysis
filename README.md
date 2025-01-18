# Spotify Streaming History Analysis

## Overview
This project focuses on analyzing and visualizing Spotify streaming history data to gain insights into listening habits and preferences. The dataset used for this analysis comes from your spotify `Extended streaming history` from spotify's [privacy page](https://www.spotify.com/us/account/privacy/). It contains detailed information about the user's listening history, including the date, time, artist, track, and duration of each played song.

## Motivation
The goal of this project is to explore the patterns and trends within the user's Spotify streaming history and extract meaningful insights such as:

- What are the user's all time top listened to artists/tracks/albums?
- How has the user's listening behavior changed over time?
- Are there any noticeable patterns in listening habits, such as specific time periods or days of the week when the user listens to music the most?

## Data Source
The data used for this analysis was obtained from the Spotify streaming history feature, which provides users with a downloadable dataset containing their listening history. The dataset is in JSON format and includes information such as track name, artist, album, and timestamp.

## Tools and Libraries Used
- Jupyter Notebook
- pandas
- plotly
- glob

## Project Structure
- `streaming-history-data`: contains your Spotify streaming history data files (e.g., `Streaming_History_Audio_2016_1.json`).
- `analysis.ipynb`: Jupyter notebook file that loads, processes and creates plots.

## How to Use
1. Clone this repository to your local machine.
2. Install the necessary dependencies listed above.
3. Download your `Extended streaming history` from spotify's [privacy page](https://www.spotify.com/us/account/privacy/)
    - this may take several days
    - your full streaming history will be in files with the format: `Streaming_History_Audio*.json`
4. Place your Spotify streaming history data files (`Streaming_History_Audio*.json`) in the `streaming-history-data` folder.
5. Open and run the Jupyter Notebook files in the `notebooks` folder in sequential order to preprocess the data and perform the analysis.
    - Cannot recommend VS Code and the respective Jupyter extension enough
6. The generated plots will be at the bottom of the Jupyter Notebook


## Contribution Welcome! (Dev Notes)
- If you create and new or better visualizations, please feel free to pull request them in!
- Clear all .ipynb outputs before commits

## Future Plans
- Deal with Timezone warnings
- Separate Songs by Artist
- aggregate deluxe albums
- assign singles to an album
- filter out listens under 30 sec
- most skipped artists? haha
- Create a GUI using Dash or similar

## Acknowledgments
- The Spotify streaming history feature for providing users with access to their listening data.
- The Pandas and Plotly libraries for enabling data analysis and visualization in Python.

