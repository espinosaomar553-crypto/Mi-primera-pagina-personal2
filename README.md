# Mi-primera-pagina-personal2
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Omar Espinosa Pinto — Portafolio</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;400;600;700&family=Share+Tech+Mono&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">
</head>
<body>

<!-- CURSOR -->
<div class="cursor" id="cursor"></div>
<div class="cursor-trail" id="cursorTrail"></div>

<!-- LOADER -->
<div id="loader">
  <div class="loader-text">CARGANDO</div>
  <div class="loader-bar"><div class="loader-progress"></div></div>
</div>

<!-- PARTICLES -->
<div id="particles"></div>
<div class="grid-bg"></div>

<!-- NAVBAR -->
<nav id="navbar">
  <div class="nav-logo">OEP</div>
  <ul class="nav-links">
    <li><a href="#about">Sobre Mí</a></li>
    <li><a href="#education">Educación</a></li>
    <li><a href="#contact">Contacto</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-glow"></div>
  <div class="hero-content">
    <div class="hero-text">
      <div class="hero-badge"><span class="badge-dot"></span>Disponible</div>
      <h1 class="hero-name">Omar<br>Espinosa<br>Pinto</h1>
      <p class="hero-sub" id="typewriter"></p>
      <p class="hero-desc">
        Estudiante apasionado por la <strong style="color:var(--cyan)">tecnología</strong>, el fútbol, la lectura y la investigación.
        Construyendo el futuro digital desde Panamá.
      </p>
      <div class="hero-btns">
        <a href="#contact" class="btn-primary">Contactar</a>
        <a href="#about" class="btn-secondary">Sobre Mí</a>
      </div>
    </div>
    <div class="hero-photo">
      <div class="photo-frame">
        <div class="photo-inner">
          <img id="profile-photo" src="" alt="Omar Espinosa Pinto">
          <div class="photo-overlay"></div>
          <div class="photo-tag">
            <div class="photo-tag-name">OMAR ESPINOSA</div>
            <div class="photo-tag-role">Lic. Sistemas & Programación</div>
          </div>
        </div>
        <div class="photo-corner tl"></div>
        <div class="photo-corner tr"></div>
        <div class="photo-corner bl"></div>
        <div class="photo-corner br"></div>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="section-inner">
    <div class="section-header reveal">
      <div class="section-label">Sobre Mí</div>
      <h2 class="section-title">¿Quién Soy?</h2>
      <div class="section-line"></div>
    </div>
    <div class="about-grid">
      <div class="about-text reveal">
        <p>Soy <strong>Omar Espinosa Pinto</strong>, nacido el 16 de diciembre de 2005 en Panamá. Actualmente cursando la <strong>Licenciatura en Sistemas y Programación</strong> en la UMECIT.</p>
        <p>Me apasiona la tecnología y el mundo digital, pero también soy una persona con muchas facetas: <strong>el fútbol</strong> forma parte de mi vida cotidiana y es uno de mis grandes amores.</p>
        <p>Disfruto profundamente de la <strong>lectura y la investigación</strong>, siempre buscando aprender algo nuevo y comprender el mundo desde diferentes perspectivas. Creo que el conocimiento es la herramienta más poderosa.</p>
      </div>
      <div class="about-cards reveal">
        <div class="about-card">
          <div class="about-card-icon">⚽</div>
          <div class="about-card-title">Fútbol</div>
          <div class="about-card-text">El deporte rey que me enseña trabajo en equipo, disciplina y perseverancia.</div>
        </div>
        <div class="about-card">
          <div class="about-card-icon">📚</div>
          <div class="about-card-title">Lectura</div>
          <div class="about-card-text">Los libros son ventanas al mundo. Leo para crecer, soñar y entender.</div>
        </div>
        <div class="about-card">
          <div class="about-card-icon">🔬</div>
          <div class="about-card-title">Investigación</div>
          <div class="about-card-text">La curiosidad me impulsa a investigar y encontrar respuestas a cada pregunta.</div>
        </div>
        <div class="about-card">
          <div class="about-card-icon">💻</div>
          <div class="about-card-title">Estudio</div>
          <div class="about-card-text">Comprometido con el aprendizaje continuo y la excelencia académica.</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EDUCATION -->
<section id="education">
  <div class="section-inner">
    <div class="section-header reveal">
      <div class="section-label">Formación Académica</div>
      <h2 class="section-title">Trayectoria Educativa</h2>
      <div class="section-line"></div>
    </div>
    <div class="timeline">
      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="timeline-date">FORMACIÓN PRIMARIA</div>
        <div class="timeline-title">Escuela Hipólito Pérez Tello</div>
        <div class="timeline-sub">Educación Primaria — Base sólida del conocimiento fundamental.</div>
        <div class="timeline-badge">🎓 Completado</div>
      </div>
      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="timeline-date">EDUCACIÓN SECUNDARIA</div>
        <div class="timeline-title">Colegio José Daniel Crespo</div>
        <div class="timeline-sub">Bachillerato — Desarrollo del pensamiento crítico y analítico.</div>
        <div class="timeline-badge">🎓 Completado</div>
      </div>
      <div class="timeline-item">
        <div class="timeline-dot" style="border-color: var(--neon2); box-shadow: 0 0 12px var(--neon2);"></div>
        <div class="timeline-date">EDUCACIÓN SUPERIOR · EN CURSO</div>
        <div class="timeline-title">UMECIT</div>
        <div class="timeline-sub">Licenciatura en Sistemas y Programación — Formando las competencias del futuro tecnológico.</div>
        <div class="timeline-badge" style="border-color: rgba(123,47,255,0.4); color: var(--neon2);">⚡ En Progreso</div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="section-inner">
    <div class="section-header reveal">
      <div class="section-label">Contacto</div>
      <h2 class="section-title">Hablemos</h2>
      <div class="section-line"></div>
    </div>
    <div class="contact-grid">
      <div class="contact-info reveal">
        <h3>¿Quieres conectar?</h3>
        <p>Estoy abierto a nuevas conversaciones, colaboraciones y proyectos. No dudes en escribirme por cualquiera de estos medios.</p>
        <div class="contact-links">
          <a href="tel:68016186" class="contact-link">
            <span class="link-icon">📞</span>
            <span>6801-6186</span>
          </a>
          <a href="mailto:espinosaomar553@gmail.com" class="contact-link">
            <span class="link-icon">📧</span>
            <span>espinosaomar553@gmail.com</span>
          </a>
          <a href="https://instagram.com/omarespinosa160" target="_blank" class="contact-link">
            <span class="link-icon">📸</span>
            <span>@omarespinosa160</span>
          </a>
        </div>
      </div>
      <div class="reveal">
        <form class="contact-form" onsubmit="handleSubmit(event)">
          <div class="form-group">
            <label>Nombre</label>
            <input type="text" placeholder="Tu nombre completo" required>
          </div>
          <div class="form-group">
            <label>Email</label>
            <input type="email" placeholder="tu@email.com" required>
          </div>
          <div class="form-group">
            <label>Mensaje</label>
            <textarea placeholder="Escríbeme lo que quieras..." required></textarea>
          </div>
          <button type="submit" class="form-submit">ENVIAR MENSAJE</button>
        </form>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2024 <span>Omar Espinosa Pinto</span> · Diseñado con 💙 y código</p>
</footer>

<script src="script.js"></script>
</body>
</html>
