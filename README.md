<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width , initial-scale=1.0">
    <link rel="Stylesheet" href="style.css">
    <title>Document</title>
 <style>
    <!--styling for the navbar element-->
    *{margin: 0;
        padding: 0;
        box-sizing: border-box;}
       header{position: fixed;
       width: 100%;
       padding: 2rem;
       background: black;
      display: flex;
      color: aquamarine;
       align-items: center;
       justify-content: space-between;}
    .logo{
    font-size: 2rem;
    font-weight: 600;
    color: rgb(164, 178, 204);}
    .navbar a{font-size: 1.2rem;
    margin-left: 2rem;
    text-decoration: none;
    color: thistle;}
    .navbar a:hover{color: darkviolet;}
    .logo:hover{color: darkviolet;}
     body{font-family: 'roboto' sans-serif;}

    
 </style> 
</head>
<body>
    <header>
      <div class="logo">MIRACLE's Portfolio</div>
      <nav class="navbar">
        <a href="#Home">HOME</a>
        <a href="#About">ABOUT</a>
        <a href="#Work">WORK</a>
        <a href="#Resume">RESUME</a>
        <a href="#Contact">CONTACT</a>
      </nav>
    </header>

<main>
  <section id="Home" style="height:100; padding:2rem; background:#f0f8ff;">
    <h1>Welcome to MIRACLE's Portfolio</h1>
    <p>This is where your journey begins. Showcase your personality and purpose here.</p>
  </section>

  <section id="About" style="height:100; padding:2rem; background:#e6e6fa;">
    <h2>About Me</h2>
    <p>I was raised in a family who sort to achieve in all endeavours of life.
        i enjoy watching sports, firm believer of your craft has to be refurblished mentally. 
    </p>
  </section>

  <section id="Work" style="height:100; padding:2rem; background:#ebd6e8;">
    <h2>My Work</h2>
    <p><ul>
        <li> 1996 - Born in uganda</li>
        <li>2016 - Introduced to Ai intelligence and web development </li>
        <li>2017/2020 - Worked for Microsoft Programming Texas</li>
        <li>2021/2023 - Executive Head Developer in Ignitech, Paris</li>
        <li>2024/Till now - Consult Head for Apple,SAMSUNG</li>
        
    </ul> </p>
  </section>

  <section id="Resume" style="height:100; padding:2rem; background:#d5d0d3;">
    <h2>Resume</h2>
    <p><ul>
        <Li><a href="link">//github.com/yanmite</a></Li>
    </ul></p>
  </section>

  <section id="Contact" style="color: white; height:100; padding:2rem; background:#044665;">
    <h2>Contact Me</h2>
    <p><a href="contact">+2349090473203 </a></p>
  </section>
</main>
    
</body>

</html>