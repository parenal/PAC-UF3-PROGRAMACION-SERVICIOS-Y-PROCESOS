# PAC-UF3-PROGRAMACION-SERVICIOS-Y-PROCESOS
PAC de Desarrollo de la asignatura Progamación de serivcios y procesos Ilerna

*Te recomiendo ver el README en RAW*

En esta PAC se valorarán vuestro conocimiento sobre los sockets de conexión
entre diferentes aplicaciones.
¿Qué tiene que realizar la aplicación?
Básicamente se va a centrar en una comunicación entre 1 cliente y 1 servidor.
¿Cuál va a ser la estructura (obligatoria) del fichero que deberás subir en esta
PAC?
• Proyecto comprimido en ZIP
o Carpeta: src
▪ Carpeta: server (package)
• Main
• Server
• Tarea
▪ Carpeta: client (package)
• Main
• Client
Como podemos observar debemos crear dos packages con la información
correspondiente a cada uno de ellos. Recuerda que el nombre de los ficheros
y packages han de ser los mismos que se indican en este enunciado.
Datos de conexión necesarios:
• Dirección: localhost
• Puerto: 9876
Deberás crear un programa en Java que utilice la comunicación mediante
sockets entre un cliente y un servidor, de forma que se replique este
intercambio de mensajes:

Servidor: Inicia Servidor
Cliente:
Servidor:
Cliente: Cliente se conecta
Servidor: Pregunta nombre del cliente
Cliente:
Servidor:
Cliente: Cliente envia su nombre
Servidor: Servidor recibe nombre de cliente
Cliente:
Servidor: Servidor pregunta nº de tareas a realizar
Cliente:
Servidor:
Cliente: Cliente envia nº de tareas a realizar
Servidor: Bucle
Cliente: Bucle
Servidor: Servidor envia al cliente nº de la tarea
Cliente:
Servidor: 
Cliente: Cliente recibe nº de tarea
Servidor: Servidor solicita la descripcion de la tarea
Cliente:
Servidor:
Cliente: Cliente solicita al usuario la descirpcion de la tarea y se la envia al servidor
Servidor: Servidor solicita el estado de la tarea
Cliente:
Servidor:
Cliente: Cliente solicita al usuario
Servidor: Fin bucle
Cliente: Fin bucle
Servidor: Servidor envia mensaje al cliente informando de que va enviar las tareas
Cliente:
Servidor: Servidor envia todas las tareas
Cliente:
Servidor:
Cliente: Cilente recibe la informacion de las tareas

Además de las clases descritas, deberás crear una clase adicional Tarea para
instanciar objetos para las tareas introducidas por el usuario a través del
cliente. Esta clase tendrá como atributos:
• String descripcion
• String estado.
Una vez hayas completado este programa, deberás hacer una copia del mismo
para organizar los ficheros de la forma indicada en el enunciado para la
entrega de la tarea y no perder así el proyecto original.
