# Project Responsive Web Design using Bootstrap
## Date:15-10-2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VisionArt Studio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f2f5f7;
      color: #333;
    }

    header {
      background-color: #343a40;
      color: #f8f9fa;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
    }

    header h1 {
      font-size: 26px;
      font-weight: 600;
      letter-spacing: 1px;
    }

    nav a {
      color: #ccc;
      text-decoration: none;
      margin-left: 25px;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ffb400;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
      padding: 40px 60px;
    }

    .card {
      background-color: white;
      border-radius: 14px;
      box-shadow: 0 4px 14px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
    }

    .card img {
      width: 100%;
      height: 190px;
      object-fit: cover;
    }

    .card-content {
      padding: 16px 20px;
    }

    .card-content h3 {
      margin: 0;
      font-size: 18px;
      color: #222;
    }

    .card-content p {
      margin-top: 8px;
      font-size: 14px;
      color: #666;
    }

    footer {
      background-color: #343a40;
      color: white;
      text-align: center;
      padding: 18px 0;
      margin-top: 40px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>VisionArt Studio</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Gallery</a>
      <a href="#">Projects</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="gallery">
    <div class="card">
      <img src="https://picsum.photos/id/237/400/300" alt="Artwork 1">
      <div class="card-content">
        <h3>Silent Reflections</h3>
        <p>A calm visual exploring still waters and golden skies.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://picsum.photos/id/1069/400/300" alt="Artwork 2">
      <div class="card-content">
        <h3>Neon Streetlights</h3>
        <p>Modern urban photography with vibrant night tones.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://picsum.photos/id/1035/400/300" alt="Artwork 3">
      <div class="card-content">
        <h3>Dreamscape Horizon</h3>
        <p>Futuristic digital art blending light and geometry.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://picsum.photos/id/1041/400/300" alt="Artwork 4">
      <div class="card-content">
        <h3>Forest Harmony</h3>
        <p>Nature-inspired piece with earthy tones and textures.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://picsum.photos/id/1084/400/300" alt="Artwork 5">
      <div class="card-content">
        <h3>Cosmic Journey</h3>
        <p>Abstract visualization of galaxies and star patterns.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://picsum.photos/id/1050/400/300" alt="Artwork 6">
      <div class="card-content">
        <h3>Vintage Essence</h3>
        <p>Retro-style art evoking classic film aesthetics.</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 VisionArt Studio | Crafted with 🎨 by Abdul
  </footer>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2025-10-15 103717.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
