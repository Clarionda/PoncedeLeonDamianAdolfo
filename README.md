<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mi Portafolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>👨‍💻  Ponce de León Damián Adolfo </h1>
    <p>Desarrollador Web | Tecnologías Modernas</p>
  </header>

  <section class="about">
    <h2>Sobre Mí</h2>
    <p>Soy un desarrollador apasionado por la tecnología...</p>
  </section>

  <section class="projects">
    <h2>Proyectos</h2>
    <div class="project">
      <h3>🛠 Proyecto 1</h3>
      <p>Descripción del proyecto con tecnologías usadas.</p>
      <a href="https://github.com/tuusuario/proyecto1" target="_blank">Ver en GitHub</a>
    </div>
    <!-- Añade más proyectos aquí -->
  </section>

  <footer>
    <p>© 2025 Tu Nombre · <a href="https://github.com/tuusuario" target="_blank">GitHub</a></p>
  </footer>
</body>
</html>
style.css
css
Copiar
Editar
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #0e0e0e;
  color: #e0e0e0;
  line-height: 1.6;
  padding: 20px;
}
header {
  text-align: center;
  margin-bottom: 40px;
}
h1 {
  font-size: 2.5rem;
  color: #00ffc3;
}
h2 {
  color: #00ffc3;
  margin-top: 20px;
}
a {
  color: #00ffc3;
  text-decoration: none;
}
.project {
  background: #1a1a1a;
  padding: 15px;
  border-left: 5px solid #00ffc3;
  margin-bottom: 15px;
  border-radius: 10px;
}
footer {
  text-align: center;
  margin-top: 40px;
  font-size: 0.9rem;
  color: #aaa;
}
