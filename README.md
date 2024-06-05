# keripik-lumer-coklat-ragip-te
<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Amatic+SC">
<style>
body, html {height: 100%}
body,h1,h2,h3,h4,h5,h6 {font-family: "Amatic SC", sans-serif}
.menu {display: none}
.bgimg {
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("9332092_108616c9-2b40-4e46-b8e8-3f860e684f1c_1080_1080.jpg");
  min-height: 90%;
}
</style>
</head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top w3-hide-small">
  <div class="w3-bar w3-xlarge w3-black w3-opacity w3-hover-opacity-off" id="myNavbar">
    <a href="#" class="w3-bar-item w3-button">HOME</a>
    <a href="#menu" class="w3-bar-item w3-button">MENU</a>
    <a href="#about" class="w3-bar-item w3-button">ABOUT</a>
    <a href="#myMap" class="w3-bar-item w3-button">CONTACT</a>
  </div>
</div>
  
<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-padding">
    <span class="w3-tag w3-xlarge">Open from 10am to 12pm</span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white w3-hide-small" style="font-size:100px">thin<br>CRUST PIZZA</span>
    <span class="w3-text-white w3-hide-large w3-hide-medium" style="font-size:60px"><b>thin<br>CRUST PIZZA</b></span>
    <p><a href="#menu" class="w3-button w3-xxlarge w3-black">Let me see the menu</a></p>
  </div>
</header>

<!-- Menu Container -->
<div class="w3-container w3-black w3-padding-64 w3-xxlarge" id="menu">
  <div class="w3-content">
  
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">THE MENU</h1>
    <div class="w3-row w3-center w3-border w3-border-dark-grey">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Pizza');" id="myLink">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">Pizza</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Pasta');">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">ABOUT</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Starter');">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">CONTACT</div>
      </a>
    </div>

    <div id="Pizza" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>keripik pisang coklat </b> <span class="w3-right w3-tag w3-dark-grey w3-round">RP10.000</span></h1>
      <p class="w3-text-grey">KERIPIK RASA COKLAT </p>
      <hr>
   
      <h1><b>keripik pisang match</b> <span class="w3-right w3-tag w3-dark-grey w3-round">RP13.000</span></h1>
      <p class="w3-text-grey">KERIPIK RASA MATCHA </p>
      <hr>
      
      

      <h1><b>keripik pisang tiramisu</b> <span class="w3-right w3-tag w3-dark-grey w3-round">RP15.000</span></h1>
      <p class="w3-text-grey">KERIPIK RASA TIRAMISU</p>
      <hr>

      <h1><b>keripik pisang taro </b> <span class="w3-tag w3-red w3-round">Hot!</span><span class="w3-right w3-tag w3-dark-grey w3-round">RP20.000</span></h1>
      <p class="w3-text-grey">KERIPIK RASA TARO</p>
      <hr>
    <div id="Pasta" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Lasagna</b> <span class="w3-tag w3-grey w3-round">Popular</span> <span class="w3-right w3-tag w3-dark-grey w3-round">$13.50</span></h1>
      <p class="w3-text-grey">Special sauce, mozzarella, parmesan, ground beef</p>
      <hr>
   
      <h1><b>Ravioli</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$14.50</span></h1>
      <p class="w3-text-grey">Ravioli filled with cheese</p>
      <hr>
      
      <h1><b>Spaghetti Classica</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$11.00</span></h1>
      <p class="w3-text-grey">Fresh tomatoes, onions, ground beef</p>
      <hr>

      <h1><b>Seafood pasta</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$25.50</span></h1>
      <p class="w3-text-grey">Salmon, shrimp, lobster, garlic</p>
    </div>


    <div id="Starter" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Today's Soup</b> <span class="w3-tag w3-grey w3-round">Seasonal</span><span class="w3-right w3-tag w3-dark-grey w3-round">$5.50</span></h1>
      <p class="w3-text-grey">Ask the waiter</p>
      <hr>
   
      <h1><b>Bruschetta</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$8.50</span></h1>
      <p class="w3-text-grey">Bread with pesto, tomatoes, onion, garlic</p>
      <hr>
      
      <h1><b>Garlic bread</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$9.50</span></h1>
      <p class="w3-text-grey">Grilled ciabatta, garlic butter, onions</p>
      <hr>
      
      <h1><b>Tomozzarella</b> <span class="w3-right w3-tag w3-dark-grey w3-round">$10.50</span></h1>
      <p class="w3-text-grey">Tomatoes and mozzarella</p>
    </div><br>

  </div>
</div>

<!-- About Container -->
<div class="w3-container w3-padding-64 w3-red w3-grayscale w3-xlarge" id="about">
  <div class="w3-content">
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">About</h1>
    <p>The Pizza Restaurant was founded in blabla by Mr. Italiano in lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    <p><strong>The Chef?</strong> Mr. Italiano himself
    <p>We are proud of our interiors.</p>
    <img src="images.jfif" style="width:100%" class="w3-margin-top w3-margin-bottom" alt="Restaurant">
    <h1><b>Opening Hours</b></h1>
    
    <div class="w3-row">
      <div class="w3-col s6">
        <p>minggu libur</p>
        <p>senin 10.00 - 24.00</p>
        <p>selasa 10:00 - 24:00</p>
      </div>
      <div class="w3-col s6">
        <p>rabu 10:00 - 12:00</p>
        <p>kamis 10:00 - 23:00</p>
        <p>Sunday Closed</p>
      </div>
    </div>
    
  </div>
</div>

<!-- Image of location/map -->
<img src="/w3images/map.jpg" class="w3-image w3-greyscale" style="width:100%;" id="myMap">

<!-- Contact -->
<div class="w3-container w3-padding-64 w3-blue-grey w3-grayscale-min w3-xlarge">
  <div class="w3-content">
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">Contact</h1>
    <p>KALAU YANG MAU PESAN TELP ATAU WA 082215730019</p>
    <p><span class="w3-tag">FYI!</span> menawarkan katering layanan lengkap untuk acara apa pun, besar atau kecil. Kami memahami kebutuhan Anda dan kami akan menyediakan makanan untuk memenuhi kriteria terbesar, baik tampilan maupun rasa.</p>
    <p class="w3-xxlarge"><strong>Reserve</strong> a table, ask for today's special or just send us a message:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
      <p><button class="w3-button w3-light-grey w3-block" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-48 w3-xxlarge">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
     tablinks[i].className = tablinks[i].className.replace(" w3-red", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-red";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
