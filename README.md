# Delete Images
<!DOCTYPE html>
<html lang="en">
<head>
  <script type="text/javascript">

    function removephotoQueen(){
      var image = document.getElementById(Queen);
      node.parentNode.removeChild(Queen);
    }
    function removephotoPeppers(){
      var image = document.getElementById(Queen);
      node.parentNode.removeChild(Queen);
    }
    function removephotoRush(){
      var image = document.getElementById(Queen);
      node.parentNode.removeChild(Queen);
    }
  </script>
</head>
<body>

    <img src="https://en.wikipedia.org/wiki/Queen_(band)#/media/File:Queen_%E2%80%93_montagem_%E2%80%93_new.png" id="Queen" onclick="removephotoQueen();">
    <img src="https://en.wikipedia.org/wiki/Red_Hot_Chili_Peppers#/media/File:Red_Hot_Chili_Peppers_2012-07-02_001.jpg" id="Peppers" onclick="removephotoPeppers();">
    <img src="https://en.wikipedia.org/wiki/Rush_(band)#/media/File:Rush-in-concert.jpg" id="Rush" onclick="removephotoRush();">

</body>
</html>
