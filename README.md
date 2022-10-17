# Ciberseguridad
## Suplantacion (phising)
El phishing es una técnica de ingeniería social que consiste en el envío de un email en el que los ciberdelincuentes suplantan la identidad de una compañía conocida o de una entidad pública para solicitar información personal y bancaria al usuario. A través de un enlace incluido en el correo electrónico intentan redirigirle a una página web fraudulenta para que introduzca su número de tarjeta de crédito, DNI, la contraseña de acceso a la banca digital, etc.

Estos correos electrónicos fraudulentos suelen incluir el logotipo o la imagen de marca de la entidad, contienen errores gramaticales e intentan transmitir urgencia y miedo para que el usuario realice las acciones que le solicitan.

Un email de tipo phishing también puede llevar un archivo adjunto infectado con software malicioso. El objetivo de este malware es infectar el equipo del usuario y robar su información confidencial.

Este tipo de ataque también es ejecutado por los ciberdelincuentes a través de mensajes SMS (smishing) y de llamadas telefónicas (vishing).

# NMAP
## Historia
Nmap es un programa de código abierto que sirve para efectuar rastreo de puertos escrito originalmente por Gordon Lyon (más conocido por su alias Fyodor
Vaskovich[1]​) y cuyo desarrollo se encuentra hoy a cargo de una comunidad. Fue creado originalmente para Linux aunque actualmente es multiplataforma. 
Se usa para evaluar la seguridad de sistemas informáticos, así como para descubrir servicios o servidores en una red informática, para ello Nmap envía unos paquetes definidos 
a otros equipos y analiza sus respuestas.
Este software posee varias funciones para sondear redes de computadores, incluyendo detección de equipos, servicios y sistemas operativos. Estas funciones son extensibles mediante 
el uso de scripts para proveer servicios de detección avanzados, detección de vulnerabilidades y otras aplicaciones. Además, durante un escaneo, es capaz de adaptarse a las condiciones 
de la red incluyendo latencia y congestión de la misma.

## Funcionamiento 
Nmap es un software de código abierto que se utiliza para escanear
una red y sus puertos con el objetivo de obtener información importante sobre la misma para controlar y gestionar su seguridad. 
Es una aplicación que se utiliza normalmente para realizar auditorías de seguridad y monitoreo de redes.

![Captura 1](https://user-images.githubusercontent.com/101887562/188697933-cc320a74-cf45-4d54-b899-081fd1e23d6d.PNG)

# RECONOCIMIENTO DEL SISTEMA 

![Captura 1](https://user-images.githubusercontent.com/101887562/188697933-cc320a74-cf45-4d54-b899-081fd1e23d6d.PNG)
![image](https://user-images.githubusercontent.com/101887562/188697774-43bff4ae-b721-4d48-bca3-350f9d00a2f2.png)

## 4
A. El comando 6 de la lista anterior ejecuta una tubería compuesta por dos comandos del sistema operativo Linux en WSL lo que es el comportamiento esperado y también funcionaria en una máquina virtual huésped o en un anfitrión con Linux; el comando 12 es un comando del sistema 
operativo Windows que no se puede ejecutar en sistemas Linux, pero si se puede ejecutar en WSL, Explique.


### El comando 6: si ya que al tratarse de comandos en Linux, y sabemos que estos funcionan como tubería y prácticamente lo que hacen es enviar información y el otro extremo lo confirma.

### El comando 12: este nos permite enviar paquetes con una diferencia que nos muestra la ruta que toma hasta el destino.

B. La línea 15 describe una tubería que ejecuta un comando Windows y lo canaliza a la entrada de un comando que no existe en Windows, explique.

### línea 15: esto permite que al canalizar dicho comando Windows este forjado a ejecutar el comando desconocido para realizar dicha ejecución.

C. La línea 16 y 17 describen la situación anterior pero adicionalmente accede al sistema de archivos de Windows para crear un archivo, explique.
