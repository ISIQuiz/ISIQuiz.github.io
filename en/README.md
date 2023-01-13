## Introduction

ISIQuiz is a project that was developed with the intention of helping a student to review the key concepts of a university course, 
verifying the completeness of the knowledge acquired during the study.
The objective was achieved with the design of a fun-to-use application with multiple-choice questions and feedback.
The purpose of ISIQuiz is therefore to gamify the pre-exam review through a stimulating tool that enables students 
to feel more confident in their preparation, to collaborate by adding their questions, and to track their progress.

## User Guide

To play the app is required: Java >= 8

Tu run the app, double click it, or _right-click -> run with -> Java_

If it doesn't open try with the terminal in the same folder:
```bash
java -jar ISIQuiz.jar
```

### How to Play
Once the application is opened, an initial menu is displayed:

__Play__
Select at least one course to be able to start a game with quizzes regarding the indicated courses.
Next, choose the game mode:
- _standard game_: 10 quizzes, each to be answered in a maximum of 15 seconds; each quiz has 4 possible answers, only 1 answer is correct; you will discover the correctness of the answer given after each question
- _blitz match_: answer as many quizzes as possible in 2 minutes (120 seconds); each quiz has 4 possible answers, only 1 answer is correct; you will discover the correct of the answers given only at the end of the game
- _custom game_: choose the number of quizzes to answer and the maximum time (in seconds) you can answer each one; each quiz has 4 possible answers, only 1 answer is correct

At the end of a game there is a summary with:
- the total number of correct answers
- the total number of points earned
- for each quiz in the game:
   - course
   - answer given
   - correct answer, if yours is incorrect or missing

__Statistics__
View statistics about your reviews:
- regarding a selected course
- regarding a quiz selected from those of the indicated course
- global
 
For each type of statistic there are:
- acquired points
- answered quizzes
- correct answers
- precision (%)
- average time for answer (sec)

__Settings__
To be able to make changes in the general settings:
- Import quiz: Import a JSON file from the file system containing new couses and quizzes
- Export quiz: export the JSON file containing all the courses with the related quizzes
- Add course: create a new course
- Add quiz: add new quizzes to a certain course, so you can practice on more topics, or custom questions
- Edit course: change the info of a course
- Edit quiz: change the quiz of a course

__Exit__
To exit the application

## Team

The Team Members in the development of this project are:
- Daniele Gambaletta
- Igor Lirussi
- Riccardo Omiccioli
- Cecilia Teodorani

<div align="center">
    <img src="https://github.com/ISIQuiz/ISIQuiz-Report/raw/gh-pages/Extra/ISIQuizLogoLineTransparent.png" width="80%">
</div>
