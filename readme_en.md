Dataset documentation  
#SARS-CoV-2 Sequence Data from Germany

[Robert Koch Institute](https://grid.ac/institutes/grid.13652.33) | RKI  
Nordufer 20  
13353 Berlin  
  
---

Robert Koch Institute (2021): SARS-CoV-2-Sequenzdaten aus Deutschland, Berlin: Zenodo. [DOI: 10.5281/zenodo.5139363](https://doi.org/10.5281/zenodo.5139363)  

The dataset "SARS-CoV-2-Sequenzdaten aus Deutschland" is licensed under the [Creative Commons Attribution 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de)  
 
## Information about the dataset and context of origin.

Accurate knowledge of the properties of SARS-CoV-2 is of central importance for planning measures to contain COVID-19. Mutations of the virus play a special role in this context. For successful containment of the pandemic, it is therefore crucial to obtain a detailed overview of the spread patterns of specific SARS-CoV-2 mutations and also to detect new mutations at an early stage.  

For this purpose, the Robert Koch Institute provides the systems for nationwide molecular surveillance. Every laboratory in Germany that sequences SARS-CoV-2 is required by the [Verordnung zur molekulargenetischen Surveillance des Coronavirus SARS-CoV-2](https://www.bundesgesundheitsministerium.de/presse/pressemitteilungen/2021/1-quartal/coronavirus-surveillanceverordnung.html) to transmit the sequence and associated metadata to the Robert Koch Institute. This transmission is implemented via the [German Electronic Sequence Data Hub](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/DESH.html) (DESH).

In the project "OSEDA - Open Sequence Data", the RKI aims at providing the processed and quality-controlled sequence data together with a selection of clinical epidemiological data via the publicly accessible repositories of the [European Nucleotide Archive](https://www.ebi.ac.uk/ena/browser/home) (ENA) and [GISAID](https://www.gisaid.org/) for further research projects.  

![**Figure:** System Structure of the German Electronic Sequence Data Hub (DESH)](/Context Materials/2021-07-13_DESH_System_Sructure.jpg "Figure: System Structure of the German Electronic Sequence Data Hub (DESH)")  

>[Context materials/2021-01-29_DESH_CorSurV_BAnz_AT_V2.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/master/Kontextmaterialien/2021-01-29_DESH_CorSurV_BAnz_AT_V2.pdf)  
 
### Administrative and organizational data.

The dataset "SARS-CoV-2 Sequence Data from Germany" is provided by the [Robert Koch Institute](https://rki.de) for research related to the SARS-CoV-2 pandemic.  

Data transfer to the RKI is done via the system of the [German Electronic Sequence Data Hub](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/DESH.html) (DESH). Part of this system is the DESH platform provided by Bundesdruckerei through which sequence data can be transmitted by sequencing laboratories (can only be accessed with an individual certificate). Questions regarding the DESH platform can be directed to the DESH team at [desh@rki.de](mailto:desh@rki.de). 

Data publication, data curation, and quality management of the (meta-)data are performed by the RKI department [MF 4 | Research Data Management](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MF/MF4/mf4_node.html). Questions regarding data management can be directed to the Open Data Team of the Department MF4 ([OpenData@rki.de](mailto:opendata@rki.de)).  

### Submission of sequence data.

The RKI's [DESH project website](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/DESH.html) contains [instructions for providing sequence data](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Anleitung-Bereitstellung-Sequenzdaten.html?) to assist sequencing laboratories in the process of providing metadata and sequence data via https://desh.bdr.de (only accessible with an individual certificate). Sequencing laboratories are required to meet certain [quality criteria](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Qualitaetskriterien.html?) for sequence data. Compliance with the quality criteria is ensured by the sequencing laboratories. The RKI has no knowledge of the underlying raw data (so-called "reads").  

>[Context materials/2021-02-18_DESH_instruction_on_providing_sequence_data.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/master/Kontextmaterialien/2021-02-18_DESH_Anleitung_zur_Bereitstellung_Sequenzdaten.pdf)  
>[Contextual_materials/2021-02-08_DESH_Quality_requirements_for_the_sequence_data.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/master/Kontextmaterialien/2021-02-08_DESH_Qualitätsvorgaben_für_die_Sequenzdaten.pdf)  
>
### Publication of sequence data
In the publication of sequence data in [ENA](https://www.ebi.ac.uk/ena/browser/home) and [GISAID](https://www.gisaid.org/), there is a delay in publication due to necessary intermediate steps. Therefore, the RKI additionally provides all sequence data received via DESH on a daily basis. 


:warning: The data set has not undergone any further quality control by the RKI. It should be noted that data in this dataset for example:  

   - contain sequence data of low quality  
   - predict unverified frameshifts  
   - is present more than once in the dataset  
   - have already been published by the sequencing laboratory  

Therefore, the data published here cannot be compared with the weekly [Report on viral variants of SARS-CoV-2 in Germany by the RKI](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Berichte-VOC-tab.html). Furthermore, these data can explicitly not be used as a basis for billing with the KBV.  


## Structure and content of the data set

The dataset contains data on SARS-CoV-2 sequences in Germany and the contextual materials supporting the data processing. Included in the dataset are:  

* Sequence data of the submitted SARS-CoV-2 genome sequences (SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz)
* Metadata on the SARS-CoV-2 genome sequences (SARS-CoV-2-Sequenzdaten_Deutschland.csv.xz)
* Information about the viral lineages (PANGOLIN Lineages) of the SARS-CoV-2 genome sequences (SARS-CoV-2-Entwicklungslinien_Deutschland.csv.xz)
* License of the dataset.  
* Dataset documentation and context materials in German language  
* Metadata file for import into Zenodo  

### Formatting of the sequence data  

The SARS-CoV-2 sequence data is provided as an [xz-compressed](https://en.wikipedia.org/wiki/XZ_Utils) [.fasta](https://en.wikipedia.org/wiki/FASTA_format) file. This results in the .fasta.xz file extension. The lines are wrapped at 80 characters. Linux line breaks are used.

* Character set: UTF-8  
* Compression: [.xz](https://en.wikipedia.org/wiki/XZ_Utils)  
* Included file format: [.fasta](https://de.wikipedia.org/wiki/FASTA-Format)  
* Line length: maximum 80 characters  
* Line breaks: Linux line breaks  

### Formatting the metadata 
The sequencing metadata is provided as an [xz-compressed](https://en.wikipedia.org/wiki/XZ_Utils), comma-separated .csv file. This results in the .csv.xz file extension. The character set used for the .csv file is UTF-8. The separator of the individual values is a comma ",". Dates are formatted in the ISO-8601 standard.

* Character set: UTF-8  
* Date format: ISO 8601  
* Compression: [.xz](https://en.wikipedia.org/wiki/XZ_Utils)  
* Included file format: .csv
* .csv separator: Comma ","  

 

### Formatting the development lines
Sequencing development lines are provided as an [xz-compressed](https://en.wikipedia.org/wiki/XZ_Utils), comma-separated .csv file. This results in the .csv.xz file extension. The character set used in the .csv file is UTF-8. The separator of the individual values is a comma ",". Dates are formatted in the ISO-8601 standard.

* Character set: UTF-8  
* Date format: ISO 8601  
* Compression: [.xz](https://en.wikipedia.org/wiki/XZ_Utils)  
* Included file format: .csv
* .csv separator: Comma ","  

The files can be unpacked on common operating systems, for example with either [7zip](https://www.7-zip.org/) or [XZ Utils](https://tukaani.org/xz/). Compression is performed because the .fasta files in particular are several gigabytes (GB) in size. 


## SARS-CoV-2 sequence data and sequencing metadata.

The SARS-CoV-2 sequence data are provided on a daily basis in the main directory under "SARS-CoV-2-Sequenzdaten-Deutschland.fasta.xz". The same applies to associated metadata contained in the dataset under "SARS-CoV-2-Sequenzdaten-Deutschland.csv.xz" and the lineages contained in the dataset under "SARS-CoV-2-Entwicklungslinien_Deutschland.csv.xz". **Developmental lines are not available for all SARS-CoV-2 sequence datasets.**

>SARS-CoV-2-Sequenzdaten-Deutschland.fasta.xz
>SARS-CoV-2-Sequenzdaten-Deutschland.csv.xz
>SARS-CoV-2-Entwicklungslinien_Deutschland.csv.xz

The data is extended every day by the processed sequence data of the current day (cummulation). Sequence data sent in after 20:00 are not processed until the following day. The data status therefore always represents the status of the current day at 19:59.  
 
### Structure of the sequence data  

The sequence entries of the .fasta file provided start with a one-line description, the header line, also called "Description line". The header line is followed by the [nucleic acid sequence](https://de.wikipedia.org/wiki/Nukleotidsequenz) of the sequenced SARS-CoV-2 virus.  
The header line is marked by a "&gt;", a sequence ends with the end of the file or another sequence tag, start with a new header line.  
In the provided sequence data, the header contains the FASTA ID, which in the data corresponds to the IMS_ID of the sample. The IMS_ID allows linkage to the metadata. The coding of the nucleotides of the sequence data follow the IUB/IUPAC standard.  

* Header: &gt;IMS_ID
* Nucleic acid sequence: IUB/IUPAC standard

This results in the following structure of a .fasta file as an example:

>&gt;IMS-101XX-CVDP-XX  
NNNNNNNNNNNNNNNNNNNNNNNNACCAACCAACTTTCGATCTCTT  
GTTCTCTAAACGAACTTTAAAATCTGTGGCTCTCTCGGCTGCATGCTTAGTGCACT  
...  
YGACCGGGTGTGACCGAAAGGTAAGATGGAGCCTTGTCCCTGGTTTCAACGAGAA  
GGGAGGACTTGAAAGAGCCACCACATTTTCACCGAGGCN  
>&gt;IMS-101YY-CVDP-YY   
NNNNNNNNNNNNNNNNNNNNNNACCAACTCTCGGCTGCATGCT  
GTTCTCTAAACGAACTTTAAAATCTGTGGCTGTCTTGAAAGAGCCACCACATTTTCA  
...  

### Variables and variable characteristics metadata 

The metadata file provided as a .csv contains variables listed in the following table as columns. Central to linking the metadata to the genome sequences is the IMS_ID, which is included in all three data files. 


| Variable | Description | Value Set |
| -------- | -------- | --- |
| IMS_ID | A unique identifier that combines sequence data and metadata. This identifier is used as the FASTA ID in the sequence data | 
| DATE_DRAW | The date of sampling in YYYY-MM-DD format |
| SEQ_TYPE | The sequencing platform used | [ena](https://ena-docs.readthedocs.io/en/latest/submit/reads/webin-cli.html#permitted-values-for-platform)
| SEQ_REASON| The reason for performing the sequencing| [rki](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Anleitung-Bereitstellung-Sequenzdaten.pdf?__blob=publicationFile#page=4)
| SAMPLE_TYPE| Type of sample| [snomed](https://simplifier.net/covid-19labormeldung/materialsarscov2)
| OWN_FASTA_ID | The FASTA ID used by the lab in encrypted form|
| PROCESSING_DATE | Date of submission to the RKI (YYYY-MM-DD).|
| RECEIVE_DATE | Date received at the RKI (YYYY-MM-DD). Usually <24 hours after submission by laboratories|.
| SEQUENCING_LAB_PC | The zip code of the sequencing laboratory|
| SENDING_LAB_PC | The zip code of the prime diagnostic laboratory|

For more information on the listed variables, see [Instructions for Providing Sequence Data](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Anleitung-Bereitstellung-Sequenzdaten.html?) which is also deposited in [Context Materials](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/tree/master/Kontextmaterialien).  

### Variables and variable expressions development lines. 

The information provided on developmental lineages corresponds to the current [PANGOLIN Lineage Format](https://cov-lineages.org/resources/pangolin/output.html). Only the "Taxon" column has been renamed to IMS_ID for easier re-use. Central to linking the developmental lineages to the rest of the data is the IMS_ID, which is included in all three data. 

## Notes on the subsequent use of the data 

:warning: the dataset has not undergone further quality control by the RKI. It should be noted that data in this dataset for example:  

   - contain sequence data of low quality  
   - predict unverified frameshifts  
   - are present more than once in the dataset  
   - have already been published by the sequencing laboratory  

Therefore, the data published here cannot be readily compared with the weekly [Report on viral variants of SARS-CoV-2 in Germany by the RKI](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Berichte-VOC-tab.html). Furthermore, these data explicitly cannot be used as a basis for billing laboratories with KBV.  

Additional, open research data from the RKI are provided on GitHub.com as well as Zenodo.org:  

* https://github.com/robert-koch-institut
* https://zenodo.org/communities/robertkochinstitut  

### Publication metadata.  

The data provided are described with metadata and are scientifically citable, including through the assignment of a DOI by Zenodo.org. The metadata provided for import into Zenodo is stored in the following file:  

> .zenodo.json 

Documentation of the individual metadata variables can be found at https://developers.zenodo.org/#representation. 

### License  

The dataset "SARS-CoV-2-Sequenzdaten aus Deutschland" is licensed under the [Creative Commons Attribution 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de)  

The data provided in the dataset are freely available, on condition that the Robert Koch Institute is credited as the source. This means that everyone has the right to process and modify the data, to create derivatives of the dataset and to use it for commercial and non-commercial purposes. For more information about the license, see the [LICENSE](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/master/LICENSE) or [LICENSE](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/master/LIZENZ) file of the dataset.  

The recommended citation is:

Robert Koch Institute (2021): SARS-CoV-2-Sequenzdaten aus Deutschland,, Berlin: Zenodo. [DOI: 10.5281/zenodo.5139363](https://doi.org/10.5281/zenodo.5139363) .
