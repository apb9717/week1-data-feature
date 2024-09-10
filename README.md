# week1-data-feature
A Colab library using two API keys to return information on your favorite NBA player's alma mater. 

# Overview:
This feature allows users to input the name of any NBA player and retrieve the following player statistics:
*   Team
*   Position
*   Draft Year
*   Draft Round
*   College

The program then provides basic information on the player's college at the time they were drafted, including acceptance rate, average SAT score, and enrollment.

# APIs Used
balldontlie:
This API is used to retrieve the player statistics. It was chosen for its comprehensive and up-to-date NBA data, covering various player details.

Dept. of Education College Scoreboard:
This API fetches data from a large dataset of college statistics for higher education institutions in the US.

# Setup Instructions

balldontlie API Key: Sign up on balldontlie and obtain your API key.

Dept. of Education API Key: Sign up on News API and obtain your API key.

Install Required Python Package: Make sure you have Python installed. Then, install the "requests" package.

# Usage
Run the following cells in order and, when prompted, enter the first and last name of any NBA player. Ensure the name is valid and spelled correctly.

# Prerequisites
Python 3.x
API keys for both balldontlie and Dept. of Education College Scorecard, added to **Secrets** in Google Colab.
