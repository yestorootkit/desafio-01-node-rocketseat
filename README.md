# Desafio 01 Node - Rocketseat

## Dependencies used
* This project use Native Libraries from [nodejs](https://nodejs.org/en) version 18.17.1

## How to run?
Run with `npm run dev`

## API Routes
* To list tasks: `GET => /tasks`
* To list task by query `GET => /tasks?search=Teste`
* To create an task `POST => /tasks` 
```
{Content-Type: application/json}

{"title":"Task 01","description":"First Task"}
```
* To change Title or Description of Task `PUT => /tasks/:id`
```
{Content-Type: application/json}

{"title":"Title changed","description":"Description changed"}
```
* To complete an Task `PATCH => /tasks/:id/complete`
