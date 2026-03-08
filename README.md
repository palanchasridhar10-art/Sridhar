<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yodha Fitness Centre</title>

<style>

body{
margin:0;
font-family:Arial, Helvetica, sans-serif;
background:linear-gradient(white, #ffd6e7);
}

/* Navbar */

nav{
background:#ffb6c1;
padding:15px;
display:flex;
justify-content:space-between;
align-items:center;
}

nav h1{
color:white;
}

nav ul{
list-style:none;
display:flex;
gap:20px;
}

nav ul li{
color:white;
cursor:pointer;
}

/* Hero */

.hero{
text-align:center;
padding:80px 20px;
background:white;
}

.hero h2{
color:#ff4d88;
font-size:40px;
}

.hero p{
color:#555;
}

/* Equipment Section */

.equipment{
padding:50px;
text-align:center;
}

.equipment h2{
color:#ff4d88;
}

.equipment-container{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:30px;
margin-top:30px;
}

.card{
background:white;
padding:20px;
border-radius:10px;
width:200px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

.card img{
width:100%;
border-radius:10px;
}

/* Training Section */

.training{
background:white;
padding:50px;
display:flex;
flex-wrap:wrap;
align-items:center;
justify-content:center;
gap:40px;
}

.training img{
width:250px;
border-radius:10px;
}

.training-text{
max-width:400px;
}

.training-text h2{
color:#ff4d88;
}

/* Footer */

footer{
text-align:center;
background:#ffb6c1;
padding:20px;
color:white;
}

</style>
</head>

<body>

<nav>
<h1>Yodha Fitness</h1>
<ul>
<li>Home</li>
<li>Equipments</li>
<li>Training</li>
<li>Contact</li>
</ul>
</nav>

<section class="hero">
<h2>Welcome to Yodha Fitness Centre</h2>
<p>Transform your body with the best gym training and modern equipments.</p>
</section>

<section class="equipment">
<h2>Gym Equipments</h2>

<div class="equipment-container">

<div class="card">
<img src="https://images.unsplash.com/photo-1583454110551-21f2fa2afe61">
<h3>Dumbbells</h3>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b">
<h3>Treadmill</h3>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1599058917212-d750089bc07e">
<h3>Bench Press</h3>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1598971639058-bc6f6b5b4c7d">
<h3>Squat Rack</h3>
</div>

</div>

</section>

<section class="training">

<img src="your-image.jpg" alt="Gym Training">

<div class="training-text">
<h2>Personal Gym Training</h2>
<p>
Our professional trainers help you build strength, endurance,
and confidence. We provide personal training, weight loss programs,
and muscle building workouts.
</p>

<p>
Join Yodha Fitness and start your fitness journey today.
</p>

</div>

</section>

<footer>
<p>© 2026 Yodha Fitness Centre | Stay Strong 💪</p>
</footer>

</body>
</html>