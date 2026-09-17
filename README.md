# Base de Datos: Ocupación de la Vía Pública de Málaga

Práctica de la asignatura **Análisis y Diseño de Bases de Datos (ADBD)**, curso 2024-2025.

## Descripción

El objetivo es diseñar e implementar una base de datos que simule el sistema de gestión municipal del Ayuntamiento de Málaga para la ocupación de la vía pública (terrazas, toldos, instalaciones y aprovechamientos especiales en festividades), a partir de la [Ordenanza Reguladora de la Ocupación de la Vía Pública](comercio%20via%20publica%20malaga-9.pdf) del propio Ayuntamiento.

A partir de ese documento se identificaron las entidades, atributos y relaciones necesarios para modelar:

- **Titulares** de establecimientos (personas físicas o jurídicas).
- **Establecimientos** y su historial de titularidad.
- **Autorizaciones** de los cuatro títulos de la ordenanza (mesas y sillas, toldos, instalaciones, aprovechamientos especiales).
- **Elementos** de mobiliario urbano solicitados en cada autorización.
- **Infracciones** asociadas a las autorizaciones.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| [`PlanteamientoMalaga.txt`](PlanteamientoMalaga.txt) | Análisis inicial de requisitos: clases principales, atributos y relaciones extraídas de la ordenanza. |
| [`ModeloMalaga.jpeg`](ModeloMalaga.jpeg) | Diagrama del modelo Entidad-Relación. |
| [`UML/`](UML) | Proyectos de Visual Paradigm con los diagramas UML. |
| [`G25/G25/Memoria.pdf`](G25/G25/Memoria.pdf) | Memoria del grupo G25: diseño conceptual, diseño lógico y consultas implementadas. |
| [`G25/G25/script.sql`](G25/G25/script.sql) | Script SQL (PostgreSQL) con la creación de tablas, tipos, datos de prueba y consultas. |
| [`comercio via publica malaga-9.pdf`](comercio%20via%20publica%20malaga-9.pdf) | Ordenanza pública del Ayuntamiento de Málaga en la que se basa el modelo. |

## Tecnología

Base de datos implementada en **PostgreSQL**.

## Autoría

Grupo G25: Almaraz Arranz, Marcos · Carbajo Orgaz, Ainhoa · De Diego Martín, Marcos · Peña Marqués, Rodrigo

> Nota: los datos de ejemplo del script SQL (nombres, DNIs, direcciones) son ficticios y se usan únicamente con fines de prueba.
