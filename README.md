# dog-website
dog website using HTML and CSS

html>

<head>
    <title>Website using HTML and CSS</title>
    <link href="style.css" rel="stylesheet" type="text/css">
</head>

<body>
    <header>
        <div class="top">
            <ul class="nav-menu">
                <li class="Homebtn"> <a href="">Home</a></li>
                <li> <a href="">About</a></li>
                <li> <a href="">Breeds</a></li>
                <li> <a href="">Adoption</a></li>
                <li> <a href="">Contact</a></li>
            </ul>
        </div>
        <div class="tagline">
            <h1>Share your home with a cute dog</h1>
            <div class="Adopt">
                <a href="" class="bttn">Adopt Now</a>
            </div>
        </div>




    </header>
</body>

</html>

CSS code

{
    margin: 0;
    padding: 0;
}

header {
    background-image: linear-gradient(rgba(0, 0, 0, 0, 5), rgba(0, 0, 0, 0, 5)), url('puppy\ img/');
    height: 100vh;
    background-size: cover;
    background-position: center;
}

.nav-menu {
    float: right;
    list-style: none;
    margin: 30px;
}

.nav-menu li {
    display: inline-block;

}

.nav-menu li {
    color: yellow;
    text-decoration: none;
    padding: 5px 20px;
    font-family: "Verdina", "sans-serif";
    font-size: 20px;
}

.Homebtn a {
    border: 1px solid gray;
    background-color: white;
}

.nav-menu li a:hover {
    border: 1px solid gray;
    background-color: white;
}

.tagline {
    position: absolute;
    width: 12000px;
    margin-left: 0;
    margin-top: 0;
}

h1 {
    color: black;
    font-size: 50px;
    font-family: "Verdana", "sans-serif";
    text-align: center;
    margin-top: 100px;
}

.Adopt {
    margin-top: 100px;
    margin-left: 100px;

}

.bttn {
    border: 1px solid black;
    padding: 10px 30px;
    color: yellow;
    font-family: "Verdana", "sans-serif";
    font-size: 22px;
    text-decoration: none;

}

.Adopt a :hover {
    background-color: black;
}
