# mutual-friend-recommendation
Python implementation of a mutual friend recommendation algorithm simulating the “People You May Know” feature in social networks.

Overview
This project implements the "People You May Know" feature used in social networks.
It recommends potential friends to a user based on the number of mutual friends they share.
The system analyzes a social network dataset and suggests new connections using a mutual friend algorithm.

Project Workflow
1. JSON Data Handling
The dataset is stored in JSON format containing users and their friend connections.
The notebook demonstrates how to:
Load JSON data in Python
Convert it into dictionaries
Access and manipulate user connection data
2. Data Processing
User connections are structured into Python data structures to represent a social network graph.
3. Mutual Friend Recommendation
The algorithm:
Finds friends of friends
Counts the number of mutual friends
Recommends users with the highest number of shared connections

Technologies Used
Python
JSON data handling
Basic graph-based logic
Jupyter Notebook


Project Logic
Load the social network dataset from a JSON file.
Store each user's friends in a dictionary.
Identify friends of friends for a given user.
Count the number of mutual friends between users.
Recommend users with the highest mutual friend count.

How to Run
Clone the repository
Open the notebook
