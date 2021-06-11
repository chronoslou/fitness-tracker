# Fitness-tracker

## Link:

### Repo:

https://github.com/chronoslou/fitness-tracker

### Deploy:

https://mysterious-headland-85365.herokuapp.com/

## Description

This is a fitness tracker with a Mongo database with a Mongoose schema and handle routes with Express.

## User Story

The goal of this app is to view, create and track daily workouts to reach fitness goals.

- EU should be able to log multiple exercises in a workout on a given day.
- When the user loads the page, the EU should be given the option to create a new workout or continue with their last workout.
- The user should be able to add exercises to the most recent workout plan.
- The user should be able to add new exercises to a new workout plan.
- Should also be able to track the name, type, weight, sets, reps, and duration of exercise.
- If the exercise is a cardio exercise, the EU should be able to track the distance traveled.
- The user should be able to view the combined weight of multiple exercises from the past seven workouts on the `stats` page.
- The user should be able to view the total duration of each workout from the past seven workouts on the `stats` page.

## Installation

## Preview of App

![Screenshot](screenshot.png)

# Lincense

- MIT

Look into using a MongoDB aggregate function to dynamically add up and return the total duration for each workout. Check out the [MongoDB documentation on the $addFields](https://docs.mongodb.com/manual/reference/operator/aggregation/addFields/)
the [MongoDB documentation on the $sum operator](https://docs.mongodb.com/manual/reference/operator/aggregation/sum/)
the [Mongoose documentation on aggregate functions](https://mongoosejs.com/docs/api.html#aggregate_Aggregate)

To deploy an application with a MongoDB database to Heroku, you'll need to set up a MongoDB Atlas account and connect a database from there to your application. Be sure to use the following guides for support:

- [Set Up MongoDB Atlas](../04-Important/MongoAtlas-Setup.md)
- [Deploy with Heroku and MongoDB Atlas](../04-Important/MongoAtlas-Deploy.md)
