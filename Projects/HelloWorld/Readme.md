var express = require('express');
console.log("Yes");
var app = express();

app.get('/', function(req,res){
    res.send('Hello World');
});

app.listen(3000)
