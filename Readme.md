Datensatzdokumentation  
# SARS-CoV-2-Virusvarianten in Deutschaland </br><small>SARS-CoV-2-Virus variants in Germany </small>

[Robert Koch-Institut](https://grid.ac/institutes/grid.13652.33) | RKI  
Nordufer 20  
13353 Berlin  
  
---

Robert Koch-Insitut (2021): SARS-CoV-2-Virusvarianten in Deutschaland, Berlin: Zenodo. [DOI:muss.hier_eingetragen/werden](http://dx.doi.org/10.0000/0000)  

Der Datensatz "SARS-CoV-2-Virusvarianten in Deutschaland" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de)  
 
## Informationen zum Datensatz und Entstehungskontext

Für die Planung von Maßnahmen zur Eindämmung von COVID-19 kommt der genauen Kenntnis der Eigenschaften von SARS-CoV-2 eine zentrale Bedeutung zu. Eine besondere Rolle spielen in diesem Zusammenhang Mutationen des Virus. Für eine erfolgreiche Eindämmung der Pandemie ist es daher entscheidend, einen detaillierten Überblick über die Ausbreitungsmuster spezifischer SARS-CoV-2-Mutationen zu erhalten und auch neue Mutation frühzeitig zu entdecken.  

Hierfür stellt das Robert Koch-Institut die Systeme zur bundesweiten molekularen Surveillance bereit. Jedes Labor in Deutschland, das SARS-CoV-2 sequenziert, ist laut der [Verordnung zur molekulargenetischen Surveillance des Coronavirus SARS-CoV-2](https://www.bundesgesundheitsministerium.de/presse/pressemitteilungen/2021/1-quartal/coronavirus-surveillanceverordnung.html) verpflichtet, dem Robert Koch-Institut die Sequenz- und zugehörige Metadaten zu übermitteln. Technisch erfolgt diese Übermittlung über den [Deutschen Elektronischen Sequenzdaten-Hub](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/DESH.html) (DESH). Die Vergütung der Sequemnzierungen verantwortet die [Kassenärztliche Bundesvereinigung](https://www.kbv.de/media/sp/2021-02-05_KBV-Vorgaben_CorSurV.pdf).  

Im Projekt "OSEDA - Offene Sequenzdaten" verpflichtet sich das RKI, die aufgearbeiteten und qualitätskontrollierten Sequenzdaten zusammen mit einer Auswahl von klinisch-epidemiologischen Daten über die öffentlich zugängliche Repositorien des [European Nucleotide Archive](https://www.ebi.ac.uk/ena/browser/home) (ENA) und [GISAID](https://www.gisaid.org/) für weitere Forschungsvorhaben bereitzustellen.  

![**Abbildung:** Systemaufbau des Deutschen Elektronischen Sequenzdaten-Hub (DESH)](Kontexmaterialien/2021-07-13_DESH_Systemaufbau.jpg "Abbildung: Systemaufbau des Deutschen Elektronischen Sequenzdaten-Hub (DESH)")  

>[Kontexmaterialien/2021-01-29_DESH_CorSurV_BAnz_AT_V2.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/2021-01-29_DESH_CorSurV_BAnz_AT_V2.pdf)  
>[Kontexmaterialien/2021-02-05_DESH_KBV-Vorgaben_CorSurV.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/2021-02-05_DESH_KBV-Vorgaben_CorSurV.pdf)  
 
### Administrative und organisatorische Angaben

Der Datensatz "SARS-CoV-2-Virusvarianten in Deutschaland" wird vom [Robert Koch-Institut](https://rki.de) für Forschungsarbeiten im Zusammenhang mit der SARS-CoV-2-Pandemie bereitgestellt.  
Die Datenübermittlung an das RKI erfolgt über das System des [Deutschen Elektronischen Sequenzdaten-Hub](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/DESH.html) (DESH). Teil dieses Systems ist die von der Bundesdruckerei bereitgestellte DESH-Plattform über die Sequenzdaten durch sequenzierenden Labore übermittelt werden können (nur mit einem individuellen Zetifikat anfrufbar). Fragen bezüglich der DESH-Platform können diekt an das DESH Team unter [desh@rki.de](mailto:desh@rki.de) gerichtet werden.  
Die Veröffentlichung der Daten, die Datenkuration sowie das Qualitätsmanagement der (Meta-)Daten erfolgen durch das Fachgebiet [MF 4 | Forschungsdatenmanagement](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MF/MF4/mf4_node.html) des RKI. Fragen zum Datenmanagement können an das Fachgebiet MF4 gerichtet werden ([MF4@rki.de](mailto:MF4@rki.de)).  

### Übermittlung der Sequenzdaten

Auf der [DESH Projektwebseite](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/DESH.html) des RKI befindet sich eine [Anleitung zur Bereitstellung der Sequenzdaten](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Anleitung-Bereitstellung-Sequenzdaten.html?), die Sequenzierenden Laboren im  Prozess der Bereitstellung Ihrer Sequenzdaten über https://desh.bdr.de (nur mit einem individuellen Zetifikat aufrufbar) behilflich ist. Das RKI stellt außerdem beispielhaft eine [.csv-Datei](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Metadatenschema-csv.csv?) mit dem in der Anleitung geforderten Metadatenschema zur Verfügung. Außerdem werden bestimmte [Qualitätskriterien](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Qualitaetskriterien.html?) für die Sequenzdaten gefordert. Die Einhaltung der Qualitätskritierien wird durch die sequenzierenden Labore sichergestellt. Das RKI hat keine Kentniss über die zugrundeliegenden Rohdaten (sog. "Reads").  
Die Sequenzdaten können  über eine REST-API auch automatisert bereitgestellt werden. Dazu stellt das RKI eine [Anleitung](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Spezifikation-Upload.html) nebst einem ergänzendem [Sequenzdiagramm](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Sequenzdiagramm.html?nn=13490888) bereit. Die Upload-Spezifikation nach OpenAPI 3.0.3 können der [Receiver.yaml](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Receiver-yaml.zip) entnommen werden.  

>[Kontexmaterialien/2021-02-18_DESH_Anleitung_zur_Bereitstellung_Sequenzdaten.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/2021-02-18_DESH_Anleitung_zur_Bereitstellung_Sequenzdaten.pdf)  
>[Kontexmaterialien/2021-02-18_DESH_Metadatenschema.csv](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/2021-02-18_DESH_Metadatenschema.csv)  
>[Kontexmaterialien/2021-02-08_DESH_Qualitätsvorgaben_für_die_Sequenzdaten.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/2021-02-08_DESH_Qualitätsvorgaben_für_die_Sequenzdaten.pdf)  
>[Kontexmaterialien/2021-04-27_DESH_Spezifikation der Bereitstellung über REST API.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/2021-04-27_DESH_Spezifikation_der_Bereitstellung_über_REST_API.pdf)  
>[Kontexmaterialien/2021-05-03_DESH_Sequenzdiagramm_REST_API.pdf](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/2021-05-03_DESH_Sequenzdiagramm_REST_API.pdf)  
>[Kontexmaterialien/2021-04-08_DESH_Receiver_Spezifikationen.yaml](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/2021-04-08_DESH_Receiver_Spezifikationen.yaml)  

### Veröffentlichung der Sequenzdaten
In der Veröffentlichung von Sequenzdaten im [ENA](https://www.ebi.ac.uk/ena/browser/home) und [GISAID](https://www.gisaid.org/)  kommt es durch notwendige Zwischenschritte zu einer zeitlichen Verzögerung der Publikation. Daher stellt das RKI zusätzlich alle über DESH empfangenen Sequenzdaten tagesaktuell zu Verfügung. 


:warning:Der Datensatz ist keiner weitere Qualitätskontrolle durch das RKI durchlaufen. Zu beachten ist, dass Daten in diesem Datensatz zum Beispiel:  

   - Sequenzdaten von niedriger Qualität enthalten  
   - unverifizierte Frameshifts vorhersagen  
   - mehrmals im Datensatz vorhanden sind  
   - bereits vom sequenzierendem Labor veröffentlicht worden sind  

Die hier veröffentlichten Daten können daher nicht ohne weiteres mit dem wöchentlichen [Bericht zu Virusvarianten von SARS-CoV-2 in Deutschland des RKIs](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Berichte-VOC-tab.html) vergleichen werden. Außerdem können diese Daten ausdrücklich nicht als Grundlage für die Abrechnung der Labore mit der KBV verwendet werden.  


## Aufbau und Inhalt des Datensatzes

Der Datensatz enthält Daten über SARS-CoV-2-Genomsequenzend in Deutschland und die in der Datenverarbeitung unterstützenden Kontextmaterialien. Im Datensatz enthalten sind:  

* Sequenzdaten mit tagesaktuell übermittelten SARS-CoV-2-Genomsequenzen  
* Metadaten der Sequenzierungen  
* Archiv mit der Sammlung aller bisherig übermittelten SARS-CoV-2-Genomsequenzen und der Metadaten der Sequenzierungen  
* Lizenz Datei mit der Nutzungslizenz des Datensatzes  
* Datensatzdokumentation und Kontextmaterialien in deutscher Sprache  
* Metadaten Datei zum Import in Zenodo  

### Formatierung der Daten  

Die SARS-CoV-2-Sequenzdaten werden als [xz-komprimierte](https://en.wikipedia.org/wiki/XZ_Utils) [.fasta](https://en.wikipedia.org/wiki/FASTA_format) Datei bereitgestellt. Daraus ergibt sich die Dateiendung .fasta.xz. Die Zeilen werden bei 80 Zeichen umgebrochen. Es werden Linux Zeilenumbrüche verwendet.

* Zeichensatz: UTF-8  
* Komprimierung: [.xz](https://en.wikipedia.org/wiki/XZ_Utils)  
* Enhaltenes Dateiformat: [.fasta](https://de.wikipedia.org/wiki/FASTA-Format)  
* Zeilenlänge: maximal 80 Zeichen  
* Zeilenumbüche: Linux Zeilenumbrüche  

Die Metadaten der Sequenzierung werden als [xz-komprimierte](https://en.wikipedia.org/wiki/XZ_Utils), kommaseparierte .csv-Datei bereitgestellt. Daraus ergibt sich die Dateiendung .csv.xz. Der verwendete Zeichensatz der .csv-Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Komma ",". Datumsangaben sind im ISO-8601-Standard formatiert.

* Zeichensatz: UTF-8  
* Datumsformat: ISO 8601  
* Komprimierung: [.xz](https://en.wikipedia.org/wiki/XZ_Utils)  
* Enhaltenes Dateiformat: .csv
* .csv-Trennzeichen: Komma ","  

Die Dateien können auf gängigen Betriebsystemen, beispielsweise mit den Programmen [7zip](https://www.7-zip.org/) oder [XZ Utils](https://tukaani.org/xz/), entpackt werden. Die komprimirung wird vorgenommen, da insbesondere die .fasta-Datein mehrere Gigabeit (GB) groß sind.  

## SARS-CoV-2-Sequenzdaten und Metadaten der Sequenzierung

Die SARS-CoV-2-Sequenzdaten werden tagesaktuell im Hauptverzeichnis unter "Aktuell_SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz" bereitgestellt. Gleiches gilt für sugehörigen Metadaten der Sequenzierung, die unter "Aktuell_SARS-CoV-2-Sequenzdaten_Deutschland.csv.xz" im Datensatz enhalten sind. Im Archivordner sind die täglichen Datenstände unter den Dateinamen "JJJJ-MM-TT_SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz" und "JJJJ-MM-TT_SARS-CoV-2-Sequenzdaten_Deutschland.csv.xz" abgelegt.  

>Aktuell_SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz
>Aktuell_SARS-CoV-2-Sequenzdaten_Deutschland.csv.xz
>Archiv/JJJJ-MM-TT_SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz
>Archiv/JJJJ-MM-TT_SARS-CoV-2-Sequenzdaten_Deutschland.csv.xz

Im Dateinamen repräsentiert die Sequenz "JJJJ-MM-TT" das Erstellungsdatum der Datei und gleichzeitig das Datum des enthaltenen Datenstands. "JJJJ" steht dabei für das Jahr, "MM" für den Monat und "TT" für den Tag der Erstellung bzw. des enthaltenen Datenstands. Die "Aktuell_SARS-CoV-2-Sequenzdaten_Deutschland.fasta/csv.xz" sind identisch mit dem neusten Datenstand des Archivs.  
Die Daten werden jeden Tag um die verarbeiteten Sequenzdaten des aktuellen Tages erweitert (kummulation). Dabei werden nach 20:00 eingesendete Sequenzdaten erst am Folgetag verarbeitet. Der Datenstand bildet also immer den Stand des aktuellen Tages um 19:59 ab.  
 
### Stuktur der SARS-CoV-2-Sequenzdaten  

Die Sequenzeinträge der bereitgestellten .fasta-Datein beginnen mit einer einzeiligen Beschreibung, der Kopfzeile, auch "Description line" genannt. Auf die Kopfzeile folgt die [Nukleinsäuresequenz](https://de.wikipedia.org/wiki/Nukleotidsequenz) des Sequenzierten SARS-CoV-2-Virus.  
Die Kopfzeile wird durch ein "&gt;" markiert, eine Sequenz endet mit dem Ende der Datei oder einem weiteren Sequnezeintag, beginnen mit einer neuen Kopfzeile.  
In den bereitgestelten Sequenzdaten enhält die Kopfzeile die FASTA-ID, die in den Daten der IMS_ID der Probe entspricht. Die IMS_IDerlaubt die Verküfung mit den Metadaten der Sequenzierung. Die Kodierung der Nucleotide der Sequenzdaten folgen dem IUB/IUPAC Standard.  

* Kopfzeile: &gt;IMS_ID
* Nukleinsäuresequenz: IUB/IUPAC Standard

Daraus ergibt sich beispielhaft folgende Struktur der .fasta-Datein:

>&gt;IMS-101XX-CVDP-XX  
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNACCAACCAACTTTCGATCTCTT  
GTTCTCTAAACGAACTTTAAAATCTGTGTGGCTGTCTCTCGGCTGCATGCTTAGTGCACT  
...  
YGACCGGGTGTGACCGAAAGGTAAGATGGAGAGCCTTGTCCCTGGTTTCAACGAGAA  
GGGAGGACTTGAAAGAGCCACCACATTTTCACCGAGGCN  
>&gt;IMS-101YY-CVDP-YY   
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNACCAACTCTCGGCTGCATGCT  
GTTCTCTAAACGAACTTTAAAATCTGTGTGGCTGTCTTGAAAGAGCCACCACATTTTCA  
...  

### Variablen und Variablenausprägungen Metadaten der Sequenzierung  

In den als .csv bereitgestellten Metadaten der Sequenzierung enthalten in folgender Tabelle aufgeführte Variablen. Zentral für die Verknüfung der Metadaten der Sequenzierung mit den Sequenzeinträgen ist die IMS_ID, die in beiden Daten enhalten ist. 


| Variable | Beschreibung | Value Set |
| -------- | -------- | --- |
| IMS_ID     | Ein eindeutiger Identifikator der Sequenzdaten und Metadaten zusammenführt. Dieser Identifikator wird als FASTA ID in den Sequenzdaten genutzt      | 
| DATE_DRAW | Das Datum der Probeentnahme im Format JJJJ-MM-TT |  |
| SEQ_TYPE | Die verwendete Sequenzierungs-Plattform | [ena](https://ena-docs.readthedocs.io/en/latest/submit/reads/webin-cli.html#permitted-values-for-platform)
| SEQ_REASON| Der Grund für die Durchführung der Sequenzierung| [rki](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Anleitung-Bereitstellung-Sequenzdaten.pdf?__blob=publicationFile#page=4)
| SAMPLE_TYPE|  Art der Probe|[snomed](https://simplifier.net/covid-19labormeldung/materialsarscov2)
| OWN_FASTA_ID | Die vom Labor genutzte  FASTA ID in verschlüsselter Form|
| RECEIVE_DATE | Verarbeitungsdatum im RKI (JJJJ-MM-TT). Üblicherweise <24 Stunden nach Einsendung durch die Labore|
| SENDING_LAB_PC | Die Postleitzahl des sequenzierenden Labors|
| PRIMEDIAGNOSTIC_LAB_PC | Die Postleitzahl des primärdiagnostischen Labors|

Weitere Informationen zu den aufgeführten Variablen finden sich in der [Anleitung zur Bereitstellung der Sequenzdaten](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Anleitung-Bereitstellung-Sequenzdaten.html?) die auch in [Kontextmaterialien](https://github.com/robert-koch-institut/SARS-CoV-2-Virusvarianten_in_Deutschaland/blob/master/Kontexmaterialien/) hinterlegt ist.  

## Hinweise zur Nachnutzung der Daten 

:warning: Der Datensatz ist keiner weitere Qualitätskontrolle durch das RKI durchlaufen. Zu beachten ist, dass Daten in diesem Datensatz zum Beispiel:  

   - Sequenzdaten von niedriger Qualität enthalten  
   - unverifizierte Frameshifts vorhersagen  
   - mehrmals im Datensatz vorhanden sind  
   - bereits vom sequenzierendem Labor veröffentlicht worden sind  

Die hier veröffentlichten Daten können daher nicht ohne weiteres mit dem wöchentlichen [Bericht zu Virusvarianten von SARS-CoV-2 in Deutschland des RKIs](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Berichte-VOC-tab.html) vergleichen werden. Außerdem können diese Daten ausdrücklich nicht als Grundlage für die Abrechnung der Labore mit der KBV verwendet werden.  

Weitere, offene Forschungsdaten des RKI werden auf GitHub.com sowie Zenodo.org bereitgestellt:  

* https://github.com/robert-koch-institut
* https://zenodo.org/communities/robertkochinstitut  

### Metadaten der Publikation  

Die bereitgestellten Daten sind mit Metadaten beschrieben und wissenschaftlich zitierbar, u.a. durch die Vergabe einer DOI durch Zenodo.org. Die für den Import in Zenodo bereitgestellten Metadaten sind in folgender Datei hinterlegt:  

> .zenodo.json 

Die Dokumentation der einzelen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar. 

### Lizenz  

Der Datensatz "SARS-CoV-2-Virusvarianten in Deutschaland" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede_r hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/LICENSE) bzw. [LIZENZ](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/LIZENZ) Datei des Datensatzes.  

Die empfohlene Zitierweise ist:  

Robert Koch Institut (2021): SARS-CoV-2-Virusvarianten in Deutschaland, Berlin: Zenodo. DOI:[DOI](https://doi.org/10.5281/zenodo.DOI).
