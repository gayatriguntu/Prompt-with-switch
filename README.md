# Prompt-with-switch
<!DOCTYPE html>
<html lang="en">
<head>

</head>
<body>
  <p>
    Click the button to display a dialog box.
  </p>
  <button onclick="myFun()">Click</button>
  <p id="demo"></p>

  <script>
    function myFun(){
        var text;
        var favWeb= prompt("What's your favourite Web? Google, Youtube, Facebook", "Enter Website Name")
        switch(favWeb){
            case "Google":
                text = "you selected Google"
                window.open('https://www.google.com');
                break;
            case "Youtube":
                text = "you selected Youtube"
                window.open('https://www.youtube.com/');
                break;
            case "Facebook":
                text = "you selected Facebook"
                window.open('https://www.Facebook.com/');
        break;
    default:text = "you are not selected any website";
    }
    }
  </script>
</body>
</html>
