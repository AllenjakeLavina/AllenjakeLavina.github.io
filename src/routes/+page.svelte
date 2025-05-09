<header class="header">
    <div class="flex items-center">
        <img src="images/allen.jpg" alt="Logo" class="logo">
        <nav class="nav">
            <a href="/" class="nav-link">Home</a>
            <a href="/About me" class="nav-link">About me</a>
            <a href="/Contact" class="nav-link">Contact</a>
            <a href="/Portfolio" class="nav-link">Portfolio</a>
        </nav>
    </div>
</header>

<main class="main">
    <section class="section">
        <h1 class="heading">
            WELCOME!
        </h1>
        <p class="text">
            Howdy! I appreciate having you here. This website contains a collection of my work, an overview of my journey, and the projects I have worked on.
        </p>
        <p class="text">
            To know more about me, click in the <span class="highlight">“About Me”</span> section; check out my portfolio and delve into my innovative works. For further information, you can reach me through the <span class="highlight">“Contact”</span> page.
        </p>
        <p class="text">
            Thank you for visiting!
        </p>
    </section>
</main>

<style>
    /* Header Styles */
    .header {
        background: linear-gradient(to right, #1e40af, #3b82f6);
        padding: 1.5rem;
        border-radius: 0.5rem;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        margin-bottom: 2rem;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .logo {
        height: 3rem;
        width: 3rem;
        margin-right: 1rem;
        border-radius: 50%;
        border: 2px solid white;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s;
    }

    .logo:hover {
        transform: scale(1.1);
    }

    .nav {
        display: flex;
        gap: 3rem;
    }

    .nav-link {
        color: white;
        font-weight: 600;
        font-size: 1.125rem;
        letter-spacing: 0.05rem;
        padding: 0.75rem 1.5rem;
        border-radius: 9999px;
        transition: all 0.3s ease-in-out;
    }

    .nav-link:hover {
        background-color: #1d4ed8;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    /* Main Section Styles */
    .main {
        display: flex;
        justify-content: center;
        align-items: center;
        height: calc(100vh - 40px); /* Adjust height for header */
    }

    .section {
        background-color: rgba(255, 255, 255, 0.9);
        padding: 2.5rem;
        border-radius: 1rem;
        box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        text-align: center;
        max-width: 48rem;
    }

    .heading {
        font-size: 3rem;
        font-weight: 800;
        margin-bottom: 1.5rem;
        color: #1e3a8a;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
    }

    .text {
        font-size: 1.125rem;
        color: #4b5563;
        margin-bottom: 1rem;
        line-height: 1.75;
    }

    .highlight {
        color: #3b82f6;
        font-weight: bold;
    }
</style>
