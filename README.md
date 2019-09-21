# CVDS_LAB05

 > **Integrantes:** 
 > Juan Carlos Garcia Garzon
 > Johan Damian Garrido Florez
## Parte I. - Jugando a ser un cliente HTTP
**Qué errores existen?**
Existen varios tipos de errores, entre ellos:
-	Error 400 __(Bad Request)__ : se presentan si el servidor no puede completar la consulta (GET)
-	Error 404 __(Not Found)__ : se presentan si el servidor no encuentra la solicitud
-	Error 408 __(Request Timeout)__ : se presentan si el servidor agota el tiempo de espera
-	Error 500 __(Internal Server)__ : se presentan si se presenta un fallo o error al ejecutar una solicitud


## Parte III.

**Cambie el formulario para que ahora en lugar de POST, use el método GET . Qué diferencia observa?**
El método de envío de la información al servidor cambia.
**Get** envía los parámetros de manera visible al usuario
**Post** envía los parámetros de manera invisible al usuario

Otros métodos que podemos hallar son:
**Put** se usa para crear/actualizar datos en un servidor
**Head** similar a GET pero sin el cuerpo de respuesta
**Delete** elimina el recurso especificado.


** ¿Qué se está viendo? Revise cómo están implementados los métodos de la clase Service.java para entender el funcionamiento interno.**
 Service se encarga de hacer intermediario con Json para obtener la información de la ID especificada.
 esta ID es presentada por medio de una tabla, al dirigirnos a la página de nuestro servidos se puede ver
 una casilla para ingresar la información de una ID específica, es aquí que obtenemos la información por medio de Service