# tia-sindhu.github.io

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tia Sindhu | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #111315;
      color: #f5f5f5;
      line-height: 1.6;
    }

    .container {
      width: 90%;
      max-width: 1150px;
      margin: 0 auto;
      padding: 40px 0 60px;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 50px;
    }

    nav h1 {
      font-size: 2rem;
    }

    .nav-links a {
      color: #d6d6d6;
      text-decoration: none;
      margin-left: 24px;
      font-size: 1rem;
    }

    .nav-links a:hover {
      color: #ffffff;
    }

    .hero {
      margin-bottom: 40px;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    .hero p {
      color: #b8b8b8;
      max-width: 700px;
      font-size: 1.05rem;
    }

    .projects-title {
      font-size: 1.7rem;
      margin: 30px 0 25px;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 28px;
    }

    .card {
      background: #1b1d20;
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.25);
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      display: block;
    }

    .card-content {
      padding: 22px;
    }

    .card h3 {
      font-size: 1.5rem;
      margin-bottom: 10px;
    }

    .card p {
      color: #c9c9c9;
      margin-bottom: 16px;
      font-size: 1rem;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .tag {
      border: 1px solid #3b82f6;
      color: #60a5fa;
      border-radius: 999px;
      padding: 6px 12px;
      font-size: 0.85rem;
    }

    .card-link {
      text-decoration: none;
      color: inherit;
      display: block;
    }

    footer {
      margin-top: 60px;
      color: #9d9d9d;
      text-align: center;
      font-size: 0.95rem;
    }

    @media (max-width: 700px) {
      .hero h2 {
        font-size: 2rem;
      }

      nav {
        flex-direction: column;
        align-items: flex-start;
        gap: 12px;
      }

      .nav-links a {
        margin-left: 0;
        margin-right: 18px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <nav>
      <h1>Tia Sindhu's Project Portfolio</h1>
      <div class="nav-links">
        <a href="#projects">Projects</a>
        <a href="about.html">About</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <section class="hero" id="about">
      <h2>Hi, I'm Tia.</h2>
      <p>
        I'm an Information & Data Science student at UIUC interested in AI,
        machine learning, analytics, and building products with data.
      </p>
    </section>

    <h2 class="projects-title" id="projects">Projects</h2>

    <div class="projects-grid">
      <a class="card-link" href="project-imdb.html">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=1200&q=80" alt="AI project">
          <div class="card-content">
            <h3>AI Hiring Bias Project</h3>
            <p>
              Analyzed how AI hiring systems can improve efficiency while also
              introducing fairness concerns across applicant groups.
            </p>
            <div class="tags">
              <span class="tag">Python</span>
              <span class="tag">Pandas</span>
              <span class="tag">Machine Learning</span>
            </div>
          </div>
        </div>
      </a>

      <a class="card-link" href="#">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=1200&q=80" alt="Data analysis project">
          <div class="card-content">
            <h3>Regression Analysis Project</h3>
            <p>
              Built predictive models and compared variable relationships using
              regression, interaction effects, and model evaluation techniques.
            </p>
            <div class="tags">
              <span class="tag">Python</span>
              <span class="tag">Scikit-learn</span>
              <span class="tag">Statistics</span>
            </div>
          </div>
        </div>
      </a>

      <a class="card-link" href="#">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1518186285589-2f7649de83e0?auto=format&fit=crop&w=1200&q=80" alt="Portfolio project">
          <div class="card-content">
            <h3>Data Product Portfolio</h3>
            <p>
              A collection of technical and analytics projects focused on solving
              real-world problems through data-driven decision making.
            </p>
            <div class="tags">
              <span class="tag">SQL</span>
              <span class="tag">Visualization</span>
              <span class="tag">Analytics</span>
            </div>
          </div>
        </div>
      </a>
    </div>

    <footer id="contact">
      <p>Email: tia.sindhu28@gmail.com | GitHub: tia-sindhu</p>
    </footer>
  </div>
</body>
</html>
