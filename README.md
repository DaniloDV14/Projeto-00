  
  <head>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz@0,14..32;1,14..32&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,500;1,14..32,500&display=swap" rel="stylesheet">
   
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto</title>
    <link rel="stylesheet" href="./style.css">

</head>
<body>
   <div id="container"> 
    <div id="profile">
        <img src="./assets/avatar.png" alt="">
        <p>@Danilo</p>
    <ul>
       <li>
        <a href="https://www.instagram.com/danilo_dutra_vieira?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank">Siga meu Instagram</a>
        </li> 
       <li>
        <a href="https://www.linkedin.com/in/danilo-dutra-799530388?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank">Veja meu Linkedin</a>
       </li>
       <li>
        <a href="https://wa.me/5527996335548" target="_blank">Meu Contato</a>
       </li>
       <li>
        <a href="https://www.tiktok.com/@dan.d.1914?_r=1&_t=ZS-93QdhLY98hF" target="_blank">Conheça o meu Tiktok</a>
       </li>
    </ul>
    <div id="social-links">
        <a href="https://www.instagram.com/danilo_dutra_vieira?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank">
         <ion-icon  name = "logo-instagram"></ion-icon>
        </a>
        <a href="https://www.linkedin.com/in/danilo-dutra-799530388?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank">
        <ion-icon  name = "logo-linkedin"></ion-icon>
        </a>
        <a href="https://wa.me/5527996335548" target="_blank">
        <ion-icon  name = "logo-whatsapp"></ion-icon>
        </a>
        <a href="https://www.tiktok.com/@dan.d.1914?_r=1&_t=ZS-93QdhLY98hF" target="_blank">
        <ion-icon  name = "logo-tiktok"></ion-icon>
        </a>
    </div>
   </div>

    <script  type = "module"  src = " https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js " > </script>  
    <script nomodule src=" https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js ">   </script></body></html>

    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    background: url(./assets/bg-mobile.jpg) no-repeat center/cover;
}

body * {
     font-family: "Inter", sans-serif;
     color: white;
}

#container {
width: 100%;
max-width: 588px;
margin: 56px auto 0px;
}

#profile{
    text-align: center;
    padding: 24px;
}

#profile img {
width: 112px;
}

#profile p {
    font-weight: 500;
    line-height: 24px;
    margin-top: 8px;
}

ul{
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 16px;
    padding: 24px 0;
}

ul li a{
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 16px 24px;
    background: rgba(255, 255,255, 0.1);
    border: 1px solid rgba(255, 255,255, 0.5);
    border-radius: 8px;
    text-decoration: none;
    font-weight: 500;
    transition: background 0,2s;

}

ul li a:hover {
    background: rgba(255, 255,255, 0.05);
    border: 1.5px solid white
}

#social-links {
    display: flex;
    justify-content: center;
    gap: 16px;
    padding: 24px 0;
    font-size: 24px;
}

#social-links a {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 16px;
    transition: background .2s;
    border-radius: 50%;
}

#social-links a:hover{
    background: rgba(255, 255,255, 0.2);
}



