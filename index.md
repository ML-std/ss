<!DOCTYPE html>
<html lang="en">
<head>
    <title>Main Page</title>
    <link rel="stylesheet" href="../Styles/styles.css">
    <link rel="shortcut icon" href="../Media/favicon.ico" />
</head>
<body>
<header>

    <div class="tab">
        <form>
            <button class="tablinks" ><em> Main Page</em></button>
            <button class="tablinks" formaction="blog.html" type="submit"> Blog </button>
            <button class="tablinks" formaction="services.html" type="submit">Services</button>
            <button class="tablinks" formaction="team.html" type="submit"> Team</button>
            <button class="tablinks" formaction="gallery.html" type="submit">Gallery</button>
            <button class="tablinks" formaction="contactme.html" type="submit"> Contact Us</button>
            <button class="tablinks" formaction="registration.html" type="submit"> Register</button></form>
    </div>
      </header>
<nav>


    <form action="http://www.google.com/search" method="get">
        <label>Search On Google :</label>
        <input type="hidden" name="q"  value="">
        <label>
            <input type="text" name="q" placeholder="Search">
        </label>
         <input  type="submit" value="Search">
    </form>
</nav>
<hr>
<aside>
    <img  class = "index" src="../Media/veterinary.png" alt="Veterinary">
    <img class =" index" src="../Media/injuredGood.png" alt = "IG Logo">
    <img  class = "index" src="../Media/vet2.png" alt="Veterinary">
    <section class="right">
        <form class="fontLarge" action="index.md">
        <div class="center">
            <h4>IG Veterinary Clinic</h4>
            <h5>Please Login</h5>
            <label><input name="username" placeholder="UserName">
            </label>
            <br><br>
            <label><input name="password" type="password" maxlength="8" placeholder="password"/></label>
            <hr class="another">
           <input type="submit" value="Login">

        </div></form>
        <form action="registration.html" class="center">
            <input type="submit" value="Register!">
        </form>
    </section>
</aside>
<article>
    <h4 class="center">Should you need any information,please <a href="contactme.html">contact Us!</a></h4>
</article>

<footer>
    &copy; 2020 all rights reserved IG Company
</footer>
</body>
</html>