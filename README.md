# ConnecTo Graph-Based-Social-Network-Analysis

ConnecTo is designed as a social media application using a directed graph to analyze the connections between different users through graph concepts and algorithms.
The Graphical User Interface (GUI) is built with the latest version of the Raylib library (v5.5).

Features
ConnecTo includes the following features:

Managing and updating user profiles.
Following and unfollowing various accounts.
Searching for accounts, viewing profiles, and following specific users.
Analyzing user connections using the Shortest Path in Ties of Connection.
Providing recommendations, such as:
Mutual friend recommendations.
Interest-based recommendations.
Top 3 most influential users.
Most frequent posts and trending users.
Viewing the user’s friend list under My Friends.
Logging out of the account.

For general lookup for the connection of users you can see the picture below which was created in python language for general lookup.
![social_network_graph](https://github.com/user-attachments/assets/793300ff-be44-4c2c-9207-21e42b38557f)

Installation
To set up the Raylib library, follow the installation video. Ensure the library is correctly linked to your project for the GUI.

Project Structure
The project files are organized as follows:

include: Contains raylib.h for the GUI.
lib: Contains librarylib.a.
main.cpp: The main entry point of the application.
graph.cpp: Implementation of graph-related functionalities.
graph.h: Header file for graph functionalities.
run.bat: Script to execute the files.
users.txt: Contains user information, including IDs, usernames, passwords, interests, posts, comments, likes, and friend IDs.

How to Run
Use the terminal to navigate to the project folder.
Run the following command to create the main.exe file:
arduino
Copy code
.\run  
Execute the application using:
css
Copy code
.\main 
