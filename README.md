# Tic Tac Toe Game Kata

This short and simple Kata should be performed using Test Driven Development (TDD).
It is implementation of a simple Tic Tac Toe game.
 ## Rules
  The rules are described below :
  1) X always goes first.
  2) Players cannot play on a played position.
  3) Players alternate placing X’s and O’s on the board until either.
  4) One player has three in a row, horizontally, vertically or diagonally
  5) All nine squares are filled.
  6) If a player is able to draw three X’s or three O’s in a row, that player wins.
  7) If all nine squares are filled and neither player has three in a row, the game is a draw.
  
  ## Getting Started
    In order to run and deploy this application user needs follow below steps-
  
    1) Clone git repostitory in some local folder using below command run on cmder of bash git command prompt.
         git pull https://github.com/2020-DEV-046/TicTacToeKata.git
    2) Open STS and import project as exiting maven project in STS, Setting up STS steps given in installation section.
    3) Right click imported project and go to maven -> update project.
    4) Right click again imported project and go to Run as -> maven clean to clean project.
    5) Right click again imported project and go to Run as -> maven install to install project to compile source code and generate jar
        file in target folder.
    6) Copy TicTacToeKata-1.0-RELEASE.jar file generated in target folder to some local folder.
    7) Start dos command prompt and reach to copied jar folder location and run below java 
        command - Java -jar TicTacToeKata-1.0-RELEASE.jar
    8) One dialog will open in command prompt to enter player names of both players and scores. Once user enters the asked details,
        system calculate match outcome based on the points entered for each player.
