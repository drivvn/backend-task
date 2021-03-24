# Backend Task

## Introduction

This is a simple task to create a suitable API back-end incorporating:

 * several routes and HTTP methods
 * validation of input URI segments, parameters and data
 * generating suitable responses and/or error messages
 * testing

The solution **must** be in a back-end lanaguage capable of running on a HTTP server. You can use whatever framework or dependencies you require - e.g. PHP/Symfony, Ruby/Rails, Python/Django, JavaScript/Next. You could even use no external dependencies - it's up to you. For data storage, you are also free to chose whatever you think is suitable - e.g. MongoDB, SQLite, MySQL PostgreSQL - or you could simply store the cars in a cache or session, or use mock data. The important aspect is the handling of requests and generating responses.

## Minimum Requirements

 * The API should allow the adding, deleting and listing of cars
 * The age of each car submitted can not be older than four years
 * There should be four initial colour options - red, blue, white and black
 * The API should respond with appropriate HTTP response codes and messages
 * The API should accept and return valid JSON
 * A suite of suitable tests should be created for these requirements

## Endpoints

```
POST /cars
GET /car/<id>
DELETE /cars/<id>
GET /cars
```

## Data Models

### Car

 * ID (integer)
 * Make (string)
 * Model (string)
 * Build Date (date)
 * Colour ID (integer)

### Colour

 * ID (integer)
 * Name (string)

## Optional Requirements

 * Endpoints to add, update, delete and list additional colours
 * A short description of how extra data models could improve the design
 * A short description on how best the API could be documented

## Submission

Here's what you'll need to send us:

 * A link to a **public** GitHub repo that you have created, containing the code
 * It should contain a suite of unit tests (using whichever test framework you prefer)
 * It should also contain a README.md file explaining how to run the app and its tests
 * You may also send us a link to a location hosting your code (for example, Heroku)

**The task should take around 2-3 hours.**
