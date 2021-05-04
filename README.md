## Homework: Web Application Part 4

### Author : Parthkumar Anilkumar Gandhi

### Brief:
Created REST API end points in flask, using MySql database.
Used Docker for building the application and as deployment tool.

#### REST API end-points
|Type| URL      | Description | 
|----| ----------- | ----------- |
|GET|'/api/v1/oscars'| JSON object returned for whole DB|
|GET|'/api/v1/oscars/<actor_id>'| JSON object returned, containing info about one entry in DB|
|POST|'/api/v1/oscars/add'| Receiving a json object and passing one|
|PUT| '/api/v1/oscars/edit<actor_id>'    | Updating the particular entry in DB       | 
|DELETE| '/api/v1/oscars/delete/<actor_id>'    | Deleting the particular entry fmor DB       | 

