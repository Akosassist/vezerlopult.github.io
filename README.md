# vezerlopult.github.io
<!DOCTYPE html>
<html lang="hu">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SÁ weboldala</title>
    <link rel="stylesheet" href="stilus.css">
</head>

<body>
    <header>
        <h1>Simon Ákos <br> Weboldala</h1>
        <h3>2024. január-2028. április</h3>
    </header>
    <section>
        <nav>
            <ul>
                <li class="btnnav"><a href="https://sites.google.com/view/webalapok9a23/digikult" target="_blank">
                        Digitális Kultúra </a></li>
                <li class="btnnav"><a href="https://sites.google.com/view/webalapok9a23/webalapok"
                        target="_blank">Webalapok</a></li>
                <li class="btnnav"><a href="https://sites.google.com/view/webalapok9a23/ita" target="_blank">ITA</a>
                </li>
                <li class="btnnav"><a href="https://sites.google.com/view/webalapok9a23/" target="_blank">IKT
                        projektmunka</a></li>
            </ul>
        </nav>
        <article>
            </ul>
            <div class="card">
                <div class="card-text">
                    <img src="M:\PROGIALAPOK\1_WEBSZERKESZTÉS\cards\Képernyőkép 2024-01-25 094517.png" alt="card image">
                    <h2>WEB alapok - saját weboldalam</h2>
                    <p>A programozási gyakorlat html + css + bootstrap tudnivalónak gyűjteménye mintafeladatokkal</p>
                    <a href="https://sites.google.com/view/webalapok9a23" target="_blank" class="btn">Ugrás az oldalra</a>
                </div>
                <div class="card-text">
                    <img src="C:\Users\Alex\Desktop\vezerlopult\orarend.png" alt="card image">
                    <h2>Iskolai aktuális órarend</h2>
                    <p>Megtalálhatod az osztályok, az oktatók és a tantermek órarendjeit naprakészen</p>
                    <a href="https://akosassist.github.io/orarend.github.io/" target="_blank" class="btn">Ugrás az oldalra</a>
                </div>
                <div class="card-text">
                    <img src="C:\Users\Alex\Desktop\vezerlopult\digisulim.jpg" alt="card image">
                    <h2>Oktatási iránytű portál</h2>
                    <p>Megtalálhatod azon fontos oldalak elérhetőségét, melyek a Digitális Kultúra tantárgyhoz és az
                        Informatikai és távközlés ágazat diákjainak nyújt linkgyűjteményt a tanulmányok során
                        használandó tartalmakhoz, programokhoz</p>
                    <a href="https://digisulim.hu/" target="_blank" class="btn">Ugrás az oldalra</a>
                </div>
            </div>
        </article>
    </section>
    <footer>Footer</footer>
</body>

</html>

*{
    box-sizing:border-box;
}


body{
    margin: 0px 0px;
    
}
header{
    background-color: aquamarine;
    text-align: center;
    padding: 15px;
}
nav{
    background-color: white;
    float: left;
    width: 20%;
    height: 750px;
    padding-top: 20px;
}
nav li{
    list-style-type: none;
}
a{
    text-decoration: none;
    color: wheat;
}

.btnnav{
    background-color: blue;
    margin: auto;
    display: inline-block;
    padding: 8px;
    width: 90%;
    margin-bottom: 30px;
    border-radius: 15px;
    transition: background-color 0.3s ease;
}
.btnnav:hover{
    background-color: rgb(247, 10, 247);
}

article{
    background-color: white;
    width: 80%;
    float: left;
    height: 750px;
}
footer{
    background-color: rgb(182, 142, 223);
    color: white;
    padding: 10px;
    text-align: center;
}
.card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    border-radius: 5px;
    padding: 20px;
    background-color: #fff;
    margin: 20px;
    display: flex;
  }
  
  .card img {
    width: 100%;
    border-radius: 5px 5px 0 0;
  }
  
  .card-text {
    text-align: center;
    padding: 10px;
  }
  
  .card-text h2 {
    font-size: 24px;
    margin-bottom: 10px;
  }
  
  .card-text p {
    font-size: 18px;
    margin-bottom: 20px;
  }
  
  .btn {
    display: inline-block;
    background-color: #000;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s ease;
  }
  
  .btn:hover {
    background-color: #333;
  }
  ul{
    margin: 0;
    padding: 0%;

  }
