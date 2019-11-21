# Code
## Startseite
## Html

<!DOCTYPE>
<html>
<head>
   <meta charset="utf-8">
   <link href="main.css" type="text/css" rel="Stylesheet" >
   <header>
   <h1>Big Brain</h1>
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

## Registrierung

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
   <h1 class="Name">Big Brain</h1>
   <nav class="navigation">
      <a href="Startseite.html">Main Page</a>
      <a href="Log in.html">Log In</a>
      <a href="Sign in.html">Sign Up</a>
   </nav>
  </header>
  <section class="solve">
    
  </section>
  <section class="middle">
      <form action="Database.php" style="border:1px solid #ccc">
  <div class="container">
    <p>Please fill in this formular to create an account.</p>

    <label for="email"><b>Email</b></label>
    <input type="text" placeholder="Enter Email" name="email" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>

    <label for="password-repeat"><b>Repeat Password</b></label>
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

## Login

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

## Kontaktformular

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
