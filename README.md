# Tiempos Sustentables — Open Data

Repositorio público de datos estructurados sobre publicaciones, recursos y autoría de Tiempos Sustentables.

**Versión:** v1.1.0  
**Actualización:** 15 de noviembre de 2026  
**Página oficial:** https://tiempossustentables.cl/centro-de-recursos/tiempos-sustentables-open-data/

## Objetivo

Facilitar el descubrimiento, la verificación y la cita de las publicaciones de Jesús Patricio Blasco Valencia y Tiempos Sustentables.

## Fuentes canónicas

- Sitio oficial: https://tiempossustentables.cl/
- Perfil de autor: https://tiempossustentables.cl/jesus-blasco/
- ORCID: https://orcid.org/0009-0002-4839-104X
- Centro de Recursos: https://tiempossustentables.cl/centro-de-recursos/
- Open Data: https://tiempossustentables.cl/centro-de-recursos/tiempos-sustentables-open-data/

## Contenido

### Conjunto base

- `data/author.json`: identidad, afiliación y perfiles verificables.
- `data/publications.json`: catálogo de publicaciones, DOI y repositorios.
- `data/publications.csv`: versión tabular del catálogo.
- `data/resource-center.json`: recursos, datasets y herramientas.
- `data/resource-center.csv`: versión tabular de los recursos.

### Arquitectura de datos estructurados

- `TS_Schema_completo.jsonld`: grafo central JSON-LD de referencia, con identidades, páginas, obras, recursos, autoría y relaciones.
- `TS_Schema_completo_vista.html`: visor local del grafo con búsqueda por entidad.
- `distribucion_entidades.csv`: inventario de entidades y alcance previsto por URL.
- `metadatos_academicos.json`: metadatos `citation_*`, Dublin Core y PRISM separados del JSON-LD.
- `reglas_contenido_dinamico.json`: especificación para categorías, entradas, firmas invitadas, paginación y contenidos condicionales.
- `Datos_condicionales.json`: pendientes de verificación, datos condicionales y fuente de FAQ en cuarentena.
- `LEEME.txt`: guía de alcance, criterios de conservación, datos incompletos y validación del paquete.

## Reglas de uso

- La fuente canónica de cada publicación es su página oficial y su DOI.
- Este repositorio no reemplaza los registros de ORCID, Zenodo, OSF, ResearchGate ni Google Scholar.
- Los datos estructurados se publican bajo CC BY 4.0, salvo indicación distinta en cada recurso.
- No se incluyen artículos completos ni archivos PDF con derechos restringidos.
- El grafo JSON-LD es una referencia de arquitectura; Google recibe el marcado distribuido por URLs, no este archivo maestro.
- Los datos condicionales, FAQ, imágenes, fechas dinámicas y contenidos no inventariados requieren verificación en WordPress antes de su despliegue.

## Versiones

- `v1.1.0` — Incorpora la arquitectura completa de datos estructurados, visor HTML, metadatos académicos, reglas de contenido dinámico, inventario de entidades, datos condicionales y guía técnica.
- `v1.0.0` — Versión inicial del repositorio Open Data.