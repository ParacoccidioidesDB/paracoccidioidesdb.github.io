<p align="center"><img src="https://raw.githubusercontent.com/ParacoccidioidesDB/paracoccidioidesdb.github.io/master/images/paradb_logo.png"></p>

---

## ParaDB: a manually curated database for the human pathogenic fungi Paracoccidioides spp.

The genus Paracoccidioides consists of thermodymorphic fungi responsible for Paracoccidioidomycosis (PCM), a systemic mycosis that has been registered to affect ~10 million people in Latin America. Currently, the genus is subdivided into five different species, each represented by a reference isolate: P. lutzi (represented by isolate Pb01), P. brasiliensis (represented by isolate Pb18), P. americana (represented by isolate Pb03), P. restrepiensis (represented by isolate PbCnh) and P. venezuelensis (represented by isolate Pb300). Although genomic sequencing has already been obtained for all these five Paracoccidioides isolates, functional annotations of these genomes, available in central databases such as NCBI/RefSeq or Ensembl, have not been submitted to manual curation and, as a result, ~60-90% of the Paracoccidioides protein-coding genes (depending on isolate/annotation) are currently described as responsible for hypothetical proteins, without any further functional/structural description. ParaDB provides revised annotations for these isolates, based on extensive manual curation, which reduced the number of hypothetical proteins in their genomes to ~25 – 28%. This site also provides researches with resources to facilitate data mining of Paracoccidioides genomes, including search tools based on keywords or protein/DNA sequences.

All data contained in ParaDB can be partially or completely downloaded through spreadsheet, multi-fasta and GFF3-formatted files, which can be subsequently used in a variety of downstream functional analyses, aiding researchers in this field to conduct post-genomic studies with this important group of human pathogenic fungi.

---

# Localhost Install

ParaDB installation requirements:

- Docker
- Docker Compose
- GIT

For details on installing these prerequisites, visit the developers documentation.

---

## Requirements:

- Linux Operating System (preferably)
- 2 GB RAM
- 5 GB of disk space.

---

## Starting the ParaDB container on localhost

### FAST Install:

To start the ParaDB and Blast containers on localhost, run the following commands:

```
$ git clone https://github.com/ParacoccidioidesDB/paradb.git
$ cd paradb
$ docker-compose up -d
```

Access http://localhost in your browser. If the page is not loaded, wait for the WEB and Database service to be loaded in the containers.

### Detail Install:

Prior to the runs on the videos, the Docker and Docker Compose installations were made according to the official Docker project documentation. Details on the entire execution process are provided below. The exact time each action is displayed in the video is also provided (in parentheses) next to the instructions.


[![Watch the video](https://raw.githubusercontent.com/ParacoccidioidesDB/paracoccidioidesdb.github.io/master/images/Screenshot%20from%202019-05-28%2016-05-36.png)](https://youtu.be/xfxOfKqS-xU)


```
## Validating Docker installation [00:12]

$ docker

## Validating the installation of Docker-Compose [00:22]

$ docker-compose

## Cloning the ParaDB repository on GitHub [00:44]

$ git clone https://github.com/ParacoccidioidesDB/paradb.git

## Accessing the Cloned GitHub Folder [01:22]

$ cd paradb

## Listing the files in the folder [01:25]

ls

## Checking the file of the Docker Compose responsible for starting \
   the ParaDB service [01:34]

$ vi docker-compose.yml

## Checking the container settings: paradb-web, paradb-blast, and paradb-watchtower [01:36]
 
## Checking the network port settings of the paradb-web container [01:44]

## Checking the network port settings for the paradb-blast container [01:55] and the folder sharing settings [02:00]

## Checking the folder-sharing settings of the container paradb-watchtower [02:09] and the monitoring settings for the paradb-web and paradb-blast containers [02:13]

## Checking the Docker service network settings [02:16]

## Listing the Blast service databases [02:32]

$ ls paradb_blast

## Starting the ParaDB service on the local machine [02:49]

$ docker-compose up -d

## Downloading the Docker image: paradb-web [02:54]

## Downloading the Docker image: paradb-blast [06:06]

## Downloading the Docker image: paradb-watchtower [07:04]

## Starting the ParaDB service [07:22]

## Viewing the downloaded Docker images to the machine [07:33]

$ docker images

## Viewing the ParaDB Service Containers [07:45]

$ docker ps

## Displaying the web port (80) of the paradb-web container [07:52]

## Accessing the ParaDB page locally through the address http: // localhost [07:58]

Note: The paradb-web container has the web and database services. It may take a few seconds to become available for access. In case of an error, please wait a few minutes and try again. [08:02]

## Opening the ParaDB homepage [08:04]

## Displaying the web port (4567) of the container paradb-blast [08:18]

## Accessing the ParaDB Blast page locally through the address http: // localhost: 4567 [08:32]

## Accessing the Blast page through the ParaDB interface [08:42]

## ParaDB Access
```


### 

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
