# game-project-completed

This is a basic puzzle / treasure hunt game for assessing soft skills of a user.<br />
The theme of the puzle is colors.

**Technologies used:**
  1. Frontend: html, css, javascript, react js
  2. Backend: node js, mongodb
  
 **Soft skills assessed:**
  1. Perseverance
  2. Curiosity
  3. Eye for detail
  4. Problem Solving

**Method of evaluation of soft skills:**<br />
It is based on number of hints used<br />
  1. Perseverance & Curiosity: If an user completes all the tasks, then 100%.<br />
  2. Eye for detail & problem solving: <br />
        2.1 if number of hints used > 2, then 60% <br />
        2.2 if number of hints used == 1, then 80% <br />
        2.3 if number of hints used == 0, then 100% <br />

  
**Login page:**<br />
  This is the initial landing page for the website.<br />
  It provides features for login (for an existing user) and sign up (for a new user).<br />


After successful login, the puzzle contains two tasks to complete.<br />
Task 1: A round which has 3 questions to be answered<br />
If a user answers all the 3 questions, he/she can click a door below to find password for task 2.<br />

Task2: It is image round based on colors, if user answer these 2 question correctly then they have completed the game.<br />

After completion of the game, an user softskills report will be generated.<br />

The progess of each user will be stored in the database.<br />
The database contains score for each user, score = number of tasks completed * 50.<br />

**Deadends in game:**
  1. If an user try and fail task1 for 5 times in a row, the game ends.
  2. If an user uses 4 or more hints, the game ends.

**Solution:**
  The task is to answer all the  question and without begin caught in any deadends.
  
**Admin page:**
  The admin page contains list of all users and their corresponding score (score = number of tasks completed * 50).
  
  
  
  
  
 


 
 
 
