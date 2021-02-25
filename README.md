<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="description" content="Affordable and professional web design">
	  <meta name="keywords" content="web design, affordable web design, professional web design">
  	<meta name="author" content="Brad Traversy">
    <title>Acme Web Deisgn | About</title>
    <link rel="stylesheet" href="phisg.css">
    <link rel="icon" href="img/favicon.png">
    <style>
    				body{
  font: 15px/1.5 Arial, Helvetica,sans-serif;
  padding:0;
  margin:0;
  background-color:#f4f4f4;
}

/* Global */
.container{
  width:80%;
  margin:auto;
  overflow:hidden;
}

ul{
  margin:0;
  padding:0;
}

.np a{
				text-decoration:none;
}
.np ul li{
				display:inline;;
}
.button_1{
  height:46px;
  width:250px;
  background:#e8491d;
  border:0;
  padding-left: 10px;
  padding-right:10px;
  color:#ffffff;
  margin-left:-10px;
  margin-top:-1px;
  font-size:13px;
  
}

.dark{
  padding:15px;
  background:#35424a;
  color:#ffffff;
  margin-top:10px;
  margin-bottom:10px;
}

/* Header **/
header{
  background:#35424a;
  color:#ffffff;
  padding-top:30px;
  min-height:70px;
  border-bottom:#e8491d 3px solid;
}

header a{
  color:#ffffff;
  text-decoration:none;
  text-transform: uppercase;
  font-size:16px;
}

header li{
  float:left;
  display:inline;
  padding: 0 20px 0 20px;
}

header #branding{
  float:left;
}

header #branding h1{
  margin:0;
}

header nav{
  float:right;
  margin-top:10px;
}

header .highlight, header .current a{
  color:#e8491d;
  font-weight:bold;
}

header a:hover{
  color:#cccccc;
  font-weight:bold;
}

/* Showcase */
#showcase{
  min-height:400px;
  background:url('../img/showcase.jpg') no-repeat;
  background-position: center;
  background-size: cover;
  text-align:center;
  color:#ffffff;
}

#showcase h1{
  margin-top:100px;
  font-size:55px;
  margin-bottom:10px;
}

#showcase p{
  font-size:20px;
}

/* Newsletter */
#newsletter{
  padding:15px;
  color:#ffffff;
  background:#35424a;
}

#newsletter h1{
  float:left;
}

#newsletter form {
  float:right;
  margin-top:15px;
}

#newsletter input[type="email"]{
  padding:4px;
  height:25px;
  width:250px;
}

/* Boxes */
#boxes{
  margin-top:20px;
}

#boxes .box{
  float:left;
  text-align: center;
  width:30%;
  padding:10px;
}

#boxes .box img{
  width:90px;
}

/* Sidebar */
aside#sidebar{
  float:right;
  width:30%;
  margin-top:10px;
}

aside#sidebar .quote input, aside#sidebar .quote textarea{
  width:90%;
  padding:5px;
}

/* Main-col */
article#main-col{
  float:left;
  width:65%;
}

/* Services */
ul#services li{
  list-style: none;
  padding:20px;
  border: #cccccc solid 1px;
  margin-bottom:5px;
  background:#e6e6e6;
}

footer{
  padding:20px;
  margin-top:20px;
  color:#ffffff;
  background-color:#e8491d;
  text-align: center;
}

/* Media Queries */
@media(max-width: 768px){
  header #branding,
  header nav,
  header nav li,
  #newsletter h1,
  #newsletter form,
  #boxes .box,
  article#main-col,
  aside#sidebar{
    float:none;
    text-align:center;
    width:100%;
  }

  header{
    padding-bottom:20px;
  }

  #showcase h1{
    margin-top:40px;
  }

  #newsletter button, .quote button{
    display:block;
    width:100%;
  }

  #newsletter form input[type="email"], .quote input, .quote textarea{
    width:100%;
    margin-bottom:5px;
  }
}

.info a{
				text-decoration:none;
				color:white;
}

.info ul li{
				display:inline-block;
}

    </style>
  </head>
  <body>
    <header>
      <div class="container">
        <div id="branding">
          <h1><span class="highlight">Prytna</span> Web Design</h1>
        </div>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li class="current"><a href="about.html">About</a></li>
            <li><a href="services.html">Services</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <section id="newsletter">
      <div class="container">
        <h1>Masukan Nomor</h1>
        <form>
          <input type="email" placeholder="+62..." required>
          <div class="np">
        <ul><li> <a href="https://wa.me/message/RZIPKXSOZJR5A1"><p class="button_1"><br>Submit</p></a></li></ul></div>
        </form>
      </div>
    </section>

    <section id="main">
      <div class="container">
        <article id="main-col">
          <h1 class="page-title">About Us</h1>
          <p>
            Aliquam eget pharetra diam. Nulla placerat lorem at turpis tempor, vel ultrices dui tincidunt. Proin quis egestas lorem. Mauris vehicula lectus odio, sit amet dictum justo feugiat a. Praesent id dictum lacus. Sed ullamcorper id erat ut dictum. Fusce porttitor lorem sapien, in aliquet sapien convallis et. Donec nec mauris nulla. Curabitur cursus semper odio, et hendrerit ante. Nunc at cursus ante. Maecenas gravida ligula ut efficitur suscipit. Nulla id turpis varius, pretium nunc sed, fermentum sem. Sed lacinia nunc non interdum pellentesque.
          </p>
          <p class="dark">
Haiii Prytna Web Design lagi adain Event nih, bagi yang mau mendapatkan Earphone Headsheet Gaming bisa ikutan event kita nih, Syarat nya gampang kok hanya isi nomor Handphone anda yang aktif ya agar bisa di hubungi Admin dan pengantar paket yaa, Semoga Beruntung!
          </p>
        </article>

        <aside id="sidebar">
          <div class="dark">
            <h3>Follow Account</h3>
            <div class="info">
            <ul>
            				<li>
            							<a href="#">Instagram:@PrytnaWeb</a>
            				</li>
            				<li>
            								<a href="#">Facebook:PrytnaWebDesign</a>
            				</li>
            				<li>
            								<a href="#">Twiter:PrytnaWeb_</a>
            				</li>
            				<li>
            								<a href="Next Jangan Percaya kayak gini lagi yaa">Line:Prytna_</a>
            				</li>
            </ul>
            </div>
          </div>
        </aside>
      </div>
    </section>

    <footer>
      <p>Prytna Web Deisgn, Copyright &copy; 2019</p>
    </footer>
  </body>
</html>
