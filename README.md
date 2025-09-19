# MFAE-ontology-performing-arts-v1
This repository presents the first version of an ontology for the performing arts, based on a sample from Mercat de les Flors (Àngels Margarit/Cia. Mudances). Grounded in CIDOC CRM and LRMoo, it aims to provide a solid logical basis for future development.

La ontología ha sido confeccionada a partir del método R2LD, utilizando los modelos conceptuales CIDOC CRM y LRMoo, además de vocabularios auxiliares como schema.org y Wikidata. También se han creado especificaciones propias bajo el prefijo oficial del proyecto MFAE, resultando en subpropiedades siempre conectadas con superpropiedades, lo que evita silos y fomenta la interoperabilidad.

Se ha generado una propuesta ontológica original, flexible y coherente desde el punto de vista lógico, que servirá como punto de partida para futuras investigaciones y desarrollos. Esta ontología está compuesta por 21 clases y 41 propiedades capaces de describir los principios básicos de cualquier evento de danza, desde la idea de obra hasta los roles de cada persona involucrada en el desarrollo artístico, con datos extraídos del archivo del Mercat de les Flors.

El diseño se ha realizado buscando la máxima reutilización de vocabularios preexistentes para promover la interoperabilidad y evitar la proliferación de nuevas ontologías innecesarias. En total se han reutilizado seis vocabularios vinculados al patrimonio cultural, siempre respetando sus definiciones originales, conforme a las buenas prácticas de la Web Semántica.

Los IRIs reutilizados en esta versión beta son:

@prefix gn: <https://www.geonames.org/ontology#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix xml: <http://www.w3.org/XML/1998/namespace> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix lrmoo: <http://iflastandards.info/ns/lrm/lrmoo/> .
@prefix schema: <https://schema.org/> .
@prefix wikidata: <https://www.wikidata.org/wiki/> .
@prefix cidoc-crm: <http://www.cidoc-crm.org/cidoc-crm/> .
@prefix MFAE: <https://purl.archive.org/domain/mfae> .
