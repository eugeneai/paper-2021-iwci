Integration of Geological Data as a Knowledge Graph

E.A.Cherkashin
V.M.Matrosov Institute for System Dynamics and Control Theory, Siberian branch of Russian Academy of sciences, Irkutsk

<!-- # Introduction -->

Geological data are accumulated, analyzed and converted into cartographic works (usually, maps), generalizing current data. The maps are the main result of geologists' scientific research, but they cannot account the current state of the geological process.  Understanding this issue, researchers created dynamic GIS based interactive resources accounting seismic and volcanic events, allowing one to query the databases for the phenomena, constructing a cartographic work on request with the filtered data. However, the similar phenomena can be observed at different locations, as well as various conclusion can be drawn from the whole body of the analyzed observation.

The knowledge revealing natural laws of good quality are obtained on the base of mathematical models application to the known geological data. Nowadays, technologies implementing computer simulation services are implemented as web processing services (WPS). To support research activity, data integration between databases, cartographic services and should be implemented.

Since 2001, Semantic Web (SW) data publishing techniques are developing in the direction of information systems integration within internet and local area network. The technologies  integrate the systems, which design and implementation principles are varying drastically. The data to be published and acquired are accompanied by their metadata, allowing to develop of correct interpretation within the integration. A number of data format, processing procedures and interfaces have been developed, namely, Resource Description Framework (RDF), Knowledge Graphs (KG), and SPARQL. The flexibility of tools allows one to implement integration on various levels: databases, federated queries and document data.

The aim of the research is to raise the level of integration of geodata by introduction of the Linked Open Data (LOD) SW technologies into existing services of geological data publishing. This will allow developing flexible systems of knowledge acquisition and representation as subgraphs of a global geological graph of knowledge, as well as propose generic interactive publishing tools in the field of geological science.





requirements of the software (integrating LOD and  GIS)

1. Web technologies. (Resulting in usage of leaflet-like software, i.e. web-GIS)
2. Service-oriented to lower coupling and higher integration within a module.
3. Integration should allow (weak) coupling with sematic data servers.
4.



# Related works

In [iwaniak] a comprehensive review of projects is presented, notifying that there are too few number of projects integrating GIS and LOD data. Authors present an approach utilizing a desktop GIS to manage LOD datasets. The research is oriented on processing imported LOD data by the desktop GIS. Practical problems were solved, e.g., asserting new spacial relations between objects figured out by GIS modules. In later work [iwaniak2] of the authors' collective the spatial relations are accounted by means special SPARQL UPDATE queries and WFS, a subsystem driven by experts is used to fix answers to user questions as RDF triples. The techniques of LOD data enrichment were refined to build new prototype recommender system, a subontology was developed to denote relationships between spacial objects and their LOD data in municipal economy domain. In [abid] a problem of publishing DBPedia objects referenced by spacial coordinates is considered. The publishing is carried out with three stages: mapping the coordinate to an object (a city) by Google Maps API v3; construct a SPARQL query finding celebrities, who born in the city; show the list of the results as HTML table with LOD references.

LinkedGeoData [lgd]

Ontologies WGS84 Basic Geo and GeoSPARQL allow one to interpret the spacial attributes for LOD objects [].

In conclusion, we note that the above mentioned projects deal with DBPedia and alike resources related to OpenstreetMap topological basis.

# Discussion

Spacial data inference within domain SPARQUL queries (are there any inference in SPARQL).



# References

1. Geospatial Semantic Web Community Group. https://www.w3.org/community/geosemweb/wiki/Main_Page .
2. (iwaniak) Adam Iwaniak*, Iwona Kaczmarek, Marek Strzelecki, Jaromar Lukowicz, and Piotr Jankowski. Enriching and improving the quality of linked data with GIS. Open Geosci. 2016; 8:323–336.  DOI:10.1515/geo-2016-0020
4. (iwaniak2) Adam Iwaniak 1,2 , Marta Leszczuk 1,2, *, Marek Strzelecki 1,2 , Francis Harvey 3 and Iwona Kaczmarek. A Novel Approach for Publishing Linked Open Geodata from National Registries with the Use of Semantically Annotated Context Dependent Web Pages. International Journal of
Geo-Information. 2017, 6, 252; doi:10.3390/ijgi6080252
3. (abid) Tarek Abid, Hafed Zarzour. Integrating Linked Open Data in Geographical Information System.
5. (paramonov) Paramonov V., Fedorov R., Ruzhnikov G., Shumilov A. (2013) Web-Based Analytical Information System for Spatial Data Processing. In: Skersys T., Butleris R., Butkiene R. (eds) Information and Software Technologies. ICIST 2013. Communications in Computer and Information Science, vol 403. Springer, Berlin, Heidelberg. https://doi.org/10.1007/978-3-642-41947-8_9
3. (bakg, Book about knowledge graphs)
55. Гладков Антон Андреевич, Лунина Оксана Викторовна. "Разработка интерактивной информационной системы для построения моделей композитных сейсмогенных источников юга Восточной Сибири" Вестник Иркутского государственного технического университета, no. 9 (92), 2014, pp. 17-24.
8.
TY  - JOUR
A2  - Liu, HuaPing
AU  - Zhu, Yueqin
AU  - Zhou, Wenwen
AU  - Xu, Yang
AU  - Liu, Ji
AU  - Tan, Yongjie
PY  - 2017
DA  - 2017/02/16
TI  - Intelligent Learning for Knowledge Graph towards Geological Data
SP  - 5072427
VL  - 2017
AB  - Knowledge graph (KG) as a popular semantic network has been widely used. It provides an effective way to describe semantic entities and their relationships by extending ontology in the entity level. This article focuses on the application of KG in the traditional geological field and proposes a novel method to construct KG. On the basis of natural language processing (NLP) and data mining (DM) algorithms, we analyze those key technologies for designing a KG towards geological data, including geological knowledge extraction and semantic association. Through this typical geological ontology extracting on a large number of geological documents and open linked data, the semantic interconnection is achieved, KG framework for geological data is designed, application system of KG towards geological data is constructed, and dynamic updating of the geological information is completed accordingly. Specifically, unsupervised intelligent learning method using linked open data is incorporated into the geological document preprocessing, which generates a geological domain vocabulary ultimately. Furthermore, some application cases in the KG system are provided to show the effectiveness and efficiency of our proposed intelligent learning approach for KG.
SN  - 1058-9244
UR  - https://doi.org/10.1155/2017/5072427
DO  - 10.1155/2017/5072427
JF  - Scientific Programming
PB  - Hindawi
KW  -
ER  -


Projects
32. (lgd) Stadler, C.; Lehmann, J.; Höffner, K.; Auer, S. LinkedGeoData: A core for a Web of spatial open data. Semant. Web 2012, 3, 333–354.
33. GeoKnow: Leveraging Geospatial Data in the Web of Data
44. Databases of active and seismogenic faults in the world  http://diss.rm.ingv.it/diss/index.php/help/57%E2%80%90databases%E2%80%90of%E2%80%90active%E2%80%90and%E2%80%90seismogenic%E2%80%90faults%E2%80%90in%E2%80%90the%E2%80%90world
55.   http://activetectonics.ru/

GeoSPARQL—A Geographic Query Language for RDF Data. Available online: http://schemas.opengis.net/geosparql/1.0/geosparql_vocab_all.rdf (accessed on 23.02.2021).

Basic Geo (WGS84 lat/long) Vocabulary: W3C Semantic Web Interest Group. Available online: https://www.w3.org/2003/01/geo/ (accessed on 23.02.2021).

<!-- Reference of registration
https://conf.isem.irk.ru/event/9/registrations/9/?token=8ee3fc28-f9a4-4f15-bcf4-45b1f5d65cac
-->
