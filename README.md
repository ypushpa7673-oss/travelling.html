<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Travel World</title>

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
    padding:15px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 10px;
}

.hero{
    height:80vh;
    background:linear-gradient(rgba(0,0,0,0.4),rgba(0,0,0,0.4)),
    url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e');
    background-size:cover;
    background-position:center;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    color:white;
    text-align:center;
}

.hero h2{
    font-size:50px;
}

.hero p{
    font-size:22px;
    margin:10px 0;
}

button{
    padding:12px 25px;
    background:orange;
    border:none;
    color:white;
    border-radius:5px;
    cursor:pointer;
    font-size:18px;
}

.places{
    display:flex;
    justify-content:center;
    gap:20px;
    padding:40px;
    flex-wrap:wrap;
}

.card{
    width:250px;
    background:#f4f4f4;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
    text-align:center;
}

footer{
    background:#0077b6;
    color:white;
    text-align:center;
    padding:15px;
}
</style>

</head>
<body>

<header>
    <h1>Travel World</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Destinations</a>
        <a href="#">Packages</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Explore The World</h2>
    <p>Discover Amazing Places With Us</p>
    <button>Book Now</button>
</section>

<section class="places">
    <div class="card">
        <h3>Paris</h3>
        <p>City of Lights and Romance</p>
    </div>

    <div class="card">
        <h3>Dubai</h3>
        <p>Luxury and Adventure</p>
    </div>

    <div class="card">
        <h3>Maldives</h3>
        <p>Beautiful Beaches and Resorts</p>
    </div>
</section>

<footer>
    <p>© 2025 Travel World. All Rights Reserved.</p>
</footer>

</body>
</html>
