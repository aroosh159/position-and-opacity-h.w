<!DOCTYPE html>
<html>
<head>
<style>
div.relative{
  position: relative;
  left: 30px;
  border: 3px solid #73AD21
  }
div.fixed{
  position: fixed;
  left: 30px;
  border: 3px solid #73AD21;
}
div.absolute{
  position: absolute;
  left: 30px;
  border: 3px solid #73AD21
}
div.static{
  position: static;
  left: 30px;
  border: 3px solid #73AD21
}
</style>
</head>
<body>
<h2>POSITIONS</h2>
<P>The CSS position property is used to specify where an element is displayed on the page. When paired with the the top, right, bottom, and left CSS properties, the position property determines the final location of the element.</P>
<div class="relative">
This div element has position; relative;
</div><br><br>
<div class="fixed">
This div element has position:fixed;
</div><br><br>
<div class="absolute">
This div element has position:absolut;
</div><br><br>
<div class="static">
This div element has position:static;
</div>
</body>
</html>
