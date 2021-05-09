
<html lang="es-ES">
  <head>
    <meta charset="utf-8">
    <title>Notificar incidencia</title>
  </head>
  <body>
    <form action="procesar-incidencia.php" method="post">
      <fieldset>
        <legend>INFORMAR NOVEDADES DE LA PLATAFORMA UTPL:</legend>
        <label for="nombre_usuario">Usuario: </label>
        <br>
        <input type="text" name="usuario" id="nombre_usuario">
        <br><br>
        <label for="nombre_departamento">Área: </label>
        <br>
        <select name="departamento" id="nombre_departamento">
          <option value="informatica">Tecnologías de la Información</option>
          <option value="informatica">Informática</option>
          <option value="marketing">Marketing</option>
          <option value="ventas">Psicología</option>
        </select>
        <br><br>
        <label for="descripcion_incidencia">Descripción: </label>
        <br>
        <textarea name="incidencia" rows="3" cols="40" id="descripcion_incidencia">Detalle el problema suscitado...</textarea>
        <br><br>
        <label for="clave_usuario">Contraseña: </label>
        <br>
        <input type="password" name="clave" id="clave_usuario">
      </fieldset>
      <fieldset>
        <legend>Botones de reset y envío:</legend>
        <button type="reset">Resetear</button>
        <button type="submit">Enviar</button>
      </fieldset>
    </form>
  </body>
</html>
