
/* Assignment 9.1: Mobile-First Responsive Layout */

/* Common CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f7f7f2;
    color: #222820;
    line-height: 1.6;
}

img {
    display: block;
    width: 100%;
    max-width: 100%;
}

.container {
    width: min(100% - 32px, 1100px);
    margin: 0 auto;
}

/* Header */
header {
    background-color: white;
    border-bottom: 1px solid #dddddd;
}

.navbar {
    display: flex;
    flex-direction: column;
    gap: 12px;
    padding-top: 18px;
    padding-bottom: 18px;
}

.logo {
    color: #35452c;
    font-size: 26px;
}

nav {
    display: flex;
    flex-wrap: wrap;
    gap: 12px 18px;
}

nav a {
    color: #444444;
    text-decoration: none;
    font-size: 15px;
}

nav a:hover {
    color: #718b50;
}

/* Hero Section */
.hero {
    padding-top: 45px;
    padding-bottom: 35px;
}

.subtitle {
    color: #718b50;
    font-size: 12px;
    font-weight: bold;
    letter-spacing: 3px;
}

h1 {
    margin-top: 12px;
    font-size: clamp(34px, 8vw, 65px);
    line-height: 1.15;
}

h1 span {
    color: #718b50;
}

.description {
    max-width: 550px;
    margin-top: 15px;
    color: #666666;
}

/* Gallery Section */
.gallery-section {
    padding-top: 15px;
    padding-bottom: 55px;
}

.section-heading {
    margin-bottom: 22px;
}

.section-heading h2 {
    font-size: 27px;
}

.section-heading p {
    color: #777777;
    margin-top: 5px;
}

/* Mobile: one column */
.gallery-grid {
    display: grid;
    grid-template-columns: minmax(0, 1fr);
    gap: 20px;
}

.card {
    min-width: 0;
    overflow: hidden;
    background-color: white;
    border: 1px solid #e0e0d8;
    border-radius: 12px;
}

.card img {
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
}

.card-info {
    padding: 15px;
}

.card-info h3 {
    font-size: 18px;
}

.card-info p {
    color: #777777;
    font-size: 14px;
}

/* Footer */
footer {
    padding: 22px 15px;
    background-color: #263126;
    color: white;
    text-align: center;
    font-size: 13px;
}

/* Breakpoint 1: Tablet */
@media (min-width: 600px) {
    .navbar {
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }

    .hero {
        padding-top: 65px;
        padding-bottom: 45px;
    }

    .gallery-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 22px;
    }

    .section-heading {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
}

/* Breakpoint 2: Desktop */
@media (min-width: 900px) {
    .hero {
        padding-top: 85px;
        padding-bottom: 60px;
    }

    .gallery-grid {
        grid-template-columns: repeat(3, minmax(0, 1fr));
        gap: 25px;
    }

    .gallery-section {
        padding-bottom: 75px;
    }
}

/* Extra-small mobile screen */
@media (max-width: 360px) {
    .container {
        width: calc(100% - 24px);
    }

    nav {
        gap: 10px;
    }
}
