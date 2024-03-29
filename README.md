# Proyecto Farmaco_NTZ184

 **Proyecto acerca de una etapa de experimentacion fictícia en chimpancés en el área cientifica  de un farmaco fictício relacionando la DB con una GUI utilizando JDBC con MySQL en JAVA SE con Ant**
 
 </br>

| **Tecnologías** | **Versión** |               
| ------------- | ------------- |
| Java |   12.0.2 |
| Apache NetBeans IDE|  12.0 |
| XAMPP | 3.2.2  |
| Mysql Workbench | 8.0.20  |

 ## Patrones de Diseño Implementados
 * **Singleton** 
 * **Dao** 
 
 ## Uso de Java8
* **Streams y Lambdas**
* **Filters**
* **Collections**
* **Etc..**

</br>

![Index app](https://github.com/andresWeitzel/Graphics/blob/main/Proyectos/FarmacoNTZ184/Captura%20de%20pantalla%20(515).png)


</br>


# EJECUCIÓN DE LA APP

## DESCARGA Y TESTEO EN WINDOWS

### 1)Descargar y Descomprimir el Proyecto
 * Proyecto`.rar` en: ***https://github.com/andresWeitzel/Farmaco_NTZ184/blob/master/FarmacoNTZ184_app.rar***

### 2)Levantar el servicio mysql desde algun motor de base de datos o desde el cmd/powershell.

### 3)Configurar el driver deseado de mysql  y ejecutar el ddl/dml del proyecto  desde el ide.
* Driver desde el repositorio siguiente: ***https://github.com/andresWeitzel/Farmaco_NTZ184/tree/master/Drivers*** 
* Ruta del driver desde la carpeta dentro del proyecto  `..\FarmacoNTZ184_app\src\mypackage\driver`

### 4)Ejecutar el Proyecto desde el .jar  o desde el ide

### 5)Los campos para validar el ingreso de nuevos individuos son
* `usuario:1`
* `contraseña:1`

</br>


## DESCARGA Y TESTEO EN LINUX(DESDE TERMINAL)

### 1)Abrir la Terminal y Actualizar la lista de repositorios
* sudo apt -y update

### 2)Levantar y verificar que esta corriendo el servicio de mysql
* sudo service mysql start
* sudo service mysql status

### 3)Clonar el repositorio del Proyecto
* git clone ***https://github.com/andresWeitzel/Farmaco_NTZ184/tree/master***


### 4)Posicionarnos sobre el directorio del proyecto y visualizar el contenido
* cd rutaEjemplo/Farmaco_NTZ184
* ls -l

### 5)Si no se tiene alguna herramienta para descomprimir el .rar descargar
* sudo apt install unrar

### 5)Testeamos la integridad del proyecto comprimido(tamaño total 25605249 b)
* unrar l Farmaco_ntz184-master.rar

### 6)Descomprimimos el proyecto
* unrar l Farmaco_ntz184-master.rar

### 6)Configurar el driver en el ide y ejecutar el ddl/dml del proyecto

### 7)Posicionarse sobre la carpeta dist y darle todos los permisos al .jar
* cd FarmacoNTZ184_app/dist
* chmod +777 FarmacoNTZ184_app.jar

### 8)Ejecutar el .jar
* java -jar FarmacoNTZ184_app.jar

### 9)Los campos para validar el ingreso de nuevos individuos son
* `usuario:1`
* `contraseña:1`
