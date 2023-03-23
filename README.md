# namitaece.github.io
<!DOCTYPE html>
<html lang="en">
<head>
 <!-- main banner -->

 
 <section class="bgimage" id="home">
    <div class="container-fluid">
        <div class="row">
        <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12 hero-text">
            <h2 class="hero_title">Hi, it's me Namita </h2>
            <p class="hero_desc">I am an aspiring Web Developer !</p>
        </div>
       

        </div>
    </div>
    
   
    <div class="navbar">
        <a class="active" href="#"><i class="fa fa-fw fa-home"></i>Home</a> 
        <a href="#"><i class="fa fa-fw fa-user"></i> About</a> 
        <a href="#"><i class="fa fa-fw fa-file"></i> Project</a> 
        <a href="#"><i class="fa fa-fw fa-phone"></i> Contact</a> 
        <a href="#"><i class="fa fa-fw fa-globe"></i> Experience</a>
      </div>
     
</section>





    <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {font-family: Arial, Helvetica, sans-serif;}

.navbar {
  width: 100%;
  background-color: rgb(14, 0, 0);
  overflow: auto;
}

.navbar a {
  float: left;
  padding: 12px;
  color: white;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background-color: rgba(245, 44, 13, 0.927);
}

.active {
  background-color: #101110;
}

@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
  }
}
/* hero background image */
.bgimage {
    height:100vh;
    background: url('img/dark.jpg');
    background-size:cover;
    position:relative;
}
/* text css above hero image*/
.hero_title {
    font-size: 4.5rem;
}
.hero_desc {
    font-size: 2rem;
}
.hero-text {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: rgb(93, 91, 93);
}


html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.949);
  margin: 8px;
}

.about-section {
  padding: 50px;
  text-align: center;
  background-color: #4a4e4f;
  color: rgb(71, 13, 244);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: rgb(18, 1, 1);
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: rgb(7, 0, 0);
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}
</style>
</head>
<body>
<!-- about section-->
<section id="about">
    <div class="container mt-4 pt-4">
        <h1 class="text-center">About Me</h1>
        <div class="row mt-4">
            <div class="col-lg-4">
                <img src="images/about.jpeg" class= "imageAboutPage" alt="">
            </div>

            <div class="col-lg-8">
                
                    
                
                <div class="row mt-3">
                    <div class="col-md-6">
                        <ul>
                            <li>Name: Namita S</li>
                            <li>Age: 18</li>
                            <li>Qualification:First year, Btech ECE</li>
                            
    <p> I'm Namita ,pursuing Btech in Electronics and Communications Engineering,in Vellore Institute Of Technology(Vellore).I'm honored to be a part of The Electronics Club.I have always wanted to know how websites are been made ,so this task has actually helped me understand that. I am really excited to learn a lot of new things in this club!
                     </p>

                        </ul>
                    </div>
                    

                        </ul>
                    </div>
                </div>
                <div class="row mt-3">
                    <p> I have have a basic knowledge about programming in Python and Java.Now because of this task i've gained somewhat knowledge about HTML and CSS as well.I am an enthusiast when it comes to web development .This domain has always peaked my interest since school level.I would very much like to learn more about the techincal things through this club.
                    </p>
                </div>
            </div>
        </div>
</section>


  <!-- Footer -->
 
  <!-- contact section-->
  

            <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
</head>
<body>

<h3>Contact Me</h3>

<div class="container">
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">
   
    <label for="gender">Gender</label>
    <select id="gender" name="gender">
      <option value="male">Male</option>
      <option value="female">Female</option>
      <option value="other">Other</option>
    </select>

    
    <label for="mail">Email ID</label>
    <input type="mail"  id="email Id" name="mail" placeholder="Your mail Id..">


    
<br> <br>
        
    
    

    <label for="subject">Subject</label>

    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">
  </form>
</div>


        </div>
       
    </div>
    
</section>

<div class="body-part">
    <div class="icon-list">
        <a href="#instagram" class="instagram">
            <i class="fa fa-instagram"></i>
        </a>
         
        <a href="#facebook" class="facebook">
            <i class="fa fa-facebook"></i>
        </a>
         
        <a href="#twitter" class="twitter">
            <i class="fa fa-twitter"></i>
        </a>
         
        <a href="#linkedin" class="linkedin">
            <i class="fa fa-linkedin"></i>
        </a>
         
        <a href="#google" class="google">
            <i class="fa fa-google"></i>
        </a>
         
        <a href="#youtube" class="youtube">
            <i class="fa fa-youtube"></i>
        </a>
    </div>


 

</body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&display=swap');
*{
    box-sizing:border-box;
    padding:0;
    margin:0;
}
body {
font-family: 'Josefin', sans-serif;
color:rgb(75, 74, 77);
line-height:1.6;
}
ul{list-style-type: none;}
a{text-decoration: none;
color:black;}
h1,h2{
    font-weight: 300;
    line-height:1.2 ;
    margin:10px,0 ;
}
p{margin: 10px,0;}
img{width:100%;}

.navbar
{background-color: rgba(0, 0, 255, 0.032);
color:rgba(75, 13, 244, 0.895);
height:70px}
.navbar ul{
    display: flex;
  
}
.navbar a{
    color: rgb(112, 16, 239);
    padding:10px;
    margin:0 5px;
}

.navbar a:hover{
    border-bottom:2px rgb(31, 30, 30) solid;
}
.navbar.flex{
    justify-content:space-between;
}

.showcase{
    height: 400px;
    background-color: rgba(33, 27, 205, 0.032);
color: rgb(28, 27, 27);
position:relative;
}

.showcase h1{
    font-size:40px;
}

.showcase p{
    margin:20px 0;
}

.showcase.grid{
    grid-template-columns:55% 45%;
    gap:30px;
}

.showcase-text{
    animation: slideInFromLeft 1s ease-in;
}
.showcase-form{
    position:relative;
    top:60px;
    height:350px;
    width:400px;
    padding:40px;
    z-index:100;
    animation: slideInFromRight 1s ease-in;
}

.showcase-form .form-control{
    margin:30px 0;
    }

    .showcase-form  input[type='text'],
    .showcase-form  input[type='email'] {
        border: 0;
        border-bottom:1px solid #e217ba;
        width:100%;
        padding:3px;
        font-size:16px;
    }
    .showcase-form input:focus{
        outline:none;
    }





.container
{max-width: 1100px;
margin:0 auto;
overflow: auto;
padding:0 40px;}

.card{
    background-color:rgba(21, 20, 22, 0);
    color: rgb(19, 18, 18);
    border-radius:10px;
    box-shadow:0 30px  10px rgba(0,0,0,0.2);
    padding:20px;
    margin:10px;
    
}
.btn{
    display: inline-block;
    padding:10px 30px;
    cursor:pointer;
    background: #04d5ec;
    color:rgb(28, 29, 29);
    border:none;
    border-radius: 5px;
}
.btn-outline{
    background-color: transparent;
    border:1px rgb(215, 228, 24) solid;


}

.flex{ 
    display:flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    height:100%;
}

.grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:20px;
    justify-content:center;
    align-items:center;
    height:100%;
}
.footer.social a{
    margin:0 10px;
    
}
@media ( max-width:786px){

}
@media ( max-width:500px){
    .navbar{
        height:110px;
    }
}
.navbar.flex{
    flex-direction:column;
}
.navbar ul{
    padding:10px;
    background-color:rgba(12, 9, 9, 0.855);
}
.languages.flex{
    flex-wrap: wrap;
}
.languages .card{
    text-align: center;
    margin:18px 10px 40px;
transition: transform 0.2s ease-in;
}

.languages .card h4{
    font-size: 20px;
    margin-bottom: 10px;
}

.languages .card :hover{
    transform: translateY(-15%);
}
@keyframes slideInFromLeft{
    0% {
        transform: translateX(-100%);

    }
    100% {
        transform: translateX(0);
        
    }
}
@keyframes slideInFromRight{
    0% {
        transform: translateX(100%);

    }
    100% {
        transform: translateX(0);
        
    }
}
@keyframes slideInFromBottom{
    0% {
        transform: translateY(100%);

    }
    100% {
        transform: translateY(0);
        
    }
}
@keyframes slideInFromTop{
    0% {
        transform: translateY(-100%);

    }
    100% {
        transform: translateY(0);
        
    }
}
