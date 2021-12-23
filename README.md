# Cue-sandbox Project

## 1. Create a repo & codespace

## 2. Small server

### 2.1 Server code (index.js)
```js
var express = require('express'),
path = require('path'),
app = express();

app.set('port', process.env.PORT || 8080);

app.use(express.static(path.join(__dirname, 'public')));

app.get("/api",(req,res)=>{
   res.send("This is dynamic!"); 
});

app.listen(app.get('port'), () => {
    console.log(`The server is running on port ${app.get('port')}`);
});

```

### 2.1 Install express dependece
```
npm install express --save
```
## 3 Install Vue Client
```
npm install @vue/cli -g
```
## 4 Simple Web
```
npm install @vue/cli -g
```
