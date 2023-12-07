# Netflix Landing Page Clone :

Welcome to my Netflix landing page clone! As a beginner learning HTML and CSS, I decided to challenge myself by recreating the Netflix landing page. This project was a fantastic opportunity to practice my front-end development skills and gain hands-on experience with web design.

# Result :

# HTML Code :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix India-Watch TV Shows Online, Watch Movies Online</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,700;1,800;1,900&family=Press+Start+2P&family=Quicksand:wght@300;400;500;600;700&family=Roboto:ital,wght@0,100;0,400;0,500;0,700;0,900;1,400;1,500;1,700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="header">
        <header>
            <img src="images/logo.png" class="logo">
            <div class="items-1">
            <select name="English" class="lang">
                <option value="English">English</option>
                <option value="Tamil">Tamil</option>
                <option value="Hindi">Hindi</option>
            </select>
            <button class="Sign">Sign In</button>
            </div>
        </header>
    </div>
    <div class="text">
        <p class="sub-1">Unlimited movies, TV shows and more</p>
        <p class="sub-2">Starts at ₹149.Cancel anytime.</p>
        <p class="sub-3">Ready to watch? Enter your email to create or restart your membership.</p>
        <div class="input-1">
            <input type="email" placeholder="Email address" class="email">
            <button class="button">Get Started ></button>
        </div>
    </div>
    
</body>
</html>

```

# CSS Code :
```
body{
    background-image: linear-gradient(90deg,rgba(0,0,0,1),rgba(0,0,0,0.3)),url("images/Background.png");
    background-size: cover;
    background-attachment: fixed;
}

header{
    margin: 0;
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.items-1{
    justify-content: center;
    position: relative;
}

.logo{
    width: 200px;
    height: 120px;
    box-sizing: border-box;
    position: relative;
    top: -10px;
    left: 30px;
    cursor: pointer;
    
    
}
.Sign{
    font-size: 25px;
    padding: 10px 20px;
    text-align: center;
    margin-right: 50px;
    font-family: "Arial" ;
    font-weight: 700;
    border: none;
    border-radius: 5px;
    background-color: #E50914;
    color: white;
    
}
.Sign:hover{
    background-color: #e50914c7
}
.lang{
    font-size: 25px;
    padding: 10px 40px;
    text-align: center;
    margin-right: 50px;
    margin-right: 10px;
    border: none;
    border-radius: 5px;
    background-color: black;
    color: white;
    font-family: "Arial" ;
    font-weight: 700;
}
.text{
    display: flex;
    flex-direction: column;
    color: white;
    align-items: flex-start;
    flex-wrap: wrap;
    margin-top: 150px;
    margin-left: 100px;
}
.sub-1{
    
    line-height: 80px;
    font-size: 50px;
    font-family: "Arial" ;
    font-weight: 1000;
    margin-bottom: 0;
}
.sub-2{
    margin-top: 1px;
    margin-bottom: 25px;
    font-family: "Arial" ;
    
}
.sub-3{
    margin-top: 10px;
    font-family: "Arial" ;
    color: rgba(255,255,255,0.7);;
}
.email{
    padding-top: 12px;
    padding-bottom: 12px;
    padding-left: 22px;
    padding-right: 40px;
    font-size: 20px;
    font-family: "Arial" ;
    border: solid 1px white;
    color:white;
    background-color: rgba(8, 7, 7, 0.4);
    -webkit-backdrop-filter: blur(5px);
    backdrop-filter: blur(5px);
    border-radius: 5px;
}
.button{
    margin-top: 20px;
    padding-top: 14px;
    padding-bottom: 12px;
    padding-left: 22px;
    padding-right: 22px;
    font-size: 20px;
    font-family: "Arial" ;
    background-color: #E50914;
    border: 0;
    color: white;
    font-family: "Arial" ;
    font-weight: bolder;
    border-radius: 5px;
    margin-left: 10px;


}
.button:hover{
    background-color: #e50914c7

}
```

# Credits :

Netflix - https://www.netflix.com/in/

Background image - https://netflixtechblog.com/a-day-in-the-life-of-an-experimentation-and-causal-inference-scientist-netflix-388edfb77d21

Logo - https://www.pngwing.com/en/free-png-hnwne#google_vignette