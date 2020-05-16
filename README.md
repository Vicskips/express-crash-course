This is a small express app that i have built to learn the basics of express. 

## express api

`GET /api/members` gets me a list of all of my members

`GET /api/members/:id` returns a member matching the unique id

`POST /api/members` adds a member to the list of members
example body 

```json
{
    "name": "Dave Bobson",
    "email": "dave@dbobson.com",
}
```
`PUT /api/member/:id` allows members to update names and/or emails form the use of a unique ID

```json
{
    "name": "D Bobson",
    "email": "dave@dbobson.com"
}
```

`DELETE /api/members/:id` allows a member to be deleted by the use of thire unique ID


allows me to add members to local memory
express allows you to setup servers simply and quickly
I used handlebars to allow me to template my html to add dinamic data
I used bootstrap as a front end framework to help with building my user interface
used uuid to generate unique IDs for the added members
used nodemon in development to allow me to iterate changes to my server
used moment to track time and date when logging to the terminal