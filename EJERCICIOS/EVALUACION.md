## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?
(valor 1.5)

        1. Mantener y operar los sistemas de informacion de las organizaciones

        2. Crear bases de datos normalizadas utilizando una nomenclatura de diseño estandarizada

        3. Diseñar repositorios mas eficientes para el analisis de la informacion

        4. Transformar los requerimientos del cliente en reglas de negocio y realizar con ellas un modelo 

        5. Mantener la confidencialidad de la informacion y protegerla mediante los programas con que se manipula.

2. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)

       1. Determinan las estructuras de almacenamiento del sistema.
 
       2. Facilitan las búsquedas de datos de cualquier tipo y procedencia a los usuarios de negocio.

       3. Ayudan a mantener la integridad de los activos informacionales de la empresa.

       4. Introducen cambios en la información, si es requerido.

       5. Simplifican los procesos de consulta.

       6. Controlan los movimientos que se observan en la base de datos.

3. En una BD al usuario del sistema se le brindarán recursos para realizar diversas
operaciones sobre estos archivos, tales como: (valor 1.5)

       Lectura y registro de nuevos datos.

4. ¿Qué es un Sistema de Información? (valor 1.5)

       Un Sistema de Información (SI) es un conjunto de componentes interrelacionados que trabajan juntos para recopilar, procesar, almacenar y difundir información          
       para apoyar la toma de decisiones. Además apoyan la coordinación, control, análisis y visualización de una organización.

## Práctica 2.

2. Diseño de un modelo relacional

Objetivo: Representar desde un modelo entidad relación un problema


Ejercicio:

Tenemos que diseñar una base de datos sobre proveedores y disponemos de la siguiente
información:

Realiza el modelo entidad relación. (valor 6)

Tenemos esta información sobre una cadena editorial:

● La editorial tiene varias sucursales, con su domicilio, teléfono y un código de
sucursal.

● Cada sucursal tiene varios empleados, de los cuales tendremos su nombre,
apellidos, NIF y teléfono. Un empleado trabaja en una única sucursal.

● En cada sucursal se publican varias revistas, de las que almacenaremos su título,
número de registro, periodicidad y tipo.

● Una revista puede ser publicada por varias sucursales.

● La editorial tiene periodistas (que no trabajan en las sucursales) que pueden
escribir artículos para varias revistas. Almacenaremos los mismos datos que para
los empleados, añadiendo su especialidad.

● También es necesario guardar las secciones fijas que tiene cada revista, que
constan de un título y una extensión.

● Para cada revista, almacenaremos información de cada ejemplar, que incluirá la
fecha, número de páginas y el número de ejemplares vendidos.

![image](https://user-images.githubusercontent.com/104279688/171549483-509d6d1c-bb8b-4cd8-8507-5ec9cee6af58.png)



