
<html>
<head>
  <title>login page</title>
  <style type="text/css">
     *{
       background-color:#f5f5f5;
     }
    .nav{
      margin:80px;
    }
    .border{
      border-radius:12px;
      border:3px solid red;
    }
    h1{
      margin-left:50px;
    }
    .head{
      font-family:Monospace;
      font-size:75px;
    }
    .uname{
      font-family:None;
      font-size:40px;
      font-weight:25px;
    }
    .textbox{
      margin-left:50px;
      border-block-color:red;
      border-radius:9px;
      padding: 30px 20px;
      margin-top:-15px;
      
    }
    .submit{
  margin-left:50px;
  color: black;
  padding: 12px 30px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  border-radius:7px;
  font-weight:100;
    }
  .submitbutton{
  margin-left:200px;
  margin-top:-70px;
  color: black;
  padding: 12px 30px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  border-radius:7px;
  font-weight:100;
  }
    .p1{
      font-size:20px;
      color:blue;
      margin-left:50px;
    }
    .p2{
      font-size:20px;
      color:red;
      margin-left:50px;
    }
    img{
      margin-top:-160px;
      margin-left:400px;
    }
  
  </style>
</head>
<body>
  <br><br><br><br><br><br><br><br><br>
  <br><br><br><br><br><br><br><br>
  <nav class="nav">
  <fieldset class="border">
  <h1 class="head">Log in</h1>
  <img src="http://0.0.0.0:8080/icons8-sparkling-diamond-50.png" width="100px" height="100px" class="img">
  </p>
  <form method="post" action="index.php">
  <lable><h1 class="uname">username </h1><input type="text" placeholder="E-Mail" name="email" class="textbox"size="55" required="yes"></lable>
  <br>
  <lable><h1 class="uname">password </h1><input type="password" placeholder="Password" name="password" class="textbox"size="55" required="yes"></lable>
  <br><br><br>
  <input type="submit" value="○Login..." name="submit" class="submit">
  </form>
  <button class="submitbutton" onclick="window.location.href='http://0.0.0.0:8080/create%20.php'">○ Register</button>
  </fieldset>
  </nav>
  <?php
  ?>
</body>
</html>
