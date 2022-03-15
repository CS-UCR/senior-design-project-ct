[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=5806163&assignment_repo_type=AssignmentRepo)
# CS178A-B-Template

## Table of Contents
- [Overview](#overview)
- [Team](#team)
- [Contribution](#contribution)
- [Usage](#usage)
- [How To Run](#how-to-run)
- [Diagrams](#diagrams)
- [Reference](#reference)

## Overview
Clean Trash is a mobile application that allows users to search for an item to determine if it’s recyclable or not in their county.

Our goal is to reduce current recycling contamination which has a current rate of 25%, reduce pollution, and conserve energy.

## Team
- <a href="https://github.com/msalloum" target="_blank">Mariam Salloum </a>
- <a href="https://github.com/estela-ramirez" target="_blank">Estela Ramirez Ramirez </a>
- <a href="https://github.com/Jess-say" target="_blank">Jessie Lu </a>
- <a href="https://github.com/mandy840907" target="_blank">Tzu-Ying Chuang </a>
- <a href="https://github.com/briortega" target="_blank">Briana Ortega Vazquez </a>

## Contribution

Estela Ramirez Ramirez
- Machine learning models
- New UI
- Try connecting model
- Search Bar
- Script for county 
- Camera feature

Jessie Lu
- Old UI
- New UI
- Try connecting model
- Badge system
- Login and Create Account
- Firebase
- Cloud Firestore

Tzu-Ying Chuang
- Machine learning models
- New UI
- Try connecting model
- Bottom Navigation Bar
- Badge system
- Geolocator
- Setting/Permissions
- Cloud Firestore

Briana Ortega Vazquez
- Old UI
- New UI
- Try connecting model
- Bottom modal sheet
- Full Pages for items
- unit tests
- Cloud Firestore


## Usage

Screenshots of the app

| Login Page | Home Page | Search Bar | Classified Page
| --- | --- |  --- | --- |
| <img src="/images/LoginPage.png" alt="LoginPage" width="200"/>  | <img src="/images/HomePage.png" alt="HomePage" width="200"/>  | <img src="/images/SearchBar.png" alt="SearchBar" width="200"/> | <img src="/images/ClassifiedPage.png" alt="ClassifiedPage" width="200"/> |

| Random Facts | Badge Page | Setting Page |
| --- | --- |  --- |
| <img src="/images/RandomFacts.png" alt="RandomFacts" width="200"/>  | <img src="/images/BadgePage.png" alt="BadgePage" width="200"/>  | <img src="/images/SettingPage.png" alt="SettingPage" width="200"/> |


## How To Run

In order to be able to run our project you need to have Flutter. You can install and setup Flutter by following the steps in the link provided. [Install Flutter](https://docs.flutter.dev/get-started/install?gclid=Cj0KCQjwz7uRBhDRARIsAFqjullXwoQHzcbq8z3lmeC0BInB0g2G4ZGgbBVbAfTk_g0pU5qNsZNmROYaAtzEEALw_wcB&gclsrc=aw.ds).

Once you have Flutter installed you want to clone our repository.
  
    git clone https://github.com/CS-UCR/senior-design-project-ct.git
  
  
After installing Flutter, remember to setup an Android emulator and then direct your terminal into clean_trash_app
  
    cd clean_trash_app
  
You should now be in the clean_trash_app folder. After opening your emulator, run each of these commands in order
 
    flutter pub get
    flutter run

 Now you can see the app shows up on your simulator

## Diagrams

Overall System Diagram
  
![systemDiagram](/diagrams/newSystemDiagram.png)
  
UML for Badge System
  
![UML_For_badge](/diagrams/UML_For_badges.png) 
  
## Reference  
### Datasets
- [Waste Classification](https://www.kaggle.com/szdxfkmgnb/waste-classification)
- [Garbage Classification](https://www.kaggle.com/asdasdasasdas/garbage-classification)
- [Garbage Classification (12 Classes)](https://www.kaggle.com/mostafaabla/garbage-classification)

