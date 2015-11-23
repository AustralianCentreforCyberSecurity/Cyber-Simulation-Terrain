# README #

The Cyber Effects Simulation Ontology (CESO) is a developing middle-level ontology that is intended to represent the effects of a cyber attack on a network.
The CESO itself is comprised of three components. The CESO, which defines the effects that can occur on a network and the inter-ontology bridges between sub-ontologies. 
The Cyber Simulation Terrain (CST) is an independent network model that defines the network configuration (including vulnerabilities) that attacks will be targeted at.
The Threat Simulaton Ontology (TSO) contains the exploits that are used against the vulnerabilities on the CST. It contains informational elements of the threat actors, capabilities, coruses of action etc. 

Contained here is a demonstative usecase that instantiates the ontology and uses the *Competency Question* format to demonstrate the functionality of the CESO.

Future Work for the CESO includes testing at scale, Instantiation from an operational network, automated instantiaton and visualisation. 

### What is this repository for? ###

* This Repository is intended to overcome a problem that has been consistently observed during the research that produced the CESO. Namely, the lack of open source work into Cyber Terrains and Cyber Effects Ontologies.

* The work here is in development - the authors welcome any feedback, suggestions and development of the work. 

* If you wish to collaborate on future development of the ontology or related works please contact one of the authors on the details provided below. 

### How do I get set up? ###

* Summary of set up
*The ontology is written in RDF, stored in a graph database and queried using SPARQL. The authors have used the following software through the creation of the ontology:*
	+Sublime Text 3 (http://www.sublimetext.com/3)
	+SPARQL / RDF TTL Syntax (https://github.com/abcoates/sublime-text-turtle-sparql)
	+Stardog (http://stardog.com/)

* Configuration
	+ Follow the instructions in the STARDOG User websites to configure the stardog server. 
	+ The SPARQL used to query the ontology is presented in a stardog-parsable format to promote ease of testing. Providing that the databse name created matches that given the queries do not need to be changed. 
	+Of Note: Some queries will use the -r flag. This enables the RDF reasoner and is used in some queries to inference and gain results. 

* Dependencies
	+The Requried Files are:
		- **ceso.ttl** - The Cyber Effects Simulation Ontology RDF File. 
		- **cst.ttl** - The Cyber Simulation Terrain RDF File. 
		- **tso.ttl** - The Threat Simulation Ontology RDF File.
		- **cstUsecase.sparql** - The CST usecase presented at the 16th Australian Information Warfare Conference. 
		- **cesoUsecase.sparql** - The CESO usecase file. 

* Database configuration
	+As Per the Stardog User Manual

* How to run tests
	+See The SPARQL Files. They have examples of tests run using stardog. 
	
* Deployment instructions

### Contribution guidelines ###



### Who do I talk to? ###

* Repo owner or admin
Kent O'Sullivan - kentdanos@gmail.com
Dr Ben Turnbull - b.turnbull@adfa.edu.au

* Other community or team contact