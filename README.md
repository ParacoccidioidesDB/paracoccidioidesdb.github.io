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
