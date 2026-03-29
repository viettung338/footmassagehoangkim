
:root {
    --gold: #D4AF37;
    --dark: #1a1a1a;
    --light: #f4f4f4;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    color: #333;
}

.container {
    width: 85%;
    margin: auto;
    overflow: hidden;
}

/* Header */
header {
    background: var(--dark);
    color: #fff;
    padding: 20px 0;
    border-bottom: 2px solid var(--gold);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.logo {
    float: left;
    font-family: 'Playfair Display', serif;
}

.logo span {
    color: var(--gold);
}

nav {
    float: right;
    margin-top: 10px;
}

nav ul li {
    display: inline;
    margin-left: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 14px;
}

.btn-booking {
    background: var(--gold);
    padding: 10px 20px;
    border-radius: 5px;
    color: var(--dark) !important;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                url('https://images.unsplash.com/photo-1544161515-4ab6ce6db874?auto=format&fit=crop&w=1350&q=80');
    background-size: cover;
    background-position: center;
    height: 80vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #fff;
}

.hero h2 {
    font-size: 3rem;
    font-family: 'Playfair Display', serif;
    margin-bottom: 20px;
}

.btn-main {
    display: inline-block;
    margin-top: 20px;
    padding: 15px 30px;
    background: var(--gold);
    color: var(--dark);
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

/* Services */
.services {
    padding: 60px 0;
    background: #fff;
}

.section-title {
    text-align: center;
    margin-bottom: 40px;
    font-size: 2.5rem;
}

.service-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.service-card {
    padding: 30px;
    border: 1px solid #ddd;
    text-align: center;
    transition: 0.3s;
}

.service-card:hover {
    border-color: var(--gold);
    transform: translateY(-5px);
}

.service-card h3 {
    color: var(--gold);
    margin-bottom: 15px;
}

/* Footer */
footer {
    background: var(--dark);
    color: #fff;
    padding: 50px 0 20px;
    text-align: center;
}

footer h2 {
    color: var(--gold);
    margin-bottom: 20px;
}

.footer-bottom {
    margin-top: 30px;
    font-size: 0.8rem;
    border-top: 1px solid #444;
    padding-top: 20px;
}
