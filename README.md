<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Travel Explorer</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

header{
    background:#0077b6;
    color:white;
    padding:15px 50px;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav ul{
    list-style:none;
    display:flex;
}

nav ul li{
    margin-left:20px;
}

nav ul li a{
    color:white;
    text-decoration:none;
}

.hero{
    height:90vh;
    background:url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e')
    center/cover no-repeat;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.content h2{
    font-size:3rem;
}

.content p{
    margin:15px 0;
    font-size:1.2rem;
}

button{
    padding:10px 20px;
    border:none;
    background:#ffb703;
    border-radius:5px;
    cursor:pointer;
}

.destinations{
    padding:50px;
    text-align:center;
}

.cards{
    display:flex;
    justify-content:center;
    gap:20px;
    margin-top:20px;
    flex-wrap:wrap;
}

.card{
    width:250px;
    padding:20px;
    background:#f4f4f4;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,0.2);
}

footer{
    background:#023e8a;
    color:white;
    text-align:center;
    padding:15px;
}
</style>

</head>
<body>

<header>
    <nav>
        <h1>Travel Explorer</h1>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Destinations</a></li>
            <li><a href="#">Packages</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <div class="content">
        <h2>Discover Amazing Places</h2>
        <p>Travel the world and create unforgettable memories.</p>
        <button>Explore Now</button>
    </div>
</section>

<section class="destinations">
    <h2>Popular Destinations</h2>

    <div class="cards">
        <div class="card">
            <h3>Paris</h3>
            <p>The City of Lights.</p>
        </div>

        <div class="card">
            <h3>Bali</h3>
            <p>Tropical Paradise.</p>
        </div>

        <div class="card">
            <h3>Dubai</h3>
            <p>Luxury and Adventure.</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2026 Travel Explorer | All Rights Reserved</p>
</footer>

</body>
</html>
