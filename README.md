# Integrated Model of *Pseudomonas aeruginosa*

This repository provides supplementary material of the manuscript: **Integration of transcriptomic data and metabolic network of *Pseudomonas aeruginosa*** 
##### Authos: Medeiros Filho1†\*, Nascimento1†, Merigueti1, Costa3, Menezes4, Nicolás3, Santos3, Carvalho-Assef2, Silva1\*

######  1 Fundação Oswaldo Cruz, Programa de Computação Científica, Rio de Janeiro, RJ, Brazil; 2 Fundação Oswaldo Cruz, Instituto Oswaldo Cruz, Laboratório de Pesquisa em Infecção Hospitalar, Rio de Janeiro, RJ, Brasil; 3 Laboratório Nacional de Computação Científica, Petrópolis, RJ, Brazil; 4 Instituto de Física, Universidade Federal Fluminense, Niterói, RJ, Brazil; † These authors have contributed equally to this work and share first authorship; \* Correspondence authors



## Abstract 


*Pseudomonas aeruginosa* is an opportunistic human pathogen known to cause nosocomial infections in immunocompromised patients. A useful approach to assess this bacterium's complex behavior is to create a computational model integrating transcriptomic data into genome-scale metabolic networks. In this paper, we use an integrated model to dynamically simulate the growth of *Pseudomonas aeruginosa* in a minimal medium with glycerol or acetate as carbon source. Our simulation results show a quantitative correspondence to the available experimental data. One can expect the analysis of an integrated model can identify potential bacteriostatic targets more accurately than it is possible with a metabolic model which does not take into account data from other cellular processes. This paper investigates this assumption. In this manuscript, we use the integrated model of P. aeruginosa to list potential therapeutics targets using an automated method. We then compare these targets with the ones identified from the non-integrated model and discuss the accuracy of the potential targets found in both sets of models.

Keywords: *Pseudomonas aeruginosa*, Metabolic  Networks, Transcriptional  Data, Dynamic Integrated Model.

Correspondence: fernando.filho@ioc.fiocruz.br, fabricio.silva@fiocruz.br 

# Description of supplementary material

[Models](https://github.com/medeirosfilho1/Integration-paeruginosa/models): Here you can find the models used in the simulations performed in this manuscript. They are divided into files with matlab and sbml extensions. The .mat files were used in the session Integration of metabolic network and transcriptome data of the methods. The .sbml files were exported from matlab in order to simulate them in FindTargetsWeb and FBA and FVA analysis.

