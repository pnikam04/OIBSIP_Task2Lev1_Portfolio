# OIBSIP_Task2Lev1_Portfolio
I Developed this Portfolio using HTML &amp; CSS , JAVA SCRIPT
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio - Pratik Nikam</title>
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: "Arial", sans-serif;
      }

      body {
        background-color: #121212;
        color: #fff;
        line-height: 1.6;
      }

      .container {
        width: 80%;
        margin: 0 auto;
      }

      header {
        background-color: #1f1f1f;
        padding: 1rem 0;
      }

      nav {
        display: flex;
        justify-content: flex-end;
        gap: 2rem;
      }

      nav a {
        color: #fff;
        text-decoration: none;
        font-weight: bold;
        transition: color 0.3s;
      }

      nav a:hover {
        color: #f39c12;
      }

      .hero {
        text-align: center;
        padding: 4rem 0;
      }

      .hero-content {
        display: inline-block;
        max-width: 500px;
      }

      .profile-pic {
        border-radius: 50%;
        width: 150px;
        height: 150px;
        object-fit: cover;
      }

      h1 {
        margin: 1rem 0;
        font-size: 2.5rem;
      }

      .btn {
        display: inline-block;
        margin-top: 1rem;
        padding: 0.5rem 2rem;
        background-color: #f39c12;
        color: #fff;
        text-decoration: none;
        border-radius: 5px;
        transition: background-color 0.3s;
      }

      .btn:hover {
        background-color: #e67e22;
      }

      .services {
        padding: 2rem 0;
        background-color: #1f1f1f;
      }

      .services h2 {
        text-align: center;
        margin-bottom: 2rem;
        font-size: 2rem;
      }

      .services-cards {
        display: flex;
        justify-content: space-between;
        gap: 1rem;
      }

      .service-card {
        background-color: #292929;
        padding: 1.5rem;
        border-radius: 5px;
        width: 30%;
        text-align: center;
        transition: transform 0.3s;
      }

      .service-card:hover {
        transform: translateY(-10px);
      }

      .service-card h3 {
        margin-bottom: 1rem;
        font-size: 1.5rem;
      }

      .contact {
        text-align: center;
        padding: 2rem 0;
      }

      footer {
        background-color: #1f1f1f;
        text-align: center;
        padding: 1rem 0;
        margin-top: 2rem;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="container">
        <nav>
          <a href="#">Services</a>
          <a href="#">Works</a>
          <a href="#">Blog</a>
        </nav>
      </div>
    </header>
    <section class="hero">
      <div class="container">
        <div class="hero-content">
          <img
            src="https://via.placeholder.com/150"
            alt="Pratik Nikam"
            class="profile-pic"
          />
          <h1>Pratik Nikam</h1>
          <p>Product Designer and Developer, based in California.</p>
          <a href="#" class="btn">My story</a>
        </div>
      </div>
    </section>
    <section class="services">
      <div class="container">
        <h2>Services</h2>
        <div class="services-cards">
          <div class="service-card">
            <h3>Product Designer</h3>
            <p>120 Projects</p>
          </div>
          <div class="service-card">
            <h3>Branding Designer</h3>
            <p>78 Projects</p>
          </div>
          <div class="service-card">
            <h3>Full Stack Developer</h3>
            <p>45 Projects</p>
          </div>
        </div>
      </div>
    </section>
    <section class="contact">
      <div class="container">
        <h2>Contact</h2>
        <p>Any type of query & discussion.</p>
        <a href="mailto:hiscarlos@example.com">hiscarlos@example.com</a>
      </div>
    </section>
    <footer>
      <div class="container">
        <p>&copy; 2024 Carlos Mendoza</p>
      </div>
    </footer>
  </body>
</html>
