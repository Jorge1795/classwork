<!DOCTYPE html>
	<html>
		<head>
    <title>Web Design </title>
      <link rel="stylesheet" href="styles.css">
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css" rel="stylesheet" /
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js" rel="text/javascript" />p
    <link href="app.css" rel="stylesheet" />
     <script src="https://code.jquery.com/jquery-1.10.2.js" type="application/javascript"></script>
     <script>
        function onLoad() {
    document.getElementById("timestamp").innerHTML = Date();
}
  function checkNumber() {
    var theNumber, theMessage;

    // Get the value of the input field with id="numb"
    theNumber = $('#smallnumber').val();

    // If x is Not a Number or less than one or greater than 10
    if (isNaN(theNumber) || theNumber < 1 || theNumber > 10) {
        theMessage = "Number was expected to be between 1 and 10";
    } else {
        theMessage = "Number is Good";
    }
    $('#numberMessage').text(theMessage);
}

function getAPIBadge() {
    var ctcAPI = "http://ChooseToCodeAPI.azurewebsites.net/api/values/";
    $.post( ctcAPI, { 
        SchoolName:"YourSchoolNameHere", 
        ZipCode: "YourZipCodeHere", 
        Level:"Beginner"
    }).done(function( data ) {
        $("#badge").html(data);s
    });
}

    </script>
   
   
    <style>
    
    </style>
    
</head>
      <body onload="onLoad()">
			  
        <header class="container-fluid">
					<h1 id="hover-title">Web Designer</h1>
				</header>
    
            <nav class="container-fluid">
    <ul class="nav navbar-inverse navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li><a href="https://www.google.com/">Google</a></li>
        <li><a href="contact index.html">Contact</a></li>
        <li><a href="home index.html">Resume</a></li>
        <li><a href="artifacts index.html">Artifacts</a></li>
        <li><a href="tags index.html">Tags</a></li>
        
        
    </ul>
</nav>
    
       <div class="container-fluid">
        <div class="row">
   
   <section class="col-sm-6 col-sm-push-3">
     
     <div id="info2">
     
     <div class="row">
      <article>
    <center>
     
     <h3 id="table">Table of contents</h3>
    <a href="#objective1">What is a Web Designer</a> |
    <a href="#skills1">Education Degree requirements</a> |
    <a href="#education1">Hours of work</a> |<br>
    <a href="#work1">What Web Designers do</a> |
    <a href="#education2">How to become good at it</a>
    </center>
    
     
    
    <h2 id="#objective1"> What is a Web Designer?</h2>
    <div class="col-sm-3">
       
    </div>
    <div class="col-sm-9">
        <p>A web designer is someone who is both creative ,someone who builds and rebuilds websites.</p>

       
 
                   
    </div>
</article>
      <article>
<h2 id="skills1">Education Degree requirements </h2>
 <div class="col-sm-3">

</div>
<div class="col-sm-9">
<p>Depending on the employer, Web Designers education degree requirements range
     from an associates degree to a masters degree. An associates degree might
      be sufficient for some entry level positions, but a bachelors degree is 
      required for most Web Designer jobs, while more complex jobs might
       require a masters degree. Employers place a high value on relevant experience, 
       so it is recommended that you participate in internships while pursuing your degree.<br></p>
       
       <p>Now if you're really good at programming then I would recommend you to really put your 
       full time into learning how to code and getting different certifications in that field,
        which would be much better than going to a four
        year university and spending all of your money and then graduate and still not have a job in that field
</p>
     </div>
     </article>
     <article>
<h2 id="education1">Hours of work</h2>
 <div class="col-sm-3">

 
</div>
 <div class="col-sm-9">
     <p>Web Designers spend 4-6 hours on a computer coding the website making sure every thing is correct
         (one mistak can mess everything up).
         But before getting on the computer to code they must first design the website with pencil and paper. 
</p>
     </div>
     </article>
  </div>

  
   <article> 
     <h2 id="work1">What Web Designers do</h2>
     <div class="col-sm-3">
         </div>
         <div class="col-sm-9">
             <P>A web designer's main job is to design web pages. There is a lot to 
            consider in the design of websites which may not be immediately apparent
             when looking at a webpage for the first time.</p>
             
             <p>For example, a website aimed at children needs to hold their attention,
                  and might use bright colours and an easy-to-read font, with a lot of
                   images and not too much text. This would make it fun, attractive and 
                   easy to understand. The layout and structure must be easy to follow</p>
   
             </div>
  </article>
   
     <article>
<h2 id="education2">How to become good at it</h2>
 <div class="col-sm-3">

 
</div>
 <div class="col-sm-9">
<p>You need the following... </p>
   <ul>
      <strong><li>Communication Skills</li></strong> 
      <ol>
          <li>To be able to cimmunicate with your client.</li>
          <li>Small disputes can be resolved easily if you are good at communicating.</li>
      </ol>
      <strong><li>Evaluate Your Own Work and Get Feedback</li></strong> 
      <ol>
          <li>Learn from your mistakes.</li>
          <li>Make those negative comments into something <strong>positive</strong> .</li>
      </ol>
      
    </ul>
     </div>
     </article>
  </div>

   
   </section>
   
   <aside class="col-sm-3 col-sm-pull-6">
        <div id="ref">
       <h2 id="whattheydo"><a href="w index.html">Four Languages Web Designers have to know</a></h2>
        <ul>
            <li>HTML/CSS</li>
            <li>Ruby</li>
            <li>Python</li>
            <li>PHP</li>
            <li>JAVASCRIPT</li>
            
            </ul>
      </div>
    </aside>
   
 
            
        
<aside class="col-sm-3">
<div id="ref">
<h2>Degrees/certifications could that you can get</h2>
    <ul>
       <li>AS in Web programming</li>
       <li>BS in Computer Programming</li>
       <li>Certification on Information Technology</li>
       <li>Certification Javascript</li>
       <li>Certification in iphone app development</li>
       <li>Certification intro to software design</li>
       </ul>
    </div>  
</aside>		



     	
               
            <div class="col-sm-1">
                <p id="badge"></p>
            </div>
        </div>
    </div>
				</div>
				
		<footer class="container-fluid">
      copyright 2016
      <p id="timestamp"></p>
      </footer>		
				
      
      </body>
      </html>
