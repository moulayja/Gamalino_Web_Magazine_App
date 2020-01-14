# Gamalino Magazine
 Web platform app for authors to post their articles and receive comments from readers
 
 [![jamalino](https://img.shields.io/badge/Project%20Status-Completed-brightgreen?style=for-the-badge&logo=appveyor
)](https://github.com/moulayja/)

[![jamalino](https://img.shields.io/badge/Completion-100%25-blue)](https://github.com/moulayja/Gamalino_Web_Magazine_App/master/README.md)

## Table of Contents

- [App Preview](#app-preview)
- [Collaborators](#collaborators)
- [Project Description](#project-description)
- [Technologies](#technologies)
- [Getting Started](#getting-started)

#### Project Status: [Completed]
Final Version

## App Preview
[For a full demo, click here](https://youtu.be/3gdXWavc1AY)

## Collaborators
| Name | Github Page |
| --- | --- |
| Jamal Farah | [Profile Page](https://github.com/moulayja) |


## Project Description
#### Overview:

The idea is to create a magazine app with categories, the visiting user can leave comments without removing or editing.

The author has full access to remove written comments, he can also Create, Read, Update and Delete (CRUD).

You can also Sign Up as an author to start writing articles and post them.
#### Challenges:
 Using SQLite made a bit of issue, I have to rake instead of using rails, but I overcome that to create my final version successfully.


## Technologies
- Rails API for the Back-end
- SQLite as a backend Database-API
- RESTful architecture for CRUD actions
- Mixed of Bootstrap & CSS
- User authentication using Bcrypt

## Getting Started
1. Clone this repo
2. Cd to the project file
   ```bash
      $rake db:reset && rails s -p 3000
   ```
3. in your browser open

   ```bash
      http://localhost:3000/
   ```
4. Now you can Sign up to post articles

5. Keep posting and editing by Sign in

