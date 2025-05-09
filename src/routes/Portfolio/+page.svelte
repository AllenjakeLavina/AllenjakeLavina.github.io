<script>
    // Portfolio Page Logic
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
</svelte:head>

<header>
    <div class="flex">
        <img src="images/allen.jpg" alt="Logo">
        <nav>
            <a href="/">Home</a>
            <a href="/About me">About me</a>
            <a href="/Contact">Contact</a>
            <a href="/Portfolio">Portfolio</a>
        </nav>
    </div>
</header> 

<section>
    <h2>My Projects</h2>
    <div class="grid">
        <!-- Project 1 -->
        <div class="project-card">
            <img src="images/Project1.png" alt="Project One">
            <h3>Portfolio a First Year Midterm Project</h3>
            <p>HTML & CSS</p>
        </div>
        <!-- Project 2-->
        <div class="project-card">
            <img src="images/Project2.png" alt="Project Two">
            <h3>Weather App</h3>
            <p>Assessment Project Angular</p>
        </div>
        <!-- Project 3-->
        <div class="project-card">
            <img src="images/Project3.png" alt="Project Three">
            <h3>Appointment System</h3>
            <p>Angular Project</p>
        </div>
    </div>
</section>

<p class="text-center">Welcome to the Portfolio page.</p>

<style>
    /* General Styles */
    body {
        font-family: 'Outfit', sans-serif;
    }

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

    /* Section Styles */
    section {
        max-width: 80rem;
        margin: 0 auto;
        padding: 2.5rem;
    }

    h2 {
        font-size: 2.5rem;
        font-weight: 700;
        text-align: center;
        margin-bottom: 2.5rem;
    }

    .grid {
        display: grid;
        grid-template-columns: repeat(1, 1fr);
        gap: 2rem;
    }

    .project-card {
        background-color: white;
        border-radius: 1rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        padding: 1.5rem;
        transition: transform 0.3s ease;
    }

    .project-card:hover {
        transform: scale(1.05);
    }

    .project-card img {
        width: 100%;
        height: 12rem;
        object-fit: cover;
        border-radius: 0.5rem;
        margin-bottom: 1rem;
    }

    .project-card h3 {
        font-size: 1.5rem;
        font-weight: 600;
        margin-bottom: 1rem;
    }

    .project-card p {
        color: #4A5568;
    }

    .text-center {
        text-align: center;
        margin-top: 2rem;
    }
</style>
