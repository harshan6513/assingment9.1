
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Photo Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="container navbar">
            <h2 class="logo">PhotoSpace.</h2>

            <nav>
                <a href="#home">Home</a>
                <a href="#gallery">Gallery</a>
                <a href="#about">About</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero container" id="home">
            <p class="subtitle">A LITTLE INSPIRATION</p>
            <h1>Moments worth <span>remembering.</span></h1>
            <p class="description">
                Explore beautiful photographs of nature,
                travel and everyday moments.
            </p>
        </section>

        <section class="container gallery-section" id="gallery">
            <div class="section-heading">
                <h2>Explore the Gallery</h2>
                <p>Our collection of beautiful photographs</p>
            </div>

            <div class="gallery-grid">

                <div class="card">
                    <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=800&q=80" alt="Beautiful mountains">
                    <div class="card-info">
                        <h3>Mountain View</h3>
                        <p>Nature Photography</p>
                    </div>
                </div>

                <div class="card">
                    <img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?auto=format&fit=crop&w=800&q=80" alt="Beautiful lake">
                    <div class="card-info">
                        <h3>Peaceful Lake</h3>
                        <p>Travel Photography</p>
                    </div>
                </div>

                <div class="card">
                    <img src="https://images.unsplash.com/photo-1490750967868-88aa4486c946?auto=format&fit=crop&w=800&q=80" alt="Beautiful flowers">
                    <div class="card-info">
                        <h3>Colorful Flowers</h3>
                        <p>Flower Photography</p>
                    </div>
                </div>

                <div class="card">
                    <img src="https://images.unsplash.com/photo-1518837695005-2083093ee35b?auto=format&fit=crop&w=800&q=80" alt="Ocean waves">
                    <div class="card-info">
                        <h3>Ocean Waves</h3>
                        <p>Sea Photography</p>
                    </div>
                </div>

                <div class="card">
                    <img src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e?auto=format&fit=crop&w=800&q=80" alt="Green forest">
                    <div class="card-info">
                        <h3>Green Forest</h3>
                        <p>Nature Photography</p>
                    </div>
                </div>

                <div class="card">
                    <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=800&q=80" alt="Beautiful beach">
                    <div class="card-info">
                        <h3>Tropical Beach</h3>
                        <p>Travel Photography</p>
                    </div>
                </div>

            </div>
        </section>
    </main>

    <footer id="contact">
        <p>© 2026 PhotoSpace | Responsive Web Design Assignment</p>
    </footer>

</body>
</html>
