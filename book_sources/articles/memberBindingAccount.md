# 會員綁定遊戲帳號

## 會員綁定遊戲內使用帳號

1. 進入綁定遊戲帳號頁面
2. 選擇遊戲
3. 選擇綁定之帳號

## URL

  /member/game/binding/:memberID

## Method

  `GET`
  
## URL Params

   **Required:**

   `memberID=[integer]`

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
