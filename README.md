index.html

<html>
<head>
<link rel="stylesheet" href="css/style.css">
</head>

<body>

    <div class="con">
      <div class="dot dot1" title="Point 01"></div>
      <div class="dot dot2" title="Point 02"></div>
      <div class="dot dot3" title="Point 03"></div>
      <img src="img/dragons-ship.png" />
    </div>

</body>
</html>

style.css

.con {
  max-width: 600px;
  position: relative;
}

.dot {
  background: red;
  border-radius: 50%;
  height: 20px;
  position: absolute;
  width: 20px;
}

.dot1 {
  top: 40%;
  left: 10%;
}

.dot2 {
  top: 30%;
  right: 20%;
}

.dot3 {
  bottom: 40%;
  left: 50%;
}

img {
  width: 100%;
}
