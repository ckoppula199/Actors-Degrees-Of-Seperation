# Actors-Degrees-Of-Seperation
Demo: https://www.youtube.com/watch?v=GSjCd55yXAY  
  

This program will give the degrees of seperation between any two actors. Completed as part of Harvards CS50 Intro to AI Course.  

For Example:  

Given the names Chris Pratt and Tom Cruise, the program would return the following:  
2 degrees of separation.  
1: Chris Pratt and Cobie Smulders starred in Delivery Man  
2: Cobie Smulders and Tom Cruise starred in Jack Reacher: Never Go Back  
  
The program uses a breadth first search algorithm to find the shortest path between 2 actors, treating the actors as nodes and movies as edges.  

Note: I was responsible for writing the shortest_path and backtrack methods in degrees.py. The rest of the code is provided by Harvard CS50 and is not my own work.

To run the script simply execute python degrees.py in the command line.  
