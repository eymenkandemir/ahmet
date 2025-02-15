* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Arial, sans-serif;
    line-height: 1.6;
    background-color: #f5f5f5;
}

header {
    background-color: #2c3e50;
    padding: 1rem;
    position: fixed;
    width: 100%;
    top: 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

.logo {
    color: white;
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
    transition: 0.3s;
}

nav ul li a:hover {
    background-color: #34495e;
    border-radius: 4px;
}

main {
    margin-top: 80px;
}

.hero {
    text-align: center;
    padding: 4rem 2rem;
    background-color: #3498db;
    color: white;
}

.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.featured-books {
    max-width: 1200px;
    margin: 2rem auto;
    padding: 0 1rem;
}

.featured-books h2 {
    text-align: center;
    margin-bottom: 2rem;
    color: #2c3e50;
}

.book-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.book-card {
    background-color: white;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    text-align: center;
}

.book-card img {
    width: 100%;
    max-width: 200px;
    height: auto;
    margin-bottom: 1rem;
}

.book-card h3 {
    color: #2c3e50;
    margin-bottom: 0.5rem;
}

footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}

@media (max-width: 768px) {
    nav {
        flex-direction: column;
        text-align: center;
    }

    nav ul {
        margin-top: 1rem;
        flex-direction: column;
    }

    nav ul li {
        margin: 0.5rem 0;
    }
}
