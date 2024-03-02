
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Moonlight WiFi</title>
</head>
<header>
<div class='glow'>Welcome to <span class="M">Moonlight</span> WiFi</div>
</header>
<body>
  
    
<h2 class="BR">Browsing rate: @10bob per hour</h2>

<section class="lipa">
<section class="top">
    <h2 class="formtitle">Lipa na</h2></section>
    <section class="image">
      <img src="1200px-M-PESA_LOGO-01.svg.png" class="mr-3" height="75" />
</section>
</section>
  

  <main> 
    

<form id="paymentForm" method="post" action="./stk_initiate.php">
  <div class='glow'>
  <label for="phoneNumber">Mobile Number:</label>
<input type="tel" id="phoneNumber" name="phoneNumber" maxlength="10" required ><br><br></div>
  
  <div class="inp2">
  <div class='glow'>
  <label for="amount">Amount (10 and above):</label>
<input type="number" id="amount" name="amount" minlength="10" required><br><br></div>
  </div>
  
  <button type="submit" class="custom-btn btn-13">Pay</button>
</form>
    
  </main>
  <h2 class="bb"> About Us</h2>
  <section class="boutt">
    <p id="boutus">
      We are invested in providing Internet solutions ,therefore, we give you the best for the cheapest rates.
    </p>
  </section>
  
  <h2 class="bb"> Contact Us</h2>
  <section class="boutt">
    <p id="boutus">
      For inquiries kindly reach us through,
      moonlightconnections@gmail.com
        or
     Whatsapp us through +254790712521. 
    </p>

  </section>
  <footer>
      © moonlight connections 2024
    </footer>
  
</body>
<style>
body{
  font-family:system-ui;
  height: flex;
  margin-top:0;
  background-image: url("https://storage.needpix.com/rsynced_images/planet-1519089_1280.jpg");
  color:white;
  display:grid;
  place-items:center;
  font-size:clamp(1rem,3vw,3rem);
  overflow: auto;
}

.glow{
  padding:clamp(1.5rem,3vw,5rem);
  border:1px solid white;
  border-radius:1rem;
  position:relative;
  display: fixed;
  margin: 30px auto;
  font-weight: bold;
  background: linear-gradient(
    to right,
    #000,
    #3aada8,
  #000
  
   
  );
  
}

:root{
  --azul:#000000;
  --violeta: #3aada8;
  --blanco: white;
  --deg:0deg;
    
}
@property --deg{
  syntax:'<angle>';
  inherits:false;
  initial-value:0deg;
}
.glow::after{
  
  content:'';
  border-radius:inherit;
  inset:-0.5rem;
  background-color:Red;
  position:absolute;
  z-index:-1;
  background:conic-gradient( from var(--deg),var(--azul),var(--violeta),var(--azul))
  animation:girar s linear infinite
}

.glow::before{
  filter:blur(40px);
  --deg:0deg;
  content:'';
  border-radius:inherit;
  inset:-1.0rem;
  background-color:Red;
  position:absolute;
  z-index:-1;
  background:conic-gradient( from var(--deg),var(--azul),var(--violeta),var(--azul))
  animation:girar 3s linear infinite
}


@keyframes girar {
  from{
    --deg:0deg;
  }
  
  to{
    --deg:360deg;
  }
}

#form stuff



form {
  padding: 50px 80px 80px;
  flex: 1;
  display: inline-block;
  margin-top: 90px;
}

#paymentForm {
  top: 80px;
}

.creator {
  text-align: center;
}

.creator span {
  color: red;
}

form :is(h2, a) {
  text-align: center;
  margin: 25px auto;
  color: #fff;
}

input:not([type="checkbox"], [type="submit"]) {
  width: 80%;
  border: 2px #000;
  border-radius: 10px;
  height: 50px;
  margin: 10px auto;
  padding-left: 60px;
  color: #fff;
  background-color: rgba(150, 150, 150, 0.5);
}

input::placeholder {
  color: #fff;
}

.inp-1 {
  width: 100%;
  position: relative;
  font-size: 1.1rem;
}
.far,
.fas {
  position: absolute;
  top: 31px;
  left: 20px;
}

.inp-2 {
  margin: 10px auto 20px;
}

.inp--checkbox {
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}

input[type="checkbox"] {
  /* Double-sized Checkboxes */
  -ms-transform: scale(1.3); /* IE */
  -moz-transform: scale(1.3); /* FF */
  -webkit-transform: scale(1.3); /* Safari and Chrome */
  -o-transform: scale(1.3); /* Opera */
  transform: scale(1.3);
  margin-right: 5px;
}

h2 {
  font-size: 25px;
  margin-top: 3rem;
  border: none;
}

label {
  font-size: 0.8rem;
}

hr {
  margin: 35px auto;
  width: 95%;
}

a {
  /* width: 100%; */
  text-align: center;
  display: block;
}

button[type="submit"] {
  display: block;
  width: 70%;
  border-radius: 50px;
  height: 50px;
  margin: 25px auto;
  border: none;
  color: #fff;
  font-weight: bold;
  background: #bbd2c5; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #536976,
    #bbd2c5
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #536976,
    #bbd2c5
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

  border: 2px #000;
  cursor: pointer;
  transition: 500ms;
  overflow: hidden;
  z-index: 1;
}
input {
  outline: none;
  transition: 0.5s;
}
input:focus {
  box-shadow: 0 0 10px rgba(81, 203, 238, 1);
  /* padding: 3px 0px 3px 3px;
  margin: 5px 1px 3px 0px; */
  border: 1px solid rgba(81, 203, 238, 1);
}


.btn-13:after {
  position: absolute;
  content: "";
  width: 100%;
  height: 0;
  bottom: 0;
  left: 0;
  z-index: -1;
  border-radius: 5px;
  background: #8a2387; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #f27121,
    #e94057,
    #8a2387
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #f27121,
    #e94057,
    #8a2387
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

  transition: all 0.5s ease;
}

.btn-13:hover:after {
  top: 0;
  height: 100%;
}
.btn-13:active {
  top: 2px;
}

.custom-btn {
  width: 90px;
  height: 40px;
  color: #fff;
  border-radius: 5px;
  padding: 10px 25px;
  font-weight: 900;
  font-size: 1.15rem;
  background: transparent;
  cursor: pointer;
  transition: all 0.3s ease;
  position: relative;
  display: inline-block;
  outline: none;
}
#main stuff

main {
  top: 2rem;
}
.formtitle {
text-align: 
border-bottom: none;
color: black;
text-align: center;
}

Header {
text-align: center;
font-weight: bold;
font-size: 24px;
border-bottom: none;
bottom: 3vh;
}

.boutt {
  color: #white;
  font-weight: bold;
  margin: 18px auto;
  font-style: italic;
  background: linear-gradient(
    to right,
    #000,
    #3aada8,
    #000
  );
  background-opacity: 40%;
  text-opacity: 100%;
  padding: 1rem;
  border-radius: 25px;
}
.bb {
  color: white;
  text-align: center;
  top: 2rem;
  font-size: 35px;
  text-opacity: 70%;
  background: transparent;
}
.BR {
text-align: center;
color:lightgreen;
}
.kindly {
text-align: center;
font-size: 20px;
colour: lightgreen;
}



.M {
  color: Black;
  }

.lipa {
background: #fff;
display: relative;
border-radius: 20px;
width: 50%;
}





  .image {
  items-align: center;
  
  }
  
  footer {
  text-align: center;
  }
  
</style>

<script>
document.getElementById("paymentForm").addEventListener("submit", function(event) {
  event.preventDefault();
  
  var phoneNumber = document.getElementById("phoneNumber").value;
  var amount = document.getElementById("amount").value;

  // Check if mobile number has 10 characters
  if (phoneNumber.length !== 10) {
    alert("Mobile number must be 10 digits long.");
    return;
  }

  // Check if amount is 10 or above
  if (amount < 10) {
    alert("Amount must be 10 or above.");
    return;
  }

  // Proceed with form submission if requirements are met
  this.submit();
});
</script>

