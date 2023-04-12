# API-Rest
Fake Rest API, provided by JSON Server.

To perform a local installation globally, use the command:
npm install -g json-server

To run the server, use the command:
json-server -w -p 5555 assets/db.json
which executes the db.json file which is the file that works as the dummy database.

The db.json file is located in the assets folder. The data included refers to the Knights of the Zodiac series. In the Json server documentation the only requirement for the base is that they contain an ID attribute.

A CRUD is generated in 3 different ways:
* Through AJAX (HttpRequest).
* Using Fetch + asynchronous functions.
* Using AXIOS + asynchronous functions.
