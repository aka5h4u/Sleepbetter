
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700;900&display=swap" rel="stylesheet">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<style>
body{font-family:'Inter',sans-serif;}
.hero-bg{background:linear-gradient(135deg,rgba(0,20,50,.75),rgba(0,0,0,.65)),url('https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;}
.glass{background:rgba(255,255,255,0.08);backdrop-filter:blur(14px);}
.card:hover{transform:translateY(-10px) scale(1.03);box-shadow:0 25px 50px rgba(0,0,0,.2)}
.news-card img{transition:transform .4s}
.news-card:hover img{transform:scale(1.08)}
</style>
</head>
<body class="bg-white text-gray-900">

<!-- Top bar -->
<div class="bg-blue-950 text-white text-sm px-6 py-2 flex justify-between">
<div class="space-x-4"><a href="#">Better Sleep Council</a><a href="#">Bye Bye Mattress</a><a href="#">Mattress Recycling Council</a></div>
<div class="space-x-4"><a href="#">Search</a><a href="#">Member Login</a><a href="#">Join ISPA</a></div>
</div>

<!-- Navbar -->
<header class="fixed w-full top-8 z-50 bg-white/90 backdrop-blur-md shadow-md">
<div class="max-w-7xl mx-auto flex justify-between items-center px-6 py-4">
<h1 class="text-3xl font-black text-blue-900">SleepBetter</h1>
<nav class="hidden md:flex gap-6 font-semibold">
<a href="#">About</a><a href="#">Advocacy</a><a href="#">Sustainability</a><a href="#">Statistics</a><a href="#">Events</a><a href="#">News</a>
</nav>
</div>
</header>

<!-- Hero -->
<section class="hero-bg min-h-screen flex items-center text-white">
<div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-10 items-center">
<div data-aos="fade-right">
<h1 class="text-7xl font-black leading-tight">Helping the World Sleep Better</h1>
<p class="text-xl mt-6 text-gray-200">Empowering sleep product manufacturers and suppliers with advocacy, sustainability, innovation, and world-class events.</p>
<div class="mt-8 flex gap-4">
<a class="bg-blue-600 px-8 py-4 rounded-xl">Join ISPA</a>
<a class="bg-white text-blue-900 px-8 py-4 rounded-xl">Explore Events</a>
</div>
</div>
<div class="glass rounded-3xl p-8" data-aos="fade-left">
<h3 class="text-3xl font-bold mb-4">Industry Snapshot</h3>
<p class="mb-3">✔ 600+ Members</p>
<p class="mb-3">✔ 100+ Years of Leadership</p>
<p>✔ 40+ Countries Represented</p>
</div>
</div>
</section>

<!-- Services -->
<section class="py-24 bg-gray-50">
<div class="max-w-7xl mx-auto px-6">
<h2 class="text-5xl font-black text-center mb-14" data-aos="fade-up">Our Focus</h2>
<div class="grid md:grid-cols-4 gap-8">
<div class="card bg-white p-8 rounded-3xl transition-all" data-aos="zoom-in"><h3 class="text-2xl font-bold">Advocacy</h3></div>
<div class="card bg-white p-8 rounded-3xl transition-all" data-aos="zoom-in"><h3 class="text-2xl font-bold">Statistics</h3></div>
<div class="card bg-white p-8 rounded-3xl transition-all" data-aos="zoom-in"><h3 class="text-2xl font-bold">Sustainability</h3></div>
<div class="card bg-white p-8 rounded-3xl transition-all" data-aos="zoom-in"><h3 class="text-2xl font-bold">Events</h3></div>
</div>
</div>
</section>

<!-- Events -->
<section class="py-24">
<div class="max-w-7xl mx-auto px-6">
<h2 class="text-5xl font-black text-center mb-14">Upcoming Events</h2>
<div class="grid md:grid-cols-3 gap-8">
<div class="news-card rounded-3xl overflow-hidden shadow-xl"><img src="https://images.unsplash.com/photo-1511578314322-379afb476865?auto=format&fit=crop&w=800&q=80"><div class="p-6"><h3 class="text-2xl font-bold">ISPA EXPO</h3></div></div>
<div class="news-card rounded-3xl overflow-hidden shadow-xl"><img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=80"><div class="p-6"><h3 class="text-2xl font-bold">Sustainability Conference</h3></div></div>
<div class="news-card rounded-3xl overflow-hidden shadow-xl"><img src="https://images.unsplash.com/photo-1505373877841-8d25f7d46678?auto=format&fit=crop&w=800&q=80"><div class="p-6"><h3 class="text-2xl font-bold">Industry Conference</h3></div></div>
</div>
</div>
</section>

<!-- News -->
<section class="py-24 bg-gray-100">
<div class="max-w-7xl mx-auto px-6">
<h2 class="text-5xl font-black text-center mb-14">Latest News</h2>
<div class="grid md:grid-cols-3 gap-8">
<div class="news-card bg-white rounded-3xl overflow-hidden shadow-lg"><img src="https://images.unsplash.com/photo-1495020689067-958852a7765e?auto=format&fit=crop&w=800&q=80"><div class="p-6">Forecast Released</div></div>
<div class="news-card bg-white rounded-3xl overflow-hidden shadow-lg"><img src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?auto=format&fit=crop&w=800&q=80"><div class="p-6">Legislation Tracker</div></div>
<div class="news-card bg-white rounded-3xl overflow-hidden shadow-lg"><img src="https://images.unsplash.com/photo-1556740749-887f6717d7e4?auto=format&fit=crop&w=800&q=80"><div class="p-6">Sustainability Updates</div></div>
</div>
</div>
</section>

<!-- CTA -->
<section class="py-24 bg-blue-900 text-white text-center">
<h2 class="text-6xl font-black">Join 600+ Industry Leaders</h2>
<p class="mt-4 text-xl">Build the future of sleep products with us.</p>
<a class="inline-block mt-8 bg-white text-blue-900 px-8 py-4 rounded-xl">Become a Member</a>
</section>

<!-- Footer -->
<footer class="bg-gray-950 text-gray-300 py-16">
<div class="max-w-7xl mx-auto grid md:grid-cols-4 gap-8 px-6">
<div><h3 class="text-white font-bold mb-4">About</h3><p>Our History</p></div>
<div><h3 class="text-white font-bold mb-4">Resources</h3><p>FAQs</p></div>
<div><h3 class="text-white font-bold mb-4">Events</h3><p>EXPO</p></div>
<div><h3 class="text-white font-bold mb-4">Contact</h3><p>Contact ISPA</p></div>
</div>
</footer>
<script>AOS.init();</script>
</body>
</html>
