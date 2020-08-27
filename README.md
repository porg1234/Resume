<!DOCTYPE html>
<html lang="en">
<head>
<title>Resume</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
  padding: 0;
}

/* Header/logo Title */
.header {
  padding: 140px;
  text-align: center;
  background: #87CEDA;
  color: white;
  width: 100%
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: #333;
  position: -webkit-sticky;
  position: sticky;
  top: 0;}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #87CEDA;
  color: white;
}
/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;  
  background-color: #f1f1f1;
  padding: 20px;
}

.side h2 {
  text-align: center;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%; 
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.photo {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

.polaroid {
  width: 80%;
  background-color: white;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  margin-bottom: 25px;
}

.border {
  text-align: center;
  padding: 10px 20px;
}

/* Footer */
.footer {
  padding: 30px;
  text-align: center;
  background: #87CEDA;
  color: white;
  }

@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}

</style>
</head>
<body>

<div class="header">
  <h1>Aradia Maser</h1>
  <p>Data Engineer</p>
</div>

<div class="navbar">
   <a href="#About">About</a>  
   <a href="#Education">Education</a>
   <a href="#Career">Career</a>
  <a href="#Volunteer">Volunteer</a>
  
  <a href="https://www.linkedin.com/in/aradia-maser/" class="right">Linkedin</a>
</div>

<div class="row">
<div class="side">
 
  <a name="About"><br> </a>   
     <br>
     <h2>About Me</h2>
    <h5>Self-Driven and People-Oriented </h5>
    <div class="polaroid">
    <img alt="5 Terre" style="width:100%">
     <div class="border">
       <p>Aradia Maser</p>
    </div>
    </div>    
    <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    <h3>More Text</h3>
    <p>Lorem ipsum dolor sit ame.</p>
    <div class="photo" style="height:60px;">Image</div><br>

  </div>
  
  <div class="main">
<br>
    <a name="Education"><br>  </a>
    <br>
    <h2>Education </h2>
    <h4>Bachelor Degree | Operation Information Management</h4>
    <h4>Minor | Information Technology</h4>   
       <h5> May 2018 | University of Massachusetts Amherst</h5>  
      <p>Operation Information Management provided in-depth look at Six Sigma, SAP and  Lean strategy. </p>
     <p>Information Technology provided exposure and experience with software to find results and to visualize data displays in an easy-to-read format using Spotfire Tableau,  Python, Java and SQL. </p>

     <div class="photo" style="height:200px;">Image</div>
     <a name="Career"><br></a> 
     <br>
     <h2>Career Journey</h2>  
     <br>
     <h4> DATA ENGINEER | Mayhew Steel Products, Incorporated</h4>
     <h5> Turners Falls, MA | June 2018 - February 2019</h5>
     <b>SQL, SQL Server Reporting Services (SSRS), Macola, Excel, Visual Basic for Applications (VBA), Crystal </b>
     <p> Communicating with management to convert documents (physical copies and Windows 7 servers) to SSRS reports, improving formulas and provide back up to cloud database. Solving inconstancies in multiple departments by using Vertical Lookup (VLOOKUP), manual verification, and SQL. Reducing product release time by using SQL clusters and VBA to mange packaging components.</p>     

     <br>
     <h4> ASSISTANT MANAGER | ANNIE’S BOOK STOP </h4>
     <h5> Worcester, MA | May 2015 - December 2016</h5>
     <b>Excel, Troubleshooting, Training </b>
     <p> Created an organized database of collectable books by using Excel while managing frontline customer interaction. Troubleshooting internet, Point of Sale (POS) terminal and land lines along with setting up IT hardware for viewing events. Increased summer sales to record breaking profits by implementing and training coworkers in lean strategy. Independently led team when manager was away; trained new hires in database management (1000+ books).</p>


     <br>
     <h4> English Teacher| Avalon: Langcon of the Republic of Korea</h4>
     <h5> Ilsandong-gu, Republic of Korea | March 2019 - March 2020</h5>
     <b> PowerPoint, Word, Public Speaking, Team Work </b>
     <p>Spearheaded new initiative with team to increase company revenue by 5% through optional hobby-inspired English classes (STEM, cooking, art, and gym) for existing students to invite their friends. Using PowerPoint and Word to design team-building games and interactive lesson plan materials to make an immersive learning experience within tight schedules and daily deadlines. Keeping composer and comforted students as COVID-19 swept the country.</p>

    <br>

    <div class="photo">
    <img scr="img/sp_langcon.jpg" alt="public speaking in Korea" style="width:100%"> 
    </div>
   
  <a name="Volunteer"><br></a> 
  <br>
     <h2>Volunteer</h2>
     <h4>Cultural Exchange Program (Clucom)</h4>
     <h5>Ilsandong-gu, Republic of Korea | March 2019 - March 2020</h5>
     <p>Taking action at a language exchange, as an American expatriate working on a cross-cultural team with South Koreans, I facilitated diverse and inclusive decision groups and recommended modern learning materials for adults learning English. </p>
   
    <br>
     <h4>International Programs Office (IPO) Buddy</h4>
     <h5>University of Massachusetts Amherst | January 2016 - May 2017</h5>
     <p>Providing company and peer guidance for first year international students. During outings, managing cultural conflicts that transpire with locals to keep a positive atmosphere.</p>

     <br>
     <h4> Phi Theta Kappa (PTK): Honor Society </h4>
     <h5> Worcester, MA | January 2013 - December 2015</h5>
     <p>Reaching out to new students familiarizing them with educational and financial resources on campus. Our mission to assist and support students in their goal of earning a degree in areas where students face adversity.</p>
  </div>
</div>


<div class="footer">
  <h2> Thank You For Visiting</h2>
</div>

</body>
</html>
