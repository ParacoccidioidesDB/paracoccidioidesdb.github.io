<p align="center"><img src="https://raw.githubusercontent.com/ParacoccidioidesDB/paracoccidioidesdb.github.io/master/images/paradb_logo.png"></p>

---

## ParaDB: a manually curated database for the human pathogenic fungi Paracoccidioides spp.

The genus Paracoccidioides consists of thermodymorphic fungi responsible for paracoccidioidomycosis (PCM), a systemic mycosis that affects ~10 million people in Latin America. Biogeographic data suggest the existence of five divergent subgroups within this genus, which are currently classified into two species: P. lutzii (subgroup Pl) and P. brasiliensis (subgroups S1, PS2, PS3 and PS4). Genomic sequencing of five Paracoccidioides isolates, representing each of the abovementioned subgroups provided an important framework for the development of post-genomic studies with these fungi. However, functional annotations of these genomes were based on overly restrictive criteria and ~60-90% of the Paracoccidioides protein-coding genes (depending on isolate/annotation) are currently described as responsible for hypothetical proteins, without any further functional/structural description. 

ParaDB is a centralized database, dedicated to provide of a manually-curated reannotation effort of Paracoccidioides spp. genomes, in which the number of hypothetical proteins has been reduced to ~28% in the genomes of the main representative isolates of this group, including: Pb01 (main representative of P. lutzi, formerly referred to as subgroup Pl); Pb18 (main representative of P. brasiliensis, subgroup S1); Pb03 (main representative of P. brasiliensis, subgroup PS2); PbCnh (main representative of P. brasiliensis, subgroup PS3); Pb300 (main representative of P. brasiliensis, subgroup PS4). 

ParaDB can be accessed through a friendly graphical interface, which offers search tools based on keywords or protein/DNA sequences. All data contained in ParaDB can be partially or completely downloaded through spreadsheet, multi-fasta and GFF3-formatted files, which can be subsequently used in a variety of functional analyses, constituting an important resource to assist researchers interested in conducting functional and comparative post-genomic studies with this important group of pathogenic fungi.

---

# Localhost Install

For a ParaDB installation on your local machine, only a few requirements are required:

- Docker
- Docker Compose

For details on installing these prerequisites, visit the developers documentation.

---

## Starting the ParaDB container on localhost

To start the ParaDB and Blast containers on localhost, run the following commands:

```
$ git clone https://github.com/ParacoccidioidesDB/paradb.git
$ cd paradb
$ docker-compose up -d
```

Access http://localhost in your browser.


### EXAMPLE: Video installation ParaDB:

- Click to watch the installation of ***ParaDB*** on ***Linux***:

[![Watch the video](https://raw.githubusercontent.com/ParacoccidioidesDB/paracoccidioidesdb.github.io/master/images/Screenshot%20from%202019-05-28%2016-05-36.png)](https://www.youtube.com/watch?v=FkQOJfGIepo)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Author <a name="Author" /> [[menu]](#menu)

Current development is led by Fabiano Menegidio.

## How to cite <a name="Cite" /> [[menu]](#menu)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Contributing <a name="Contributing" /> [[menu]](#menu)

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a GitHub issue, especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.

## MIT License <a name="MIT" /> [[menu]](#menu)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

***The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. in no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.***


## Learn More <a name="Learn-More" /> [[menu]](#menu)

To learn more about Docker, go to:

http://docker.com

https://docs.docker.com/
