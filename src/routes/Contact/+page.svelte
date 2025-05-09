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
    <header>
        <div class="flex items-center">
            <img src="images/allen.jpg" alt="Logo" class="h-12 w-12 mr-4 rounded-full border-2 border-white shadow-lg transition-transform duration-300 transform hover:scale-110"> <!-- Enhanced Logo -->
            <nav>
                <a href="/">Home</a>
                <a href="/About me">About me</a>
                <a href="/Contact">Contact</a>
                <a href="/Portfolio">Portfolio</a>
            </nav>
        </div>
    </header> 

    <main>
        <h2>Connect with Me</h2>
        <p>I’d love to hear from you! Connect with me on any of these platforms:</p>
        
        <div class="flex justify-center space-x-8 mb-10">
            <a href="https://www.facebook.com/allen.lavina" class="social-icon facebook" target="_blank">
                <i class="fab fa-facebook-f"></i>
            </a>
            <a href="https://www.instagram.com/lav_nlla/profilecard/?igsh=MWlyczMyNnVvZmYxZw==" class="social-icon instagram" target="_blank">
                <i class="fab fa-instagram"></i>
            </a>
            <a href="https://www.tiktok.com/@lnellaaaaa" class="social-icon tiktok" target="_blank">
                <i class="fab fa-tiktok"></i>
            </a>
        </div>
        
        <p>Thank you for connecting! I look forward to hearing from you.</p>
    </main>

    <footer>
        <p>© 2024 Allen Jake Lavina. All rights reserved.</p>
    </footer>
</div>

<style>
    /* Header Styles */
    header {
        background: linear-gradient(to right, #1D4ED8, #3B82F6);
        padding: 1.5rem;
        border-radius: 1rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        margin-bottom: 2rem;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    header .flex {
        display: flex;
        align-items: center;
    }

    header img {
        height: 3rem;
        width: 3rem;
        margin-right: 1rem;
        border-radius: 50%;
        border: 2px solid white;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease;
    }

    header img:hover {
        transform: scale(1.1);
    }

    nav {
        display: flex;
        gap: 3rem;
    }

    nav a {
        color: white;
        font-weight: 600;
        font-size: 1.125rem;
        letter-spacing: 0.05rem;
        padding: 0.75rem 1.5rem;
        border-radius: 9999px;
        text-align: center;
        transition: all 0.3s ease;
    }

    nav a:hover {
        background-color: #1D4ED8;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
    }

    /* Main Section Styles */
    main {
        max-width: 80rem;
        margin: 0 auto;
        padding: 2.5rem;
        background-color: white;
        border-radius: 1rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    h2 {
        font-size: 2.5rem;
        font-weight: 700;
        text-align: center;
        margin-bottom: 2.5rem;
        color: #2D3748;
    }

    p {
        font-size: 1.125rem;
        color: #4A5568;
        text-align: center;
        margin-bottom: 2rem;
    }

    .flex {
        display: flex;
        justify-content: center;
        gap: 2rem;
    }

    /* Social Icon Styles */
    .social-icon {
        background-color: #3B82F6;
        border-radius: 50%;
        padding: 1rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        transition: all 0.3s ease;
    }

    .social-icon:hover {
        transform: scale(1.1);
    }

    .social-icon i {
        color: white;
        font-size: 2rem;
    }

    .facebook {
        background-color: #3B82F6;
    }

    .facebook:hover {
        background-color: #2563EB;
    }

    .instagram {
        background: linear-gradient(to right, #D61C84, #EC4899);
    }

    .instagram:hover {
        background: linear-gradient(to right, #9B1D5B, #9B1D5B);
    }

    .tiktok {
        background-color: #000;
    }

    .tiktok:hover {
        background-color: #333;
    }

    /* Footer Styles */
    footer {
        background-color: #1D4ED8;
        padding: 1rem;
        border-radius: 1rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        margin-top: 2rem;
    }

    footer p {
        color: white;
        text-align: center;
        font-size: 0.875rem;
    }
</style>
