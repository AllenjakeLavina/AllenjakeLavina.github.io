<script>
    import "../app.css"; 
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
</svelte:head>

<header class="bg-white p-4 rounded-lg shadow-md mb-6">
    <nav class="flex justify-center space-x-4">
        <a href="/" class="text-gray-700 hover:text-orange-600">Home</a>
        <a href="/About me" class="text-gray-700 hover:text-orange-600">About me</a>
        <a href="/Contact" class="text-gray-700 hover:text-orange-600">Contact</a>
        <a href="/Portfolio" class="text-gray-700 hover:text-orange-600">Portfolio</a>
    </nav>
</header>

<main class="flex justify-center items-center h-screen">
    <section class="bg-white bg-opacity-80 p-8 rounded-lg shadow-lg text-center">
        <h1 class="text-4xl font-bold mb-4 text-gray-800">Welcome!</h1>
        <p class="text-lg mb-2 text-gray-600">Hello there! I am thrilled to have you here. On this website, you will find a collection of my work, insights about my journey, and various projects I have undertaken.</p>
        <p class="text-lg mb-2 text-gray-600">Explore my portfolio to see my creative endeavors, learn more about me in the "About Me" section, or get in touch through the "Contact" page.</p>
        <p class="text-lg text-gray-600">Thank you for visiting, and I hope you enjoy your stay!</p>
    </section>
</main>

<slot></slot>
