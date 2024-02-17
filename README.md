<!DOCTYPE html>
<html lang="en">
 <head>
  <body>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Picture This!</title>
  <link rel="stylesheet" href="style.css">
</head>
 
<body>
  <header class="header">
    <div class="title">
      <h1>Picture This!</h1>
      <h4>My Really Cool Blog Post</h4>
      <img src="mickeymouse.jpg" alt="Galaxy">
    </div>
    <picture>
      <source media="(max-width: 959px)" srcset="./images/museum.jpg">
      <source media="(min-width: 960px)" srcset="./images/museum.jpg">
      
    </picture>
  </header>
</body>

</html>
