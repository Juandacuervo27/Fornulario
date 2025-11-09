# Fornulario
Formulario página web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <header>
        <h1>Formulario de prueba</h1>
    </header>
    <form>
    <!--Aquí va el nombre-->
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" placeholder="Su nombre"><br><br>

    <!--Casilla para el apellido-->
        <label for="Apellido">Apellido:</label>
        <input type="text" id="Apellido" name="Apellido" placeholder="Su apellido"><br><br>

    <!--Casilla para el tipo de identificación-->
        <label for="identificacion">tipo de identificación:</label><br>
        <select id="identificacion" name="identificacion">
            <option value="cc">Cédula de ciudadanía</option>
            <option value="ti">Tarjeta de identidad</option>
            <option value="ce">Cédula de extranjería</option>
        </select><br><br>

    <!--Casilla para el número de identificación-->
        <label for="Numero de identificacion" name="Numero de identificacion">Número de identificación:</label>
        <input type="number" id="Numero de identificacion" name="Numero de identificacion" placeholder="Su número de identificación"><br><br>

    <!--Casilla para la fecha de nacimiento-->
        <label for="Nacimiento">Fecha de Nacimiento:</label>
        <input type="date" id="Nacimiento" name="Nacimiento"><br><br>

    <!--Número de celular-->
        <label for="number">Numero de celular:</label>
        <input type="tel" id="number" name="number" placeholder="Su número de celular"><br><br>
    
    <!--Boton de tratamiento de datos-->
        <h4>Tratamiento de datos personales</h4>
        <a href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=49981" target="_blank">Términos y condiciones</a><br>
        <input type="checkbox" id="tratamiento_datos" name="tratamiento_datos">
        <label for="tratamiento_datos">Acepto el tratamiento de mis datos personales después de haber leído los terminos y condiciones</label><br><br>

    <!--Botón de envío-->    
        <input type="submit" value="Enviar">
    </form>
</body>
</html>
