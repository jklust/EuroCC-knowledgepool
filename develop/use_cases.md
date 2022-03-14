# Use Cases

This page contains a list of research projects that have successfully used HPC resources to showcase the possibilities HPC enables researchers.
<!--- 
AU: 4
KU: 2
CBS: 2
SDU: 2
ITU: 0
RUC: 0
AAU: 0
-->


## The Danish Blood Donor Study (DBDS) genomic cohort.
<!---### Affiliations: KU, AU, CBS, AUH, KUH, OUH, RUH -->

The DBDS genomic cohort is a comprehensive catalog for large-scale genetic analyses concerning numerous environmental and lifestyle factors affecting donors' health. The study includes data from more than 100.000 donors. It has assessed quality measures such as kinship, ethnicity, and minor allele frequency. The study makes continuous assessments of the donors, resulting in large amounts of data collected and processed using HPC. The use of HPC allows for simultaneously testing multiple hypotheses and dynamical scaling.

[Hansen, T. F. et al. "DBDS Genomic Cohort, a prospective and comprehensive resource for integrative and temporal analysis of genetic, environmental and lifestyle factors affecting health of blood donors" (2019), BMJ Open.](http://dx.doi.org/10.1136/bmjopen-2018-028401)


## HPC in the field: research and recording of prehistoric rock art using 3D image-based modelling
<!---### Affiliation: Aarhus University-->
<!---### Researcher: [James Dodd, Aarhus University](https://pure.au.dk/portal/da/persons/james-andrew-dodd(121a5d0d-e7dd-4c02-8783-39772e78a7a0).html)
### Publication: -->
<!---### [Dodd, J. "The application of high performance computing  in rock art documentation and research" (2018), Adoranten 92-104.](https://www.proquest.com/openview/56203dd4a1c068cf159b323e703c84f1/1?pq-origsite=gscholar&cbl=2032487)-->

This project investigated the mapping between prehistoric rock art images and their meaning. Due to the inherently three-dimensional nature of rock art, the required image processing can require a lot of computing power. By outsourcing the image processing to an HPC facility, the researchers could obtain results while in the field without the need to carry extra computing equipment to the site and make decisions based on the processed data. In this way, HPC enables greater flexibility during fieldwork by reducing the barrier of image processing time without the need for extra equipment on site.

[Dodd, J. "The application of high performance computing  in rock art documentation and research" (2018), Adoranten 92-104.](https://www.proquest.com/openview/56203dd4a1c068cf159b323e703c84f1/1?pq-origsite=gscholar&cbl=2032487)


## Exploring past economies with HPC-enabled agent-based modelling
<!---### Affiliation: Aarhus University-->
<!---### Researcher: [Izabela Romanowska, Aarhus University](https://pure.au.dk/portal/da/persons/izabela-anna-romanowska(de64c8e8-dfc4-4769-a157-fdbf252a96d3).html)
### Publication: -->
<!---### [Carrignon, S. et al "Tableware trade in the Roman East: Exploring cultural and economic transmission with agent-based modelling and approximate Bayesian computation" (2020), PLOS ONE.](https://doi.org/10.1371/journal.pone.0240414)-->

This project studied economic patterns in the Eastern Roman Empire by combining economic models with archaeological data. A significant challenge in such a project is parameter estimation due to the lack of input data. A vast parameter space has to be explored to accurately fit a sufficiently complex model to the available data. This requires a large number of model simulations necessitating advanced computational resources. HPC thus enabled the researchers to study the economic patterns of an ancient society using archaeological data.

[Carrignon, S. et al. "Tableware trade in the Roman East: Exploring cultural and economic transmission with agent-based modelling and approximate Bayesian computation" (2020), PLOS ONE](https://doi.org/10.1371/journal.pone.0240414).
<!--- DOI: [https://doi.org/10.1371/journal.pone.0240414](https://doi.org/10.1371/journal.pone.0240414 ) -->


## Inquisitiveness: distribution rational thinking
<!---### Affiliation: University of Southern Denmark -->
<!---### Researcher: [Davide Secchi, University of Southern Denmark](https://portal.findresearcher.sdu.dk/da/persons/secchi) --->

This study aims to redefine bounded reality based on a more socialized view of the individual. To that end, it introduces inquisitiveness to refer to an agent who mainly relies on learning by inquiry. It introduces a more active, forward-looking, and creative side compared to the concept of docility. The authors apply an agent-based simulation to explore the impact of inquisitiveness, where inquisitiveness is seen as the tool that links agents together. However, the simulation turned out to be complex due to the large number of parameters included. Therefore, the full model was only able to run using HPC resources. This simulation showed that inquisitiveness brings more problem-solving efficiency to the system.

[Bardone, E. and Secchi, D. "Inquisitiveness: distribution rational thinking" (2017), Team Performance Management, vol. 23, No 1/2.](https://doi.org/10.1108/TPM-10-2015-0044)


## DaCy – A Unified Framework for Danish natural language processing (NLP)

Natural language processing (NLP), such as recognizing names for anonymization or detecting hate speech on the internet, has seen considerable improvements in recent years; however, only a few Danish models exist, and they use different underlying frameworks. Using UCloud, DaCy has been developed, which besides integrating existing models, also includes multiple new models for syntactical analysis and named entity recognition that obtain state-of-the-art performance for these tasks.

The use of UCloud allowed the project to quickly scale up from a few initial models to larger models. This led to noticeable performance increases and obtaining a step change on tasks such as dependency parsing, which can determine who or what an adjective describes. Similarly, using UCloud made it easy to include multiple collaborators in the project, allowing for future projects without creating an infrastructure for secure file management.

[Enevoldsen, K. et al. "DaCy: A Unified Framework for Danish NLP" (2021), arXiv.](https://arxiv.org/abs/2107.05295)


## XPEROHS - Expression and Perceiving Online Hate Speech
<!---### Affiliation: University of Southern Denmark -->

The XPEROHS-project aims to investigate online hate speech. Its finding involves the semantics and pragmatics of denigration, the covert dynamics of hate speech, perceptions of spoken and written hate speech, and rhetorical hate speech strategies employed in online interaction. The project uses data from large-scale Facebook and Twitter corpora, yielding corpus sizes of hundreds of millions. These enormous amounts of data make linguistic annotation extremely challenging. Therefore, it is essential to the project that this annotation can be performed on HPC clusters rather than laptops. 

[Baumgarten, N. et al. "Towards Balance and Boundaries in Public Discourse: Expressing and Perceiving Online Hate Speech (XPEROHS)" (2019), RASK – International journal of language and communication.](https://www.sdu.dk/-/media/files/om_sdu/institutter/isk/forskningspublikationer/rask/rask+50/baumgarten+et+al.pdf)


## Conspicuous consumption in the United States and China
<!---### Affiliation: Copenhagen Business School -->
<!---### Researcher: [David Jinkins, Copenhagen Business School](https://www.cbs.dk/en/research/departments-and-centres/department-of-economics/staff/djeco) --->

Conspicuous consumption describes and explains the consumer practice of buying and using goods of higher quality, price, or greater quantity than practical. This study considered differences in conspicuous consumption in the United States and China. The paper uses a partial-equilibrium, heterogeneous-agent structural model, where the consumer's peer infers the consumer's wealth based on their purchases. The model was simulated and shown to produce data similar to the observed data using HPC. Simulations were also used to estimate welfare gains of sales taxes on various consumer goods.

[Jinkins, D. "Conspicuous consumption in the United States and China" (2016), Journal of Economic Behavior & Organization.](https://doi.org/10.1016/j.jebo.2016.03.018)


## Detection of *Mycobacterium leprae* in archeaological human dental calculus using HPC-enabled sequencing
<!---### Affiliation: University of Copenhagen -->

This study is the first to demonstrate the recovery of ancient *M. leprae* biomolecules from archaeological dental calculus. As dental calculus are pretty robust, it is often conserved over long periods. Therefore, it may represent an alternative sample source to bones and teeth for detecting and molecularly characterizing *M. leprae* in individuals from the archaeological record, especially in the absence of definitive osteological markers. This is particularly
relevant for cases where human remains are poorly preserved or too precious to warrant destructive bone sampling. The *M. leprae* genome was recovered using shotgun sequencing done using HPC resources.

[Fotakis, A. K. et al. "Multi-omic detection of *Mycobacterium leprae* in archaeological human dental calculus" (2020), Phil. Trans. R. Soc. B 375: 20190584.](https://doi.org/10.1098/rstb.2019.0584)


## HPC-enabled genomic sequencing of dog skin garments
<!---### Affiliation: University of Copenhagen -->

Among Indigenous populations of the Arctic, domestic dogs were social actors aiding in traction and subsistence activities. Less commonly, dogs fulfilled a fur-bearing role in both the North American and Siberian Arctic. This study sequenced the mitochondrial genomes of macroscopically identified dog skin garments. This sequencing was made possible using HPC resources. The study found that dog provisioning practices were variable across the Siberian and North American Arctic, but in all cases, involved considerable human labor.

[Harris, A. J. T. et al. "Archives of human-dog relationships: Genetic and stable isotope analysis of Arctic fur clothing" (2020), Journal of Anthropological Archeaology 59, 101200.](https://doi.org/10.1016/j.jaa.2020.101200)

