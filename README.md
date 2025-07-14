
             
             TP-3 "Productora Musical"

             
Este proyecto consiste en el desarrollo de una aplicacion para gestion Musical llamada "Productora Musical" donde tiene 
una base de datos SQL que gestiona la información de una productora musical.
La app esta desarrollado en en Java con Spring Boot, utilizando Maven como gestor de dependencias 
(Spring Boot DevTools, Lombok, Spring Web, JDBC API, MySQL Driver, HikariCP)

Esta aplicación simula el funcionamiento interno de una **productora musical** que organiza recitales, 
shows en vivo y otros eventos culturales en la Ciudad de Buenos Aires.

¿Qué permite hacer esta aplicación?

- Registrar y administrar **bandas musicales**, con datos como género, integrantes y contacto.
- Registrar Lugares donde se pueden hacer shows, como bares, teatros o centros culturales.
- Programar Eventos, asociando una banda y un lugar con una fecha específica.
- Registrar Necesidades técnica (sonido, luces, escenario) para cada evento.
- Consultar Bandas por género musical o cantidad de músicos.


El proyecto cuenta con:

Paquete entities:
Banda - Evento - Necesidad - Lugar - BandaEvento

Paquete Enums:
Genero - Tipo_Lugar

Paquete Repositories:
En este paquete se encuentran las interfaces de cada clase que luego se implementaran en sus respectivos repositorios
BandaRepository implementa I_BandaRepository
EventoRepository implementa I_EventoRepository
LugarRepository implementa I_LugarRepository
NecesidadRepository implementa I_NecesidadRepository
BandaEventoRepository implementa I_BandaEventoRepository

Paquete tests:
Incluye una clase testConection.java para verificar la conexion a la base de datos 
funcione correctamente 
Incluye una clase TestRepositories.java que contiene pruebas para cada repositorio.

Paquete resources:
Contiene la carpeta "DOCS" el cual contiene el DER (Diagrama de Entidad de Relación).
Contiene la carpeta "sql" el cual contiene los archivos schema_DDL, Data_DML y queries.

Autor
Joaquín Flores
Proyecto académico TP3 de Programación Orientada a Objetos
Centro 8 SMATA – Curso de Java



 

