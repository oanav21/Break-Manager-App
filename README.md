# Break-Manager-App

Life can feel overwhelming. But it doesn’t have to.

A Simple To-do app design in flutter to keep track of your task on daily basis. You can add project, labels and due-date to your tasks

## Features

- Build on [**BLoC**](#bloc-diagram) Architecture Pattern
- Add [**Labels**](#labels) by specifying a unique color to it
- Add [**Task**](#task) by defining its priority
- [**Tap**](#tap-the-task) to delete or complete the task
- Works offline using [**Sqflite**](https://github.com/tekartik/sqflite "Flutter Database") database

## BLoC Diagram
This diagram show case the dependencies to create a feature specific BLoCs.The HomeBloc is independent and used as communication channel between its child widgets.
![](https://i.imgur.com/iCdcCUh.png)

