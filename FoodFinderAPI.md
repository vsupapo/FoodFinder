## Overview

The FoodFinder API provides information about restaurants, including restaurant location, cuisine, price range and rating. Our API is organized around REST and returns JSON-formatted responses along with standard HTTP response codes. All requests are made to endpoints beginning:
`https://foodfinder.com`

All requests must use `https` to be secure. Do not use `http`.

### Authentication

No authentication is required to access resources for this API.

### Endpoints

| HTTP Method     | Endpoint                  |  Description                                    |
| -------------   |---------------------------|-------------------------------------------------|
| `GET`           | `/restaurants`            | Gets a list of all restaurants. |
| `GET`           | `/restaurants/{id}`       | Gets a specific restaurant by ID. |

### Response Codes
