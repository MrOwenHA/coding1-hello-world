# Hello World Assignment

index.html

<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Hello World</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
  <h1>Hello World</h1>
  <img src="helloWorldAstronaut.jpg">
  <h3 id="dateLocation"></h3>
  <script src="script.js"></script> 
</body>

</html>




style.css

html, body {
  height: 100%;
  width: 100%;
}

body {
  background-color: black;
  text-align: center;
  
}

h1 {
  font-size: 48pt;
  color: white;
}

h3 {
  font-size: 24pt;
  color: white;
}

img {
  max-width: 100%;
  height: auto;
}



script.js

const date = new Date();
document.getElementById("dateLocation").innerHTML = date;
