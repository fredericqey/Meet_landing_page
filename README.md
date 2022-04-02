# Meet_landing_page


html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Red+Hat+Display&display=swap" rel="stylesheet">    
    <link rel="stylesheet" href="desktop.css">
</head>
<body class="body_text">
    <div class="container">
        <img  id="meet"  src="/meet-landing-page/starter-code/assets/logo.svg" alt="">
    </div>
    <!--Group chat for everyone-->
    <div class="everyone">
        <div>
            <img src="/meet-landing-page/starter-code/assets/desktop/image-hero-left.png" alt="">
        </div>
            
        <div>
            <h1 id="heading_text">Group Chat<br> for Everyone</h1>
            <p id="para_text">Meet makes it easy to connect with others face-to-face virtually<br> and collaborate across any device</p>
        </div>

        <div>
            <img src="/meet-landing-page/starter-code/assets/desktop/image-hero-right.png" alt="">
        </div>

    </div>

    <section class="section">
        <button id="button_one">Download <p class="button1_para">v1.3</p></button>
        <button id="button_two">What is it?</button>
    </section>
</body>
</html>




CSS
.body_text{
    font-family: 'Red Hat Display', sans-serif;
    font-weight: 700;
    /* font-size: 20px;
    font-weight: 400px;
    line-height: 64px; */
}

.container{
    position: relative;
    width: 1440px;
    height: 1895px;
    background-color: #fafafa;
    /*top: 3440px;
    left: -4549px;*/
}
#meet{
    position: absolute;
    width: 118.72px;
    height: 28px;
    left: 661px;
    top: 80px;
}
.everyone{
    position: absolute;
    width: 1504px;
    height:358px;
    left:-32px;
    top:169px;
    display: grid;
    grid-template-columns: 1fr 3fr 1fr;
}
#heading_text{
    text-align: center;
    position:absolute;
    top: 69px;
    left:681px;
    line-height: 40px;
    font-weight: bolder;
}
#para_text{
    text-align:center;
    position: absolute;
    top:169px;
    left:530px;
    line-height: 30px;
    padding: 10px;
    font-weight: 100 !important;
    color: #87879d;
}
.section{
    position: absolute;
    top: 400px;
    left:530px; 
}

#button_one{
    background-color: #4d96a9;
    color:#fff;
    border-radius: 20px;
    position: absolute;
    top:40px;
    left:90px;
    padding-left: 25px;
    padding-right: 50px;
    padding-top: 10px;
    padding-bottom: 10px;
    border: none;
}
#button_one:hover{
    background-color: #8fe3f9;
    cursor: pointer;
    opacity: 0.9;
}

#button_two{
    background-color: #855fb1;
    color:#fff;
    border-radius: 20px;
    position: absolute;
    top:40px;
    left: 240px;
    padding-left: 25px;
    padding-right: 25px;
    padding-top: 10px;
    padding-bottom: 10px;
    white-space: nowrap;
    text-align: center;
    border: none;
}
.button1_para{
    position:absolute;
    color: #8fe3f9;
    padding: 0px 5px 5px 0px;
    left:95px;
    top:-3px;
}
