# Snippets

Small pieces of code to help you with this assignment

##### starter code

```javascript
import express from "express";
const app = express();

app.listen(3001, () => {
  console.log("The server is listening... 🐒");
});
```

##### HTTP GET request

```javascript
// replace "/" with your own path
app.get("/path", (request, response) => {});
```

##### GET request with parameters

```javascript
// replace "/path" with your own path
// replace ":param1" with your own param
// add as many params as you need
app.get("/path/:param1", (request, response) => {
  const params = request.params;
});
```
