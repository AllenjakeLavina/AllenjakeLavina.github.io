<script>
    // Contact Page Logic
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"> <!-- Ensure Font Awesome is included -->
</svelte:head>

<div class="min-h-screen flex flex-col">
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

    <main class="flex-grow max-w-7xl mx-auto px-4 py-10 bg-white rounded-lg shadow-xl">
        <h2 class="text-5xl font-bold mb-6 text-center text-gray-800">Connect with Me</h2>
        <p class="text-lg mb-8 text-center text-gray-600">I’d love to hear from you! Connect with me on any of these platforms:</p>
        
        <div class="flex justify-center space-x-8 mb-10">
            <a href="https://www.facebook.com/allen.lavina" class="bg-blue-500 border border-blue-600 rounded-full p-4 shadow-lg hover:bg-blue-600 transform hover:scale-110 transition duration-300" target="_blank">
                <i class="fab fa-facebook-f text-white text-4xl"></i> <!-- Font Awesome icon -->
            </a>
            <a href="https://www.instagram.com/lav_nlla/profilecard/?igsh=MWlyczMyNnVvZmYxZw==" class="bg-gradient-to-r from-pink-500 to-pink-400 border border-pink-600 rounded-full p-4 shadow-lg hover:scale-110 transform transition duration-300" target="_blank">
                <i class="fab fa-instagram text-white text-4xl"></i> <!-- Font Awesome icon -->
            </a>
            <a href="https://www.tiktok.com/@lnellaaaaa" class="bg-black border border-gray-800 rounded-full p-4 shadow-lg hover:bg-gray-800 transform hover:scale-110 transition duration-300" target="_blank">
                <i class="fab fa-tiktok text-white text-4xl"></i> <!-- Font Awesome icon -->
            </a>
        </div>
        
        <p class="text-center text-lg text-gray-600">Thank you for connecting! I look forward to hearing from you.</p>
    </main>

    <footer class="bg-blue-600 p-4 rounded-lg shadow-md mt-10">
        <p class="text-center text-white text-sm">© 2024 Your Name. All rights reserved.</p>
    </footer>
</div>