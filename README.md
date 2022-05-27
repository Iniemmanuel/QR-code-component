<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="index1.css"> <!-- CSS file -->
  <title>QR code component</title>
  <style>
    body {
      background-color: rgb(220, 231, 240);
    }

    .container {
      margin-top: 10%;
      margin-left: 41%;
      width: 248px;
      height: 387px;
      background-color: white;
      background-position: center;
      border-radius: 15px;
      text-align: center;
    }

    .container img {
      margin-top: 10px;
      width: 33.5vh;
      height: 34.5vh;
      border-radius: 10px;
    }

    .container h3 {
      font-family: "Century Gothic", sans-serif;
      font-size: 15px;
      color: rgb(57, 57, 112);
      text-align: center;
      
    }
    .container p{
      font-family: "Century Gothic", sans-serif;
      font-size: 12.2px;
      color: rgb(147, 147, 168);
    }
    @media (max-width: 600px){
      .body{
        background-size: 200%;
      }
      .container{
        width: 240px;
        margin:0 auto;
      }
    }
        
  </style>
</head>

<body>
  <div class="container">
    <img src="qr-code.png" alt="">
    <h3><b>Improve your front-end <br>skills by building projects</b></h1>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level </p>
  </div>
</body>

</html>
