<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>tahttawi</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
    <style type="text/css">
    *{
        color: #D28F38;
    }
      .navbar-brand{
        font-size: 1.8em;
        color: #D28F38;
      }
      #topContainer{
        background-image: url("taha.jpg");
        height: 400px;
        width: 100%;
        background-size: cover;
      }
      #topRow{
        margin-top: 100px;
        text-align: center;
      }
      #topRow h1{
        font-size: 500%;
        color: #D28F38;
        font-weight: bold;
      }
      .bold{
        font-weight: bold;
        font-size: 1.5em;
      }
      .tab{
        font-size: 1.2em;
        
      }
      .marginTop{
        margin-top: 30px;
      }
      .center{
        text-align: center;
      }
      .title{
        margin-top: 80px;
        font-size: 300%;
      }
      #footer{
        background-color: #4F4744;
        padding-top: 40px;
        width: 100%;
      }
      .marginBottom{
        margin-bottom: 30px;
      }
      .googleStore{
        margin-top: 20PX;
        width: 250px;
      }
      
    </style>
  </head>
  <body>
    <div class="navbar navbar-default navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" style="  color: #D28F38;">Tahttawi</a>
        </div>
        <div class="collapse navbar-collapse">
          <ul class="nav navbar-nav">
              <li class="active"><a href="#Home">Home</a></li>
              <li><a href="#About">About</a></li>
              <li><a href="#download">Download The App</a></li>
            
          </ul>
          <form class="navbar-form navbar-right">
            <div class="form-group">
              <input type="email" placeholder="Email" class="form-control"/>
            </div>
            <div class="form-group">
              <input type="password" placeholder="password" class="form-control"/>
            </div>
            <button type="submit" class="btn btn-success">Log In</button>
            
          </form>
          
        </div>
      </div>
    </div>
    <div class="container contentContainer" id="topContainer">
      <div class="row">
        <div class="col-md-6 col-md-offset-3" id="topRow">
         <h1 class="marginTop">My Awesome App</h1>
         <p class="lead"><strong>This is why should download this fantastic App.</strong></p>
         <p class="tab">Some more information about the app. You can go into a little more details if you want to.</p>
         <p class="bold marginTop">Interested? Join our mailing list</p>
         <form class="marginTop">
           <div class="input-group">
             <span class="input-group-addon">@</span>
             <input type="email" class="form-control" placeholder="Your Email"/>
           </div>
           <input type="submit" class="btn btn-success btn-lg marginTop">
         </form>
          
        </div>
        
      </div>
    </div>
    <div class="container contentContainer">
      <div class="row" class="center">
        <h1 class="center title">Why This App Is Awesome</h1>
        <p class="lead center">Summary of the app's awesomeness</p>
      </div>
      <div class="row marginBottom">
        <div class="col-md-4 marginTop">
          <h2><span class="glyphicon glyphicon-music"></span>Header</h2>
         <p> A brief description of one of the best of your app. Maybe a little more text. A brief description of one of the best of your app. Maybe a little more text.</p>
          <button class="btn btn-success marginTop ">signup!</button>
        </div>
        <div class="col-md-4 marginTop">
          <h2><span class="glyphicon glyphicon-off"></span>Header</h2>
         <p> A brief description of one of the best of your app. Maybe a little more text. A brief description of one of the best of your app. Maybe a little more text.</p>
          <button class="btn btn-success marginTop ">signup!</button>
        </div>
        <div class="col-md-4 marginTop ">
          <h2><span class="glyphicon glyphicon-pencil"></span>Header</h2>
         <p> A brief description of one of the best of your app.    Maybe a little more text. A brief description of one of the best of your app. Maybe a little more text.</p>
          <button class="btn btn-success marginTop ">signup!</button>
        </div>
      </div>
    </div>
    <div class="container contentContainer" id="footer">
      <div class="row">
        <h1 class="center title marginTop">Download The App!</h1>
        <p class="lead center marginTop">Really , why should i download this app?</p>
        <p class="center"><img src="images.jfif" class="googleStore"></p>
      </div>
      
    </div>

    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
    <script type="text/javascript">
      $(".contentContainer").css("min-height",$(window).height());
    </script>
  </body>
</html># tahttawi-test
