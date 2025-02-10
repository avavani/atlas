+++
date = '2025-01-31T20:04:02-05:00'
draft = false
title = 'About'
excludeFromIndex = true
+++

<div class="hero-section">
    <div class="hero-text">
        <h1 class="greeting">Hi, I'm Avani <span class="wave">👋</span></h1>
    </div>
    <div class="hero-image">
        <img src="avani.jpeg" alt="Avani" class="profile-image">
    </div>
</div>

<div class="main-content">
    <div class="intro-section">
    <p>I'm a technologist passionate about leveraging spatial data to address our most pressing challenges.</p> 
    <p>The individual person thinks in terms of space. Spatial data can help uncover unique insights on transit, consumer behaviour, public health, supply chains, and labour markets through a people-first lens.</p>
    <p>This is my personal website where I document my own learnings about our world. I am very grateful to all that are taking their time to view my work—please feel free to direct any feedback, suggestions, or thoughts to my <a href="mailto:avaniadhikari@hotmail.com">email</a>.
    </p>
</div>
<div class="gallery-section">
    <h2 class="gallery-header">Featured Projects</h2>
    <div class="gallery-grid">
        <a href="/posts/nepal_census/" class="gallery-item">
            <img src="valmap.png" alt="Map showing Household Wealth Distribution in Kathmandu Valley">
            <div class="gallery-overlay">
                <h3 class="gallery-title">Unpacking Nepal's Census</h3>
                <p class="gallery-description">Using data cleaning methods, I converted tabular census data into spatial formats that can be easily mapped.</p>
            </div>
        </a>
        <a href="/posts/coal-plants/" class="gallery-item">
            <img src="coal.png" alt="Map showing distribution of coal plants in America">
            <div class="gallery-overlay">
                <h3 class="gallery-title">Where are America's Coal Plants?</h3>
                <p class="gallery-description">A short analysis of the coal industry in America.</p>
            </div>
        </a>
        <a href="/posts/spotspotter-a-parking-finder/" class="gallery-item">
            <img src="img3.png" alt="Screenshot from Parking Finder App">
            <div class="gallery-overlay">
                <h3 class="gallery-title">Spotspotter</h3>
                <p class="gallery-description">Spotspotter is my first mobile application that seeks to crowdsource information on parking availability.</p>
            </div>
        </a>
        <a href="/philly-crash" class="gallery-item">
            <img src="crash.png" alt="Philadelphia's Crash Index">
            <div class="gallery-overlay">
                <h3 class="gallery-title">Finding Safe Strees in Philly</h3>
                <p class="gallery-description">Analysis of traffic accident patterns and safety metrics across Philadelphia.</p>
            </div>
        </a>
    </div>
</div>
<div class="facts-section">
    <h2 class="facts-header">Some quick facts about me:</h2>
<div class="custom-bullets">
<ul>
  <li data-emoji="🌏">
    I had a very international childhood, an experience that instilled in me a love for seeing and learning about the world. So far, I've lived in 6 countries and counting!
  </li>
  <li data-emoji="📈🌇">
    I am an Urban Economist by training. I have a Bachelor's in Economics from Yale-NUS College and a Master's in Urban Planning from the University of Pennsylvania.
  </li>
  <li data-emoji="👩‍💻">
    My projects are a way for me to improve my own technical skills. My work is done in the following languages:
    <ul>
      <li class="tech">Data Analysis: Python, R, SQL</li>
      <li class="tech">Software Development: HTML, CSS, Javascript </li>
    </ul>
  </li>
</ul>
</div>
</div>
</div>

<style>

.custom-bullets ul {
    list-style: none;
    padding-left: 0;
    margin: 0;
}

.custom-bullets li {
    position: relative;
    color:  #29524a;
    padding-left: 3.5rem;
    margin-bottom: 1.5rem;
    min-height: 3rem;
}

/* Style for the emoji bullets */
.custom-bullets li::before {
    content: attr(data-emoji);
    position: absolute;
    left: 0;
    top: 0;
    font-size: 2rem;
    line-height: 1.5;
    width: 3rem;
    text-align: center;
}

/* Nested list styling */
.custom-bullets li ul {
    margin-left: 0;
}

.custom-bullets li ul li {
    padding-left: 1.5rem;
}

/* Badge styling improvements */
.custom-bullets img {
    vertical-align: middle;
    margin: 0 0.25rem;
}

/* Hero section styling */
.hero-section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 2rem 0 4rem 0;
    gap: 2rem;
}

.hero-text {
    flex: 1;
}

.hero-image {
    flex: 0 0 300px;
}

/* Profile image styling */
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* Greeting header styling */
.greeting {
    font-size: 3.5rem;
    font-weight: bold;
    margin-bottom: 2rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
}

/* Waving hand animation */
.wave {
    display: inline-block;
    animation: wave 2.5s infinite;
    transform-origin: 70% 70%;
}

@keyframes wave {
    0% { transform: rotate(0deg); }
    10% { transform: rotate(14deg); }
    20% { transform: rotate(-8deg); }
    30% { transform: rotate(14deg); }
    40% { transform: rotate(-4deg); }
    50% { transform: rotate(10deg); }
    60% { transform: rotate(0deg); }
    100% { transform: rotate(0deg); }
}


/* Facts section styling */
.facts-section {
    margin: 3rem 0;
}

.facts-header {
    font-size: 2rem;
    font-weight: bold;
    margin-bottom: 2rem;
}

.custom-bullets {
    background: rgba(255, 255, 255, 0.8);
    border-radius: 1rem;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 2rem;
}

.custom-bullets li {
    background: white;
    padding: 1.5rem 1.5rem 1.5rem 4.5rem;
    border-radius: 0.5rem;
    margin-bottom: 1.5rem;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.custom-bullets li::before {
    font-size: 2.5rem;
    left: 1rem;
    top: 50%;
    transform: translateY(-50%);
}

/* Nested list improvements */
.custom-bullets li ul {
    margin-top: 1rem;
}

.custom-bullets li ul li {
    background: none;
    box-shadow: none;
    padding: 0.5rem 0.5rem;
    margin-bottom: 0.25rem;
}

/* Responsive design */
@media (max-width: 768px) {
    .hero-section {
        flex-direction: column-reverse;
        text-align: center;
    }
    
    .hero-image {
        flex: 0 0 200px;
    }
    
    .profile-image {
        width: 200px;
        height: 200px;
    }
    
    .greeting {
        font-size: 2.5rem;
        justify-content: center;
    }
}

.intro-section {
    max-width: 800px;
    margin: 2rem auto;
    backdrop-filter: blur(2rem);
}

.intro-section p {
    font-size: 1.1rem;
    line-height: 1.8;
    margin-bottom: 1.5rem;
    letter-spacing: 0.01em;
}

.intro-section p:first-child {
    font-size: 1.2rem;
    line-height: 1.9;
    font-weight: bold;
}


@media (max-width: 768px) {
    .intro-section {
        padding: 1.5rem;
        margin: 1rem;
    }
    
    .intro-section p {
        font-size: 1rem;
        line-height: 1.7;
    }
    
    .intro-section p:first-child {
        font-size: 1.1rem;
    }
}

/* Gallery section styles */
.gallery-section {
    margin: 4rem 0;
}

.gallery-header {
    font-size: 2rem;
    font-weight: bold;
    margin-bottom: 2rem;
    color:rgb(255, 255, 255);
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1rem;
    padding: 1rem;
}

.gallery-item {
    position: relative;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    aspect-ratio: 4/3;
    cursor: pointer;
}

.gallery-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.15);
}

.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.gallery-item:hover img {
    transform: scale(1.05);
}

.gallery-overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: linear-gradient(to top, rgba(41, 82, 74, 0.9), rgba(41, 82, 74, 0.7), transparent);
    padding: 2rem 1rem 1rem;
    transform: translateY(100%);
    transition: transform 0.3s ease;
}

.gallery-item:hover .gallery-overlay {
    transform: translateY(0);
}

.gallery-title {
    color: white;
    font-size: 1.2rem;
    font-weight: 500;
    margin-bottom: 0.5rem;
}

.gallery-description {
    color: rgba(255, 255, 255, 0.9);
    font-size: 0.9rem;
    line-height: 1.4;
}

@media (max-width: 768px) {
    .gallery-grid {
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 1rem;
    }
    
    .gallery-title {
        font-size: 1.1rem;
    }
    
    .gallery-description {
        font-size: 0.85rem;
    }
}
</style>