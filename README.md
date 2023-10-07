# Desafio 01 Node - Rocketseat

## Dependencies used
* [nodejs](https://nodejs.org/en) version 18.17.1
* [csv-parse](https://www.npmjs.com/package/csv-parse) version 5.5.1

## How to run?
First run `npm install` and run the project with `npm run dev`
* You can import Tasks in mass via csv using `npm run mass` with the server running

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
* To delete an Task `DELETE => /tasks/:id`
