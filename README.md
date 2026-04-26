
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<script src="https://cdn.tailwindcss.com"></script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;900&display=swap" rel="stylesheet">
<style>
body{font-family:'Inter',sans-serif;scroll-behavior:smooth;}
.hero-bg{background:linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),url('https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;}
.glass{background:rgba(255,255,255,0.1);backdrop-filter:blur(12px);}
.wave{position:relative;}
.wave:after{content:'';position:absolute;bottom:-1px;left:0;width:100%;height:100px;background:url('https://svgshare.com/i/12xA.svg') center/cover no-repeat;}
.card:hover{transform:translateY(-10px) scale(1.02);}
.fade-in{animation:fadeInUp 1s ease forwards;opacity:0;}
@keyframes fadeInUp{from{opacity:0;transform:translateY(30px)}to{opacity:1;transform:translateY(0)}}
</style>
</head>
<body class="bg-white text-gray-900">

<!-- Top Bar -->
<div class="bg-blue-950 text-white text-sm py-2 px-6 flex justify-between">
<div class="space-x-4"><a href="#">Better Sleep Council</a><a href="#">Bye Bye Mattress</a><a href="#">Mattress Recycling Council</a></div>
<div class="space-x-4"><a href="#">Search</a><a href="#">Login</a><a href="#">Join ISPA</a></div>
</div>

<!-- Navbar -->
<header class="fixed top-8 left-0 w-full z-50 bg-white/90 backdrop-blur-md shadow">
<div class="max-w-7xl mx-auto flex justify-between items-center p-4">
<h1 class="text-3xl font-black text-blue-900">ISPA</h1>
<nav class="hidden md:flex space-x-6 font-semibold">
<a href="#">About</a><a href="#">Advocacy</a><a href="#">Events</a><a href="#">Resources</a><a href="#">News</a>
</nav>
</div>
</header>

<!-- Hero -->
<section class="hero-bg h-screen flex items-center justify-center text-center text-white wave">
<div class="max-w-4xl px-6 fade-in">
<h1 class="text-7xl font-black leading-tight">Helping the World Sleep Better</h1>
<p class="text-2xl mt-6">Empowering the global sleep products industry through advocacy, sustainability, and innovation.</p>
<div class="mt-10 space-x-4">
<a class="bg-blue-600 hover:bg-blue-700 px-8 py-4 rounded-xl text-lg">Join ISPA</a>
<a class="bg-white text-blue-900 px-8 py-4 rounded-xl text-lg">Explore Events</a>
</div>
</div>
</section>

<!-- Stats -->
<section class="py-20 bg-white">
<div class="max-w-7xl mx-auto grid md:grid-cols-3 gap-8 text-center">
<div><h2 class="text-6xl font-black text-blue-900">600+</h2><p>Members</p></div>
<div><h2 class="text-6xl font-black text-blue-900">100+</h2><p>Years</p></div>
<div><h2 class="text-6xl font-black text-blue-900">40+</h2><p>Countries</p></div>
</div>
</section>

<!-- Services -->
<section class="py-20 bg-gray-50">
<div class="max-w-7xl mx-auto px-6">
<h2 class="text-5xl font-black text-center mb-12">Our Focus</h2>
<div class="grid md:grid-cols-4 gap-8">
<div class="card transition-all duration-300 bg-white rounded-2xl p-6 shadow-xl"><h3 class="text-2xl font-bold">Advocacy</h3></div>
<div class="card transition-all duration-300 bg-white rounded-2xl p-6 shadow-xl"><h3 class="text-2xl font-bold">Statistics</h3></div>
<div class="card transition-all duration-300 bg-white rounded-2xl p-6 shadow-xl"><h3 class="text-2xl font-bold">Sustainability</h3></div>
<div class="card transition-all duration-300 bg-white rounded-2xl p-6 shadow-xl"><h3 class="text-2xl font-bold">Events</h3></div>
</div>
</div>
</section>

<!-- Events -->
<section class="py-20">
<div class="max-w-7xl mx-auto px-6">
<h2 class="text-5xl font-black text-center mb-12">Upcoming Events</h2>
<div class="grid md:grid-cols-3 gap-8">
<div class="card transition-all duration-300 rounded-2xl overflow-hidden shadow-xl"><img src="https://images.unsplash.com/photo-1511578314322-379afb476865?auto=format&fit=crop&w=800&q=80"><div class="p-6"><h3 class="text-2xl font-bold">ISPA EXPO</h3></div></div>
<div class="card transition-all duration-300 rounded-2xl overflow-hidden shadow-xl"><img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=80"><div class="p-6"><h3 class="text-2xl font-bold">Sustainability Conference</h3></div></div>
<div class="card transition-all duration-300 rounded-2xl overflow-hidden shadow-xl"><img src="https://images.unsplash.com/photo-1505373877841-8d25f7d46678?auto=format&fit=crop&w=800&q=80"><div class="p-6"><h3 class="text-2xl font-bold">Industry Conference</h3></div></div>
</div>
</div>
</section>

<!-- CTA -->
<section class="py-24 bg-blue-900 text-white text-center">
<h2 class="text-5xl font-black">Become Part of the Future of Sleep</h2>
<p class="text-xl mt-4">Connect, innovate, and grow with ISPA.</p>
<a class="inline-block mt-8 bg-white text-blue-900 px-8 py-4 rounded-xl">Become a Member</a>
</section>

<!-- Footer -->
<footer class="bg-gray-950 text-gray-300 py-16">
<div class="max-w-7xl mx-auto grid md:grid-cols-4 gap-8 px-6">
<div><h3 class="text-white font-bold mb-4">About</h3><p>Membership</p><p>Contact</p></div>
<div><h3 class="text-white font-bold mb-4">Resources</h3><p>FAQs</p><p>Research</p></div>
<div><h3 class="text-white font-bold mb-4">Events</h3><p>EXPO</p><p>Conference</p></div>
<div><h3 class="text-white font-bold mb-4">News</h3><p>Latest Updates</p></div>
</div>
<div class="text-center mt-10">© 2026 ISPA</div>
</footer>

</body>
</html>
