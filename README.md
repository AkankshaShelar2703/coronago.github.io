
<!-- saved from url=(0035)http://localhost/coronago/index.php -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title></title>

  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="./index.php_files/bootstrap.min.css">
  <link href="./index.php_files/css" rel="stylesheet">
  <link rel="stylesheet" href="./index.php_files/font-awesome.min.css" integrity="sha256-eZrrJcwDc/3uDhsdt61sL2oOBY362qM3lon1gyExkL0=" crossorigin="anonymous">
  <script src="./index.php_files/jquery.min.js.download"></script>
 <script src="./index.php_files/jquery.waypoints.min.js.download" integrity="sha256-jDnOKIOq2KNsQZTcBTEnsp76FnfMEttF6AV2DF2fFNE=" crossorigin="anonymous"></script>
 <script src="./index.php_files/jquery.counterup.min.js.download" integrity="sha256-JtQPj/3xub8oapVMaIijPNoM0DHoAtgh/gwFYuN5rik=" crossorigin="anonymous"></script>
<!-- Popper JS -->
  <script src="./index.php_files/popper.min.js.download"></script>
  <script src="./index.php_files/bootstrap.min.js.download"></script><style type="text/css">
html{scroll-behavior:smooth;}
*{margin:0; padding:0; box-sizing:border-box;font-family: 'Muli', sans-serif;}
.nav_style{background-color:#a29bfe!important;}
.nav_style a{color:white;}
.main_header{height:450px; width:100%;}
.rightside h1{font-size:3rem;}
.corona_rot img{animation: gocorona 3s linear infinite;}
@keyframes gocorona{0%{transform: rotate(0);}100%{transform: rotate(360deg);}}
.leftside img {animation : heartbeat 5s linear infinite;}
@keyframes heartbeat{0%{transform: scale(.75);}
20%{transform: scale(1);}
40%{transform: scale(.75);}
60%{transform: scale(1);}
80%{transform: scale(.75);}
100%{transform: scale(.75);}}

.corona_update{margin:0 0 30px 0;}
.corona_update h3{color: #ff7675;}
.corona_update h1{font-size:2rem; text-align:center;}


.sub_section{background-color:#D1F2EB;}
.container figcaption{color:darkblue;}

.footer_style{background-color:#a29bfe!important;}
.footer_style p{margin-bottom: 0!important;}

/*****************top scroll***********/
#myBtn{
	display:none;/* hidden by default */
	position:fixed;/* fixed/stick position */
	bottom:30px;/*place the button at the bottom of the page */
	right:40px; /* place the 30px from the right */
	Z-index:99; /* make sure it dors not over lap */
	border:none;
	outline:none;
	background-color:#00A8FF;
	color: white;
	cursor:pointer;
	padding:10 px;
	border-radius: 10px;
}
#myBtn:hover{background: #606060;}
	
}
</style></head>

<body>
<nav class="navbar navbar-expand-lg nav_style p-3">
  <a class="navbar-brand pl-5" href="http://localhost/coronago/index.php#">COVID-19</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto pr-5 text-capitalize">
      <li class="nav-item active">
        <a class="nav-link" href="http://localhost/coronago/index.php#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item active">
        <a class="nav-link" href="http://localhost/coronago/index.php#aboutid">about  </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link" href="http://localhost/coronago/index.php#sympid">symptoms </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link" href="http://localhost/coronago/index.php#preventid">prevention </a>
      </li>
	   <li class="nav-item active">
        <a class="nav-link" href="http://localhost/coronago/index.php#contactid">contact</a>
      </li>
    </ul>
   
  </div>
</nav>
 <div class="main_header">
	<div class="row w-100 h-100">
		<div class="col-lg-5 col-md-5 col-12 order-lg-1 order-2">
			<div class="leftside w-100 h-100 d-flex justify-content-center align-items-center">
				<img src="./index.php_files/earth.png" width="300" hight="300"></div></div>
        <div class="col-lg-7 col-md-7 col-12 order-lg-2 order-1">
            <div class="rightside w-100 h-100 d-flex justify-content-center align-items-center">
<h1> Let's stay safe &amp; fight together<br> against cor<span class="corona_rot"><img src="./index.php_files/corona.png" width="90" hight="90"></span>na virus</h1>
</div></div></div></div>
<!--/////////////////// corona latest update///////////////-->
<section class="corona_update">
<div class="mb-3">
<h3 class="text-uppercase text-center pb-3">covid-19 updates</h3></div>
<div class="d-flex justify-content-around align-items-center">
<div><h1 class="count">1,524,266</h1>
<p>Passengers screened at airport</p></div>
<div><h1 class="count">512</h1>
<p>Active COVID-19 cases*</p></div>
<div><h1 class="count">40</h1>
<p>Cursed/discharged cases</p></div>
<div><h1 class="count">9</h1>
<p>Death cases</p></div></div>

<!--/////////////////////about section////////////////////-->

<div class="container-fluid  sub_section pt-5 pb-5" id="aboutid">
<div class="section_header text-center mb-5 mt-4">
<h1>About COVID-19</h1>
</div>
<div class="row pt-5">
<div class="col-lg-5 col-md-6 col-12 ml-5">
<img src="./index.php_files/corona5.jpg" class="img-fluid" hight="500" width="500"></div>
<div class="col-lg-6 col-md-6 col-12 "><h2> What is COVID-19(corona-virus)</h2>
 <p>COVID-19 is a disease caused by the “novel corona virus”. Common symptoms are: Fever, Dry cough, Breathing difficulty
Some patients also have aches and pains, nasal congestion, runny nose, sore throat or diarrhoea About 80% of confirmed cases recover from the disease
without any serious complications. However, one out of every six people who gets COVID-19 can become seriously ill* and develop difficulty in breathing. In more
severe cases, infection can cause severe pneumonia and other complications which can be treated only at higher level facilities (District Hospitals and above). In a
few cases it may even cause death.</p></div></div></div>

<div class="container-fluid  sub_section  pt-2 pb-5" id="aboutid">
<div class="row pt-2">
<div class="col-lg-5 col-md-6 col-12 ml-5">
<img src="./index.php_files/corona4.jpg" class="img-fluid" hight="500" width="500"></div>
<div class="col-lg-6 col-md-6 col-12 "><h2> How does COVID-19 spread</h2>
<p>COVID-19 spreads mainly by droplets produced
as a result of coughing or sneezing of a COVID-19
infected person. This can happen in two ways:<br>1. Direct close contact: one can get the infection by being in close contact with COVID-19
patients (within one Metre of the infected person), especially if they do not cover their face when coughing or sneezing.<br>
2.Indirect contact: the droplets survive on surfaces and clothes for many days. Therefore,touching any such infected surface or cloth
and then touching one’s mouth, nose or eyes can transmit the disease. The incubation period of COVID 19 (time between
getting the infection and showing symptoms) is 1 to 14 days Some people with the infection, but without any
serious symptoms can also spread the disease.</p> </div></div></div>

<!--////////////////////corona symptoms/////////////-->
<div class="container-fluid   pt-5 pb-5" id="sympid">
<div class="section_header text-center mb-5 mt-4">
<h1>Coronavirus Symptoms</h1></div>
<div class="container">
	<div class="row">
		<div class="col-lg-4 col-md-4 col-12 mt-5 pt-2">
			<figure class="text-center">
			<img src="./index.php_files/cough2.png" class="img-fluid" width="120" height="120">
			<figcaption>PERSISTENT<br> COUGH</figcaption>
			</figure>
			</div>
		<div class="col-lg-4 col-md-4 col-12 mt-5 pb-3">
			<figure class="text-center">
			<img src="./index.php_files/fever3.png" class="img-fluid" width="120" height="120">
			<figcaption>FEVER</figcaption>
			</figure>
			</div>	
		<div class="col-lg-4 col-md-4 col-12 mt-3 ">
			<figure class="text-center">
			<img src="./index.php_files/breath.png" class="img-fluid" width="120" height="120">
			<figcaption>DIFFICULTY<br> BREATHING</figcaption>
			</figure>
			</div>	
		<div class="col-lg-4 col-md-4 col-12 mt-5">
			<figure class="text-center">
			<img src="./index.php_files/3.png" class="img-fluid" width="120" height="120">
			<figcaption>RUNNY NOSE</figcaption>
			</figure>
			</div>	
		<div class="col-lg-4 col-md-4 col-12 mt-5">
			<figure class="text-center">
			<img src="./index.php_files/throat.png" class="img-fluid" width="120" height="120">
			<figcaption>SORE THROAT</figcaption>
			</figure>
			</div>
        <div class="col-lg-4 col-md-4 col-12 mt-5">
			<figure class="text-center">
			<img src="./index.php_files/tired.png" class="img-fluid" width="120" height="120">
			<figcaption>TIREDNESS</figcaption>
			</figure>
			</div>			
	</div>
  </div>
</div>

<!--////////////////////prevention against corona/////////////-->
<div class="container-fluid sub_section  pt-5 pb-5" id="preventid">
<div class="section_header text-center mb-5 mt-4">
<h1>6 Steps To Prevent COVID-19</h1></div>
<div class="container">
	<div class="row">
		<div class="col-lg-4 col-md-4 col-12 mt-5">
			<div class="row">
				<div class="col-lg-4 col-md-4 col-12">
				<figure class="text-center">
				<img src="./index.php_files/handwash7.png" class="img-fluid">
			</figure>
			</div>
			<div class="col-lg-8 col-md-8 col-12">
			<p>Wash with soap and water for at least 20 seconds. You can also use hand sanitizer that contains 
			at least 60% alcohol.</p></div>
		</div>
</div>		

<div class="col-lg-4 col-md-4 col-12 mt-5">
			<div class="row">
				<div class="col-lg-4 col-md-4 col-12">
				<figure class="text-center">
				<img src="./index.php_files/distance5.png" class="img-fluid">
			</figure>
			</div>
			<div class="col-lg-8 col-md-8 col-12">
			<p>Put distance between yourself and others Put distance between yourself and other people if COVID-19 is spreading in your community.
                 Avoid close contact with people who are sick.</p></div>
		</div>
</div>		
<div class="col-lg-4 col-md-4 col-12 mt-5">
			<div class="row">
				<div class="col-lg-4 col-md-4 col-12">
				<figure class="text-center">
				<img src="./index.php_files/stayhome.png" class="img-fluid">
			</figure>
			</div>
			<div class="col-lg-8 col-md-8 col-12">
			<p>Stay home if you’re sick Don’t leave home except to get medical care.</p></div>
		</div>
</div>		
<div class="col-lg-4 col-md-4 col-12 mt-5">
			<div class="row">
				<div class="col-lg-4 col-md-4 col-12">
				<figure class="text-center">
				<img src="./index.php_files/covermouth.png" class="img-fluid">
			</figure>
			</div>
			<div class="col-lg-8 col-md-8 col-12">
			<p>Cover coughs and sneezes Cover with a tissue or the inside of your elbow. Throw tissues in the trash and clean your hands.</p></div>
		</div>
</div>		
<div class="col-lg-4 col-md-4 col-12 mt-5">
			<div class="row">
				<div class="col-lg-4 col-md-4 col-12">
				<figure class="text-center">
				<img src="./index.php_files/onlywearfacemask2.png" class="img-fluid">
			</figure>
			</div>
			<div class="col-lg-8 col-md-8 col-12">
			<p>Only wear a face mask if you’re sick or caring for someone who is You should wear a face mask when you are around other people and before you enter a healthcare provider’s office. If you are not sick, 
 you do not need to wear a face mask unless you are caring for someone who is sick.</p></div>
		</div>
</div>		
<div class="col-lg-4 col-md-4 col-12 mt-5">
			<div class="row">
				<div class="col-lg-4 col-md-4 col-12">
				<figure class="text-center">
				<img src="./index.php_files/cleansurface.jpg" class="img-fluid">
			</figure>
			</div>
			<div class="col-lg-8 col-md-8 col-12">
			<p>Clean and disinfect frequently touched surfaces These are things like countertops, doorknobs, light switches, phones and keyboards.</p></div>
		</div>
</div>	</div></div></div>

<!--////////////////////contact us form/////////////-->
<div class="container-fluid  pt-5 pb-5" id="contactid">
<div class="section_header text-center mb-5 mt-4">
<h1>Contact us</h1></div>
<div class="container">
	<div class="row">
		<div class="col-lg-8 offset-lg-2  col-12 ">
		<form action="http://localhost/coronago/index.php" method="POST">
		<div class="form-group">
    <label>Username</label>
    <input type="text" class="form-control" name="username" placeholder="name" autocomplete="off" required="">
  </div>
  
  <div class="form-group">
    <label>Email </label>
    <input type="email" class="form-control" name="email" placeholder="name@example.com" required="" autocomplete="off">
  </div>
  
	<div class="form-group">
    <label>Mobile</label>
    <input type="number" class="form-control" name="mobile" placeholder="mobile" autocomplete="off" required="">
  </div>
  <div class="form-group">
    <label>Select Symptoms</label><br>
  
  <div class="custom-control custom-checkbox custom-control-inline text-capitalize pt-4 ">
  <input type="checkbox" class="custom-control-input" id="customcheckbox1" name="coronasym[]" value="cold">
  <label class="custom-control-label" for="customcheckbox1">Cold</label>
  </div>
  
  <div class="custom-control custom-checkbox custom-control-inline text-capitalize">
  <input type="checkbox" class="custom-control-input" id="customcheckbox2" name="coronasym[]" value="fever">
  <label class="custom-control-label" for="customcheckbox2">Fever</label>
  </div>
  
  <div class="custom-control custom-checkbox custom-control-inline text-capitalize">
  <input type="checkbox" class="custom-control-input" id="customcheckbox3" name="coronasym[]" value="breath">
  <label class="custom-control-label" for="customcheckbox3">Difficulty in breath</label>
  </div>
  
  <div class="custom-control custom-checkbox custom-control-inline text-capitalize">
  <input type="checkbox" class="custom-control-input" id="customcheckbox4" name="coronasym[]" value="tired">
  <label class="custom-control-label" for="customcheckbox4">Feeling weak</label>
  </div>
  </div>
  
  <div class="form-group pt-4">
    <label for="exampleFormControlTextarea1 ">Describe how you are feeling</label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" name="msg"></textarea>
  </div>
   <button type="submit" class="btn btn-primary mb-2" name="submit">Submit</button>
</form>
		
		</div>
	</div>	
</div>
</div>
<!--/////////////////top cursor///////////////-->
<div class="container scrolltop float-right pr-5">
<i class="fa fa-arrow-up" onclick="topFunction()" id="myBtn" style="display: none;"></i>
</div>

<!--//////////////////footer////////////-->
<footer class="mt-5">
<div class="footer_style text-white text-center container-fluid">
<p>copyright by LearnMore</p>
</div></footer>
<script type="text/javascript">

$('.count').counterUp({
	delay:10,
	time:3000
})
mybutton = document.getElementById("myBtn");
//when the user scrolls down 20px from the top of the document,show the button
window.onscroll= function(){scrollFunction()};
function scrollFunction(){
	if(document.body.scrollTop > 100 || document.documentElement.scrollTop > 100)
	{ mybutton.style.display= "block";
	}else{
		mybutton.style.display="none";
	}
}
// when the user clicks on the button, scroll to the top of the document
function topFunction(){
	document.body.scrollTop=0;//for safari
	document.documentElement.scrollTop=0;//for chrome,firefox,IE and opera
}
</script>









</section></body></html>
