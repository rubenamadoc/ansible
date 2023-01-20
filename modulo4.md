Los playbooks permiten gestionar la configuración del despliegue, definiendo la serie de pasos a seguir.

La configuración se realiza de la siguiente manera.

1. Crear un directorio donde se guardarán los archvios necesarios para el despliegue.

2. Crear dentro del directorio un archivo de nombre hosts, el cual se utilizará para indicar la información del servidor remoto.

![](Imagenes/hosts)

3. Crear las keys de ssh y pasarlo al servidor remoto para facilitar nuestra conexión con el mismo.

![](Imagenes/ssh-keygen)

![](Imagenes/copykey)

4. Crear el playbook dentro del directorio.

- Los parámetros son introducidos en un archivo .yml.

- La estrcutura de un playbook:

![](Imagenes/playbook)

Hosts: indico el nombre de dominio donde instalaré NGINX

remote_user: es el nombre de usuario de la maquina donde se realizará la acción

- Ansible proporciona distintos módulos que realizan un acción determinada:

1. Gestor de paquetes: nos permite instalar, borrar, actualizar etc.

Que es el que he realizado como prueba

2. Service: para, inicia, habilita o deshabilita servicios.

![](Imagenes/servicio)

3. Copy: copia archivos de una máquina a otra.

![](Imagenes/copia)

4. Debug: imprime declaraciones.

![](Imagenes/debug)

5. File: maneja archivos.

![](Imagenes/file)

6. Command: ejecuta comandos en el servidor remoto.

![](Imagenes/comando)
