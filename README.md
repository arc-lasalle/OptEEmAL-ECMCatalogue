# ECM Catalogue / InstanceCreator

The ECM Catalog and the Instance Creator form a system that enable that takes advantage of the capabilities of Semantic Web technologies to integrate ECM data into Building Energy Performance (BEP) simulation models in an automated way. BEP simulation models are described in the [SimModel specification](https://escholarship.org/content/qt70c7j74t/qt70c7j74t.pdf "SimModel specification")
The system has been developed in the context of [OptEEmAL](https://www.opteemal-project.eu/ "OptEEmAL"), a research project aimed at creating a web platform to facilitate building simulations at district scale. The applicability of the system is demonstrated in a case study of a district-scale project.

## InsCreatorLite Usage

The [Instance Creator Lite](https://github.com/arc-lasalle/OptEEmAL-ECMCatalogue/tree/master/src/main/bin/InsCreatorLite.jar "Instance Creator Lite") can be run using the following command-line arguments:

Usage:

`java -jar InsCreatorLite.jar [-hret] <scenario_vector.json> [-b <baseline_model.ttl>]`  
  
`optional arguments:`  
` -h: help.`  
` -r: generate a report file.`  
` -e: show extra info.`  
` -t: shows execution times.`  
` -b: specifies a specific baseline file (if not, check the nomenclature below).`   
 
Example:

`java -jar InsCreatorLite.jar -e -t scenario_vector_test.json -b simmodel_baseline_test.ttl`

## Authors

See the list of partners [collaborators](https://www.opteemal-project.eu/about-opteemal/partners.html) who participated in this project.

## Acknowledgments

Most of the work presented in this article is included in the research carried out within the project “Optimised Energy Efficient Design Platform for Refurbishment at District Level” (OptEEmAL), which has received funding from the European Union Horizon 2020 Framework Programme (H2020/2014-2020) under grant agreement n° 680676.

## Issues - contact

You can report any errors that you found to the authors: 

ECM Catalogue:
Xabat Oregi (Tecnalia) - xabat.oregi@tecnalia.com | xabat.oregi@ehu.eus
Lara Mabe (Tecnalia) - lara.mabe@tecnalia.com
Juan Pedrero (Tecnalia) - juan.pedrero@tecnalia.com

InstanceCreator:
Gonçal Costa (LaSalle BCN) - goncal.costa@salle.url.edu
Alvaro Sicilia (LaSalle BCN) - alvaro.sicilia@salle.url.edu
