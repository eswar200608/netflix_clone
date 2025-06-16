<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix - Watch TV Shows Online, Watch Movies Online</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="C:\Users\laksh\Desktop\netflix.png" type="image/png">
    <script src="https://kit.fontawesome.com/YOUR_FONT_AWESOME_KIT_CODE.js" crossorigin="anonymous"></script>
</head>
<body>

    <header class="navbar">
        <div class="container">
            <a href="#" class="logo" aria-label="Netflix Home">
                <img src=""C:\Users\laksh\Desktop\netflix.png"" alt="Netflix Logo">
            </a>
            <nav class="main-nav" aria-label="Main Navigation">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">TV Shows</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">New & Popular</a></li>
                    <li><a href="#">My List</a></li>
                    <li><a href="#">Browse by Languages</a></li>
                </ul>
            </nav>
            <div class="secondary-nav">
                <button class="icon-button" aria-label="Search">
                    <i class="fas fa-search" aria-hidden="true"></i>
                </button>
                <a href="#" class="text-link">Kids</a>
                <button class="icon-button" aria-label="Notifications">
                    <i class="fas fa-bell" aria-hidden="true"></i>
                </button>
                <div class="profile-dropdown">
                    <button class="profile-toggle" aria-haspopup="true" aria-expanded="false" aria-label="Profile Menu">
                        <img src="images/profile_avatar.png" alt="User Profile Avatar" class="profile-avatar">
                        <i class="fas fa-caret-down" aria-hidden="true"></i>
                    </button>
                    <ul class="dropdown-menu" role="menu">
                        <li role="none"><a href="#" role="menuitem">Manage Profiles</a></li>
                        <li role="none"><a href="#" role="menuitem">Account</a></li>
                        <li role="none"><a href="#" role="menuitem">Help Center</a></li>
                        <li role="none"><a href="#" role="menuitem">Sign Out</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </header>

    <main>
        <section class="hero-section" aria-labelledby="hero-title">
            <div class="hero-content">
                <h1 id="hero-title">The Witcher</h1>
                <p>Geralt of Rivia, a mutated monster-hunter for hire, journeys toward his destiny in a turbulent world where people often prove more wicked than beasts.</p>
                <div class="hero-buttons">
                    <button class="play-button" aria-label="Play The Witcher">
                        <i class="fas fa-play" aria-hidden="true"></i> Play
                    </button>
                    <button class="info-button" aria-label="More Info about The Witcher">
                        <i class="fas fa-info-circle" aria-hidden="true"></i> More Info
                    </button>
                </div>
            </div>
            </section>

        <section class="content-row-section" aria-labelledby="trending-now-heading">
            <h2 id="trending-now-heading">Trending Now</h2>
            <div class="row-container">
                <article class="movie-card">
                    <a href="#" aria-label="View details for Movie Title 1">
                        <img src="images/movie_thumbnail_1.jpg" alt="Movie Title 1 Thumbnail">
                        <div class="card-overlay">
                            <h3>Movie Title 1</h3>
                            </div>
                    </a>
                </article>
                <article class="movie-card">
                    <a href="#" aria-label="View details for Movie Title 2">
                        <img src="images/movie_thumbnail_2.jpg" alt="Movie Title 2 Thumbnail">
                        <div class="card-overlay">
                            <h3>Movie Title 2</h3>
                        </div>
                    </a>
                </article>
                </div>
        </section>

        <section class="content-row-section" aria-labelledby="netflix-originals-heading">
            <h2 id="netflix-originals-heading">Netflix Originals</h2>
            <div class="row-container">
                <article class="movie-card">
                    <a href="#" aria-label="View details for Movie Title 3">
                        <img src="images/movie_thumbnail_3.jpg" alt="Movie Title 3 Thumbnail">
                        <div class="card-overlay">
                            <h3>Movie Title 3</h3>
                        </div>
                    </a>
                </article>
                <article class="movie-card">
                    <a href="#" aria-label="View details for Movie Title 4">
                        <img src="images/movie_thumbnail_4.jpg" alt="Movie Title 4 Thumbnail">
                        <div class="card-overlay">
                            <h3>Movie Title 4</h3>
                        </div>
                    </a>
                </article>
                </div>
        </section>

        <section class="content-row-section" aria-labelledby="continue-watching-heading">
            <h2 id="continue-watching-heading">Continue Watching for [User Name]</h2>
            <div class="row-container">
                <article class="movie-card">
                    <a href="#" aria-label="Continue watching Movie Title 5">
                        <img src="images/movie_thumbnail_5.jpg" alt="Movie Title 5 Thumbnail">
                        <div class="card-overlay">
                            <h3>Movie Title 5</h3>
                            </div>
                    </a>
                </article>
                <article class="movie-card">
                    <a href="#" aria-label="Continue watching Movie Title 6">
                        <img src="images/movie_thumbnail_6.jpg" alt="Movie Title 6 Thumbnail">
                        <div class="card-overlay">
                            <h3>Movie Title 6</h3>
                        </div>
                    </a>
                </article>
                </div>
        </section>

        </main>

    <footer class="footer">
        <div class="container">
            <div class="social-links" role="contentinfo" aria-label="Social Media Links">
                <a href="#" aria-label="Netflix on Facebook"><i class="fab fa-facebook-f" aria-hidden="true"></i></a>
                <a href="#" aria-label="Netflix on Instagram"><i class="fab fa-instagram" aria-hidden="true"></i></a>
                <a href="#" aria-label="Netflix on Twitter"><i class="fab fa-twitter" aria-hidden="true"></i></a>
                <a href="#" aria-label="Netflix on YouTube"><i class="fab fa-youtube" aria-hidden="true"></i></a>
            </div>
            <nav class="footer-nav" aria-label="Footer Navigation">
                <ul>
                    <li><a href="#">Audio Description</a></li>
                    <li><a href="#">Help Center</a></li>
                    <li><a href="#">Gift Cards</a></li>
                    <li><a href="#">Media Center</a></li>
                    <li><a href="#">Investor Relations</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Terms of Use</a></li>
                    <li><a href="#">Privacy</a></li>
                    <li><a href="#">Legal Notices</a></li>
                    <li><a href="#">Cookie Preferences</a></li>
                    <li><a href="#">Corporate Information</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </nav>
            <p>&copy; 2025 Netflix, Inc.</p>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
