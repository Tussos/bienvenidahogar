<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TUSSOS Login</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>
  <div class="container">
    <h1>TUSSOS</h1>
    <form id="loginForm">
      <label for="email">Correo electrónico / Email</label>
      <input type="email" id="email" name="email" required/>

      <label for="password">Contraseña / Password</label>
      <input type="password" id="password" name="password" required/>

      <button type="submit">Iniciar sesión / Log In</button>
    </form>

    <p>¿No tienes cuenta?<br/>Don’t have an account?</p>

    <button class="register-button" onclick="registerTechnician()">
      Regístrate como Técnico<br/>Sign up as Technician
    </button>
  </div>

  <script src="script.js"></script>
</body>
</html>
