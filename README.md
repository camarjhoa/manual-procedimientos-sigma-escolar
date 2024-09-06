<center>
   <a href="http:/cbitzaraza.com.ve/"><img src="https://i.pinimg.com/474x/aa/7a/1c/aa7a1ccaf2bfbca53eb46f9c3f8d8388.jpg" /></a>
</center>

# Manual de Políticas y Procedimientos del Sistema de Gestión, Monitoreo y Administración Escolar

## **(SIGMA ESCOLAR)**

## Nodo Complejo Educativo ***"Eduardo Delfín Méndez"***<br>
<br>

## Índice
* [Declaración](#declaración)
* [Estructura del Proyecto](#estructura-del-proyecto)
* [Nombre de Dominio](#nombre-de-dominio)
* [Perfiles de Usuarios](#perfiles-de-usuario-y-acceso-a-los-datos)
* [Módulo Director](Director.md)
* [Módulo Sub Director Administrativo](Sub Director Administrativo.md)


<br>

# Declaración:

**SIGMA ESCOLAR** ES UN PROYECTO TECNOLÓGICO QUE SURGIÓ EN EL MES DE JULIO DEL AÑO 2018 CON EL PROPÓSITO DE SERVIR COMO SISTEMA DE INFORMACIÓN Y APOYO A LA GERENCIA EDUCATIVA, CONCEBIDO COMO UN CONJUNTO DE NODOS ESCOLARES QUE PERMITEN SISTEMATIZAR Y GESTIONAR LOS PROCESOS ACADÉMICOS, ADMINISTRATIVOS Y DE RECURSOS HUMANOS INSTITUCIONALES, CONDUCENTES A MAXIMIZAR LA EFICACIA Y EFICIENCIA EN LA GERENCIA EDUCATIVA.

ESTE PROYECTO ASPIRA A SER UNA HERRAMIENTA ÁGIL Y PRÁCTICA QUE PUEDE SER IMPLEMENTADA EN INSTITUCIONES AFINES, TODO EN ARAS DE ESCALAR EN EL ÁMBITO MUNICIPAL  DENTRO DE LAS INSTITUCIONES DE EDUCACIÓN MEDIA GENERAL DEL MUNICIPIO PEDRO ZARAZA DEL ESTADO GUÁRICO, VENEZUELA.

AUN CUANDO ORIGINALMENTE ES UNA IDEA CONCEBIDA POR EL AUTOR Y PROPIETARIO DEL SISTEMA (**LCDO. JHONNY PÉREZ** –<camarjhoa@gmail.com>-), ESTÁ ABIERTO A RECIBIR COLABORACIONES EN MATERIA  TECNOLÓGICA U OPERATIVA, TODO EN EL MARCO DE LA FILOSOFÍA DE INTERACCIÓN Y COOPERACIÓN BAJO EL MÉTODO DEL TRABAJO COLABORATIVO, ASÍ COMO TAMBIÉN ES ASPIRACIÓN DEL AUTOR, LIBERAR EL PROYECTO CUANDO EL MISMO ADQUIERA LA SUFICIENTE AUTONOMÍA E INDEPENDENCIA EN CUANTO A FUNCIONAMIENTO SE REFIERE, YA QUE EL MISMO FORMA PARTE DE LA INSTITUCIÓN COMO UN ACTIVO TECNOLÓGICO DE GRAN VALOR Y DE VANGUARDIA EN EL MUNICIPIO Y DENTRO DEL  ESTADO GUÁRICO, YA QUE FUE EL PRIMERO EN SU CLASE, PRODUCTO DE LOS CONOCIMIENTOS DEL PERSONAL PROPIO DE UNA INSTITUCIÓN EDUCATIVA PÚBLICA COMO ES EL COMPLEJO EDUCATIVO **"EDUARDO DELFÍN MÉNDEZ"**.

## Estructura del Proyecto

El sistema está estructurado por niveles y jerarquías de autoridad, conformado por módulos que se interconectan y aportan información aplicable al nivel y jerarquía en la competencia inherente a cada módulo. En tal sentido, esta visión le confiere seguridad, integridad y garantías de que lo que cada responsable manipule no contradice o vulnera la integridad de sus pares, superiores o subordinados en la generalidad del proyecto, salvo que los datos que requieran modificación estén en el ámbito de acción y responsabilidad del funcionario que sea designado para realizar tales acciones, donde el índice general y neurálgico del sistema está sustentado en el documento de identidad de la población que administra: Estudiantes (Cédula Escolar o Cédula Laminada); Personal Directivo, Docente y Administrativo (Cédula Laminada); Inventario u otros elementos que puedan ser administrados por el sistema estará sujeto a elaboración de identificadores únicos para cada grupo.
<br>

[Regresar al Inicio](#índice)

<br>

[![estructura-Sigma.png](https://i.postimg.cc/4NhtfgJ7/estructura-Sigma.png)](https://postimg.cc/qz4gwW64)

<br>

## Nombre de Dominio:
***SIGMA ESCOLAR*** funciona bajo la modalidad de ***Página Web***, por lo que el proyecto debe contar con dos elementos importantes; a saber: 
* **Registro de Dominio Propio:** Para facilitar el acceso al Sistema, se ha determinado el uso de Dominios bajo la extensión **.com.ve** ofrecidos por el Prestador de Servicios  **Conatel**, donde actualmente opera bajo el dominio: ***https://www.cbitzaraza.com.ve***, nombre reservado por el autor del presente proyecto, sin menoscabo de que pueda ser utilizado a futuro otro nombre de Dominio. En este punto es conveniente señalar que, el uso de dominios implica un pago anual en forma de arancel al Estado por el uso de tales nombres de dominio.
* **Alojamiento (Hosting):** La estructura de archivos y la Base de Datos (BBDD) del proyecto deben reposar en un Servicio de Hosting, con la finalidad de enlazar el dominio con estos archivos, lo cual implica en algunos casos pagos por concepto de aumento de procesamiento (CPU), memoria RAM, entre otros elementos que permiten agilizar la velocidad de las operaciones del Sistema, sobretodo en tiempos de alto tráfico como son inscripciones, revisión de expedientes, generación de procedimientos al inicio y/o final del Año Escolar.

<br>

[Regresar al Inicio](#índice)

# Perfiles de Usuario y Acceso a los Datos:
Al ser un proyecto interconectado, es necesario que diferentes tipos de usuario se registren en el sistema, asignándoles roles con el propósito de garantizar acceso a los datos e información inherente a cada rol, sin menoscabo de obtener datos provenientes de otros módulos pero siempre respetando el orden jerárquico y el resguardo de la información, por lo que **todos los perfiles se rigen por la asignación o denegación de los siguientes privilegios:** Lectura (**r**), Escritura (**w**) y Ejecución de archivos o comandos (**x**). En tal sentido, se perfilan los siguientes tipos de usuarios:
* ***Directivo:*** Máximos privilegios, salvo aquellos que vulneren el funcionamiento de otros Módulos.
* ***Subdirectivo:*** Privilegios de lectura, ejecución y escritura inherentes a sus funciones, así como también privilegios especiales sólo si el Directivo lo autoriza desde su Módulo).
* ***Coordinador:*** Privilegios de lectura, escritura y ejecución sólo en su módulo. No tiene acceso a otros módulos, pero otros perfiles de igual rango y nivel, así como también perfiles superiores pueden acceder en modo sólo lectura a su información. El Nivel Directivo tiene privilegios para auditar este Módulo, pero en modo Sólo Lectura.
* ***Control de Estudios:*** Privilegios de lectura, escritura y ejecución sólo en su módulo. Tiene acceso a otros módulos – Coordinaciones -- , pero otros perfiles de menor o igual rango, así como también perfiles superiores pueden acceder en modo sólo lectura a cierta información. El Nivel Directivo tiene privilegios para auditar este Módulo, pero en modo Sólo Lectura.
* ***Inscripciones:*** Privilegios sólo para inscribir estudiantes de Nuevo Ingreso previamente pre-inscritos por el usuario Directivo o su Autorizado, renovar inscripciones de Estudiantes Regulares (Lisos), Estudiantes con Materia Pendiente o Repitientes de conformidad con el Calendario de Inscripciones. Sólo se tiene acceso a este Módulo por direcciones IP Autorizadas por el Directivo, con la finalidad de garantizar transparencia en los procesos de inscripción.
* ***Otros Módulos:*** Se podrán crear otros Módulos, pero siempre respetando la metodología de Nodos, roles y los privilegios (r,w,x) antes mencionados.

<br>

[Regresar al Inicio](#índice)

