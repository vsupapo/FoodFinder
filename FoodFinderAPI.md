## Overview

The FoodFinder API provides information about restaurants, including restaurant location, cuisine, price range and rating. Our API is organized around REST and returns JSON-formatted responses along with standard HTTP response codes. All requests are made to endpoints beginning:
`https://foodfinder.com`

All requests must use `https` to be secure. Do not use `http`.

### Authentication

No authentication is required to access resources for this API.

### Endpoints

| HTTP Method     | Endpoint                                               |  Description                                    |
| -------------   |--------------------------------------------------------|-------------------------------------------------|
| `GET`           | `/restaurants`                                         | Gets a list of all restaurants. |
| `GET`           | `/restaurants/{id}`                                    | Gets a specific restaurant by ID. |
| `GET`           | `/restaurants?restaurant_name={restaurant_name}`       | Gets a list of all restaurants with a specific name. |
| `GET`           | `/restaurants?city={city}`                             | Gets a list of all restaurants in a specific city. |
| `GET`           | `/restaurants?cuisine={cuisine}`                       | Gets a list of all restaurants that serve a specific cuisine. |
| `GET`           | `/restaurants?price={price}`                           | Gets a list of all restaurants in a specific price range. |
| `GET`           | `/restaurants?rating={rating}`                         | Gets a list of all restaurants with a specific rating. |
| `POST`          | `/restaurants`                                         | Creates a new restaurant. |
| `PUT`           | `/restaurants/{id}`                                    | Updates an existing restaurant by ID. |
| `DELETE`        | `/restaurants/{id}`                                    | Deletes a specific restaurant by ID. |

### Response Codes

| Code                      | Description                                                                               |
| ------------------------- |---------------------------------------------------------------------------------------------------------|
| 200 OK	                  | The request succeeded. |
| 400 Bad Request	          | The request was not processed by the server due to client error. |
| 402 Request Failed	      | The parameters were valid but the request failed. |
| 404 Not Found	            | The requested resource cannot be found. |
| 410 Gone                  |	The requested resource is no longer available. |
| 500 Internal Server Error	| The server encountered an unexpected error while fulfilling the request. |


