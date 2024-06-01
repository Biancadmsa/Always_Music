<h1>Pasos a realizar para ejecutar la base de datos:</h1>

<p>Instalar npm i pg </p>

<h2>***Pasos de registro en la base de datos:***</h2>

<h3>1-Registrar un nuevo estudiante:</h3>
<ul>
<li>node server.js registrar 12345678-9 "Juan Perez" G70 7  ( ya se encuentra agregado, intentar con el siguiente.) </li>
<li>node server.js registrar 12345678-4 "Bianca Salcedo" G70 7</li>
<li>node server.js registrar 12345678-5 "Eduardo Ramos" G70 7</li>
<li>node server.js registrar 12345678-6 "Ignacio Dubo" G70 7</li>
<li>node server.js registrar 12345678-7 "Diego Cabre" G70 7</li>
</ul>
<p>Traerá como resultado por ejemplo un alumno que sea registrado:</p>
<ul>
<li>***** Academy Always Music *****</li>
<li>Alumno Juan Perez: 12345678-9 fué registrado con éxito!</li>
<li>Alumno Registrado:  { rut: '12345678-9', nombre: 'Juan Perez', curso: 'G70', nivel: 7 } </li>
</ul>
<p>y asì mostrara todos los agregados..</p>
<br>
<h3>2-Obtener el registro de un estudiante:</h3>
<p>node server.js rut 12345678-4</p>
<ul>
  <li>Traerá  como resultado:</label></li>
<li>Alumno consultado: { rut: '12345678-9', nombre: 'Juan Perez', curso: 'G70', nivel: 7 }</li>
</ul>
<br>
<h3>3-Consultar el registro de todos los estudiantes registrados de la base de datos:</h3>
<p>node server.js consulta</p>
<ul>
<li>Traerá  como resultado:</li>
<li>Alumnos registrados: [ { rut: '12345678-9', nombre: 'Juan Perez', curso: 'G70', nivel: 7 } ]</li>
</ul>
<br>
<h3>4-Actualizar el registro de un estudiante de la base de datos:</h3>
<p>node server.js actualizar 12345678-9 "Juan Perez" g70 8 </p>
<ul>
  <li>Traerá  como resultado:</li>
  <li>Alumno Actualizado: { rut: '12345678-9', nombre: 'Juan Perez', curso: 'g70', nivel: 8 }</li>
</ul>
<br>
<h3>5-Eliminar el registro de un estudiante de la base de datos:</h3>
<p>node server.js eliminar 12345678-9</p>
<ul>
<li>Traerá  como resultado por ejemplo:</li>
<li>***** Academy Always Music *****</li>
<li>Alumno con rut 25675678-9 eliminado con éxito</li>
<li>Alumno Eliminado:  {
  rut: '12345678-9',
  nombre: 'Juan Perez',
  curso: 'g70',
  nivel: 18
}</li>
</ul>
