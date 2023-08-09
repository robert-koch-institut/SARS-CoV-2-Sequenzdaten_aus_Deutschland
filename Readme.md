Datensatzdokumentation  
# SARS-CoV-2-Sequenzdaten aus Deutschland  

[Robert Koch-Institut | RKI](https://rki.de)  
Nordufer 20  
13353 Berlin  

---
**Zitieren**

Robert Koch-Institut (2023): SARS-CoV-2-Sequenzdaten aus Deutschland, Berlin: Zenodo. [DOI: 10.5281/zenodo.8228641](https://doi.org/10.5281/zenodo.8228641)  
 
## Informationen zum Datensatz und Entstehungskontext  

Ein zentraler Bestandteil einer erfolgreichen Erregersurveillance ist das Verständnis der Verbreitung eines Erregers sowie seiner pathogenen Eigenschaften. Hierbei stellt das Wissen über das Erregergenom eine wichtige Informationsquelle dar. So erlaubt der Nachweis von Mutationen im Genom eines Erregers, Verwandtschaftsbeziehungen zu rekonstruieren, Übertragungswege aufzudecken und Resistenzen vorherzusagen. Die Integrierte Genomische Surveillance (IGS) von SARS-CoV-2 zielt darauf ab, die Verbreitung des Virus und insbesondere von besorgniserregenden Virusvarianten in der Bevölkerung zu überwachen sowie auftretende Veränderungen des Virus genau zu beobachten. Besondere Bedeutung kommt dabei der öffentlichen Bereitstellung der genomischen Daten zu, um Wissenschaftlern in Deutschland und weltweit die Möglichkeit zu eigenständigen Analysen zu eröffnen.  

Im Rahmen der [Coronavirus-Surveillanceverordnung](https://www.gesetze-im-internet.de/corsurv/BJNR601910021.html) wurden bis zum 31.05.2023 [SARS-CoV-2 Sequenzdaten aus ganz Deutschland über den Deutschen Elektronischen Sequenzdaten-Hub (DESH) an das RKI übermittelt](https://doi.org/10.5281/zenodo.8228641). Mit Ablauf der Verordnung werden künftig Proben durch das IMSSC2 Labornetzwerk bereitgestellt und am RKI sequenziert, analysiert und hier bereitgestellt. Trotz reduzierter  Probenanzahl, wird durch die sorgfältige Auswahl der beteiligten Labore ein repräsentativer Einblick in die Viruspopluation gesichert ([Djin Ye Oh  *et al.* **2022**)](https://doi.org/10.1093/cid/ciac399). Zusätzlich werden Sequenzen vom NRZ Coronaviren an der Charité beigetragen um das IMSSC2 Netzwerk zu ergänzen. 
 
### Administrative und organisatorische Angaben

Der Datensatz "SARS-CoV-2-Sequenzdaten aus Deutschland" wird vom [Robert Koch-Institut](https://rki.de) für Forschungsarbeiten im Zusammenhang mit der SARS-CoV-2-Surveillance im IGS Projekt bereitgestellt.  

Die Datenerhebung am RKI erfolgt mit Ablauf der Coronavirus-Surveillanceverordnung über das IMSSC2 Labornetzwerk unter der Leitung von [FG 17 | Influenzaviren und weitere Viren des Respirationstraktes](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt1/FG17/fg17_node.html) und durch das [Nationale Referenzzentrum für Coronaviren](https://virologie-ccm.charite.de/diagnostik/konsiliarlaboratorium_fuer_coronaviren/).  

Im Rahmen des IGS Projektes werden die produzierten Daten von [MF1 | Genome Competence Centre](https://www.rki.de/EN/Content/Institute/DepartmentsUnits/MF/MF1/mf1_node.html) bioinformatisch analysiert. Fragen bezüglich des Projektes können am besten an [IGS@rki.de](mailto:IGS@rki.de) gerichtet werden.  

Die Koordinierung und Meldedatenerfassung wird von [FG 36 | Respiratorisch übertragbare Erkrankungen](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG36/FG36_node.html) durchgeführt.  

Die Veröffentlichung der Daten, die Datenkuration sowie das Qualitätsmanagement der (Meta-)Daten erfolgen durch das Fachgebiet [MF 4 | Fach- und Forschungsdatenmanagement](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MF/MF4/mf4_node.html) des RKI. Fragen zum Datenmanagement können an das Open Data Team des Fachgebiets MF4 gerichtet werden ([OpenData@rki.de](mailto:opendata@rki.de)).   


### Datenerhebung  

Das IMSSC2 Labornetzwerk besteht aus &gt;20 labormedizinische Einrichtungen in 13 Bundesländern, die wöchentlich zufällig ausgewähltes SARS-CoV-2-positives Probenmaterial ans RKI senden. Hier erfolgt eine Ganzgenomsequenzierung sowie weiterführende phylogenetische und genombiologische Analysen, die eine Identifizierung der häufigsten in Deutschland zirkulierenden SARS-CoV-2 Linien ermöglicht. Die Ergebnisse werden auf der Webseite des RKI und in Fachzeitschriften zeitnah publiziert und tragen zur Bewertung der aktuellen epidemiologischen Lage von COVID-19 bei. Erweitert werden die IMSSC2 Daten durch Sequenzen, die durch das Nationales Konsiliarlaboratorium für Coronaviren erhoben werden. Die Daten aus beiden Quellen werden über GitHub und andere öffentliche Datenbanken der Öffentlichkeit zur Verfügung gestellt. Ebenfalls im Datensatz enthalten sind SARS-CoV-2 Sequenzdaten aus ganz Deutschland die bis zum 31.05.2023 über den [Deutschen Elektronischen Sequenzdaten-Hub (DESH)](https://doi.org/10.5281/zenodo.8228641) an das RKI übermittelt wurden.   

### Zuordnung von Viruslinien (basierend auf Pangolin)  

Die Zuordnung bekannter Viruslinien zu den erhobenen Sequenzen erfolgt mittels [Pangolin](https://github.com/cov-lineages/pangolin). Mit Erscheinen einer neuen Version oder aktualisierter Liniendefinitionen von [Pangolin](https://github.com/cov-lineages/pangolin) erfolgt eine Neuzuordnung der Linieninformation für die gesamte Sequenzkollektion den gesamten Sequenzdatensatz. Die Informationen über die Lineage und die genutzte Pangolin Version befindet sich für jede Sequenz in den Metadaten.   

Die bereitgestellten Informationen zu den Viruslinien entsprechen dem aktuellen [PANGOLIN Lineage Format](https://cov-lineages.org/resources/pangolin/output.html). Nur die Spalte "Taxon" wurde zur einfacherer Nachnutzung in SEQUENCE.ID umbenannt. Zentral für die Verknüpfung der Entwicklungslinien mit den weiteren Daten ist die SEQUENCE.ID, die in allen drei Daten enthalten ist. [PANGOLIN Lineage Format](https://cov-lineages.org/resources/pangolin/output.html) ist bei Widersprüchen authoritativ.  

### Qualitätsmanagement  

Die Daten, die durch DESH erhoben wurden, durchliefen die Qualitätskontrolle (QC) der IGS am RKI nach veröffentlichten Kriterien (siehe: https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Qualitaetskriterien.pdf?__blob=publicationFile). Zusätzlich wird für alle Sequenzen, inklusive IMSSC2 Proben, eine bioinformatische QC der Sequenz mit [PRESIDENT: PaiRwisE Sequence IDENtiTy](https://github.com/hoelzer-lab/president) durchgeführt mit einen Identitäts-Grenzwert von 70% und einen N-Grenzwert von 20%. Die Metadaten-QC überprüft die Metadaten auf fehlerhafte Daten und Eingaben, die die weitere Verarbeitung beeinflussen würden.
Bei nicht bestehen der QC für Metadaten oder Sequenzdaten werden diese Daten nicht öffentlich  bereitgestellt, um die hohe Qualität des öffentlichen Datensatzes zu gewährleisten.  

## Aufbau und Inhalt des Datensatzes

Der Datensatz umfasst genomische Sequenzen von SARS-CoV-2-Isolaten aus ganz Deutschland und zugehörige Metadaten. Im Datensatz enthalten sind:  

* [übermittelte SARS-CoV-2-Genomsequenzen](#struktur-der-sequenzdaten)  
* [Metadaten zu den SARS-CoV-2-Genomsequenzen](#variablen-und-variablenausprägungen-metadaten)  
* Lizenz mit der Nutzungslizenz des Datensatzes  
* Metadaten Datei zum Import in Zenodo  
* Informationen über VOCs und VOIs   
* Liste von relevanten Lineages   


### SARS-CoV-2-Sequenzdaten 

Die SARS-CoV-2-Sequenzdaten werden tagesaktuell im Hauptverzeichnis unter "SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz" bereitgestellt.   

>[SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/master/SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz)  
 
#### Struktur der Sequenzdaten  

Die bereitgestellte Datei enthält Sequenzeinträge, die nach dem FASTA-Format strukturiert sind. In diesem Format beginnt jeder Eintrag mit einer kurzen Beschreibung, auch Kopfzeile oder "Description line" genannt. Diese Zeile wird durch ein ">"-Zeichen am Zeilenanfang gekennzeichnet. Nach der Kopfzeile folgt die Sequenz selbst, die eine Abfolge von Nukleinsäuren im IUB/IUPAC Format darstellt  

Jede Sequenz endet mit dem Beginn eines neuen Sequenzeintrages, gekennzeichnet durch eine neue Kopfzeile, oder, im Falle des letzten Sequenzeintrages, mit dem Ende der Datei.  

In den bereitgestellten Sequenzdaten entspricht die Kopfzeile der SEQUENCE.ID, was eine einfache Verknüpfung mit den bereitgestellten Metadaten erlaubt.  

* Kopfzeile: &gt;IMS_ID  
* Nukleinsäuresequenz: IUB/IUPAC Standard  

Daraus ergibt sich beispielhaft folgende Struktur einer .fasta-Datei:  

>&gt;IMS-101XX-CVDP-XX  
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNACCAACCAACTTTCGATCTCTT...  
>&gt;IMS-101YY-CVDP-YY   
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNACCAACTCTCGGCTGCATGCT...  

#### Komprimierung der Sequenzdaten  

Die SARS-CoV-2-Sequenzdaten werden als [xz-komprimierte](https://en.wikipedia.org/wiki/XZ_Utils) [.fasta](https://en.wikipedia.org/wiki/FASTA_format) Datei bereitgestellt. Daraus ergibt sich die Dateiendung .fasta.xz. Es werden Linux Zeilenumbrüche verwendet.  

* Zeichensatz: UTF-8  
* Komprimierung: [.xz](https://en.wikipedia.org/wiki/XZ_Utils)  
* Enthaltenes Dateiformat: [.fasta](https://de.wikipedia.org/wiki/FASTA-Format)  
* Zeilenumbrüche: Linux Zeilenumbrüche  

Die Dateien können auf gängigen Betriebssystemen, beispielsweise mit den Programmen [7zip](https://www.7-zip.org/) oder [XZ Utils](https://tukaani.org/xz/), entpackt werden. Die Komprimierung wird vorgenommen, da insbesondere die .fasta-Dateien mehrere Gigabyte (GB) groß sind.   

### Sequenzmetadaten

Die Sequenzmetadaten werden in der "SARS-CoV-2-Sequenzdaten_Deutschland.tsv.xz" bereitgestellt. Diese Daten enthalten ebenfalls die zugeordneten Viruslinien.  

>[SARS-CoV-2-Sequenzdaten_Deutschland.tsv.xz](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/master/SARS-CoV-2-Sequenzdaten_Deutschland.tsv.xz)  

#### Variablen und Werte  

In den als .tsv bereitgestellten Metadaten sind die in folgender Tabelle aufgeführte Variablen als Spalten enthalten. Zentral für die Verknüpfung der Metadaten mit den Genomsequenzen ist die SEQUENCE.ID, die in allen drei Daten enthalten ist.  


| Variable | Typ | Ausprägungen | Beschreibung |
| -------- | --- | ------------- | ------------ | 
| SEQUENCE.ID | String |   | Ein eindeutiger Identifikator der Sequenzdaten und Metadaten zusammenführt. Dieser Identifikator wird als FASTA ID in den Sequenzdaten genutzt| Text |  
| SEQUENCE. DATE_OF_SAMPLING |  Date  |  JJJJ-MM-TT | Datum der Probeentnahme im ISO 8601 Format|  
| SEQUENCE. SEQUENCING_METHOD |  String  | siehe [ena](https://ena-docs.readthedocs.io/en/latest/submit/reads/webin-cli.html#permitted-values-for-platform) | Die verwendete Sequenzierungs-Plattform auf Basis der von ENA zugelassenen Ontologie |)|  
| SEQUENCE. SEQUENCING_REASON|  String | `X`,`N`,`Y`,`A` | Grund für die Durchführung der Sequenzierung <br>`X`: (dem sequenzierenden Labor) <br>`N`: Nein (z. B. zufällige Auswahl einer in der PCR positiven Probe zur Sequenzierung)<br> `Y`: Ja, aber die Art der Mutation bzw. Variante ist (dem sequenzierenden Labor) jedoch unbekannt<br> `A`: Ja, es besteht aus der vorherigen Diagnostik Verdacht auf die Mutation/Variante <br>|  
| SEQUENCE. SAMPLE_TYPE|  String | `s001`, `s002`, ..., `s025`, `X`  | `s001 - s025`: Art der Probe <br> `X`: Unbekannt (dem sequenzierenden Labor) |  
| SEQUENCE. SEQUENCING_ LAB_SAMPLE_ID | String | |Vom Labor genutzte FASTA ID in verschlüsselter Form|  
| SEQUENCE. PUSHED_TO_DWH |Timestamp|  `JJJJ-MM-TT hh:mm:ss +TZ`  |  Eingang am RKI  |
| SEQUENCE.VERSION|String|    |  Version der Sequenz  |
| DL.ID |String|    | Identifikationsnummer  des primärdiagnostischen Labors (DL)|
| DL. POSTAL_CODE|String||Postleitzahl des primärdiagnostischen Labors (DL)|
| SL.ID|String|    | Identifikationsnummer  des sequenzierenden Labors (SL)   |
| SL. POSTAL_CODE|String||Postleitzahl des sequenzierenden Labors (SL)|
| PANGOLIN. LINEAGE_LATEST	|String|       |  Pangolin Lineage  |
| PANGOLIN. PANGOLIN_VERSION \_LATEST|String|    |  Für die Lineage-Zuordnung verwendete [Pangolin Version](#Zuordnung-von-Viruslinien-basierend-auf-Pangolin)  |

#### Formatierung der Sequenzmetadaten  

Die Sequenzmetadaten werden als [xz-komprimierte](https://en.wikipedia.org/wiki/XZ_Utils), kommaseparierte .csv-Datei bereitgestellt. Daraus ergibt sich die Dateiendung .csv.xz. Der verwendete Zeichensatz der .csv-Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Komma ",". Datumsangaben sind im ISO-8601-Standard formatiert.  

* Zeichensatz: UTF-8  
* Datumsformat: ISO 8601  
* Komprimierung: [.xz](https://en.wikipedia.org/wiki/XZ_Utils)  
* Enthaltenes Dateiformat: .tsv  
* .csv-Trennzeichen: Tab "\t"  

Die Dateien können auf gängigen Betriebssystemen, beispielsweise mit den Programmen [7zip](https://www.7-zip.org/) oder [XZ Utils](https://tukaani.org/xz/), entpackt werden. Die Komprimierung wird vorgenommen, da insbesondere die .fasta-Dateien mehrere Gigabyte (GB) groß sind.   


### Metadaten  

Zur Erhöhung der Auffindbarkeit sind die bereitgestellten Daten mit Metadaten beschrieben. Über GitHub Actions werden Metadaten an die entsprechenden Plattformen verteilt. Für jede Plattform existiert eine spezifische Metadatendatei, diese sind im Metadatenordner hinterlegt:  

> [Metadaten/](/Metadaten/)  

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/representation nachlesbar.   

> [Metadaten/zenodo.json](/Metadaten/zenodo.json)  


## Hinweise zur Nachnutzung der Daten  

Offene Forschungsdaten des RKI werden auf [GitHub.com](http://GitHub.com/), [Zenodo.org](http://Zenodo.org/) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:  

- https://github.com/robert-koch-institut  
- https://zenodo.org/communities/robertkochinstitut  
- https://edoc.rki.de/  

### Lizenz  

Der Datensatz "SARS-CoV-2-Sequenzdaten aus Deutschland" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License | CC-BY ](https://creativecommons.org/licenses/by/4.0/deed.de).  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede Person hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](/LICENSE) bzw. [LIZENZ](/LIZENZ) Datei des Datensatzes.
