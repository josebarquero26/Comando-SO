# Comando-SO
# Lista de comando del Curso de SO Ulacit
| Comando | Descripcion  | Ejemplo  |
| :-----: | :-: | :-: |
|ip addr | Me indica el IP de mi maquina | ip addr |
|cd | Se utiliza para navegar por los archivos del sistema | cd Documentos |
| pwd | Se utiliza para obtener la ruta del directorio en el cual estoy ubicado | pwd |
| ls | Se utiliza ver el contenido de un directorio, si se utiliza sin ruta es el directorio actual, pero se puede agregar una ruta para ver el de otro directorio | ls o  ls/home/nombredeusuario/Documentos |
| ls -l | lista todos los archivos con sus permisos |ls -l Documentos |
| cat | Se utiliza para listar el contenido de un archivos o concatenar | cat > nombre (crea un archivo con el nombre) // cat nombredearchivo1 nombredearchivo2>nombredearchivo3|
|mkdir | Crear nuevo directorio | mkdir directorio |
|sudo apt update | Se utiliza para ver cuales archivos se pueden actualizar | sudo apt update |
|sudo apt upgrade| Se utiliza para actualizar los programas | sudo apt upgrade |
|&&| && se utiliza para poder ejecutar comandos uno despues de otro |sudo apt update && sudo apt upgrade |
|mv| Se puede utilzar para mover achivos o cambiarlos de nombre | mv texto.txt /home/nombredeusuario/Documentos. // mv nombreviejo.txt nombrenuevo.txt |
|cp| Se utiliza para copiar archivos del directorio acutal a otro | cp foto.jpg /home/nombredeusuario/Imagenes |
|rmdir | Se utiliza para eliminar directorios vacios | rmdir directorio |
|rm | Se utiliza para eliminar directorios y su contenido | rm directorio |
| locate | Se utiliza para localizar directorios y archivos | locate nombreArchivo |
| find | Se utilzia para buscar archivos dentro de un directorio dado | find text.txt |
| grep | Se utiliza para buscar una palabra en un archivo |grep -r linux /var/log/syslog |
| sudo | Se utiliza para realizar comandos como el administrador |sudo apt get update|
| sudo su | Se utiliza para concetarse como root y evitar escribir la clave cada vez |sudo su |
| su root | Se utiliza para convertirse en usuario root |su root |
| exit | Se utiliza para salirse de root |exit |
| nano| Se utiliza para crear archivos de texto |nano text |
| vi| Es un editor de texto algo complejo |vi text |
| df -h| Se utiliza para ver el espacio del disco duro |df -h |
| sudo apt install gparted | sirve para administrar las particiones del sistema|sudo apt install gparted  |
| ls /tmp | grep texto2.txt  |Comando compuesto para mostrar contenido de la carpeta tmp y lo uno con grep para ver si existe| ls /tmp | grep texto2.txt |
| history| Se utiliza para ver el historial de la terminar |history |
| rm  -Rf| Elimina folder y todos los archivos dentro de forma forzada |rm prueba -Rf  |
| sudo rm -Rf| Comando de la muerte, borra todo el sistema operativo |sudo rm -Rf /   |
| wget | Se utiliza para obtener los urls | wget https://wordpress.org/latest.zip |
| head | Se utiliza para ver las primeras lineas de archivos de texto | head -n 5 nombredearchivo.ext. (con el -n num  se escogen la cantidad de filas que se ven)|
| tail | Se utiliza para ver las ultimas lineas de archivos de texto | tail -n 5 nombredearchivo.ext. (con el -n num  se escogen la cantidad de filas que se ven)|
| diff | Se utiliza para comparar el contendo linea por linea de dos archivos | diff archivo1.ext archivo2.ext|
| tar | Es el formato zip de linux | tar -cvf sampleArchive.tar /home/sampleArchive |
| chmod | Se utiliza para cambiar los permisos de lectura, escritura y ejecucion | chmod 754 myfile (utilizando la nomenclatura octagonal de los permisos)|
| chown | Se utiliza para cambiar la propiedad de los archivos | chown usuariolinux2 archivo.ext |
| more |  Permite ver por lineas un archivo | more /var/log/syslog  |
| history > historial.txt  |  Permite ver por lineas un archivo | history > historial.txt   |
| du -h  | Me dice el tamaño del archivo |du -h Prueba.txt |
| touch  | Cambia la hora de modificacion, si se utiliza y el archivo no existe, se crea |touch Prueba.txt |
| file | Me da el formato del archivo |file Prueba.txt |
| whoami| Me da el nombre del usuario |whoami |
| kill | Cierra los programas de manera manual | kill-9$SPID |
| shutdown now | Apaga la maquina | shutdown now   |
| reboot | Reinicia la maquina | sudo reboot   |
| sudo useradd | Crea un usuario nuevo | sudo useradd username |
| uname | Da la informacion detallada de la maquina| uname |
| top | Como un terminal equivalente al Administrador de tareas en Windows | top |
| man | Este comando muestra los manuales del comando | man tail |
| hostname -l | Sirve para conocer el nombre del host/red | hostname -l  |
| curl | Muestra el contenido de una página | curl -O http://testdomain.com/testfile.tar.gz |
| scp | Es un protocolo de transferencia de archivos en red que permite la transferencia de archivos fácil y segura entre un host remoto y uno local| scp texto.txt jbarquerog653@pegarIp:/home/jbarquerog653/Semana09/texto3.txt |
| wc | Realiza conteo de palabras, letras, lineas en archivos | wc ideas.txt excerpt.txt   |
| docker pull | Obtiene imagenes de Docker Hub | docker pull ubuntu  |
| docker rename | Permite cambiar el nombre del contenedor | docker rename my_container my_new_container  |
| docker create | Crea contenedores pero no los inicia | docker create ubuntu  |
| docker run | Crea contenedores y los inicia | docker run --name test -it debian  |
| docker rm | Borra contenedores | docker rm gnix  |
| docker update | Actualiza contenedores | dockerupdate gnix  |
| docker start| Inicia contenedores | docker start ubuntu  |
| docker stop | Detiene contenedores | docker stop gnix  |
| docker restart | Detiene e inicia un contenedor | docker restart gnix  |
| docker pause | Pausa contenedores | docker pause gnix  |
| docker unpause | Reanuda contenedores | docker unpause gnix  |
| docker wait | Bloquea hasta que un contenedor corriendo se detiene |  docker wait my_container  |
| docker pause | Pausa contenedores | docker pause gnix  |
| docker ps -a | Da una lista de todos los contenedores | docker ps -a |
| docker port | Muestra el puerto publico de un contenedor | docker port gnix  |
| docker inspects | Obseva toda la informacion de un contendor | docker inspects gnix  |
| docker stats | Muestra las estadisticas de recursos usados por un contendor | docker stats gnix  |










