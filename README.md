# MFAE-ontology-performing-arts-v1
This repository presents the first version of an ontology for the performing arts, based on a sample from Mercat de les Flors (Àngels Margarit/Cia. Mudances). Grounded in CIDOC CRM and LRMoo, it aims to provide a solid logical basis for future development.

The ontology has been developed using the R2LD method, based on the conceptual models CIDOC CRM and LRMoo, as well as auxiliary vocabularies such as schema.org and Wikidata. Project-specific specifications have also been created under the official MFAE prefix, resulting in subproperties always connected to superproperties, thus avoiding silos and fostering interoperability.

This work presents an original, flexible, and logically coherent ontological proposal, intended as a starting point for future research and developments. The ontology consists of 21 classes and 41 properties capable of describing the fundamental aspects of any dance event, from the idea of a work to the roles of each person involved in the artistic process, using data from the Mercat de les Flors archive.

The design focuses on maximizing the reuse of pre-existing vocabularies in order to promote interoperability and prevent the proliferation of unnecessary new ontologies. In total, six vocabularies related to cultural heritage have been reused, always respecting their original definitions, in line with best practices in the Semantic Web.

The IRIs reused in this beta version are:

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
