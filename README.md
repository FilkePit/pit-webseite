# pit-webseite
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PIT – Enterprise Softwarelösungen</title>
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Share Tech Mono', monospace;
      background-color: #000;
      color: #0f0;
      background-image: repeating-linear-gradient(0deg, rgba(0,255,0,0.05) 0px, rgba(0,255,0,0.05) 1px, transparent 1px, transparent 4px),
                        repeating-linear-gradient(90deg, rgba(0,255,0,0.05) 0px, rgba(0,255,0,0.05) 1px, transparent 1px, transparent 4px);
      background-size: 100% 100%;
      animation: scanlines 10s linear infinite;
    }

    @keyframes scanlines {
      0% {background-position: 0 0;}
      100% {background-position: 0 100px;}
    }

    header {
      background-color: #111;
      text-align: center;
      padding: 2rem;
    }

    header img {
      width: 120px;
      filter: drop-shadow(0 0 8px #0f0);
      border-radius: 10px;
    }

    header h1 {
      color: #0f0;
      margin: 1rem 0 0.5rem 0;
    }

    nav a {
      margin: 0 1rem;
      color: #0f0;
      text-decoration: none;
    }

    nav a:hover {
      color: #00ff99;
      text-shadow: 0 0 5px #00ff99;
    }

    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1rem;
      background-color: #111;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,255,0,0.2);
    }

    h2 {
      color: #00ff99;
      border-bottom: 1px solid #0f0;
      padding-bottom: 0.3rem;
    }

    .tech-list {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .tech-item {
      background-color: #222;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      box-shadow: 0 0 5px #0f0;
    }

    .button {
      display: inline-block;
      padding: 1rem 2rem;
      margin-top: 2rem;
      background-color: #111;
      border: 2px solid #0f0;
      color: #0f0;
      text-transform: uppercase;
      box-shadow: 0 0 10px #0f0;
      transition: all 0.3s ease-in-out;
    }

    .button:hover {
      background-color: #0f0;
      color: #000;
      box-shadow: 0 0 20px #0f0;
    }

    footer {
      text-align: center;
      padding: 2rem;
      color: #0f0;
      font-size: 0.9rem;
    }

    a {
      color: #00ff99;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo-borg-style.png" alt="PIT Logo" />
    <h1>PIT</h1>
    <p><strong>Code. Connect. Create.</strong></p>
    <p>Wo Technik logisch – und Zusammenarbeit menschlich ist.</p>
    <nav>
      <a href="#about">Über PIT</a>
      <a href="#teamwork">Teamarbeit</a>
      <a href="#tech">Technologien</a>
      <a href="#contact">Kontakt</a>
    </nav>
  </header>

  <section id="about">
    <h2>Über PIT</h2>
    <p>
      PIT steht für moderne, skalierbare und effiziente Enterprise-Softwarelösungen.
      Ich bin spezialisiert auf Java-Entwicklung, verteilte Systeme und agile Methoden
      und habe langjährige Erfahrung in der Umsetzung komplexer Softwarearchitekturen.
    </p>
    <p><em>Dein Projekt, meine Mission. Mit Code zum Erfolg.</em></p>
  </section>

  <section id="teamwork">
    <h2>Teamarbeit</h2>
    <p>
      Moderne Software entsteht im Team – mit Kommunikation, Vertrauen und klaren Zielen.
      Ich bringe nicht nur technisches Know-how mit, sondern auch Empathie, Offenheit und
      die Fähigkeit, mich schnell in neue Teams und Projekte einzufinden.
    </p>
    <p>
      Egal ob Pair Programming, Code Reviews oder agile Ceremonies – ich arbeite gern
      gemeinsam an Lösungen, die nicht nur funktionieren, sondern auch Spaß machen.
    </p>
  </section>

  <section id="tech">
    <h2>Technologien</h2>
    <div class="tech-list">
      <div class="tech-item">Java</div>
      <div class="tech-item">Spring Boot</div>
      <div class="tech-item">Neo4j</div>
      <div class="tech-item">SQL</div>
      <div class="tech-item">RabbitMQ</div>
      <div class="tech-item">RESTful APIs</div>
      <div class="tech-item">Python</div>
    </div>
  </section>

  <section id="contact">
    <h2>Kontakt</h2>
    <p>Du möchtest mit mir zusammenarbeiten oder hast Fragen?</p>
    <p>E-Mail: <a href="mailto:kontakt@pits-solution.com">kontakt@pits-solution.com</a></p>
  </section>

  <footer>
    &copy; 2025 PIT – Professional IT Services
  </footer>
</body>
</html>
