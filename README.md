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

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20220521.png" alt="Descripción de la imagen" width="500" height="350">
<br>

### ps a

> Muestra los procesos de todos los usuarios que están asociados con la  <br>
 terminal actual, no solo los que pertenecen al usuario que ejecuta el comando.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223406.png" alt="Descripción de la imagen" width="700" height="300">

### ps aux

> Combinación de comandos que te permite obtener información detallada sobre los <br>
procesos en ejecución y, al mismo tiempo, filtrar esos procesos según un patrón específico

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223456.png" alt="Descripción de la imagen" width="600" height="400">

### ps -C nano

> Busca procesos ejecutándose con el nombre nano y los muestra en un formato más limpio y compacto

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223955.png" alt="Descripción de la imagen" width="500" height="200">

</details>

<br>

<details>
 
<summary> Comandos Top </summary>

### Top T

> Ordena por tiempo acumulado del CPU. <br>
Los procesos se ordenan según la cantidad de tiempo total de CPU que han usado.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20181948.png" alt="Descripción de la imagen" width="800" height="500">

### Top M

> Ordena por uso de memoria (RAM). <br>
Esto muestra primero los procesos que están consumiendo más memoria física.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182044_M.png" alt="Descripción de la imagen" width="800" height="500">

### Top P

> Ordena por uso del CPU. <br>
Los procesos se clasifican según el porcentaje de CPU que están utilizando en ese momento.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182150_%20P.png" alt="Descripción de la imagen" width="800" height="500">

### Top p

> Filtra o selecciona procesos específicos por su PID. <br>
Por ejemplo, puedes filtrar para que solo se muestre información de un proceso en particular.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182222_p.png" alt="Descripción de la imagen" width="800" height="500">

### Top R

> Invierte el orden de la clasificación. <br>
Por ejemplo, si los procesos están ordenados del más alto al más bajo en consumo de CPU, esta opción invierte el orden (de menor a mayor).

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182255_R.png" alt="Descripción de la imagen" width="800" height="500">

### Top U

> Muestra procesos de un usuario específico. <br>
Puedes ingresar el nombre de usuario y filtrar los procesos para mostrar solo aquellos ejecutados por ese usuario.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182319_U.png" alt="Descripción de la imagen" width="800" height="500">

### Top q

> Salir del comando top. <br>
Finaliza la sesión de top y regresa a la terminal.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182357_q.png" alt="Descripción de la imagen" width="800" height="500">

### Top k

> Mata un proceso. <br>
Se te pedirá ingresar el PID de un proceso que quieras finalizar manualmente.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182420_k.png" alt="Descripción de la imagen" width="800" height="500">

</details>

<br>

<details>

<summary>Comandos htop</summary>


### htop -u <usuario>

> Filtra y muestra solo los procesos que pertenecen a un usuario específico.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20184807.png" alt="Descripción de la imagen" width="750" height="500">

### htop --tree 

> Muestra los procesos en un formato de árbol jerárquico.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20184825.png" alt="Descripción de la imagen" width="750" height="500">

### htop -p <PDI1, PDI2>

> Filtra y muestra información únicamente sobre procesos específicos, identificados por sus PIDs.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20185010.png" alt="Descripción de la imagen" width="750" height="500">

 <br>
 <br>

<summary>Atajos de teclado</summary>

### F2

> Abre el menú de configuración de htop, donde puedes personalizar el entorno. Algunas de las configuraciones que puedes ajustar son: <br>
Cambiar los colores de la interfaz. <br>
Mostrar u ocultar columnas específicas. <br>
Configurar cómo se visualizan los procesos (por ejemplo, combinarlos por usuario). <br>
Personalizar las métricas que se muestran en las barras de CPU y memoria.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200059_f2.png" alt="Descripción de la imagen" width="750" height="500">

### F3

> Permite buscar procesos específicos escribiendo parte del nombre, PID u otros atributos. <br>
Escribe el término que buscas, y htop resaltará las coincidencias en la lista de procesos en tiempo real.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200153_f3.png" alt="Descripción de la imagen" width="750" height="500">

### F4

> Aplica un filtro para mostrar solo los procesos que coincidan con un término específico. <br>
Al activarlo, escribe el término que deseas filtrar, y la lista de procesos se limitará únicamente a los que coincidan con el término.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200227_f4.png" alt="Descripción de la imagen" width="750" height="500">

### F5

> Cambia la visualización de los procesos para mostrarlos en formato jerárquico (árbol). <br>
Muestra la relación entre procesos padre e hijos, indicando quién inició qué procesos. <br>
Es útil para analizar dependencias entre procesos.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200253_f5.png" alt="Descripción de la imagen" width="750" height="500">

### F6

> Permite cambiar el criterio de ordenación de los procesos en la lista. <br>
Los procesos se pueden ordenar por columnas como: <br>
Uso de CPU. <br>
Uso de memoria. <br>
PID. <br>
Estado, entre otros. <br>
Al presionar F6, aparece un menú donde puedes elegir la columna por la que deseas ordenar.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200312_f6.png" alt="Descripción de la imagen" width="750" height="500">

### F9

> Abre un menú para enviar señales a un proceso específico, generalmente para terminarlo. <br>
Cuando seleccionas un proceso y presionas F9, puedes elegir qué señal enviar (por defecto, SIGTERM para solicitar al proceso que se cierre).
SIGTERM (15): Termina el proceso de manera educada, permitiéndole limpiar recursos. <br>
SIGKILL (9): Fuerza la terminación inmediata del proceso (se recomienda usarlo como último recurso).

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200346_f9.png" alt="Descripción de la imagen" width="750" height="500">

</details>

<br>

<details>

 <summary>Comando atop</summary>

### atop -r 

> Se utiliza para leer archivos de registro previamente guardados con el comando atop en modo registro

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20193117.png" alt="Descripción de la imagen" width="750" height="500">
 
</details>

<br>

<h1 align="center">Monitorización del almacenamiento<a name="2"></a></h1>

<details>

<summary>Comandos free</summary>

### -h

> Muestra la información de la memoria en un formato no binario. <br>
Las cantidades se presentan en KiB, MiB, GiB, o la unidad más apropiada en lugar de mostrar los valores en kilobytes sin procesar.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20201831_-h.png" alt="Descripción de la imagen" width="700" height="300">

### -t

>Agrega una línea adicional a la salida que muestra el total combinado de todas las memorias, tanto RAM como swap.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20201904_-t.png" alt="Descripción de la imagen" width="700" height="400">

### -s <segundos>

> Ejecuta el comando free de forma repetitiva, mostrando la salida cada [segundos] que especifiques. <br>
Es útil para monitorear el uso de la memoria en tiempo real, con actualizaciones periódicas.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20201929_-s.png" alt="Descripción de la imagen" width="700" height="400">
 
</details>

<br>

<details>

 <summary>Comandos df</summary>

### -h

> Muestra la información en un formato no binario. <br>
Los valores del tamaño, espacio usado y espacio disponible se muestran en unidades como KB, MB, GB, etc., en lugar de bytes.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20203101_-h.png" alt="Descripción de la imagen" width="900" height="400">
 
### -t

> Muestra el tipo de sistema de archivos además de la información habitual. <br>

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20203156_-t.png" alt="Descripción de la imagen" width="900" height="400">

 ### -x [Tipo]

> Excluye de la salida los sistemas de archivos que coincidan con el [tipo] especificado.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20203232_-x.png" alt="Descripción de la imagen" width="900" height="400">

</details>

<br>

<details>

<summary>Comandos du</summary>

### -h

> Muestra el espacio ocupado de manera legible.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20204454.png" alt="Descripción de la imagen" width="900" height="400">

### -s

> Muestra el total de espacio usado por un directorio (sin desglosar).

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20204518.png" alt="Descripción de la imagen" width="900" height="400">

### -d [nivel]

> Muestra el espacio ocupado por los directorios hasta el nivel de profundidad especificado.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20204614.png" alt="Descripción de la imagen" width="900" height="400">

</details>

<br>

<details>

<summary>Comandos iostat</summary>

### -x

> Muestra estadísticas extendidas de los dispositivos de almacenamiento, proporcionando más detalles sobre el rendimiento de los discos. <br>
Incluye métricas adicionales como el porcentaje de tiempo que el dispositivo está ocupado, la cantidad de operaciones por segundo, la espera de la cola de disco, y más.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20205343.png" alt="Descripción de la imagen" width="900" height="400">

### -d

> Muestra solo estadísticas de dispositivos de almacenamiento, sin incluir información sobre la CPU.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20205403.png" alt="Descripción de la imagen" width="900" height="400">

### -c

> Muestra solo estadísticas de la CPU, omitiendo la información sobre los discos.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20205433.png" alt="Descripción de la imagen" width="900" height="400">
 
</details>

<br>

<h1 align="center">Monitorización de la red<a name="3"></a></h1>

<details>

<summary>Comandos tcpdump</summary>

### sudo tcpdump

> Captura el tráfico de todas las interfaces.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20210523.png" alt="Descripción de la imagen" width="500" height="400">

### sudo tcpdump -i <nombre_interfaz>

> Especifica la interfaz de red para capturar.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20210636.png" alt="Descripción de la imagen" width="500" height="400">

### sudo tcpdump -i <nombre_interfaz>

> Filtra por puerto específico.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20210709.png" alt="Descripción de la imagen" width="500" height="400">
 
</details>

