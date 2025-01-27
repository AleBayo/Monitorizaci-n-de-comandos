# Monitorizacion de comandos
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

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20220521.png" alt="Descripción de la imagen">
<br>

### ps a

> Muestra los procesos de todos los usuarios que están asociados con la  <br>
 terminal actual, no solo los que pertenecen al usuario que ejecuta el comando.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223406.png" alt="Descripción de la imagen">

### ps aux

> Combinación de comandos que te permite obtener información detallada sobre los <br>
procesos en ejecución y, al mismo tiempo, filtrar esos procesos según un patrón específico

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223456.png" alt="Descripción de la imagen">

### ps -C nano

> Busca procesos ejecutándose con el nombre nano y los muestra en un formato más limpio y compacto

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-23%20223955.png" alt="Descripción de la imagen">

</details>

<br>

<details>
 
<summary> Comandos Top </summary>

### Top T

> Ordena por tiempo acumulado del CPU. <br>
Los procesos se ordenan según la cantidad de tiempo total de CPU que han usado.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20181948.png" alt="Descripción de la imagen">

### Top M

> Ordena por uso de memoria (RAM). <br>
Esto muestra primero los procesos que están consumiendo más memoria física.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182044_M.png" alt="Descripción de la imagen">

### Top P

> Ordena por uso del CPU. <br>
Los procesos se clasifican según el porcentaje de CPU que están utilizando en ese momento.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182150_%20P.png" alt="Descripción de la imagen">

### Top p

> Filtra o selecciona procesos específicos por su PID. <br>
Por ejemplo, puedes filtrar para que solo se muestre información de un proceso en particular.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182222_p.png" alt="Descripción de la imagen">

### Top R

> Invierte el orden de la clasificación. <br>
Por ejemplo, si los procesos están ordenados del más alto al más bajo en consumo de CPU, esta opción invierte el orden (de menor a mayor).

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182255_R.png" alt="Descripción de la imagen">

### Top U

> Muestra procesos de un usuario específico. <br>
Puedes ingresar el nombre de usuario y filtrar los procesos para mostrar solo aquellos ejecutados por ese usuario.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182319_U.png" alt="Descripción de la imagen">

### Top q

> Salir del comando top. <br>
Finaliza la sesión de top y regresa a la terminal.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182357_q.png" alt="Descripción de la imagen">

### Top k

> Mata un proceso. <br>
Se te pedirá ingresar el PID de un proceso que quieras finalizar manualmente.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20182420_k.png" alt="Descripción de la imagen">

</details>

<br>

<details>

<summary>Comandos htop</summary>


### htop -u <usuario>

> Filtra y muestra solo los procesos que pertenecen a un usuario específico.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20184807.png" alt="Descripción de la imagen">

### htop --tree 

> Muestra los procesos en un formato de árbol jerárquico.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20184825.png" alt="Descripción de la imagen">

### htop -p <PDI1, PDI2>

> Filtra y muestra información únicamente sobre procesos específicos, identificados por sus PIDs.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20185010.png" alt="Descripción de la imagen">

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

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200059_f2.png" alt="Descripción de la imagen">

### F3

> Permite buscar procesos específicos escribiendo parte del nombre, PID u otros atributos. <br>
Escribe el término que buscas, y htop resaltará las coincidencias en la lista de procesos en tiempo real.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200153_f3.png" alt="Descripción de la imagen">

### F4

> Aplica un filtro para mostrar solo los procesos que coincidan con un término específico. <br>
Al activarlo, escribe el término que deseas filtrar, y la lista de procesos se limitará únicamente a los que coincidan con el término.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200227_f4.png" alt="Descripción de la imagen">

### F5

> Cambia la visualización de los procesos para mostrarlos en formato jerárquico (árbol). <br>
Muestra la relación entre procesos padre e hijos, indicando quién inició qué procesos. <br>
Es útil para analizar dependencias entre procesos.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200253_f5.png" alt="Descripción de la imagen">

### F6

> Permite cambiar el criterio de ordenación de los procesos en la lista. <br>
Los procesos se pueden ordenar por columnas como: <br>
Uso de CPU. <br>
Uso de memoria. <br>
PID. <br>
Estado, entre otros. <br>
Al presionar F6, aparece un menú donde puedes elegir la columna por la que deseas ordenar.

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200312_f6.png" alt="Descripción de la imagen">

### F9

> Abre un menú para enviar señales a un proceso específico, generalmente para terminarlo. <br>
Cuando seleccionas un proceso y presionas F9, puedes elegir qué señal enviar (por defecto, SIGTERM para solicitar al proceso que se cierre).
SIGTERM (15): Termina el proceso de manera educada, permitiéndole limpiar recursos. <br>
SIGKILL (9): Fuerza la terminación inmediata del proceso (se recomienda usarlo como último recurso).

<br>

<img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20200346_f9.png" alt="Descripción de la imagen">

</details>

<br>

<details>

 <summary>Comando atop</summary>

### atop -r 

> Se utiliza para leer archivos de registro previamente guardados con el comando atop en modo registro

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20193117.png" alt="Descripción de la imagen">
 
</details>

<br>

<h1 align="center">Monitorización del almacenamiento<a name="2"></a></h1>

<details>

<summary>Comandos free</summary>

### -h

> Muestra la información de la memoria en un formato no binario. <br>
Las cantidades se presentan en KiB, MiB, GiB, o la unidad más apropiada en lugar de mostrar los valores en kilobytes sin procesar.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20201831_-h.png" alt="Descripción de la imagen">

### -t

>Agrega una línea adicional a la salida que muestra el total combinado de todas las memorias, tanto RAM como swap.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20201904_-t.png" alt="Descripción de la imagen">

### -s <segundos>

> Ejecuta el comando free de forma repetitiva, mostrando la salida cada [segundos] que especifiques. <br>
Es útil para monitorear el uso de la memoria en tiempo real, con actualizaciones periódicas.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20201929_-s.png" alt="Descripción de la imagen">
 
</details>

<br>

<details>

 <summary>Comandos df</summary>

### -h

> Muestra la información en un formato no binario. <br>
Los valores del tamaño, espacio usado y espacio disponible se muestran en unidades como KB, MB, GB, etc., en lugar de bytes.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20203101_-h.png" alt="Descripción de la imagen">
 
### -t

> Muestra el tipo de sistema de archivos además de la información habitual. <br>

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20203156_-t.png" alt="Descripción de la imagen">

 ### -x [Tipo]

> Excluye de la salida los sistemas de archivos que coincidan con el [tipo] especificado.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20203232_-x.png" alt="Descripción de la imagen">

</details>

<br>

<details>

<summary>Comandos du</summary>

### -h

> Muestra el espacio ocupado de manera legible.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20204454.png" alt="Descripción de la imagen">

### -s

> Muestra el total de espacio usado por un directorio (sin desglosar).

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20204518.png" alt="Descripción de la imagen"">

### -d [nivel]

> Muestra el espacio ocupado por los directorios hasta el nivel de profundidad especificado.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20204614.png" alt="Descripción de la imagen">

</details>

<br>

<details>

<summary>Comandos iostat</summary>

### -x

> Muestra estadísticas extendidas de los dispositivos de almacenamiento, proporcionando más detalles sobre el rendimiento de los discos. <br>
Incluye métricas adicionales como el porcentaje de tiempo que el dispositivo está ocupado, la cantidad de operaciones por segundo, la espera de la cola de disco, y más.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20205343.png" alt="Descripción de la imagen">

### -d

> Muestra solo estadísticas de dispositivos de almacenamiento, sin incluir información sobre la CPU.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20205403.png" alt="Descripción de la imagen">

### -c

> Muestra solo estadísticas de la CPU, omitiendo la información sobre los discos.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20205433.png" alt="Descripción de la imagen">
 
</details>

<br>

<h1 align="center">Monitorización de la red<a name="3"></a></h1>

<details>

<summary>Comandos tcpdump</summary>

### sudo tcpdump

> Captura el tráfico de todas las interfaces.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20210523.png" alt="Descripción de la imagen">

### sudo tcpdump -i <nombre_interfaz>

> Especifica la interfaz de red para capturar.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20210636.png" alt="Descripción de la imagen">

### sudo tcpdump -i <nombre_interfaz>

> Filtra por puerto específico.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20210709.png" alt="Descripción de la imagen">
 
</details>

<br>

<details>

<summary>Comandos tcptrack</summary>

### sudo tcptrack -i <nombre_interfaz>

> Monitoriza las conexiones TCP en la interfaz especificada.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20211833.png" alt="Descripción de la imagen">
 
</details>

<br>

<details>

<summary>Comandos iptraf-ng</summary>

### sudo iptraf-ng

> Esto iniciará el programa en modo interactivo en la terminal. <br>
Necesitarás privilegios de superusuario porque iptraf-ng necesita acceso a las interfaces de red del sistema.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20212231.png" alt="Descripción de la imagen">

</details>

<br>

<details>

<summary>Comandos netstat</summary>

### netstat -a

>Muestra todas las conexiones de red activas y los puertos abiertos en el sistema. <br>
Incluye conexiones TCP y UDP tanto activas como en espera.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20212754.png" alt="Descripción de la imagen">

### netstat -n

> Muestra las conexiones activas con direcciones IP y números de puertos numéricos, en lugar de resolver nombres de dominio o servicios. <br>
Es útil para identificar direcciones y puertos exactos sin resolución de nombres.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20212817.png" alt="Descripción de la imagen">

### netstat -tp

> Muestra conexiones TCP activas, junto con el proceso asociado a cada conexión. <br>
Incluye información sobre el PID y el nombre del proceso que mantiene la conexión.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20212834.png" alt="Descripción de la imagen">

### netstat -l

> Muestra únicamente los puertos en escucha. <br>
Esto es útil para identificar los servicios o aplicaciones que están esperando conexiones entrantes.

<br>

 <img src="https://github.com/AleBayo/Monitorizaci-n-de-comandos/blob/main/Captura%20de%20pantalla%202025-01-27%20212854.png" alt="Descripción de la imagen">

</details>

<h1 align="center">Referencias<a name="4"></a></h1>

He conseguido toda la información mediante internet buscando en varias páginas y con un poco de la ayuda de la inteligencia artificial en casos concretos
