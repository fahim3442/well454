
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animation step</title>
    <link rel="stylesheet"href="second project css code.css">
    <style>.wellcome{
    background-image:linear-gradient(#ff5722,#ffc107);
    position: relative;
    height: 100vh;
    overflow: hidden;
    font-family: sans-serif;
}
h1{
    color: rgb(255, 255, 255) ;
    position: absolute;
    transform: translate(-50%,-50%);
    top: 50%;
    left: 50%;
    font-size: 40px;
    z-index:1;
}
ul li 
{
    position: absolute;
    border: 1px solid rgba(255, 255, 255, 0.842);
    width: 10px;
    height: 10px;
    list-style: none;
    opacity: 0;
    background: rgba(174, 165, 175, 0.876);
}
.square li{
    top: 50vh;
    left: 45vw;
   animation: square 10s linear infinite;
  animation-delay: 1s;
}
.square li:nth-child(2)
{
    top: 80vh;
    left: 10vw;
    animation-delay: 4s;
}
    </style>
</head>
<body>
    <div class="wellcome"></div>
    <h1>Animation Css Tutorial.</h1>
    <div class="square">
        <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
       
        </ul>
    </div>
    <div class="circle">
        <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
       
        </ul>
    </div>
    
</body>
</html>
