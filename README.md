

<html lang="en">
<head>
<title> Hello world </title>
<meta charset = "utf-8">
<meta name = "viewport" content = "width=device-width, initial-scale=1">
<style>
*{
 box-sizing: border-box; 
}
  
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0 ;
}
/*Colors, fonts and backgrounds*/
  
  /* Header background color and font color*/
.header { 
  padding: 10 px;
  text-align: center;
  background: #87CEDA;
  color: white; 
  }
  /* font size for header */
.header h1 {
  font-size: 40px;
  }
/*Style the top Navigation bar*/
  .navbar{
  overflow: hidden;
  background-color: #333;
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
   backgound-color: #87CEDA;
   color: black;
}

.row {  
  display: flex;
  flex-wrap: wrap;
}

/*Side column*/
/*.side {
display: flax;
flex-wrap:wrap;
}*/

.comment{
  width: 100%
  background-color: f1f1f1;
  padding: 20px;
}

/*Main column*/ 
.main {
   width: 100%
   background-color: white;
   padding: 20px;
}

/*image*/
.photo {
   background-color: #ddd;
   width: 100%;
   padding: 20px;
    text-align: center;   
}

/*footer*/
.footer{
padding: 20px;
text-align: center; 
background: #87CEDA;
}

  </style>
  </head>

<body>

  
<div class="header">
  <h1> Simple professional </h1>
  <p> Into the unknown</p>


<div class="navbar">
  <a href="#">Resume</a>
  <a href="#">Education</a>
  <a href="#">Projects</a>
  <a href="#" class="right">Linked-in</a>
  </div>
  
  </div>
  
<div class="row">
    <div class="main">
    <h2> About Me<h2>
    <br>
    <p> Stuff about me and why I can help people</p>
     <div class="photo" style="height:200px;">Image</div>
    <h5> What is in the photo</h5>
    <h3> another side of me</h3>
    <p>jkebkjfbejksb </p>
    <div class="photo" style="height:200px;">Image</div>
     
 

 <br>
  <div class="comment">...</div>
  


<div class="footer">
 <h2>Thanks for visiting! </h2>
  </div>
  

  
  </body>

</html>


