# Title

## FunctionDescription

1. FunctionFlow

## URL

  /users/:id

## Method

  `GET`
  
## URL Params

   **Required:**

   `id=[integer]`

## Data Params

  None

## Success Response

* **Code:** 200
 **Content:** `{ id : 12, name : "Michael Bloom" }`

## Error Response

* **Code:** 404 NOT FOUND
  **Content:** `{ error : "User doesn't exist" }`

OR

* **Code:** 401 UNAUTHORIZED
  **Content:** `{ error : "You are unauthorized to make this request." }`
