# Belly Terminator!

Prototype for the BellyNator portal 
## Inspiration
We all love to eat awesome food! So why not track our intake and crush our health goals. Recent times have made my belly grow so I thought of managing my health goals and love for food better with BellyNator.

## What it does
To monitor daily calorie intake and achieve fitness goals I introduce you with the smartest health analyst BellyNator. With BellyNator a user can scan the nutrition value of food or can choose a meal from a predefined list. System will store the value and give recommendations to achieve the user's goal. If the calorie intake goes beyond the daily goal exercise recommendation would be shown to the user.

## How I built it
A number of frameworks where used:

* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework 
* [Postgres] - Database
* [React] - for frontend Purpose

And of course **GitHub**

API
- FoodData Central Api- for calorie Value.
- Clarifai- Detection of Image
- Elephant SQL - Postgres Database

## Challenges I ran into
I wanted to integrate the OCR to scan labels and display the calorie thereby enabling the users to decide better. But turns out I now get to submit my project in another category.(Half baked)

## Accomplishments that I'm proud of
To be able to submit a fullstack project.

## What's next for BellyNator
OCR and a mobile app.




### Features!
  - Signup and login to keep track of your health.
  - Enter Food item and Log Calorie.
  - Burn Extra Calorie with recommendations.
  - Reach your fitness goal by knowing the recommended Calorie.

### Installation
Install the dependencies and devDependencies and start the server.

```sh
    cd server
    npm run fullStackInstall
    npm run fullStack
```

### License
MIT
