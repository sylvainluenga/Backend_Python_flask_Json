Backend Task

Resources
If you are not familiar with how to set up a basic API, we recommend the following
resources:
● Python - Flask (Flask JSON API)
● Javascript - Node + Express
● Java - Spring Boot (JSON API)
● Ruby - Rails JSON API

Data Source
You will be building an API that requires you to fetch data from this API:
Request:
Route: https://api.hatchways.io/assessment/blog/posts
Method: GET
Query Parameters:
Field Type Description
tag String (required) The tag associated with
the blog post.
Notice that the parameter is a query parameter - you can read more about query
parameters here. An example of sending the tag parameter is
https://api.hatchways.io/assessment/blog/posts?tag=tech.
