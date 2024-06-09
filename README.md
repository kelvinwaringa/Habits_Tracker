# Cycling Habit Tracker

This Python script uses the Pixela API to track your cycling habit. Pixela is a service that helps you create and maintain a habit graph. This script allows you to create a user account, set up a cycling graph, and log your daily cycling distance in kilometers. The script can be modified to track different habits based on your needs.

## Features

- **User Creation**: Create a Pixela user account with your username and token.
- **Graph Creation**: Set up a graph to track your cycling habit.
- **Log Cycling Data**: Input the distance you cycled each day and log it to your Pixela graph.
- **Update Data**: Update the logged data for a specific day.
- **Delete Data**: Delete the logged data for a specific day.

## Requirements

- Python 3.x
- `requests` library

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/main.git
   cd main
2. Install the required library:
   ```
   pip install request

3. Modify the script with your Pixela USERNAME and TOKEN.

Run the script:

    python main.py
  
When prompted, enter the number of kilometers you cycled today. The script will log the data to your Pixela graph.
  
Notes
To enable the update and delete functionalities, uncomment the respective sections of the code.

This script can be modified to track other habits by changing the graph configuration and input prompts.
