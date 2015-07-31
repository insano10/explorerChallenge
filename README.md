explorerChallenge
=================

explorerChallenge is a maze traversal coding challenge suitable for running as a competitive dojo session.
The participant must implement an API to direct an explorer around a maze to find the exit.

![](https://raw.githubusercontent.com/insano10/explorerChallenge/master/docs/front_end.png)

The project consists of:

* A web front end accessible at localhost:8080 to drive the algorithm and show the maze traversal

* A maze API to provide maze definitions (the participant should not change this)

* An explorer API to provide directions through the maze. A dummy implementation has been provided but this is what the participant needs to implement.

A handout to run the dojo is available [here](https://docs.google.com/document/d/1O1aMwZY5A6b2a5FSSaTswy0nfM3wbmZtr630Cbo-1F4/edit?usp=sharing "explorerChallenge handout").
This contains information on how to setup and run the project.

There are 2 branches of interest to the project:

* **master** - this is the branch participants should develop against
* **judge** - this branch contains extra mazes the participants algorithms should be tested against. It also adds an additional control to the web front end to allow the user 
              to connect to explorer APIs on remote hosts. This allows for testing participants algorithms without giving them access to the test mazes
               
         

