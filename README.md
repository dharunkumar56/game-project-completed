# game-project-completed

This is a basic puzzle / trasure hunt game for assessing soft skills of a user.
The theme of the puzle is colors.

Technologies used:
  Frontend: html, css, javascript, react js
  Backend: node js, mongodb
  
 Soft skills assessed:
  1. Perseverance
  2. Curiosity
  3. Eye for detail
  4. Problem Solving

Method of evaluation of soft skills:
It is based on number of hints used
  1. Perseverance & Curiosity: If an user completes all the tasks, then 100%.
  2. Eye for detail & problem solving: 
        if number of hints used > 2, then 60%
        if number of hints used == 1, then 80%
        if number of hints used == 0, then 100%

  
Login page:
  This is the initial landing page for the website.
  It provides features for login (for an existing user) and sign up (for a new user).


After successful login, the puzzle contains two tasks to complete.
Task 1: A round which has 3 questions to be answered
If a user answers all the 3 questions, he/she can click a door below to find password for task 2.

Task2: It is image round based on colors, if user answer these 2 question correctly then they have completed the game.

After completion of the game, an user softskills report will be generated.

The progess of each user will be stored in the database.
The databse contains score for each user, score = number of tasks completed * 50.

Deadends in game:
  1. If an user try and fail task1 for 5 times in a row, the game ends.
  2. If an user uses 4 or more hints, the game ends.

Solution:
  The task is to answer all the  question and without begin caught in any deadends.
  
Admin page:
  The admin page contains list of all users and their corresponding score (score = number of tasks completed * 50).
  
  
  
  
  
 


 
 
 
