# Code
## Startseite
## Html
!DOCTYPE
html
head
   meta charset="utf-8"
   link href="main.css" type="text/css" rel="Stylesheet"
   header
   h1 Database for pictures h1
   <nav class="navigation">
      <a href="Startseite.html">Main Page</a>
      <a href="Log in.html">Log In</a>
      <a href="Sign In.html">Sign Up</a>
   </nav>
  </header>
  <section>
   <p>Many have the same problem that I had. I had too many pictures. So<br> 
   	  I was searching for a website were I can save my pictures, because I didn`t<br> 
   	  wanted to use my space on computer, but have access to them everytime.<br>
      This is why I made this website, to give everyone the chance to have such a<br> 
      website. A website were you can save all your pictures on your account and<br> show you family and friends everytime.  
   </p>
   <h2>How to use this Website</h2>
   <p>First Step:<br>
   </p>
   <p>Second Step:<br> 
   </p>
   <p>Third Step:<br>
   </p>
   <p>
     <a href="#top">Back to the Top</a>
   </p>
   </section>
   <aside>
    	hello
   </aside>
  <footer>
    <nav>
      <a href="Impressum.html">Impressum</a><br>
      <a href="Help.html">Help</a><br>
      <small>&copy; Main Page</small>
    </nav>
   </footer>
 </body>
</html>

## Css
html{
    color: white;	
}
header{
	background-color: white;
	margin-left: 20px;
}
h1{
	float: left;
	color: black;
}
body{
   background-color: white;
   margin-left: 0;
   margin-right: 0;
   font-size: 17px;
}
nav{
	background-color: grey;
}
section{
	background-color: green;
	float: left;
	width: 63%;7
	margin: 0 1,5%;
	clear: left;
}
aside{
	background-color: red;
	float: right;
	margin: 0 1,5%;
	width: 34%;
}
footer{
	background-color: white;
	clear: both;
	margin-left: 0;
	margin-right: 0;
	color: black;
	float: left;
	width: 100%;
}
small{
	float: right;
	background-color: grey;
	width: 100%;
}
a{
	color: black;
}
.navigation {
	float: right;
	width: 40%;
	margin-top: 67px;
}
.Name{
	float: left;
}

## Regitrierung
## Html
<!DOCTYPE>
<!DOCTYPE html>
<html>
<head>
   <meta charset="utf-8">
   <link href="Signup.css" type="text/css" rel="Stylesheet" >
   <title></title>
</head>
 <body> 
  <header>
   <h1 class="Name">Database for pictures</h1>
   <nav class="navigation">
      <a href="Startseite.html">Main Page</a>
      <a href="Log in.html">Log In</a>
      <a href="Sign in.html">Sign Up</a>
   </nav>
  </header>
  <section class="solve">
    
  </section>
  <section class="middle">
      <form action="action_page.php" style="border:1px solid #ccc">
  <div class="container">
    <p>Please fill in this form to create an account.</p>

    <label for="email"><b>Email</b></label>
    <input type="text" placeholder="Enter Email" name="email" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>

    <label for="psw-repeat"><b>Repeat Password</b></label>
    <input type="password" placeholder="Repeat Password" name="psw-repeat" required>

    <label>
      <input type="checkbox" checked="checked" name="remember" style="margin-bottom:15px"> Remember me
    </label>

    <p>By creating an account you agree to our <a href="#" style="color:dodgerblue">Terms & Privacy</a>.</p>

    <div class="clearfix">
      <button type="button" class="cancelbtn">Cancel</button>
      <button type="submit" class="signupbtn">Sign Up</button>
    </div>
  </div>
</form>
  </section>
  <section class="sides">
    
  </section>
<footer>
    <nav>
      <a href="Impressum.html">Impressum</a><br>
      <a href="Help.html">Help</a><br>
      <small>&copy; Sign Up</small>
    </nav>
   </footer>
 </body>
</html>

## Css
html{
    color: white; 
}
header{
  background-color: white;
  margin-left: 20px;
}
h1{
  color: black;
  height: 41px;

}
body{
   background-color: white;
   margin-left: 0;
   margin-right: 0;
   font-size: 17px;
}
section{
  background-color: green;
  float: left;
  width: 15%;
  height: 394px
}
nav{
  background-color: grey;

}
footer{
  background-color: white;
  clear: both;
  margin-left: 0;
  margin-right: 0;
  color: black;
  float: left;
  width: 100%;
}
small{
  float: right;
  background-color: grey;
  width: 100%;
}
a{
  color: black;
}
* {box-sizing: border-box}

input[type=text], input[type=password] {
  width: 100%;
  padding: 0px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}
.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}
.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}
.container {
  padding: 16px;
}
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
    width: 100%;
  }
}
.navigation {
  float: right;
  width: 40%;
  margin-top: 67px;
}
.Name{
  float: left;

}
.solve{
    clear: left;
    background-color: grey;
}
.middle{
  width: 70%;
}
.sides{
  background-color: grey;
}

## Einloggen
## Html
<!DOCTYPE>
<!DOCTYPE html>
<html>
<head>
   <meta charset="utf-8">
   <link href="Log in.css" type="text/css" rel="Stylesheet" >
   <header>
   <h1 class="Name">Big Brain</h1>
   <nav class="navigation">
      <a href="Startseite.html">Main Page</a>
      <a href="Log in.html">Log In</a>
      <a href="Sign In.html">Sign Up</a>
   </nav>
  </header>
  <section class="solve">
    
  </section>
 <section class="middle">
   <form action="action_page.php" method="post">
  <div class="container">
    <label for="uname"><b>Username</b></label>
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>

    <button type="submit">Login</button>
    <label>
      <input type="checkbox" checked="checked" name="remember"> Remember me
    </label>
  </div>

  <div class="container" style="background-color:#f1f1f1">
    <button type="button" class="cancelbtn">Cancel</button>
    <span class="psw">Forgot <a href="#">password?</a></span>
  </div>
</form>
 </section>
 <section class="sides">
   
 </section>
<footer>
    <nav>
      <a href="Impressum.html">Impressum</a><br>
      <a href="Help.html">Help</a><br>
      <small>&copy; Log In</small>
    </nav>
   </footer>
</body>

## Css
html{
    color: white;	
}
header{
	background-color: white;
	margin-left: 20px;
}
h1{
	color: black;
	height: 41px;
}
body{
   background-color: white;
   margin-left: 0;
   margin-right: 0;
   font-size: 17px;
}
section{
	background-color: green;
	float: left;
	width: 15%;
	height: 394px
}
nav{
	background-color: grey;

}
footer{
	background-color: white;
	clear: both;
	margin-left: 0;
	margin-right: 0;
	color: black;
	float: left;
	width: 100%;
}
small{
	float: right;
	background-color: grey;
	width: 100%;
}
a{
	color: black;
}
form {
  border: 3px solid #f1f1f1;
}
input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}
button:hover {
  opacity: 0.8;
}
.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}
.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}
.container {
  padding: 16px;
}
span.psw {
  float: right;
  padding-top: 16px;
}
@media screen and (max-width: 300px) {
  span.psw {
    display: block;
    float: none;
  }
  .cancelbtn {
    width: 100%;
  }
 }
.navigation {
	float: right;
	width: 40%;
	margin-top: 67px;
}
.Name{
	float: left;

}
.solve{
    clear: left;
    background-color: grey;
}
.middle{
	width: 70%;
}
.sides{
	background-color: grey;
}

## Kontakt Formular
## Html
<!DOCTYPE>
<!DOCTYPE html>
<html>
<head>
   <meta charset="utf-8">
   <link href="Help.css" type="text/css" rel="Stylesheet" >
   <title></title>
</head>
 <body> 
  <header>
   <h1 class="Name">Big Brain</h1>
   <nav class="navigation">
      <a href="Startseite.html">Main Page</a>
      <a href="Log in.html">Log In</a>
      <a href="Sign In.html">Sign Up</a>
   </nav>
  </header>
  <section class="solve">
     
   </section>
   <section class="middle">
    <form action="Database.php" id="container">
      <label for="name">Name</label>
       <input type="text" id="name" name="Name" placeholder="Your Name...">
      <label for="Country">Country</label>
       <select>
        <option value="Germany">Germany</option>
        <option value="France">France</option>
        <option value="England">England</option>
        <option value="Usa">Usa</option>
       </select>
      <label for="Problem">Problem</label>
       <select>
        <option value="Account Problem">Account problem</option>
        <option value="Saving Problem">Saving problem</option>
        <option value="Technichal Problem">Technical problems</option>
       </select>
      <textarea id="subject" name="subject" placeholder="Write something..." style="height: 300px">
      </textarea>
      <input type="submit" name="submit">
    </form>
   </section>
   <section class="sides">
    
   </section>
  <footer>
    <nav>
      <a href="Impressum.html">Impressum</a><br>
      <a href="Help.html">Help</a><br>
      <small>&copy; Help</small>
    </nav>
   </footer>
 </body>
</html>

## Css
html{
    color: white;	
}
header{
	background-color: white;
	margin-left: 20px;
}
h1{
	color: black;
	height: 41px;

}
body{
   background-color: white;
   margin-left: 0;
   margin-right: 0;
   font-size: 17px;
}
section{
	background-color: green;
	float: left;
	width: 15%;
	height: 394px
}
nav{
	background-color: grey;

}
footer{
	background-color: white;
	clear: both;
	margin-left: 0;
	margin-right: 0;
	color: black;
	float: left;
	width: 100%;
}
small{
	float: right;
	background-color: grey;
	width: 100%;
}
a{
	color: black;
}
input[type=text]{
	width: 30%;
	border: 1px solid #ccc
	border-radius: 4px;
	box-sizing: border-box;
	margin-top: 6px;
	margin-bottom: 16px;	
}
input[type=submit]{
	background-color: #4CAF50
	color: white;
	padding: 12px 20px;
	border: none;
	border-radius: 4px
	cursor: pointer;
}
input[type=submit]:hover {
  background-color: grey;
}
textarea{
	width: 85%;
}
.navigation {
	float: right;
	width: 40%;
	margin-top: 67px;
}
.Name{
	float: left;

}
.solve{
    clear: left;
    background-color: grey;
}
.middle{
	width: 70%;
}
.sides{
	background-color: grey;
}
