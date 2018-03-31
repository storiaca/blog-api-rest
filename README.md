# blog-api-rest

# start server

npm run start

Test your server with Postman, CURL or any other HTTP agent or tester. For example, the CRUD commands are


# posts post data
curl -H "Content-Type: application/json" -X POST -d '{"name": "Top 10 ES6 Features", "url":"http://webapplog.com/es6", "text": ""}'  "http://localhost:3000/posts" 

# updates post data at specific id
curl -H 'Content-Type: application/json' -X PUT -d '{"name": "Top 10 ES6 Features Every Developer Must Know", "url":"http://webapplog.com/es6", "text": ""}' "http://localhost:3000/posts/0"

# gets post data
curl "http://localhost:3000/posts" 

# deletes post data at specific id
curl -X DELETE "http://localhost:3000/posts/0" 
