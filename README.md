<center>
   <a href="http:/cbitzaraza.com.ve/"><img src="https://i.pinimg.com/474x/aa/7a/1c/aa7a1ccaf2bfbca53eb46f9c3f8d8388.jpg" /></a>
</center>

# Manual de Políticas y Procedimientos del Sistema de Gestión, Monitoreo y Administración Escolar

## **(SIGMA ESCOLAR)**

## Nodo Complejo Educativo ***"Eduardo Delfín Méndez"***<br>
<br>

## Indice
* [Declaración](#declaración)
* [Estructura del Proyecto](#estructura-del-proyecto)
* [Nombre de Dominio](#nombre-de-dominio)
* [Perfiles de Usuarios](#perfiles-de-usuario-y-acceso-a-los-datos)
* [Auditoría de Sistema](#auditoría-de-sistema)
* [Módulo Director](Director.md)
* [Módulo Sub Director Administrativo](Sub-Director-Administrativo.md)


<br>

# Declaración:

**SIGMA ESCOLAR** ES UN PROYECTO TECNOLÓGICO QUE SURGIÓ EN EL MES DE JULIO DEL AÑO 2018 CON EL PROPÓSITO DE SERVIR COMO SISTEMA DE INFORMACIÓN Y APOYO A LA GERENCIA EDUCATIVA, CONCEBIDO COMO UN CONJUNTO DE NODOS ESCOLARES QUE PERMITEN SISTEMATIZAR Y GESTIONAR LOS PROCESOS ACADÉMICOS, ADMINISTRATIVOS Y DE RECURSOS HUMANOS INSTITUCIONALES, CONDUCENTES A MAXIMIZAR LA EFICACIA Y EFICIENCIA EN LA GERENCIA EDUCATIVA.

ESTE PROYECTO ASPIRA A SER UNA HERRAMIENTA ÁGIL Y PRÁCTICA QUE PUEDE SER IMPLEMENTADA EN INSTITUCIONES AFINES, TODO EN ARAS DE ESCALAR EN EL ÁMBITO MUNICIPAL DENTRO DE LAS INSTITUCIONES DE EDUCACIÓN MEDIA GENERAL DEL MUNICIPIO PEDRO ZARAZA DEL ESTADO GUÁRICO, VENEZUELA.

AUN CUANDO ORIGINALMENTE ES UNA IDEA CONCEBIDA POR EL AUTOR Y PROPIETARIO DEL SISTEMA (**LCDO. JHONNY PÉREZ** –<camarjhoa@gmail.com>-), ESTÁ ABIERTO A RECIBIR COLABORACIONES EN MATERIA  TECNOLÓGICA U OPERATIVA, TODO EN EL MARCO DE LA FILOSOFÍA DE INTERACCIÓN Y COOPERACIÓN BAJO EL MÉTODO DEL TRABAJO COLABORATIVO, ASÍ COMO TAMBIÉN ***ES ASPIRACIÓN DEL AUTOR LIBERAR EL PROYECTO CUANDO EL MISMO ADQUIERA LA SUFICIENTE AUTONOMÍA E INDEPENDENCIA*** EN CUANTO A FUNCIONAMIENTO SE REFIERE, YA QUE FORMA PARTE DE LA INSTITUCIÓN COMO UN ACTIVO TECNOLÓGICO DE GRAN VALOR Y DE VANGUARDIA EN EL MUNICIPIO Y DENTRO DEL  ESTADO GUÁRICO, YA QUE FUE EL PRIMERO EN SU CLASE, PRODUCTO DE LOS CONOCIMIENTOS DEL PERSONAL INSTITUCIONAL COMO ES EL COMPLEJO EDUCATIVO **"EDUARDO DELFÍN MÉNDEZ"**.




## Nombre de Dominio:

***SIGMA ESCOLAR*** funciona bajo la modalidad de ***Página Web***, por lo que el proyecto debe contar con dos elementos importantes; a saber: 
* **Registro de Dominio:** Para facilitar el acceso al Sistema, se ha determinado el uso de Dominios bajo la extensión **.com.ve** ofrecidos por el Prestador de Servicios Nacional  **Conatel**, donde actualmente opera bajo a través de la dirección: ***https://www.cbitzaraza.com.ve***, nombre reservado por el autor del presente proyecto, sin menoscabo de que pueda ser utilizado a futuro otro nombre de Dominio. En este punto es conveniente señalar que, el uso de dominios implica un pago anual en forma de arancel al Estado por concepto de estos servicios.
* **Alojamiento (Hosting):** La estructura de archivos y la Base de Datos (BBDD) del proyecto deben reposar en un Servicio de Hospedaje de Archivos, con la finalidad de enlazar el dominio reservado con estos archivos, lo cual implica en algunos casos pagos por concepto de aumento de procesamiento de (CPU), memoria RAM, entre otros elementos que permiten agilizar la velocidad de las operaciones del Sistema, sobretodo en tiempos de alto tráfico como son inscripciones, revisión de expedientes, generación de procedimientos al inicio y/o final del Año Escolar.

<br>

[Regresar al Inicio](#indice)

## Perfiles de Usuario y Acceso a los Datos:
Al ser un proyecto interconectado, es necesario que diferentes tipos de usuario se registren en el sistema, asignándoles roles con el propósito de garantizar acceso a los datos e información inherente a cada usuario, sin menoscabo de obtener datos provenientes de otros módulos pero siempre respetando el orden jerárquico y el resguardo de la información, por lo que **todos los perfiles se rigen por la asignación o denegación de los siguientes privilegios:** Lectura (**r**), Escritura (**w**) y Ejecución de archivos o comandos (**x**). En tal sentido, se perfilan los siguientes tipos de usuarios:

* ***Directivo:*** Máximos privilegios, salvo aquellos que vulneren el funcionamiento de otros Módulos. En este punto, es conveniente señalar que de manera temporal y hasta que se diseñe el procedimiento de autogestión del proyecto mediante ***Protocolo de Concenso de Usuarios***, asumen máximos privilegios en este Módulo el ***"Personal Cbit Pedro Zaraza"*** desde sus usuarios respectivos y todo con el aval de la Dirección del Plantel y bajo las reglas de auditoría que rigen a los demás usuarios del Sistema. Para la creación de estos perfiles, a nivel de sistema se les asigna la denominación **"@directivo"**.
  
* ***Subdirectivo:*** Privilegios de lectura, escritura y ejecución inherentes a sus funciones, así como también privilegios especiales sólo si el Directivo lo autoriza desde su Módulo. Operan en el Módulo Directivo pero con la delimitación de privilegios sólo de su competencia, por lo que a nivel de sistema el Sub Director Académico opera bajo el perfil **"@sub-academico"** y el Sub Director Administrativo tendrá la denominación **"@sub-administrativo"**.
  
* ***Coordinador:*** Privilegios de lectura, escritura y ejecución sólo en su módulo. No tiene acceso a otros módulos, pero otros perfiles de igual rango y nivel, así como también perfiles superiores pueden acceder en modo sólo lectura a su información. El Nivel Directivo tiene privilegios para auditar este Módulo, pero en modo Sólo Lectura. Este Módulo secciona la información en niveles y turnos, por lo que en cada escolaridad se designarán (10) roles en Coordinaciones que se distribuirán en los niveles: ***1° Año, 2° Año, 3° Año, 4° Año y 5° Año*** uno por cada nivel y turno ***(MAÑANA Y TARDE)***. Todos operan bajo el perfil **"@coordinador"**.

* ***Control de Estudios:*** Privilegios de lectura, escritura y ejecución sólo en su módulo. Tiene acceso a otros módulos – Coordinaciones -- , pero otros perfiles de menor o igual rango, así como también perfiles superiores pueden acceder en modo sólo lectura a cierta información. El Nivel Directivo tiene privilegios para auditar este Módulo, pero en modo Sólo Lectura. Se crearán sólo (02) perfiles; uno por cada turno ***(MAÑANA Y TARDE)*** y operan bajo el perfil **"@ctrl-estudios"**.
  
* ***Inscripciones:*** Privilegios sólo para inscribir estudiantes de Nuevo Ingreso previamente pre-inscritos por el usuario Directivo o su Autorizado, renovar inscripciones de Estudiantes Regulares (Lisos), Estudiantes con Materia Pendiente o Repitientes de conformidad con el Calendario de Inscripciones. Sólo se tiene acceso a este Módulo por direcciones IP Autorizadas por el Directivo, con la finalidad de garantizar transparencia en los procesos de inscripción. Operan bajo este Módulo todos los anteriormente descritos y todos los usuarios registrados pero sin los privilegios de autoridad mencionados, siempre y cuando sean ***"Nómina Activa"*** de la institución y hayan sido precargados en sistema por el ***Sub Director Administrativo*** en los turnos correspondientes (MAÑANA ó TARDE).
  
* ***Otros Módulos:*** Se podrán crear otros Módulos, pero siempre respetando la metodología de Nodos, roles y los privilegios (r,w,x) antes mencionados.

<br>

[Regresar al Inicio](#indice)


## Auditoría de Sistema:

En aras de garantizar la transparencia de cada uno de los procesos y la integridad de los datos, ***SIGMA ESCOLAR*** escucha cada una de las operaciones que los diferentes usuarios en sus roles realizan, por lo que los procesos de auditoría están enfocados en dos vertientes; a saber: **OPERACIONES GENERALES Y OPERACIONES PARTICULARES**.

Se consideran ***OPERACIONES GENERALES*** aquellas que tienen como propósito registrar movimientos generales conducentes a clarificar si fuese necesario alguna posibilidad de vulneración del sistema u otros intereses. Pertenecen a esta categoría, las siguientes:

* LOGUEO DE USUARIO.
* CIERRE DE SESIÓN.


Se consideran ***OPERACIONES PARTICULARES***, todos aquellos movimientos, registros o eliminación de datos específicos y que involucren información precisa con el propósito de resarcir o clarificar cualquier eventualidad. En tal sentido, se consideran las siguientes categorías:

* ASIGNACION DE SECCION.
* LIBERACION ESTUDIANTE.
* CAMBIO DE SECCION.
* DELEGACIÓN DE FUNCIONES.
* INGRESO ESTUDIANTE.
* RETIRO ESTUDIANTE.
* CARGA ZONIFICADOS POR ARCHIVO.
* CARGA DE CUADRATURA DE PERSONAL POR ARCHIVO.
* ACTUALIZACION DATOS PERSONALES ESTUDIANTE.
* ACTUALIZACION DATOS MADRE DEL ESTUDIANTE.
* ACTUALIZACION DATOS REPRESENTANTE DEL ESTUDIANTE.
  
De igual manera, queda abierta la posibilidad de agregar nuevas funciones de auditoría, manteniendo los preceptos anteriormente expuestos en el presente Manual. Los datos recopilados en estas operaciones están enfocados a registrar:

* Fecha y hora de la operación.
* Usuario que realizó la operación (No compartir su usuario y/o clave de acceso).
* Dirección IP del equipo cliente.
* Dirección MAC del equipo cliente.
* Tipo de Movimiento (descritos anteriormente en las categorías).
* Cédula, apellidos y nombres asociados al movimiento realizado.
* Observaciones (detalles del movimiento si es necesario).

[Regresar al Inicio](#indice)

