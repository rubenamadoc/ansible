Los playbooks permiten gestionar la configuración del despliegue, definiendo la serie de pasos a seguir.

La configuración se realiza de la siguiente manera.

- Los parámetros son introducidos en un archivo .yml.

- La estrcutura de un playbook:

<>(![](Imagenes/playbook))

- Ansible proporciona distintos módulos que realizan un acción determinada:

1. Gestor de paquetes: nos permite instalar, borrar, actualizar etc.

<>(![](Imagenes/paquetes))

2. Service: para, inicia, habilita o deshabilita servicios.

<>(![](Imagenes/servicio))

3. Copy: copia archivos de una máquina a otra.

<>(![](Imagenes/copia))

4. Debug: imprime declaraciones.

<>(![](Imagenes/debug))

5. File: maneja archivos.

<>(![](Imagenes/file))

6. Command: ejecuta comandos en el servidor remoto.

<>(![](Imagenes/comando))
