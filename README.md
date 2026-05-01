<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Perfil GitHub</title>

  <!-- Fuente bonita -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0d1117;
      color: #c9d1d9;
    }

    header {
      background: #161b22;
      padding: 20px;
      text-align: center;
      border-bottom: 1px solid #30363d;
    }

    header h1 {
      color: #58a6ff;
    }

    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 20px;
    }

    .profile {
      text-align: center;
    }

    .profile img {
      width: 150px;
      border-radius: 50%;
      border: 3px solid #58a6ff;
    }

    .profile h2 {
      margin-top: 10px;
    }

    .profile p {
      color: #8b949e;
    }

    .section {
      margin-top: 40px;
    }

    .section h3 {
      margin-bottom: 15px;
      color: #58a6ff;
      border-bottom: 1px solid #30363d;
      padding-bottom: 5px;
    }

    .repos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .repo {
      background: #161b22;
      padding: 15px;
      border-radius: 10px;
      border: 1px solid #30363d;
      transition: 0.3s;
    }

    .repo:hover {
      transform: translateY(-5px);
      border-color: #58a6ff;
    }

    .repo h4 {
      color: #58a6ff;
    }

    .repo p {
      font-size: 14px;
      margin: 10px 0;
    }

    .repo a {
      text-decoration: none;
      color: #fff;
      background: #238636;
      padding: 5px 10px;
      border-radius: 5px;
      font-size: 12px;
    }

    footer {
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      border-top: 1px solid #30363d;
      color: #8b949e;
    }
  </style>
</head>

<body>

  <header>
    <h1>Mi Perfil GitHub</h1>
  </header>

  <div class="container">

    <!-- PERFIL -->
    <div class="profile">
      <img src="https://via.placeholder.com/150" alt="Foto de perfil">
      <h2>Tu Nombre</h2>
      <p>Desarrollador Web | JavaScript | React</p>
    </div>

    <!-- SOBRE MÍ -->
    <div class="section">
      <h3>Sobre mí</h3>
      <p>
        Soy desarrollador apasionado por crear aplicaciones web modernas.
        Me gusta trabajar con JavaScript, Node.js y React.
      </p>
    </div>

    <!-- REPOS -->
    <div class="section">
      <h3>Proyectos</h3>
      <div class="repos">

        <div class="repo">
          <h4>Proyecto 1</h4>
          <p>Aplicación web con React y API.</p>
          <a href="#">Ver repo</a>
        </div>

        <div class="repo">
          <h4>Proyecto 2</h4>
          <p>Backend con Node.js y MongoDB.</p>
          <a href="#">Ver repo</a>
        </div>

        <div class="repo">
          <h4>Proyecto 3</h4>
          <p>Landing page moderna.</p>
          <a href="#">Ver repo</a>
        </div>

      </div>
    </div>

  </div>

  <footer>
    <p>© 2026 - Tu Nombre | GitHub</p>
  </footer>

</body>
</html>

<!--
**Samy-Garcia/Samy-Garcia** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
