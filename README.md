# ConnecTo Graph-Based-Social-Network-Analysis

ConnecTo is designed as a social media application using a directed graph to analyze the connections between different users through graph concepts and algorithms.
The Graphical User Interface (GUI) is built with the latest version of the Raylib library (v5.5).

Features
ConnecTo includes the following features:
1. Managing and updating user profiles.
2. Following and unfollowing various accounts.
3. Searching for accounts, viewing profiles, and following specific users.
4. Analyzing user connections using the Shortest Path in Ties of Connection.
5. Providing recommendations, such as:
   - Mutual friend recommendations.
   - Interest-based recommendations.
   - Top 3 most influential users.
   - Most frequent posts and trending users.
6. Viewing the user’s friend list under My Friends.
7. Logging out of the account.

For general lookup for the connection of users you can see the picture below which was created in python language for general lookup.

![social_network_graph](https://github.com/user-attachments/assets/793300ff-be44-4c2c-9207-21e42b38557f)

Installation
To set up the Raylib library, follow the installation video https://youtu.be/HPDLTQ4J_zQ?si=lt3rLL34TPG-l6AB. 
Ensure the library is correctly linked to your project for the GUI.

Project Structure
The project files are organized as follows:
1. include: Contains raylib.h for the GUI.
2. lib: Contains librarylib.a.
3. main.cpp: The main entry point of the application.
4. graph.cpp: Implementation of graph-related functionalities.
5. graph.h: Header file for graph functionalities.
6. run.bat: Script to execute the files.
7. users.txt: Contains user information, including IDs, usernames, passwords, interests, posts, comments, likes, and friend IDs.

How to Run
Use the terminal to navigate to the project folder.
Run the following command to create the main.exe file: .\run  
Execute the application using: .\main 
