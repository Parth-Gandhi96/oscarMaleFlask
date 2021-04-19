## Homework: Web Application Part 3

### Author : Parthkumar Anilkumar Gandhi

### Brief:
Created CRUD application in flask, using MySql database.
Used Docker for building the application and as deployment tool.

### CheckList:
- [x] Created HTML pages for Add, Delete, View and Update
- [x] HTTP routes added in application, with their implementation
- [x] Doc with all screenshots
    

#### GET HTTP request routes:    
| URL      | Description | 
| ----------- | ----------- | 
| '/'      | Home page, tabular view of whole DB       | 
| '/view/<actor_id>'   | view one particular entry in DB    |
|'/edit/<actor_id>'| Renderring the HTML page for the form of Editing entry in DB|
|'/oscar/new'| (renders the HTML form) Creating new entry for inserting in DB|
|'/api/v1/oscars'| JSON object returned for whole DB|
|'/api/v1/oscars/<actor_id>'| JSON object returned, containing info about one entry in DB|

#### POST HTTP request routes: (Insert/Update)
| URL      | Description | 
| ----------- | ----------- |
|'/edit/<actor_id>'|Updating the entry in DB |
|'/oscar/new'| Inserting new entry in DB|
|'/delete/<actor_id>'| Deleting the entry in DB|
|'/api/v1/oscars/'| Receiving a json object and passing one|

#### PUT HTTP request route (Update):
| URL      | Description | 
| ----------- | ----------- | 
| '/api/v1/oscars/<actor_id>'    | Updating the particular entry in DB       | 

#### DELETE HTTP request route:
| URL      | Description | 
| ----------- | ----------- | 
| '/api/oscars/<actor_id>'    | Deleting the particular entry fmor DB       | 

