![CF](http://i.imgur.com/7v5ASc8.png) LAB   
=================================================  
  
## Lab 06 - Simple API   
  
### Author: Morgana Spake  
  
### Links and Resources  
* [submission PR](https://github.com/401-advanced-javascript-mspake/simple-api/pull/1)  
* [react-app](https://11fnt.codesandbox.io/)  
  
#### Documentation  
* [Swagger api docs](https://app.swaggerhub.com/apis-docs/MSpake/simple-api/0.1)  
  
### Setup  
#### `.env` requirements  
* `PORT` - 3000  
  
#### Running the app  
* `npm start` or `json-server --watch --id _id ./data/db.json`  
* Endpoint: `/categories`  
  * Returns a JSON object with all entries accessible via the categories route in it.  
* Endpoint: `/products`  
  * Returns a JSON object with all entries accessible via the categories route in it.  
  * Endpoint: `/categories/:id`  
  * Returns a JSON object with a singular entry from the categories route where the id matches the id included in the url.  
* Endpoint: `/products/:id`
  * Returns a JSON object with a singular entry from the products route where the id matches the id included in the url.  
  
#### UML  
![uml](https://github.com/401-advanced-javascript-mspake/simple-api/blob/master/assets/20190520_145029.jpg)  