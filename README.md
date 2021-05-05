# 2test
Sorry github
<!doctype html>
<html>
  <head>
    <title>Hover</title>
  </head>
  <style>
  *{
  margin: 0;
  padding: 0;
  }
  body{
  background-color: black;
  }
  .main{
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  }
  ol{
  list-style: none;
  display: flex;
  font-size: 1.2rem;
  }
  ol li{
  margin: 0 20px;
  padding: 10px 20px;
  position: relative;
  transition: all 0.2s;
  transition-delay: 0.2s;
  }
  ol li a{
  color: #FFFFFF;
  text-decoration: none;
  }
  ol li::before{
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height:2px;
  background: #FFFFFF;
  transition: all 0.2s;
  }
  ol li:hover::before{
  bottom: 40px;
  background: rgb(255, 63, 63);
  }
  ol li:hover{
  background: rgb(255, 63, 63);
  }
  </style>
  <body>
    <div class="main">
      <ol>
        <li><a href="#">Home</a></li>
        <li><a href="#">Service</a></li>
        <li><a href="#">About us</a></li>
        <li><a href="#">Contact us</a></li>
      </ol>
      
    </div>
  </body>
</html>
