Built following the tutorial found here - https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api

Creates the following APIs:

API	Description	Request body	Response body
GET /api/todo	Get all to-do items	None	Array of to-do items
GET /api/todo/{id}	Get an item by ID	None	To-do item
POST /api/todo	Add a new item	To-do item	To-do item
PUT /api/todo/{id}	Update an existing item  	To-do item	None
DELETE /api/todo/{id}    	Delete an item    	None	None