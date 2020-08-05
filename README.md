Desarrollo de una aplicación web que permita acceso a una base de datos multidimensional utilizando herramientas de software libre.
# Casos de COVID-19 en España - Grupo 7

El presente proyecto integrador se compone de dos partes. La primera es un sistema donde se aplicará los conocimientos de Sistemas de Información y Gestión de Base de Datos;

mientras que, la segunda parte es la gestión del proyecto, el cual se manejará como si se tratara de un proyecto de Software Libre.

## Comenzando 🚀

Se debe gestionar una base de datos multidimensional, cuya información provenga de diversas fuentes de datos. Para esto se utilizará las herramientas de Pentaho Community Server. La información contenida en la base de datos será presentada utilizando una aplicación web con reportes en PDF y gráficos estadísticos. Todo el desarrollo del proyecto se lo realizará de manera cooperativa entre todos los miembros del grupo. Los avances, el código fuente y toda la información que se genere durante el proyecto se manejará de forma centralizada a través de un repositorio de código fuente en GitHub.

## Construido con 🛠️

Sistemas de Información ---> WildFly 12.0, Eclipse JEE, Planner, Office 365

Software Libre ---> GutHub 

Gestión de base de datods ---> Postgres, Pentaho Report Designer, Pentaho Data Integration, Power Architect

### Módulos 🔧

--Módulo de Seguridad 

Este módulo permite la administración de usuarios (creación de usuarios, cambio de clave, bloqueo de usuarios y consulta de usuarios). Además, en este módulo se guarda el registro de las actividades realizadas en la base de datos mediante auditoría. Existen tres tipos de usuarios: invitado quien no necesita registrarse para acceder a la información pública del portal, administrador quien tiene acceso al módulo de seguridad y usuario registrado que puede visualizar reportes especializados en el módulo de reportes.

--Módulo Reportes 

Este módulo consiste en la creación y publicación de reportes avanzados, cuya fuente de información será la base de datos multidimensional (Almacén de datos), cada uno de los reportes deben ser presentados en una aplicación web, desde la cual el usuario ingresará o seleccionará los criterios de búsqueda para generar el reporte. Los reportes deberán ser para contestar las preguntas que cada grupo tendrá en el archivo de requerimientos del Datawarehouse. Los tipos de reportes que deberán presentar son: 

· Tipo texto  
· Con gráficos de barras 
· Con gráficos tipo pastel 

--Módulo de invitado 

Este módulo se accede sin necesidad de autenticación. Muestra información básica de la aplicación para visitantes. Contiene un resumen de los indicadores que maneja el sistema y gráficas básicas. Los visitantes en esta parte no pueden aplicar filtros ni generar reportes. También debe mostrar información sobre los autores del sistema y los enlaces al repositorio de software.


## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/AlexanderPadilla1/proyecto-git5.wiki.git)


## Autores ✒️
Alexander Padilla, 
Marlon Ruales, 
Jordy Quilachamin, 
Bryan Ocaña, 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

*Un trabajo de investigación es siempre fruto de ideas, proyectos y esfuerzos previos que
corresponden a otras personas. En este caso damos un sincero agradecimiento a la Universidad Politecnica Salesiana y en especial a los ingenierios de la carrera de Ingenieria en Ciencias de la Computacion, ya que por su conocimiento brindado nos ayudara en un futuro a enfrentar la vida profesional sin duda estaremos siempre en
deuda. Gracias a todos por su  su tiempo y sus ideas. 


---

