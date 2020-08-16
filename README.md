

<html lang="en">
<head>
<title> Hello world </title>
<meta charset="UTF-8">
<meta name="viewport" 
      content="width=device-width, initial-scale=1">
<style>
* {
 box-sizing: border-box; 
}
  
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0 ;
}
/*Colors, fonts and backgrounds*/
  
  /* Header background color and font color*/
.header { 
 width: 100%;
  height: 100%;
  text-align: center;
  background: #87CEDA;
  color: white; 
  margin: 0;
 

 
  }

  /* font size for header */
.header h1 {
  font-size: 40px;
  margin: 0;
  }

/*Style the top Navigation bar*/
  .navbar{
  overflow: hidden;
  background-color: #333;
  width: 100%;
  position: -webkit-sticky;
  position: sticky;
 top: 0;
  }

/* Style the navigation bar links*/
.navbar a {
  float: left;
  display: block; 
  color: white; 
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/*Right-aligned link*/
.navbar a.right {
float: right;
}

/* Change color on hover/mouse-over */
.navbar a:hover {
   background-color: #87CEDA;
   color: black;
}





.comment{
  background-color: #ddd;
  padding: 20px;
}

/*Main column*/ 
.main {

   background-color: white;
   padding: 20px;
}

/*image*/
.photo {
   background-color: #aaa;
   width: 100%;
   padding: 20px;
  
}

/*footer*/
.footer{
padding: 20px;
text-align: center; 
background: #87CEDA;
float:none;
}

@media screen and (max-width: 400px) { 
  .navbar a{
  float: none;
  width 100%;
  }
  }

  </style>
  </head>
<body>


   
<div class="header">
      <br><br> <br>
  <h1> Simple professional </h1>
  <h5> Into the unknown</h5>
      <br><br><br>
     </div>     
     
 <div class="navbar">
    <a href="#">Resume</a>
    <a href="#">Education</a>
    <a href="#">Projects</a>
    <a href="#" class="right">LinkedIn</a>
   </div>
    

 
 <div class="main">
     <h2> Education<h2>
    <br>
           <p> The joys of college</p></div>
         
 <div class="main">          
    <h2> About Me<h2>
    <br>
          <p> Stuff about me and why I can help people </p>
     <div class="photo" style="height:200px;">Image</div>
    <h5> What is in the photo</h5>
    <h3> another side of me</h3>
    <p>jkebkjfbejksb </p>
          <div class="photo" style="height:200px;">Image</div> </div>
     

 <br>
 
  <div class="comment">
  <h3>deserunt mollit anim id est laborum </h3>

</div>
  


<div class="footer">
 <h2>Thanks for visiting! </h2>
  </div>
 

</body>
</html>
