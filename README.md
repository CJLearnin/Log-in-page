# Log-in-page
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Sign Up Form</title>
        <link rel="stylesheet" href="css/normalize.css">
        <link href='http://fonts.googleapis.com/css?family=Nunito:400,300' rel='stylesheet' type='text/css'>
        <link rel="stylesheet" href="bootstrap%20footer.css">
    </head>
    <body>
<header class="header">
        <h1 class="logo">Logo</h1>
        <ul class="nav">
          <li><a href="#">Features</a></li>
          <li><a href="#">Pricing</a></li>
          <li><a href="#">Sign In</a></li>
          <li><a href="#">Free Trial</a></li>
        </ul>
      </header>
        
        
        
      <form action="index.html" method="post">
        <legend><span class="number">1</span>Your basic Info</legend>
        <h1>Sign Up</h1>
        <fieldset>
        <label for="name">Name:</label>
        <input type="text" id="name" name="user_name">
        <label for="mail">Email:</label>
        <input type="email" id="mail" name="user_mail">
        <label for="password">Enter password:</label>
        <input type="password" id="password" name="user_password">
          
          <label for="job">  Job Role</label>
          <select id="job" name="user_job">
          <option value="frontend_dev">Front-End Dev</option>
          <option value="PHP_dev">PHP Dev</option>
          <option value="Ruby_dev">Ruby Dev</option>
          <option value="Pyhton_dev">Phyton Dev</option>
        <button type="submit" name="submit_button">Submit</button>
            </select>
      </fieldset>
        <label for="bio"></label>
      
      </form>
        
        <!--Footer-->
<div class="content">
</div>
    <footer id="myFooter">
        <div class="container">
            <div class="row">
                <div class="col-sm-3 myCols">
                    <h5>Get started</h5>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Sign up</a></li>
                        <li><a href="#">Downloads</a></li>
                    </ul>
                </div>
                <div class="col-sm-3 myCols">
                    <h5>About us</h5>
                    <ul>
                        <li><a href="#">Company Information</a></li>
                        <li><a href="#">Contact us</a></li>
                        <li><a href="#">Reviews</a></li>
                    </ul>
                </div>
                <div class="col-sm-3 myCols">
                    <h5>Support</h5>
                    <ul>
                        <li><a href="#">FAQ</a></li>
                        <li><a href="#">Help desk</a></li>
                        <li><a href="#">Forums</a></li>
                    </ul>
                </div>
                <div class="col-sm-3 myCols">
                    <h5>Legal</h5>
                    <ul>
                        <li><a href="#">Terms of Service</a></li>
                        <li><a href="#">Terms of Use</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="social-networks">
            <a href="#" class="twitter"><i class="fa fa-twitter"></i></a>
            <a href="#" class="facebook"><i class="fa fa-facebook-official"></i></a>
            <a href="#" class="google"><i class="fa fa-google-plus"></i></a>
        </div>
        <div class="footer-copyright">
            <p>© 2016 Copyright Text </p>
        </div>
    </footer>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<!--/.Footer-->
      
    </body>
</html>
