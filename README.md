

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
  padding: 80 px;
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
float right;
}

/* Change color on hover/mouse-over */
.navbar a:hover {
   backgound-color: #ddd;
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
/*flex: 30%*/
background-color: f1f1f1;
padding 20px;
}

/*Main column*/ 
.main {
   /*flex: 70%;*/
   background-color: white
   padding 16px;
}

/*image*/
.photo {
   background-color: #ddd;
   width:100%
   padding 16px;
   
}

/*footer*/
.footer{
padding: 16px;
text-align: center; 
background: #87CEDA;
}

  </style>
  </head>

<body>

  
<div class="header">
<h1> Simple professional </h1>
<p> Into the unknown</p>
</div>

<div class="navbar">
  <a href="#">Resume</a>
  <a href="#">Education</a>
  <a href="#">Projects</a>
  <a href="#" class="right">Linked-in</a>
  </div>
  
<div> class="row">
  /*<div class="side">*/
    <div class="main">
    <h2> About Me<h2>
    <br>
    <p> Stuff about me and why I can help people</p>
    <dis class="photo" style="height:200px;">Image
    <h5> What is in the photo</h5>
    <h3> another side of me</h3>
    <p>jkebkjfbejksb </p>
    <div class="photo" style ="height:100px;">Image</div>
 </div>
 

 <br>
  <div class="comment">...</div>
  


<div class="footer">
 <h2>Thanks for visiting! </h2>
  </dev>
  
  </dev>
  
  </body>

</html>


