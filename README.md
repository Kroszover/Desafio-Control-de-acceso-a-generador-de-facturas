# Desafio-Control-de-acceso-a-generador-de-facturas

Para realizar este desafío debes haber estudiado previamente todo el material
disponibilizado correspondiente a la unidad.

● Una vez terminado el desafío, comprime la carpeta que contiene el desarrollo de los
requerimientos solicitados y sube el .zip en el LMS.


● Desarrollo desafío:


○ El desafío se debe desarrollar de manera Individual
Descripción


Se requiere añadir un control de acceso con login al proyecto Generador factura que se ejecutó
en el Desafío anterior.


En este desafío se pide un formulario jsp login que cuente con:



● Usuario.

● Contraseña.


● Un servlet de nombre ProcesaLogin.java, cuya función será validar la existencia de un
usuario y password (configurado en el mismo servlet, ya que aun no tenemos base de
datos).


● Si el usuario existe, generar una variable de sesión con el nombre de usuario como
clave, y redirigir a la página ingresoValores.jsp.


● Si usuario y password no coinciden, alertar al usuario que sus datos son erróneos.



Instrucciones


1. Se pide una página JSP que sea capaz de recibir un usuario y un password, para luego
enviarlo al servlet.


2. Se pide un servlet de nombre ProcesaLogin.java, cuya función será validar la existencia
de un usuario y password.


3. El servlet debe ser capaz de crear una variable de sesión asignado como nombre el
nombre de usuario recibido desde el formulario de login.


4. El servlet debe mostrar una alerta en caso de ingresar valores incorrectos, y redirigir
nuevamente al formulario de login

