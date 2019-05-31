# Break-Manager-App

Life can feel overwhelming. But it doesn’t have to.

A Simple To-do app design in flutter to keep track of your task on daily basis. You can add project, labels and due-date to your tasks

## Features

- Build on [**BLoC**](#bloc-diagram) Architecture Pattern
- Add different [**Task blocks**](#blocks) by specifying a unique color to them
- Add [**Task**](#task) in the desired block
- [**Tap**](#tap-the-task) to delete or complete the task
- Works offline using [**Sqflite**](https://github.com/tekartik/sqflite "Flutter Database") database

## BLoC Diagram
This diagram show case the dependencies to create a feature specific BLoCs.The HomeBloc is independent and used as communication channel between its child widgets.
![](https://i.imgur.com/iCdcCUh.png)
* Diagram was made for the final app, not this intermediary task manager app *

## User Stories

### Developer
- :black_square_button: As a developer, I want to create an app which facilitates the coordination of breaks through an entire
company.
- :white_check_mark: As a developer, I want to create an easy to use, accessible app.
- :white_check_mark: As a developer, I want to create a friendly design for the app.

### Admin
- :black_square_button: As an admin, I want to be able to create groups for each task.
- :black_square_button: As an admin, I want to be able to allow or not other users to take breaks.
- :black_square_button: As an admin, I want to be able to make changes in users' calendars.

### User
- :black_square_button: As a user, I want to be able to log in with my E-mail address and password.
- :black_square_button: As a user, I want to be able to see my calendar.
- :white_check_mark: As a user, I want to be able to see what tasks I have everyday.
- :black_square_button: As a user, I want to be able to personalize my calendar.
- :white_check_mark: As a user, I want to be able to add tasks.
- :white_check_mark: As a user, I want to be able to delete tasks.
- :white_check_mark: As a user, I want to be able to change tasks.
- :white_check_mark: As a user, I want to be able to modify my personal tasks.
- :white_check_mark: As a user, I want to be able to verify what tasks I have to achieve.
- :white_check_mark: As a user, I want to be able to create groups for each task.

### Guest
- :black_square_button: As a guest, I want to be able to create a profile and edit it later.
- :black_square_button: As a guest, I want to be able to create an admin profile( in a special case).


## Inspiration
[TO DO Concept](https://dribbble.com/shots/3812962-iPhone-X-Todo-Concept)
