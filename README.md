# 01 Fundamentos Node

## Dependencies used
* This project use Native Libraries from [nodejs](https://nodejs.org/en) version 18.17.1

## How to run?
Run with `npm run dev`

## API Routes
* To list users: `GET => /users`
* To list an specific user `GET => /users?search=John`
* To create an user `POST => /users` {Content-Type: application/json} {"name":"John Doe","email":"johndoe@dev.com"}
* To update an user `PUT => /users/:id` {Content-Type: application/json} {"name":"John Doe Changed","email":"johndoe@dev.com"}
* To delete an user `DELETE => /users/:id`