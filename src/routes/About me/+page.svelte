<script>
    // About Page Logic
</script>

<svelte:head>
    <title>About Me</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
</svelte:head>

<header class="bg-gradient-to-r from-blue-600 to-blue-400 p-6 rounded-lg shadow-lg mb-8 flex items-center justify-between">
    <div class="flex items-center">
        <img src="/src/assets/jake.jpg" alt="Logo" class="h-12 w-12 mr-4 rounded-full border-2 border-white shadow-lg transition-transform duration-300 transform hover:scale-110"> <!-- Enhanced Logo -->
        <nav class="flex space-x-12"> <!-- Increased space between links -->
            <a href="/" class="text-white font-semibold text-lg tracking-wider hover:bg-blue-700 hover:shadow-lg px-6 py-3 rounded-full transition-all duration-300 ease-in-out">Home</a>
            <a href="/About me" class="text-white font-semibold text-lg tracking-wider hover:bg-blue-700 hover:shadow-lg px-6 py-3 rounded-full transition-all duration-300 ease-in-out">About me</a>
            <a href="/Contact" class="text-white font-semibold text-lg tracking-wider hover:bg-blue-700 hover:shadow-lg px-6 py-3 rounded-full transition-all duration-300 ease-in-out">Contact</a>
            <a href="/Portfolio" class="text-white font-semibold text-lg tracking-wider hover:bg-blue-700 hover:shadow-lg px-6 py-3 rounded-full transition-all duration-300 ease-in-out">Portfolio</a>
        </nav>
    </div>
</header> 

<main class="max-w-5xl mx-auto px-10 py-10 bg-gradient-to-br from-blue-50 to-blue-100 rounded-lg shadow-lg transition duration-300 hover:shadow-xl">
    <h1 class="text-5xl font-bold text-center mb-6 text-gray-800 underline decoration-blue-400">About Me</h1>
    <p class="text-lg text-gray-700 mb-6 leading-relaxed border-b-2 border-gray-300 pb-4">
        Hi! I’m <span class="font-semibold text-blue-600">Allen Jake Orel Lavina</span>, a joyful 21-year-old third-year college student studying Information Technology. I love playing online and PC games, and I'm a fan of movies and English series, especially those about historical wars.
    </p>
    <p class="text-lg text-gray-700 mb-6 leading-relaxed">
        I'm always eager to learn new things and expand my horizons. Traveling is another passion of mine, as it allows me to experience different cultures and create unforgettable memories. I'm excited about what the future holds and look forward to new adventures!
    </p>
    <div class="text-center mt-6">
        <a href="/Contact" class="bg-blue-600 text-white font-semibold py-2 px-4 rounded-lg shadow hover:bg-blue-700 transition duration-300">Get in Touch</a>
    </div>
</main>


