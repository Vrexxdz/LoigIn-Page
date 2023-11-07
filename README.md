# LoigIn-Page
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <script src="main.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>LogIn Page</title>
</head>
<body>
    <div class="Everything">

       <div class="IMG" >
       <img src="icons8-benutzer-96.png">
       </div>
        

        <div>
            <h2>Welcome Back</h2>
        </div>

        <div>
            <form>
                <label for="fname"></label><br>
                <input type="text" id="fname" name="fname" placeholder="Email" ><br>
                <label for="lname"></label><br>
                <input type="password" id="lname" name="lname" placeholder="Password">
                <div>
                    <button>LOGIN</button>
                </div>
              </form>
        </div>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Barlow:ital@1&family=Inter:wght@300;400&family=Lato:ital@1&family=Onest:wght@300;400;500&family=Open+Sans:wght@400;800&family=Pixelify+Sans:wght@400;500;600&family=Poppins&family=Raleway:wght@300&family=Roboto:ital,wght@0,300;0,400;0,500;1,300;1,400&display=swap" rel="stylesheet">
    </div>

      <div class="AA" >
        <input type="checkbox">
        <a href="#">Remember Me</a>
        <a href="#">Forgot Password?</a>
      </div>
      

    <footer class="Link" >
    <a href="Impressum.html" class="Link1" target="_blank" >Impressum</a>
    <br>
    <a href="#" class="Link1" target="_blank" >Datenschutzerklärung</a>
    </footer>

<div class="Icons">
    <a href="https://www.instagram.com/djamal.049/" target="_blank"><i class="fa-brands fa-instagram fa-beat"></i></a>
    <a href="https://github.com/Vrexxdz" target="_blank" ><i class="fa-brands fa-github fa-beat"></i></a>
    <a href="https://www.linkedin.com/in/djamal-moumouni-bb5a15252/" target="_blank" ></i><i class="fa-brands fa-linkedin fa-beat"></i></a>
    <a href="https://linktr.ee/vrexdz" target="_blank" ><i class="fa-solid fa-tree fa-beat"></i></a>
</div>
</body>
</html>

body{
    text-align: center;
    font-family: 'Onest', sans-serif;
    background: rgb(21,23,23);
    background: linear-gradient(90deg, #304352 0%, #d7d2cc 100%);
}

.Everything{
    border: 2px solid rgb(15, 15, 15);
    margin-top: 210px;
    border-radius: 50px;
    padding: 160px;
    background-color: rgb(194, 190, 190);
    margin-left: 650px;
    margin-right: 650px;
    font-weight: bold;
}

button{
    border-radius: 30px;
    padding: 13px;
    color: white;
    position: absolute;
    left: 820px;
    right: 820px;
    top: 530px;
    font-size: 20px;
    cursor: pointer;
    z-index: 0;
    overflow: hidden;
    transition: all 0.3s cubic-bezier(0.02, 0.01, 0.47, 1);
    position: absolute;
    top: 535px;
    background: rgb(21,23,23);
    background: linear-gradient(90deg, #304352 0%, #474746 100%);
}
  
  button:hover {
    animation: rotate624 0.7s ease-in-out both;
  }
  
  button:hover span {
    animation: storm1261 0.7s ease-in-out both;
    animation-delay: 0.06s;
  }
  
  @keyframes rotate624 {
    0% {
      transform: rotate(0deg) translate3d(0, 0, 0);
    }
  
    25% {
      transform: rotate(3deg) translate3d(0, 0, 0);
    }
  
    50% {
      transform: rotate(-3deg) translate3d(0, 0, 0);
    }
  
    75% {
      transform: rotate(1deg) translate3d(0, 0, 0);
    }
  
    100% {
      transform: rotate(0deg) translate3d(0, 0, 0);
    }
  }
  
  @keyframes storm1261 {
    0% {
      transform: translate3d(0, 0, 0) translateZ(0);
    }
  
    25% {
      transform: translate3d(4px, 0, 0) translateZ(0);
    }
  
    50% {
      transform: translate3d(-3px, 0, 0) translateZ(0);
    }
  
    75% {
      transform: translate3d(2px, 0, 0) translateZ(0);
    }
  
    100% {
      transform: translate3d(0, 0, 0) translateZ(0);
    }
  }

a{
    color: black;
    text-decoration: none;
    font-size: 20px;
    position: relative;
    bottom: 15px;
    padding: 5px;
}

a:hover{
    text-decoration: underline;
}

input[type=text]{
    padding: 15px;
    background: rgb(21,23,23);
    background: linear-gradient(90deg, #304352 0%, #474746 100%);
    color: white;
    margin-bottom: 7px;
}

input[type=password]{
  padding: 15px;
  background: rgb(21,23,23);
  background: linear-gradient(90deg, #304352 0%, #474746 100%);
  color: white;
}

input[type=checkbox]{
  position: relative;
  left: 10px;
  bottom: 20px;
}

::placeholder{
  color: white;
}

h2 {
    animation: colorchange 5s infinite;
    margin-top: -210px;
    text-shadow: 2px 2px 2px 2px black;
    margin-bottom: -2px;
  }
  

  img{
    position: relative;
    top: -230px;
    border-radius: 70px;
    padding: 20px;
    background: rgb(21,23,23);
    background: linear-gradient(90deg, #304352 0%, #474746 100%);
  }

 
  .Link{
    position: relative;
    bottom: -230px;
    font-size: 20px;
    color: rgb(226, 226, 226);
  }

  .Link1{
    color: rgb(226, 226, 226);
    font-size: 20px;
  }

  .AA{
    position: relative;
    bottom: 130px;
  }

.AA:hover{
  text-decoration: none;
}

.Icons{
  color: black;
  font-size: 20px;
  position: relative;
  top: -90px;
}

@media (max-width: 1024px) {
  .Everything{
    margin-left: 340px;
  }

  .IMG{
    margin-left: -60px;
  }

  h2{
    margin-left: -35px;
    font-size: 20px;
    display: grid;
  }

  button{
    margin-top: 10px;
    margin-left: -400px;
    margin-right: 210px;
    padding: 10px;
  }

  a{
    font-size: 14px;
  }

  input[type=text]{
    margin-left: -95px;
  }
  input[type=password]{
    margin-left: -95px;
  }
}

@media (max-width: 768px) {
  .Everything{
    margin-left: 210px;
  }

  button{
    margin-left: -520px;
    margin-right: 350px;
  }

}

@media (max-width: 375px){
  .Everything{
    margin-left: 10px;
  }

  button{
    margin-left: -720px;
    margin-right: 540px;
  }
}

@media (max-width: 414px){
  .Everything{
    margin-left: 30px;
  }
  button{
    margin-left: -690px;
    margin-right: 540px;
  }

}

@media (max-width: 375px){
.Everything{
  margin-left: 8px;
}
button{
  margin-left: -720px;
  margin-right: 540px;
}
}

@media (max-width: 820px){
  .Everything{
    margin-left: 240px;
  }
  button{
    margin-left: -480px;
    margin-right: 320px;
  }
}

@media (max-width: 768px){
  .Everything{
    margin-left: 210px;
  }
  button{
    margin-left: -520px;
    margin-right: 345px;
  }
}

@media (max-width: 412px){
  .Everything{
    margin-left: 32px;
  }
  button{
    margin-left: -700px;
    margin-right: 530px;
  }
}

@media (max-width: 360px){
  .Everything{
    margin-left: 10px;
  }
  button{
    margin-left: -730px;
    margin-right: 560px;
  }
}

@media (max-width: 430px){
  .Everything{
    margin-left: 40px;
  }
  button{
    margin-left: -700px;
    margin-right: 510px;
  }
}

@media (max-width: 390px){
  .Everything{
    margin-left: 20px;
  }
  button{
    margin-left: -700px;
    margin-right: 550px;
  }
}

<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Impressum</title>
    <link rel="stylesheet" href="Impressum.css">
    <link rel="stylesheet" href="">
</head>
<body>
    <h1>Impressum</h1>
    <b>Contact: </b>
    <br>
    <br>
    <a href="mailto: Djamalmoumouni7@gmail.com">Djamalmoumouni7@gmail.com</a>
    <br><a href="https://www.linkedin.com/in/djamal-moumouni-bb5a15252/ targed_blank">LinkedIn: Djamal Moumouni</a>
    <br>
    <br>

    <b>Address: </b>
    <p>Deutschland Hamburg
        <br>
        Anonyme Straße
        <br>
        33569 Hamburg
    </p>

    <b>Owner of the website:</b>
    <p>Djamal Moumouni</p>




<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lato:ital@1&family=Onest:wght@300;400;500&family=Pixelify+Sans:wght@400;500;600&family=Poppins&family=Roboto:ital,wght@0,300;0,400;0,500;1,300;1,400&display=swap" rel="stylesheet">
</body>
</html>
body{
    font-family: 'Poppins', sans-serif;
    padding-left: 50px;
    background: rgb(21,23,23);
    background: linear-gradient(90deg, #304352 0%, #d7d2cc 100%);
    text-shadow: 1px black;
    color: rgb(226, 226, 226);
}

a{
    text-decoration: none;
    color: rgb(226, 226, 226);
}

a:hover{
    text-decoration: underline;
}

