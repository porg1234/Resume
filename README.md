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
  padding: 80px;
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


.row {
 display: -ms-flexbox;
 display: flex;
 -ms-flex-wrap: wrap;
 flex-wrap: wrap;
} 


.side{
 -ms- flex: 30%;
 flex: 30%;
 background-color: #f1f1f1;
 padding: 20px;
}

/*Main column*/ 
.main {
 -ms-flex:70%;
 flex:70%;
 background-color: white;
 padding: 20px
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
}

@media screen and (max-width: 700px) {
.row{
  flex-direction: column;
  }
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
  <h1> Simple professional </h1>
  <p> Into the unknown</p>
</div>     
     
 <div class="navbar">
    <a href="#">Resume</a>
    <a href="#">Education</a>
    <a href="#">Projects</a>
    <a href="#" class="right">LinkedIn</a>
   </div>
    

<div class="row">
   <div class="side">
            <h2> About Me</h2>
            <div class="photo" style="height:200px;">Image</div> 
            <p> image description </p>
      </div>
      <div class="main">
            <h2> Education<h2>
                  <h3> UMASS</h3>
                 <div class="photo" style="height:200px;">Image</div>
       <br>
    <p> The joys of college</p>         
  <div class="photo" style="height:200px;">Image</div>    
    <h3> another side of me</h3>
    <p>jkebkjfbejksb </p>
          <p> ... </p>
      

<div class="footer">
 <h2>Thanks for visiting! </h2>
</div>

