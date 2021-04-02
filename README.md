# Workout-Tracker





## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [License](#license)
* [Contributors](#contributors)
* [Questions](#questions)

## Description
An application that helps you track your daily workouts. 

## Installation Instructions
Clone or download the repository, and install node.js, npm install with dependencies.

## Usage
 The application is invoked by using the following
"node server.js" command.
Run app on node server.js, and deploy to localhost:3000 or deploy with Heroku link below. 


![Budget App](https://user-images.githubusercontent.com/65749636/111860866-91deb480-8907-11eb-8fd9-e81daf2a8468.PNG)


## Technologies Used

* Express
* Mongoose
* Mongodb
* Compression
* Morgan
* Lite-Server
* Node.js

## License
ISC

<img src="https://img.shields.io/badge/LICENSE-isc-green"/>


## Contributors
Eva Wang

## Questions
Contact me:
Email: [elphinhote@yahoo.com](elphinhote@yahoo.com)

Github: https://github.com/elphinhote/Budget-TrackApp/

Deployed App: https://budtracking.herokuapp.com/


# Workout-Tracker
# Unit 17 NoSQL Homework: Workout Tracker

For this assignment, you'll create a workout tracker. You have already been provided with the front end code in the `Develop` folder. This assignment will require you to create Mongo database with a Mongoose schema and handle routes with Express.

## User Story

* As a user, I want to be able to view create and track daily workouts. I want to be able to log multiple exercises in a workout on a given day. I should also be able to track the name, type, weight, sets, reps, and duration of exercise. If the exercise is a cardio exercise, I should be able to track my distance traveled.

## Business Context

A consumer will reach their fitness goals more quickly when they track their workout progress.

## Acceptance Criteria

When the user loads the page, they should be given the option to create a new workout or continue with their last workout.

The user should be able to:

  * Add exercises to the most recent workout plan.

  * Add new exercises to a new workout plan.

  * View the combined weight of multiple exercises from the past seven workouts on the `stats` page.

  * View the total duration of each workout from the past seven workouts on the `stats` page.

> **Important:** Look into using a MongoDB aggregate function to dynamically add up and return the total duration for each workout. Check out the [MongoDB documentation on the $addFields](https://docs.mongodb.com/manual/reference/operator/aggregation/addFields/), the [MongoDB documentation on the $sum operator](https://docs.mongodb.com/manual/reference/operator/aggregation/sum/), and the [Mongoose documentation on aggregate functions](https://mongoosejs.com/docs/api.html#aggregate_Aggregate) to learn how it can be accomplished.

To deploy an application with a MongoDB database to Heroku, you'll need to set up a MongoDB Atlas account and connect a database from there to your application. Be sure to use the following guides for support:

  * [Set Up MongoDB Atlas](../04-Important/MongoAtlas-Setup.md)

  * [Deploy with Heroku and MongoDB Atlas](../04-Important/MongoAtlas-Deploy.md)



# Table of Contents
1. [User Story](#User-Story)
2. [Usage](#Usage)
3. [Installation](#Installation)
4. [Contributors](#Contributors)
5. [Links](#Links)


## User Story

As a user, I want to be able to view, create and track daily workouts. I want to be able to log multiple exercises in a workout on a given day. I should also be able to track the name, type, weight, sets, reps, and duration of exercise. If the exercise is a cardio exercise, I should be able to track my distance traveled.


## Usage

This app uses a Mongo database, Mongoose shcema and Express. 

## Installation

Open up the root directory in your terminal. "Npm i" to install packages. 

## Contributors
* Aldo Vibanco - https://github.com/alvivanco85

## Links
* Github Repo - https://github.com/alvivanco85/Workout_Tracker
* Heroku app - https://hidden-sands-45687.herokuapp.com/
