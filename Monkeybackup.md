

<!DOCTYPE html>
<html>
<head>
 <title>Password</title>
 <style>
  body {
   background-color: white;
   padding: 30px;
  }
 </style>
 <script>
  function checkPassword() {
   var password = document.getElementById("passwordBox");
   var passwordText = password.value;
   if(passwordText == "Ernest300") {
    return true;
   }
   alert("Access denied! Incorrect password!");
   return false;
   }
 </script>
</head>
<body>
 <p style="font-size: 30pt;">OutRed Games</p>
 <p>Please enter the password to view this website.</p>
 <p>Password:<input id="passwordBox" type="password"/></p>
 <a href="https://outred.github.io/games.md" onclick="return checkPassword();">
  Click here to submit password and play games
 </a>
</body>
</html>

  This page was NOT generated by Github Pages, ignore what is said down below.

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
 
