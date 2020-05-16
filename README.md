# Express crash course
This is a small express app that I have built to learn the basics of express. 

## Express API

`GET /api/members` gets me a list of all the members

`GET /api/members/:id` returns a member matching the unique id

`POST /api/members` adds a member to the list of members
example body 

```json
{
    "name": "Dave Bobson",
    "email": "dave@dbobson.com",
}
```
`PUT /api/member/:id` allows members to update names and/or emails form the use of a unique ID example body

```json
{
    "name": "D Bobson",
    "email": "dave@dbobson.com"
}
```

`DELETE /api/members/:id` allows a member to be deleted using their unique ID


## Dependencies



Allows me to add members to local memory

#### Express
Express allows you to setup servers simply and quickly

#### Handlebars
Handlebars allows me to template my html to add dynamic data

#### Bootstrap
Bootstrap was used as a front-end framework to help with building my user interface

#### Uuid
Uuid allows me to generate unique IDs for the added members

#### Nodemon
Nodemon was used in development to allow me to iterate changes to my server

#### Moment
Moment allows me to track time and date when logging to the terminal
