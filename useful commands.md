## Sample cURL commands
- curl -i https://jsonplaceholder.typicode.com/todos/1
- curl -i -X GET https://jsonplaceholder.typicode.com/todos/1
- cURL -X POST -d "name=cURL&type=article" https://jsonplaceholder.typicode.com/posts
- cURL -X PUT -d '{"name": "json", "type": "post"}' -H "Content-Type: application/json" https://jsonplaceholder.typicode.com/posts/1
### Downloading Images and Files to a Device
- cURL https://www.google.com/images/branding/googlelogo/2x/googlelogo_light_color_272x92dp.png > google-logo.png
### Save content
- cURL -o google.html https://www.google.com

