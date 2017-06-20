
<!DOCTYPE html>
<html lang="en">
<head>

  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<style>

  body{
    background-image: url("http://www.desktop-background.com/download/1366x768/2011/02/16/158589_blank-white-book_5000x3750_h.jpg");
   
    }
   .container-fluid{
   	margin-top: 200px;
   	margin-left: 100px;
   }
   .carousel{
   	margin-left: 50px;
   	height: 250px;
   	width: 500px;
   }


</style>


</head>
<body>

<div class="container-fluid" >



	<div class="row">
<div class="col-lg-6 col-xs-12">
<h4 id="demo" align="center" ></h4>

	 <script>
 function date_time()
 {
  var dt = new Date();
  document.getElementById("demo").innerHTML = dt;
  setTimeout(function(){ date_time(); }, 1000);
 }
date_time();
</script>
</div>
</div>
<div class="row">

<div class="col-lg-6">
<div id="myCarousel" class="carousel slide" data-ride="carousel">
 
  <ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
    <li data-target="#myCarousel" data-slide-to="2"></li>
  </ol>


  <div class="carousel-inner">
    <div class="item active">
      <img src="https://images5.alphacoders.com/480/thumb-1920-480537.png" alt="Los Angeles">
    </div>

    <div class="item">
      <img src="http://wallpup.com/wp-content/uploads/2013/04/Anonymous-Wallpaper-1080p.jpg" alt="Chicago" >
    </div>

    <div class="item">
      <img src="http://www.wallpaperup.com/uploads/wallpapers/2015/07/03/741665/fa1ef980ad210a8e3c9f5e9d29b95a06.jpg" alt="New York">
    </div>
  </div>

  
  <a class="left carousel-control" href="#myCarousel" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#myCarousel" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
  </div>
  <div class="col-lg-4">
 <ul class="nav nav-tabs">
  <li class="active"><a data-toggle="tab" href="#Signup">Sign up</a></li>
  <li><a data-toggle="tab" href="#Login">Log in</a></li>

</ul>

<div class="tab-content">
<div id="Signup" class="tab-pane fade in active">
 
 <form class="form-horizontal">
<fieldset>

<div class="form-group">
  <label class="col-md-4 control-label" for="1">Name</label>  
  <div class="col-md-4">

  <input id="1" name="1" type="text" placeholder="Name" class="form-control input-md" required="">
  </div>
</div>

<div class="form-group">
  <label class="col-md-4 control-label" for="Gender">Gender</label>
  <div class="col-md-4">
  <div class="checkbox">
    <label for="Gender-0">
      <input type="checkbox" name="Gender" id="Gender-0" value="1">
      Male
    </label>
	</div>
  <div class="checkbox">
    <label for="Gender-1">
      <input type="checkbox" name="Gender" id="Gender-1" value="2">
      Female
    </label>
	</div>
  </div>
</div>

<div class="form-group">
  <label class="col-md-4 control-label" for="5">Enter Password </label>
  <div class="col-md-4">
    <input id="5" name="5" type="password" placeholder="Password" class="form-control input-md" required="">
   
  </div>
</div>

<div class="form-group">
  <label class="col-md-4 control-label" for="6">Re-Enter Password</label>
  <div class="col-md-4">
    <input id="6" name="6" type="password" placeholder="Re-enter Password" class="form-control input-md" required="">
   
  </div>
</div>

<div class="form-group">
  <label class="col-md-4 control-label" for="1"></label>
  <div class="col-md-8">
    <button id="1" name="1" class="btn btn-success">Submit</button>
    
  </div>
</div>

</fieldset>
</form>

  </div>
  <div id="Login" class="tab-pane fade">
   
    <form class="form-horizontal">
<fieldset>

<div class="form-group">
  <label class="col-md-4 control-label" for="1">User Name</label>  
  <div class="col-md-4">

  <input id="1" name="1" type="text" placeholder="User Name" class="form-control input-md" required="">
  </div>
</div>



<div class="form-group">
  <label class="col-md-4 control-label" for="5">Enter Password </label>
  <div class="col-md-4">
    <input id="5" name="5" type="password" placeholder="Password" class="form-control input-md" required="">
   
  </div>
</div>



<div class="form-group">
  <label class="col-md-4 control-label" for="1"></label>
  <div class="col-md-8">
    <button id="1" name="1" class="btn btn-success">Submit</button>
    
  </div>
</div>

</fieldset>
</form>

  </div>
  </div>
  </div>


  
</body>
</html>
