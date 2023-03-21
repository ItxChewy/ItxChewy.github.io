# ItxChewy.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilos.css" />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.1/css/all.css">
    <title>Document</title>
</head>
<body>
    <div class="contenedor">
        <header class="header">
          <h2>HTML+CSS.FLEXBOX Y GRID</h2>
        </header>
        <nav class="nav">
        <div class="quenvuelve">
            <div class="textonav">
                <p >Examen 2ªEval LM-DAW1</p>
            </div>
            <div class="navegacion"> 
                <div class="espacio"><p>Sobre Nosotros </p></div> 
                <div class="espacio"><p>Servicios </p></div>
                <div class="espacio"><p>Contacto </p></div>
            </div>
            </div>
        </nav>
        <div class="contenido11">
          <div class="imagenes">
            <img src="imagenes/jiraf.jpg" alt="Descripción de la imagen 1" />
            <p>Jirafa</p>  
        </div>
          <div class="imagenes">
            <img src="imagenes/oso.jpg" alt="Descripción de la imagen 2" />
            <p>Oso</p>
          </div>
          <div class="imagenes">
            <img src="imagenes/tigre.jpg" alt="Descripción de la imagen 3" />
            <p>Tigre</p>
          </div>
          <div class="imagenes">
            <img src="imagenes/elefante.jpg" alt="Descripción de la imagen 4"/>
            <p>Elefante</p>
          </div>
          <div class="imagenes">
            <img src="imagenes/caballo.jpg" alt="Descripción de la imagen 5"/>
            <p>Caballo</p>
          </div>
        </div>
        <div class="contenido21">
          <p>
            <i>Una seleción </i>plagada de estrellas acude a <strong class="copamundo"> la copa del 2002</strong>, con un sueño lograr el pentacampeonato.
          </p>
          <div class="paracentar"><img src="imagenes/brasil.jfif" alt="Brasil" /></div>
        </div>
        <div class="contenido31">
          <p>
            <b class="pique"> Piqué</b> sobre Arbeloa: “No es mi amigo, es conocido. Cono... cido”
          </p>
          <div class="paracentar"><img src="imagenes/pique.jfif" alt="Piqué" /></div>
        </div>
        <div class="formulario">
          <label for="usuario"><b>Nombre Usuario</b></label><br><br>
          <i class="fas fa-user"></i>
          <input type="text" placeholder="Introducir nombre de usuario" id="usuario" name="usuario"><br><br>
          <label for="contraseña"><b>Contraseña</b></label><br><br>
          <i class="fas fa-lock"></i>
          <input  type="password" placeholder="Introducir contraseña" id="contraseña" name="contraseña"><br><br>
          <label for="contraseña2"><b>Contraseña</b></label><br><br>
          <i class="fas fa-lock"></i>
          <input type="password" placeholder="Introducir contraseña" id="contraseña2" name="contraseña2"><br><br>
          <input  class="boton" type="submit"></input>
        </div>
        <div class="tabla">
          <select name="desplegable" id="desplegable">
            <option value="desplegable">Google</option>
            <option value="desplegable">Palomeras-Vallecas</option>
            <option value="desplegable" selected>Atlético de Madrid</option>
          </select>
        <table class="tabla1">
                  <thead>
                      <tr>
                          <th>Nombre</th>
                          <th>Apellidos</th>
                          <th>Edad</th>
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>Jorge</td>
                          <td>Resurreción</td>
                          <td>31</td>
                      </tr>
                      <tr>
                          <td>Mariano</td>
                          <td>Diaz</td>
                          <td>29</td>
                      </tr>
                      </tr>
                      <tr>
                          <td>Pedro</td>
                          <td>Gónzalez</td>
                          <td>20</td>
                      </tr>
                      <tr>
                          <td>Thomas</td>
                          <td>Lemar</td>
                          <td>27</td>
                      </tr>
                  </tbody>
          </table>
        </div>  
        <footer class="footer">
          <p><b>Aarón García Anguita 14/03/23</b></p>
        </footer>
      </div>
</body>
