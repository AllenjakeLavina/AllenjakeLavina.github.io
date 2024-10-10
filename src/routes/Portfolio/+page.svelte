<script>
    // Portfolio Page Logic
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
</svelte:head>

<header class="bg-gradient-to-r from-blue-600 to-blue-400 p-6 rounded-lg shadow-lg mb-8 flex items-center justify-between">
    <div class="flex items-center">
        <img src="images/allen.jpg" alt="Logo" class="h-12 w-12 mr-4 rounded-full border-2 border-white shadow-lg transition-transform duration-300 transform hover:scale-110"> <!-- Enhanced Logo -->
        <nav class="flex space-x-12"> <!-- Increased space between links -->
            <a href="/" class="text-white font-semibold text-lg tracking-wider hover:bg-blue-700 hover:shadow-lg px-6 py-3 rounded-full transition-all duration-300 ease-in-out">Home</a>
            <a href="/About me" class="text-white font-semibold text-lg tracking-wider hover:bg-blue-700 hover:shadow-lg px-6 py-3 rounded-full transition-all duration-300 ease-in-out">About me</a>
            <a href="/Contact" class="text-white font-semibold text-lg tracking-wider hover:bg-blue-700 hover:shadow-lg px-6 py-3 rounded-full transition-all duration-300 ease-in-out">Contact</a>
            <a href="/Portfolio" class="text-white font-semibold text-lg tracking-wider hover:bg-blue-700 hover:shadow-lg px-6 py-3 rounded-full transition-all duration-300 ease-in-out">Portfolio</a>
        </nav>
    </div>
</header> 

<section class="max-w-7xl mx-auto px-4 py-10">
    <h2 class="text-4xl font-bold text-center mb-10">My Projects</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Project 1 -->
        <div class="bg-white rounded-lg shadow-lg p-6 transition-transform transform hover:scale-105">
            <img src="images/Project1.png" alt="Project One" class="w-full h-48 object-cover rounded-md mb-4">
            <h3 class="text-2xl font-bold mb-2">Portfolio/Midterm Project</h3>
            <p class="text-gray-600 mb-4">HTML & CSS</p>
        </div>
        <!-- Project 2-->
        <div class="bg-white rounded-lg shadow-lg p-6 transition-transform transform hover:scale-105">
            <img src="images/Project2.png" alt="Project Two" class="w-full h-48 object-cover rounded-md mb-4">
            <h3 class="text-2xl font-bold mb-2">Weather App</h3>
            <p class="text-gray-600 mb-4">Angular</p>
        </div>
        <!-- Project 3-->
        <div class="bg-white rounded-lg shadow-lg p-6 transition-transform transform hover:scale-105">
            <img src="images/Project3.png" alt="Project Three" class="w-full h-48 object-cover rounded-md mb-4">
            <h3 class="text-2xl font-bold mb-2">Appointment System</h3>
            <p class="text-gray-600 mb-4">Angular Project</p>
        </div>
    </div>
</section>

<p class="text-center mt-10 text-gray-700">Welcome to the Portfolio page.</p>
