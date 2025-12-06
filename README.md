# 📦 fetchdata – Free JSON API

This repo contains dummy JSON data hosted online using **My JSON Server**, useful for practicing Fetch API and frontend development.

## 🔗 Live API
https://my-json-server.typicode.com/imran-codes-design/fetchdata

## 📁 Endpoints
- /tasks  
- /students  
- /users  
- /products  

Example:  
https://my-json-server.typicode.com/imran-codes-design/fetchdata/tasks

## 🚀 How to Fetch
```js
fetch("https://my-json-server.typicode.com/imran-codes-design/fetchdata/tasks")
  .then(r => r.json())
  .then(data => console.log(data));
