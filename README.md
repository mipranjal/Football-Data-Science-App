# Football-Data-Science-App
NFL Football Stats (Rushing) Explorer
This app performs simple web scraping of NFL Football player stats data (focusing on Rushing).


##Installation
To run the app, first install the required libraries by running:
code: pip install streamlit pandas base64 matplotlib seaborn numpy


## Usage

To start the app, run:
code: streamlit run app.py

This will open a Streamlit app in your default web browser, where you can select a year, team, and position to view player stats for NFL Football.


## App overview
This app is built using Python and Streamlit, and uses web scraping to extract NFL Football player stats data from pro-football-reference.com.

The user can select a year, team, and position to filter the data, and the app displays the selected player stats in a table format. The user can also download the data as a CSV file.

In addition, the app provides an intercorrelation matrix heatmap, which shows the correlation between different player stats.


## Libraries used
streamlit: For building the app and creating a user interface.
pandas: For data manipulation and analysis.
base64: For encoding and decoding data in Base64 format.
matplotlib: For creating visualizations.
seaborn: For creating visualizations.
numpy: For numerical computing.



