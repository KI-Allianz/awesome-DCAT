# Awesome DCAT & DCAT‑AP

> A curated list of tools, profiles, validators and editors around DCAT, DCAT‑AP and related application profiles.
>
> Please create pull requests to add items


## Contents

- [Catalog platforms & stacks](#catalog-platforms--stacks)  
- [CKAN extensions & integrations](#ckan-extensions--integrations)  
- [DCAT‑AP profiles & specs](#dcat-ap-profiles--specs)  
- [Editors, portals & UIs](#editors-portals--uis)  
- [Conversion, harvesting & pipelines](#conversion-harvesting--pipelines)  
- [Validation & quality](#validation--quality)  
- [Meta resources & awesome lists](#meta-resources--awesome-lists)



## Catalog platforms & stacks

- **[piveau](https://gitlab.com/piveau)** – DCAT/DCAT‑AP‑based data management platform for public‑sector open data. 
    - **[piveau‑hub](https://gitlab.com/piveau/hub)** – Open Data hub service for the piveau stack (registry, search, APIs).
    - **[piveau‑consus](https://gitlab.com/piveau/consus)** – Open Data meta-data harvesting service for the piveau stack.
    - **[piveau‑ui](https://gitlab.com/piveau/ui)** – Vue based Web-UI for piveau.
- **[open.bydata competence center / portal](https://gitlab.opencode.de/byte-bayerische-agentur-f-r-digitales-gmbh/open-bydata-competence-center/open.bydata)** – Bavaria’s open data portal and competence‑centre implementation based on piveau. 
- **[GovDataPortal](https://github.com/GovDataOfficial/GovDataPortal)** – Source of the German national open data portal using DCAT‑AP.de and CKAN. 
- **[Piveau NextJS](https://github.com/KI-Allianz/piveau.nextjs)** – Next JS Frontend for Piveau developed for the KI-Allianz BW
- **[Daanse Dashboard](https://github.com/eclipse-daanse/org.eclipse.daanse.board.app)** - Smart City Dashboard that displays DCAT-AP via SPARQL endpoint
- **[Fair Data Point](https://github.com/FAIRDataTeam/FAIRDataPoint/)** - Data Catalog Reference Implementation with DCAT API and Web Client

## Proof of Concepts/Pilots
- **[EOSC MLDCAT Pilot](https://github.com/SEMICeu/EOSC-MLDCAT-AP-Pilot/)** - MLDCAT Pilot for EOSC
  

## DCAT extensions & integrations into other Data Catalog Platforms
### CKAN

- **[ckanext-dcat](https://github.com/ckan/ckanext-dcat)** – Core CKAN extension for DCAT/DCAT‑AP RDF exposure, harvesting and schemas. 
- **[ckanext-dcatde](https://github.com/GovDataOfficial/ckanext-dcatde)** – CKAN plugin implementing the German DCAT‑AP.de profile.
- **[ckanext-dcatde (FITKO GitLab mirror)](https://gitlab.opencode.de/OC000008353898/ckanext-dcatde)** – GitLab mirror of the DCAT‑AP.de CKAN extension. 
- **[ckanext-dcatde_berlin](https://github.com/berlinonline/ckanext-dcatde_berlin)** – DCAT‑AP.de profile implementation for Berlin’s Datenregister. 
- **[ckanext-healthdcat](https://github.com/Health-RI/ckanext-healthdcat)** – CKAN extension fork to support HealthDCAT‑AP via ckanext‑dcat. 
- **[ckanext-schemingdcat](https://github.com/BNELab/ckanext-schemingdcat)** – Improved CKAN scheming plugin with DCAT, DCAT‑AP and GeoDCAT‑AP schemas.




## DCAT‑AP profiles & specs

- **[DCAT‑AP (core spec)](https://github.com/SEMICeu/DCAT-AP)** – Official DCAT‑AP specification and artefacts.
- **[DCAT‑AP.de](https://github.com/GovDataOfficial/DCAT-AP.de)** – German adaptation of DCAT‑AP for data portals in Europe.
- **[DCAT‑AP-ES](https://github.com/datosgobes/DCAT-AP-ES)** – Spanish DCAT‑AP profile with docs and examples. 
- **[GeoDCAT‑AP](https://github.com/SEMICeu/GeoDCAT-AP)** – Geospatial extension of DCAT‑AP with mappings and RDF bindings. 
- **[iso-19139-to-dcat-ap](https://github.com/SEMICeu/iso-19139-to-dcat-ap)** – XSLT‑based reference implementation for GeoDCAT‑AP / DCAT‑AP transformations. 
- **[DCAT‑AP.de implementations list](https://github.com/GovDataOfficial/DCAT-AP.de/blob/master/implementations.md)** – Catalog of DCAT/DCAT‑AP/DCAT‑AP.de usages and specializations. 
- **[HealthDCAT‑AP.de](https://github.com/HealthDCAT-AP-de/healthdcat-ap.de)** – HealthDCAT‑AP.de application profile for German health data catalogs. 
- **[healthDCAT-AP controlled vocabularies](https://github.com/healthDCAT-AP/Controlled-vocabularies)** – Controlled vocabularies for HealthDCAT‑AP metadata. 



## Editors, portals & UIs

- **[GeoNetwork DCAT‑AP plugin](https://github.com/metadata101/dcat-ap)** – DCAT‑AP schema plugin for GeoNetwork catalog UI and APIs.
- **[GeoDCAT OGC API Records tooling](https://github.com/ogcincubator/geodcat-ogcapi-records)** – GeoDCAT/DCAT‑AP validation and OGC API Records bindings. 
- **[GovDataPortal (frontend & backend)](https://github.com/GovDataOfficial/GovDataPortal)** – DCAT‑AP.de‑based national portal UI and services. 
- **[piveau‑hub UI and services](https://github.com/piveau-data/piveau-hub)** – REST APIs and UI for DCAT‑based catalogs. 
- **[open.bydata portal app](https://gitlab.opencode.de/byte-bayerische-agentur-f-r-digitales-gmbh/open-bydata-competence-center/open.bydata)** – Vue/Node app powering Bavaria’s DCAT‑style open data portal. 

***

## Conversion, harvesting & pipelines

- **[dcattools](https://github.com/Fedict/dcattools)** – Harvesters and converters producing DCAT‑AP for data.gov.be and data.europa.eu. 
- **[dcat (data.gov.be export)](https://github.com/Fedict/dcat)** – DCAT‑AP export of the Belgian open data portal. 
- **[dcat-ap-pipeline](https://github.com/tenforce/dcat-ap-pipeline)** – Pipeline to generate DCAT‑AP records from Excel templates. 
- **[inspire-dcat-de-bridge](https://github.com/GovDataOfficial/inspire-dcat-de-bridge)** – Bridge between CKAN and German geospatial catalog services via DCAT‑AP.de. 
- **[CSW2DCAT](https://github.com/GovDataOfficial/CSW2DCAT)** – Tool converting CSW catalogs to DCAT‑AP.de RDF.

***

## Validation & quality

- **[validator-resources-dcat-ap](https://github.com/ISAITB/validator-resources-dcat-ap)** – Resource set (rules, vocabularies) for the DCAT‑AP RDF validator. 
- **[DCAT-AP.de SHACL Validation](https://github.com/GovDataOfficial/DCAT-AP.de-SHACL-Validation)** – SHACL shapes for validating DCAT‑AP.de metadata. 
- **[DCAT Catalog Check](https://gitlab.opencode.de/ZIT-SH/DCAT-Catalog-Check)** – Schleswig‑Holstein DCAT catalog monitor / validator. 
- **[GeoDCAT OGC API validation tooling](https://github.com/ogcincubator/geodcat-ogcapi-records)** – GeoDCAT/DCAT‑AP conformance tests and validation examples.

***

## Meta resources & awesome lists

- **[awesome-dcat-ap](https://github.com/GKStGovData/awesome-dcat-ap)** – Curated list of DCAT‑AP profiles, converters, bridges and validators. 
- **[GitHub topic: dcat-ap](https://github.com/topics/dcat-ap)** – Topic listing many DCAT‑AP‑related repos (profiles, tools, portals). 
- **[GitLab topic: dcat-ap](https://gitlab.opencode.de/explore/projects/topics/dcat-ap)** – GitLab projects tagged with DCAT‑AP/related tooling. 

## DCAT-compatible data catalogs with APIs

- **[data.europa.eu](https://dataeuropa.gitlab.io/data-provider-manual/api-documentation/)** - Pan-European open data portal exposing a Registry API with direct RDF/DCAT-AP metadata access, plus search and SPARQL interfaces. [dataeuropa.gitlab](https://dataeuropa.gitlab.io/data-provider-manual/api-documentation/)
- **[Eurostat Catalogue API](https://ec.europa.eu/eurostat/de/web/user-guides/data-browser/api-data-access/api-detailed-guidelines/catalogue-api/dcat)** - Statistical data catalog published as DCAT-AP RDF, including full and update catalog feeds. [ec.europa](https://ec.europa.eu/eurostat/de/web/user-guides/data-browser/api-data-access/api-detailed-guidelines/catalogue-api/dcat)
- **[GovData](https://www.govdata.de/suche/daten/govdata-metadatenkatalog)** - Germany’s national open data portal using DCAT-AP.de and exposing catalog metadata via RDF, Turtle, and JSON-LD through CKAN DCAT search endpoints. [govdata](https://www.govdata.de/suche/daten/govdata-metadatenkatalog)
- **[DCAT-AP.de specification and vocabularies](https://www.dcat-ap.de/def/dcatde/3.0/spec/)** - German national DCAT-AP profile used by GovData and related German portals for interoperable catalog metadata exchange. [dcat-ap](https://www.dcat-ap.de/def/dcatde/3.0/spec/)
- **[Data.gov / Project Open Data](https://resources.data.gov/resources/dcat-us3/)** - U.S. federal catalog ecosystem based on DCAT-US v3.0, with agency `data.json` catalogs harvested into Data.gov. [resources.data](https://resources.data.gov/resources/dcat-us3/)
- **[Data.gov catalog APIs](https://data.gov/developers/apis/)** - Developer entry point for the U.S. federal data catalog, backed by CKAN and the federal DCAT-US metadata standard. [data](https://data.gov/developers/apis/)
- **[data.gov.uk DCAT guidance](https://guidance.data.gov.uk/publish_and_manage_data/harvest_or_add_data/harvest_data/dcat/)** - UK government open data guidance documenting accepted DCAT and data.json fields for harvested catalog metadata. [guidance.data.gov](https://guidance.data.gov.uk/publish_and_manage_data/harvest_or_add_data/harvest_data/dcat/)
- **[data.gov.uk API](https://www.data.gov.uk/api/3/action/)** - UK national open data CKAN Action API for dataset and catalog metadata retrieval, aligned with DCAT-oriented publication guidance. [apis](https://apis.io/providers/data-gov-uk/)
- **[data.gouv.fr DCAT harvesting](https://doc.data.gouv.fr/moissonnage/dcat/)** - French national open data portal documentation for DCAT-based harvesting and interoperable catalog exchange. [doc.data.gouv](https://doc.data.gouv.fr/moissonnage/dcat/)
- **[CKAN RDF DCAT endpoints](https://docs.ckan.org/projects/ckanext-dcat/en/latest/endpoints/)** - Documentation for CKAN’s DCAT extension, used by many public data portals to expose full catalogs and datasets as DCAT RDF serializations. [docs.ckan](https://docs.ckan.org/projects/ckanext-dcat/en/latest/endpoints/)
- **[CKAN linked data and RDF](https://docs.ckan.org/en/ckan-2.3.5/maintaining/linked-data-and-rdf.html)** - Core CKAN documentation showing RDF/DCAT dataset and catalog exposure through linked-data endpoints. [docs.ckan](https://docs.ckan.org/en/ckan-2.3.5/maintaining/linked-data-and-rdf.html)
- **[DCAT-AP-CH](https://www.dcat-ap.ch/releases/3.0_workingdraft/dcat-ap-ch_3.0_workingdraft.html)** - Swiss DCAT application profile for interoperable publication of public data catalogs in RDF-based formats. [dcat-ap](https://www.dcat-ap.ch/releases/3.0_workingdraft/dcat-ap-ch_3.0_workingdraft.html)
- **[BRegDCAT-AP RDF distribution](https://interoperable-europe.ec.europa.eu/sites/default/files/distribution/access_url/2020-07/270508e5-f818-49e6-b327-8c84ba1175b0/BRegDCAT-AP_2.00.rdf)** - RDF catalog profile for interoperable business register data portals in Europe.teroperable-europe.ec.europa.eu/sites/default/files/distribution/access_url/2020-07/270508e5-f818-49e6-b327-8c84ba1175b0/BRegDCAT-AP_2.00.rdf)** - RDF catalog profile for interoperable business register data portals in Europe. [interoperable-europe.ec.europa](https://interoperable-europe.ec.europa.eu/sites/default/files/distribution/access_url/2020-07/270508e5-f818-49e6-b327-8c84ba11751e/BRegDCAT-AP_2.00.rdf)
- 
