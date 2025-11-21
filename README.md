# Project Responsive Web Design using Bootstrap
## Date:

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
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dribbble Shots</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f5f5f5;
    }

    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #2d2d2d;
      color: white;
      padding: 10px 20px;
    }

    .navbar .logo {
      font-size: 1.5rem;
      font-weight: bold;
    }

    .navbar .nav-links,
    .navbar .auth {
      display: flex;
      gap: 15px;
    }

    .navbar a {
      color: white;
      text-decoration: none;
    }

    .sub-header {
      background: #fafafa;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .sub-actions button {
      margin-left: 10px;
      padding: 8px 12px;
      border: 1px solid #ccc;
      background: white;
      cursor: pointer;
    }

    .sign-up {
      background: #ea4c89;
      color: white;
      border: none;
    }

    .filter-bar {
      display: flex;
      gap: 10px;
      padding: 15px 20px;
      background: white;
      border-bottom: 1px solid #ddd;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: white;
      border-radius: 6px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .card:hover {
      transform: translateY(-4px);
    }

    .card img {
      width: 100%;
      display: block;
    }

    .card .info {
      padding: 10px;
    }

    .card .author {
      font-weight: bold;
      margin: 0 0 4px;
    }

    .card .stats {
      font-size: 0.8rem;
      color: #666;
      margin: 0;
    }
  </style>
</head>
<body>
  <header class="navbar">
    <div class="logo">Dribbble</div>
    <nav>
      <ul class="nav-links">
        <li><a href="# "> Shots</a></li>
        <li><a href="# "> Designers</a></li>
        <li><a href="# "> Teams</a></li>
        <li><a href="# "> Community</a></li>
        <li><a href="# "> Jobs</a></li>
      </ul>
    </nav>
    <div class="auth">
      <a href="#">Sign up</a>
      <a href="#">Sign in</a>
    </div>
  </header>

  <section class="sub-header">
    <p>What are you working on? <strong>Dribbble</strong> is show and tell for designers.</p>
    <div class="sub-actions">
      <button>Learn more</button>
      <button class="sign-up">Sign up</button>
    </div>
  </section>

  <section class="filter-bar">
    <select><option>Popular</option></select>
    <select><option>Shots</option></select>
    <select><option>Now</option></select>
  </section>

  <main class="grid">
    <!-- Repeat this block for more cards -->
    <div class="card">
      <img src="c:\Users\admin\Downloads\6aed879a-d310-4940-84c1-fae0b6f8e929_802x794.jpg" alt="Design shot">
      <div class="info">
        <p class="author">Tristan Tate</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <div class="card">
      <img src="c:\Users\admin\Downloads\Andrew-Tate.jpg" alt="Design shot">
      <div class="info">
        <p class="author">Andrew Tate</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <div class="card">
      <img src="c:\Users\admin\Downloads\2182574475.webp" alt="Design shot">
      <div class="info">
        <p class="author">Andrew Garfield</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <div class="card">
      <img src="c:\Users\admin\Downloads\IMG-20250517-WA0009.jpg" alt="Design shot">
      <div class="info">
        <p class="author">CEO JERALD</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <div class="card">
      <img src="c:\Users\admin\Downloads\ImagesCAY8UW7T.webp" alt="Design shot">
      <div class="info">
        <p class="author">Vin Diesel</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <div class="card">
      <img src="c:\Users\admin\Downloads\brad-pitt_03_paramount-pictures.webp" alt="Design shot">
      <div class="info">
        <p class="author">Brad Pit</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <div class="card">
      <img src="c:\Users\admin\Downloads\Tom_Holland.webp" alt="Design shot">
      <div class="info">
        <p class="author">Tom Holland</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <div class="card">
      <img src="c:\Users\admin\Downloads\Headshot20creditE29CNational20forE29D.webp" alt="Design shot">
      <div class="info">
        <p class="author">Chris Hemsworth</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <div class="card">
      <img src="c:\Users\admin\Downloads\x8aaxbjh8r6a1.jpg" alt="Design shot">
      <div class="info">
        <p class="author">Tony Stark</p>
        <p class="stats">2.9M views • 232k comments • 953k likes</p>
      </div>
    </div>
    <!-- Add more cards as needed -->
  </main>
</body>
</html>

```

## OUTPUT:

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/788f372a-cdb6-4807-98aa-00a68ed7a7b5" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
