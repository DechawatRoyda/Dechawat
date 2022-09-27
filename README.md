<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>HTML5 Semantic</title>
    <style>
      * {
        box-sizing: border-box;
      }

      ul {
        padding: 0;
        list-style: none;
      }

      body {
        font-family: Arial, Helvetica, sans-serif;
        color: #333;
        line-height: 1.4;
      }

      #header {
        margin-bottom: 15px;
        background: #333;
        color: #fff;
        padding: 10px;
      }

      #main {
        float: left;
        width: 69%;
      }

      #sidebar {
        float: right;
        width: 29%;
      }

      .clr {
        clear: both;
      }

      #footer {
        background: #333;
        color: #fff;
        padding: 10px;
      }

      .text-center {
        display: block;
        text-align: left;
      }

      .card {
        border: 1px solid #ddd;
        background: #f4f4f4;
        padding: 20px;
        margin-bottom: 10px;
      }
    </style>
  </head>
  <body>
    <!-- Header -->
    <div id="header" class="card">

      <h1>
        Dechawat Royda <small>call me plub</small>
      </h1>
    </div>
    <!-- Main Content -->
    <main id="main">
      <!-- Welcome Section -->
      <section id="welcome" class="card">
        <h2>About Me</h2>
        <p>
          I'm a computer engineering student at the King Mongkut's University of Technology Thonburi
Interested in web development and love trying new things. <br />
          <a href="https://www.facebook.com/P-lub-Gaming-102563579143297" class="text-center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Video-Game-Controller-Icon-IDV-green.svg/1024px-Video-Game-Controller-Icon-IDV-green.svg.png" alt=""width="40" height="40">Game Streaming Page
          </a>
          <a href="https://www.facebook.com/profile.php?id=100017935664780" class="text-center">
           <img src="https://cdn3.iconfinder.com/data/icons/free-social-icons/67/facebook_circle_color-512.png" alt=""width="40" height="40">FACEBOOK</a>        
        </p>
      </section>
      <!-- Blog Section -->
      <section id="blog">
        <!-- Article One -->
        <article class="article">
          <h3 align="left"> Skills && Tools</h3>
          <h1 align="left" dir="auto">
            <a href="https://www.arduino.cc" rel="nofollow"> 
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Arduino_Logo.svg/1024px-Arduino_Logo.svg.png" alt="" width="40" height="30" style="max-width: 100%;"></a>
            <a href="https://code.visualstudio.com" rel="nofollow"> 
                <img src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_vscode_icon_130084.png" alt="" width="40" height="30" style="max-width: 100%;"></a>  
            <a href="https://console.firebase.google.com" rel="nofollow"> 
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/37/Firebase_Logo.svg/1280px-Firebase_Logo.svg.png" alt="" width="80" height="30" style="max-width: 100%;"></a>  
            </h1>   
        </article>
        <hr>
        <!-- Article Two -->
        <article class="article">
          <h3>Work Experience</h3>
          <p>
            <ul>
              <li>● HTML CSS DevWeb</li>
              <li>● C arduinoIDE make Project Hardware</li>
              <li>● Use Firbase realtime</li>
            </ul>
          <h3>Example Work</h3>
            <a href="">GitHub</a>
          </p>
        </article>
      </section>
    </main>

    <!-- Sidebar-->
    <aside id="sidebar" class="card">
      <h3>Menu</h3>
      <!-- Navigation -->
      <ul id="main-nav">
        <li><a href="#">Home page</a></li>
        <li><a href="#">About me</a></li>
        <li><a href="#">Work Experience</a></li>
      </ul>
      <hr />
      <h3>Contract</h3>
      <ul>
        <li><strong>Address:</strong> 352/1 Moo.13,Srisuk,Sichomphu,Khonkaen</li>
        <li><strong>Phone number:</strong> (+66) 97-008-4080</li>
        <li><strong>Email:</strong> dechawat357@gmail.com</li>
      </ul>
    </aside>

    <div class="clr"></div>

    <!-- Footer -->
    <footer id="footer">
      <p class="text-center">Copyright &copy; Dechawat Royda 2022</p>
    </footer>
  </body>
</html>
