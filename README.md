# Start Here
The goal of the project is to do some high level exploratory data analysis on my chess games. You can also clone this repository to analyze your own chess games or others' chess games.

1. The first script `chess_data_export_template.ipynb` extracts chess data from the Chess.com website using their API library. This provides the convenience of collecting several pgn files at once and being able to get useful metrics right up front that you would have to parse yourself. Since this script is a template, I highly recommend creating a copy and renaming it. I chose to name mine's `chess_data_export_private.ipynb` (not shown).
 
2. The second script `chess_analysis.ipynb` focuses on the data cleaning, transformation, and visualization.

Note: Using the chess.com API library is not necessary to analyze chess games. There are numerous ways one can go about extracting chess data. If you choose not to use an API library, the burden falls on you to download or scrape your pgn files and create your own parser (i.e. pgn to json are the most common parsers) to extract the appropriate information.