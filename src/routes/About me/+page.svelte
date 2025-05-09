<svelte:head>
    <title>About Me</title>
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

<main>
    <h1>About Me</h1>
    <p>
        Hi! I’m <span>Allen Jake Orel Lavina</span>, a joyful 21-year-old third-year college student studying Information Technology. I love playing online and PC games, and I'm a fan of movies and English series, especially those about historical wars.
    </p>
    <p>
        I'm always eager to learn new things and expand my horizons. Traveling is another passion of mine, as it allows me to experience different cultures and create unforgettable memories. I'm excited about what the future holds and look forward to new adventures!
    </p>
    <div class="text-center">
        <a href="/Contact">Get in Touch</a>
    </div>
</main>

<style>
    /* General Styles */
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
        max-width: 72rem;
        margin: 0 auto;
        padding: 2.5rem;
        background: linear-gradient(to bottom right, #EFF6FF, #BFDBFE);
        border-radius: 1rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        transition: box-shadow 0.3s ease;
    }

    main:hover {
        box-shadow: 0 6px 8px rgba(0, 0, 0, 0.2);
    }

    main h1 {
        font-size: 3rem;
        font-weight: 700;
        text-align: center;
        margin-bottom: 1.5rem;
        color: #2D3748;
        text-decoration: underline;
        text-decoration-color: #3B82F6;
    }

    main p {
        font-size: 1.125rem;
        color: #4A5568;
        margin-bottom: 1.5rem;
        line-height: 1.75rem;
    }

    main p span {
        font-weight: 600;
        color: #2563EB;
    }

    main .text-center {
        margin-top: 1.5rem;
    }

    .text-center a {
        background-color: #2563EB;
        color: white;
        font-weight: 600;
        padding: 0.5rem 1rem;
        border-radius: 0.75rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        transition: all 0.3s ease;
    }

    .text-center a:hover {
        background-color: #1D4ED8;
    }
</style>
