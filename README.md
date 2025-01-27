# Monitorizaci-n-de-comandos
## Alejandro Bayo Gómez

## Índice ##

1. [Monitorización de procesos](#1)
2. [Monitorización del almacenamiento](#2)
3. [Monitorización de la red](#3)
4. [Referencias](#4)


<h1 align="center">Monitorización de procesos<a name="1"></a></h1>

<details>

<summary> Comandos ps </summary>

### ps

> El comando ps proporciona una instantánea de los procesos en ejecución.  <br>
Es útil para obtener información específica sobre procesos.


<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20220521.png" alt="Descripción de la imagen" width="500" height="350">
<br>

### ps a

> Muestra los procesos de todos los usuarios que están asociados con la  <br>
 terminal actual, no solo los que pertenecen al usuario que ejecuta el comando.

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223406.png" alt="Descripción de la imagen" width="700" height="300">

### ps aux

> Combinación de comandos que te permite obtener información detallada sobre los <br>
procesos en ejecución y, al mismo tiempo, filtrar esos procesos según un patrón específico 

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223456.png" alt="Descripción de la imagen" width="600" height="400">

### ps -C nano

> Busca procesos ejecutándose con el nombre nano y los muestra en un formato más limpio y compacto

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223955.png" alt="Descripción de la imagen" width="500" height="200">

</details>

<br>

<details>
 
<summary> Comandos Top </summary>

### Top T

> Ordena por tiempo acumulado del CPU. <br>
Los procesos se ordenan según la cantidad de tiempo total de CPU que han usado.

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20181948.png" alt="Descripción de la imagen" width="800" height="500">

### Top M

> Ordena por uso de memoria (RAM). <br>
Esto muestra primero los procesos que están consumiendo más memoria física.

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182044_M.png" alt="Descripción de la imagen" width="800" height="500">

### Top P

> Ordena por uso del CPU. <br>
Los procesos se clasifican según el porcentaje de CPU que están utilizando en ese momento.

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182150_%20P.png" alt="Descripción de la imagen" width="800" height="500">

### Top p

> Filtra o selecciona procesos específicos por su PID. <br>
Por ejemplo, puedes filtrar para que solo se muestre información de un proceso en particular.


<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182222_p.png" alt="Descripción de la imagen" width="800" height="500">

### Top R

> Invierte el orden de la clasificación. <br>
Por ejemplo, si los procesos están ordenados del más alto al más bajo en consumo de CPU, esta opción invierte el orden (de menor a mayor).

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182255_R.png" alt="Descripción de la imagen" width="800" height="500">

### Top U

> Muestra procesos de un usuario específico. <br>
Puedes ingresar el nombre de usuario y filtrar los procesos para mostrar solo aquellos ejecutados por ese usuario.

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182319_U.png" alt="Descripción de la imagen" width="800" height="500">

### Top q

> Salir del comando top. <br>
Finaliza la sesión de top y regresa a la terminal.

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182357_q.png" alt="Descripción de la imagen" width="800" height="500">

### Top k

> Mata un proceso. <br>
Se te pedirá ingresar el PID de un proceso que quieras finalizar manualmente.

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182420_k.png" alt="Descripción de la imagen" width="800" height="500">

</details>

<details>

<summary>Comandos htop</summary>


### htop -u <usuario>

> Filtra y muestra solo los procesos que pertenecen a un usuario específico.

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20184807.png" alt="Descripción de la imagen" width="800" height="500">

### htop --tree 

> Muestra los procesos en un formato de árbol jerárquico.

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20184825.png" alt="Descripción de la imagen" width="800" height="500">

### htop -p <PDI1, PDI2>

> Filtra y muestra información únicamente sobre procesos específicos, identificados por sus PIDs.

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20185010.png" alt="Descripción de la imagen" width="800" height="500">
 
</details>


