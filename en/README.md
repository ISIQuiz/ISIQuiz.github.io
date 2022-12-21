## Introduction

ISIQuiz is a project that was born with the intention of developing a tool that allows a student 
to review the key concepts of a university course and verify the knowledge acquired during the study.
The objective was achieved with the design of an application with multiple choice questions on the most important topics.
The purpose of ISIQuiz is therefore to gamify the pre-exam review through a stimulating tool that enables students to track their progress.

## User Guide

To play the app is required: Java >= 11

Tu run the app, double click it, or run in the terminal:
```bash
java -jar ISIQuiz.jar
```

### How to Play
Once the application is opened, an initial menu is displayed:

__Play__
Select at least one course to be able to start a game with quizzes regarding the indicated courses.
Next, choose the game mode:
- standard game: 10 quizzes, each to be answered in a maximum of 15 seconds; each quiz has 4 possible answers, only 1 answer is correct; you will discover the correctness of the answer given after each question
- blitz match: answer as many quizzes as possible in 2 minutes (120 seconds); each quiz has 4 possible answers, only 1 answer is correct; you will discover the correct of the answers given only at the end of the game
- custom game: choose the number of quizzes to answer and the maximum time (in seconds) you can answer each one; each quiz has 4 possible answers, only 1 answer is correct

At the end of a game there is a summary with:
- the total number of questions answered correctly
- the total number of points earned
- for each quiz in the game:
   - course 
   - answer given
   - correct answer, if yours is incorrect

__Statistics__
View statistics about your reviews:
- regarding a selected course
- regarding a quiz selected from those of the indicated course
- global
 
For each type of statistic there are:
- acquired points
- answered quizzes
- correct answers
- accuracy (%)
- average response time (sec)

__Settings__
To be able to make changes in the general settings:
- Import Quizzes: Import a JSON file from the file system containing new quizzes
- Export quiz: export the JSON file containing the courses with the related quizzes
- Edit quizzes
- Add course: enter a new course
- Add quizzes: add new quizzes to a certain course, so you can practice on more topics

__Exit__
To exit the application

## Team

The Team Mebers in the development of this project are:
- Daniele Gambaletta
- Igor Lirussi
- Riccardo Omiccioli
- Cecilia Teodorani

<div align="center">
    <img src="https://github.com/ISIQuiz/ISIQuiz-Report/raw/gh-pages/Extra/ISIQuizLogoLineTransparent.png" width="80%">
</div>
