<title>chaukighat-team</title>
  <style>
  
  body  {
    background-image: url("https://s-media-cache-ak0.pinimg.com/originals/4e/3a/ac/4e3aaccc8ee30b316642211e6d510364.jpg");
    background-color: #cccccc;
}

  
body {font-family: "Lato", sans-serif;}

ul.tab {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    border: 1px solid #33ff00;
    background-color: ;
	
}

/* Float the list items side by side */
ul.tab li {float: center;}

/* Style the links inside the list items */
ul.tab li a {
    display: inline-block;
    color: white;
    text-align: center;
    padding: 20px auto;
    text-decoration: none;
    transition: 0.3s;
    font-size: 20px;
    background-color: #0000ff;
    border: 3px;
    display: inline-block;
    font-size: 39.45px;
    margin: 3px 1px;

}

/* Change background color of links on hover */
ul.tab li a:hover {
    background-color: #33ff00;
}

/* Create an active/current tablink class */
ul.tab li a:focus, .active {
    background-color: #00ff00;
}

/* Style the tab content */
.tabcontent {
display: none;
    padding: auto;
    border: 1px solid #ccc;
    border-top: none;
}
</style>
  <body>


	<ul class="tab">
	  <button><li><a href="javascript:void(0)" class="tablinks" onclick="openCity(event, '1')"><b>HOME</b></a></li></button>
	  <button><li><a href="javascript:void(0)" class="tablinks" onclick="openCity(event, '2')"><b>PHOTOS</b></a></li></button>
	  <button><li><a href="javascript:void(0)" class="tablinks" onclick="openCity(event, '3')"><b>VIDEOS</b></a></li></button>
	  <button><li><a href="javascript:void(0)" class="tablinks" onclick="openCity(event, '4')"><b>MUSICS</b></a></li></button>
	  <button><li><a href="javascript:void(0)" class="tablinks" onclick="openCity(event, '5')"><b>FRIENDS</b></a></li></button>
	  <button><li><a href="javascript:void(0)" class="tablinks" onclick="openCity(event, '6')"><b>ABOUT</b></a></li></button>
	  
	  
	
	  

	<div id="1" class="tabcontent">
	  <h3>London</h3>
	  <p>London is the caivyivyiugugygg
		ugg5fv5
		gggyf8ugicutfifticitdt6
		uff7tfitfyififitvitf8
		
		ifdtditfyogugoyvivtiitftivi
		ufdutcticitctifyofiyviiyvyitvi
		kgfigvitvigviyvitvigvkgcurcuyofif
		
		
		
		
		ufdifiviyviyvyogivtivtivyifyofit7
		ufcutcitviyvyivovoyvyovoyvyooviyvi
		
		tcicigviyygylvovoyviygoygoygyogyogouv
		
		tifitftifiyvouvougyogoyvyofyoggygyg8y
		
		ticitfitvohvoboygoyviypital city of England.</p>
	</div>

	<div id="2" class="tabcontent">
	  <h3><html>
<title>W3.CSS</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://www.w3schools.com/lib/w3.css">
<style>
.mySlides {display:none;}
</style>
<body>

<h2 class="w3-center">Automatic Slideshow</h2>

<div class="w3-content w3-section" style="max-width:500px">
  <img class="mySlides" src="img_la.jpg" style="width:100%">
  <img class="mySlides" src="img_ny.jpg" style="width:100%">
  <img class="mySlides" src="img_chicago.jpg" style="width:100%">
</div>

<script>
var myIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 2000); // Change image every 2 seconds
}
</script>

</body></h3>
	  <p>Paris is the capital of France.</p> 
	</div>

	<div id="3" class="tabcontent">
	  <h3>Tokyo</h3>
	  <p>Tokyo is the capital of Japan.</p>
	</div>
	<div id="4" class="tabcontent">
	  <h3>London</h3>
	  <p>London is the capital city of England.</p>
	</div>

	<div id="5" class="tabcontent">
	  <h3>Paris</h3>
	  <p>Paris is the capital of France.</p> 
	</div>

	<div id="6" class="tabcontent">
	  <h3>Tokyo</h3>
	  <p>Tokyo is the capital of Japan.</p>
	</div></ul>

<script>
function openCity(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
}

</script>

  </body>
