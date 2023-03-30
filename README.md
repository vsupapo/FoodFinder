# FoodFinder

![image](https://user-images.githubusercontent.com/47260573/124221499-bf193200-dab4-11eb-8992-db22ba3178f8.png)

## Description
FoodFinder simplifies your dining experience by finding the best restaurants catered to your preferences. This RESTful web application developed by Team Druids provides access to restaurant data in the form of JSON responses through the FoodFinder API.

## Requirements
To run the FoodFinder application, you will need to install Node.js using `Node v14.0.0`+.

## Installation
1. Clone the repository
2. CD into the project directory
3. CD into the server directory
 * Run `npm install` to install project dependencies
 * Run `npm run devStart`  to run the dev environment on `port 4000`
4. CD into the client directory
 * Run `npm install`
 * Run `npm start` to start the react environment on `port 3000`

The client and server must be running concurrently to run the application.

## Application Features
FoodFinder lets you:
- Create a personal account
- Browse restaurants
- Search for restaurants
- Find and add friends
- Set your personal restaurant preferences
- View your friends' restaurant preferences

FoodFinder lets you save your personal preferences for restaurants including:
| Field             | Description                                     |
| ------------------|-------------------------------------------------|
| `cuisine`	        | The type of cuisine served by the restaurant. |
| `price`	          | The price range of the restaurant as a number from 1 to 4. |
| `rating`	        | The average rating of the restaurant as a number from 1 to 5. |

FoodFinder restaurant results include details such as:
| Field             | Description                                     |
| ------------------|-------------------------------------------------|
| `restaurant_name`	| The name of the restaurant. |
| `street`          | The city where the restaurant is located. |
| `city`	          | The state where the restaurant is located. |
| `state`           | The state where the restaurant is located. |
| `cuisine`	        | The type of cuisine served by the restaurant. |
| `price`	          | The price range of the restaurant as a number from 1 to 4. |
| `rating`	        | The average rating of the restaurant as a number from 1 to 5. |

## API Documentation
The FoodFinder API can be found [here](https://github.com/vsupapo/FoodFinderAPI/blob/main/README.md).

## Credits
*A special thanks to Team Druids*
