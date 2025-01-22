Datensatzdokumentation  
# SARS-CoV-2-Sequenzdaten aus Deutschland  
<br>

[**Robert Koch-Institut | RKI**](https://rki.de)  
Nordufer 20  
13353 Berlin  

<br>

---

**Zitieren**  
<!-- CITATION_START: {"citation_style": "apa"} -->
Robert Koch-Institut. (2025). SARS-CoV-2 Sequenzdaten aus Deutschland [Data set]. Zenodo. https://doi.org/10.5281/zenodo.14652795
<!-- CITATION_END -->

 
## Informationen zum Datensatz und Entstehungskontext  

Ein zentraler Bestandteil einer erfolgreichen Erregersurveillance ist das Verständnis der Verbreitung eines Erregers sowie seiner pathogenen Eigenschaften. Hierbei stellt das Wissen über das Erregergenom eine wichtige Informationsquelle dar. So erlaubt der Nachweis von Mutationen im Genom eines Erregers, Verwandtschaftsbeziehungen zu rekonstruieren, Übertragungswege aufzudecken und Resistenzen vorherzusagen. Die Integrierte Genomische Surveillance (IGS) von SARS-CoV-2 zielt darauf ab, die Verbreitung des Virus und insbesondere von besorgniserregenden Virusvarianten in der Bevölkerung zu überwachen sowie auftretende Veränderungen des Virus genau zu beobachten. Besondere Bedeutung kommt dabei der öffentlichen Bereitstellung der genomischen Daten zu, um Wissenschaftlern in Deutschland und weltweit die Möglichkeit zu eigenständigen Analysen zu eröffnen.  

Im Rahmen der [Coronavirus-Surveillanceverordnung](https://www.gesetze-im-internet.de/corsurv/BJNR601910021.html) wurden bis zum 31.05.2023 [SARS-CoV-2 Sequenzdaten aus ganz Deutschland über den Deutschen Elektronischen Sequenzdaten-Hub (DESH) an das RKI übermittelt](https://doi.org/10.5281/zenodo.7992536). Mit Ablauf der Verordnung werden künftig Proben durch das IMSSC2 Labornetzwerk bereitgestellt und am RKI sequenziert, analysiert und hier bereitgestellt. Trotz reduzierter  Probenanzahl, wird durch die sorgfältige Auswahl der beteiligten Labore ein repräsentativer Einblick in die Viruspopluation gesichert ([Djin Ye Oh  *et al.* **2022**)](https://doi.org/10.1093/cid/ciac399). Zusätzlich werden Sequenzen vom NRZ Coronaviren an der Charité beigetragen um das IMSSC2 Netzwerk zu ergänzen. 
 
### Administrative und organisatorische Angaben

Der Datensatz "SARS-CoV-2-Sequenzdaten aus Deutschland" wird vom [Robert Koch-Institut](https://rki.de) für Forschungsarbeiten im Zusammenhang mit der SARS-CoV-2-Surveillance im IGS Projekt bereitgestellt.  

Die Datenerhebung am RKI erfolgt mit Ablauf der Coronavirus-Surveillanceverordnung über das IMSSC2 Labornetzwerk unter der Leitung von [FG 17 | Influenzaviren und weitere Viren des Respirationstraktes](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt1/FG17/fg17_node.html) und durch das [Nationale Referenzzentrum für Coronaviren](https://virologie-ccm.charite.de/diagnostik/konsiliarlaboratorium_fuer_coronaviren/).  

Im Rahmen des IGS Projektes werden die produzierten Daten von [MF1 | Genome Competence Centre](https://www.rki.de/EN/Content/Institute/DepartmentsUnits/MF/MF1/mf1_node.html) bioinformatisch analysiert. Fragen bezüglich des Projektes können am besten an [IGS@rki.de](mailto:IGS@rki.de) gerichtet werden.  

Die Koordinierung und Meldedatenerfassung wird von [FG 36 | Respiratorisch übertragbare Erkrankungen](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG36/FG36_node.html) durchgeführt.  

Die Veröffentlichung der Daten, die Datenkuration sowie das Qualitätsmanagement der (Meta-)Daten erfolgen durch das Fachgebiet [MF 4 | Fach- und Forschungsdatenmanagement](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MFI/MF4/mf4_node.html) des RKI. Fragen zum Datenmanagement können an das Open Data Team des Fachgebiets MF4 gerichtet werden ([OpenData@rki.de](mailto:opendata@rki.de)).   


### Datenerhebung  

Das IMSSC2 Labornetzwerk besteht aus ~20 labormedizinischen Einrichtungen in 13 Bundesländern, die wöchentlich zufällig ausgewähltes SARS-CoV-2-positives Probenmaterial ans RKI senden. Hier erfolgt eine Ganzgenomsequenzierung sowie weiterführende phylogenetische und genombiologische Analysen, die eine Identifizierung der häufigsten in Deutschland zirkulierenden SARS-CoV-2 Linien ermöglicht. Die Ergebnisse werden auf der Webseite des RKI und in Fachzeitschriften zeitnah publiziert und tragen zur Bewertung der aktuellen epidemiologischen Lage von COVID-19 bei. Erweitert werden die IMSSC2 Daten durch Sequenzen, die durch das Nationales Konsiliarlaboratorium für Coronaviren erhoben werden. Die Daten aus beiden Quellen werden über GitHub und andere öffentliche Datenbanken der Öffentlichkeit zur Verfügung gestellt. Ebenfalls im Datensatz enthalten sind SARS-CoV-2 Sequenzdaten aus ganz Deutschland die bis zum 31.05.2023 über den [Deutschen Elektronischen Sequenzdaten-Hub (DESH)](https://doi.org/10.5281/zenodo.7992536) an das RKI übermittelt wurden.   

### Zuordnung von Viruslinien basierend auf Pangolin

Die Zuordnung bekannter Viruslinien zu den erhobenen Sequenzen erfolgt mittels [Pangolin](https://github.com/cov-lineages/pangolin). Mit Erscheinen einer neuen Version oder aktualisierter Liniendefinitionen von [Pangolin](https://github.com/cov-lineages/pangolin) erfolgt eine Neuzuordnung der Linieninformation für die gesamte Sequenzkollektion den gesamten Sequenzdatensatz. Die Informationen über die Lineage und die genutzte Pangolin Version befindet sich für jede Sequenz in den Metadaten.   

Die bereitgestellten Informationen zu den Viruslinien entsprechen dem aktuellen [PANGOLIN Lineage Format](https://cov-lineages.org/resources/pangolin/output.html). Nur die Spalte "Taxon" wurde zur einfacherer Nachnutzung in SEQUENCE.ID umbenannt. Zentral für die Verknüpfung der Entwicklungslinien mit den weiteren Daten ist die SEQUENCE.ID, die in allen drei Daten enthalten ist. [PANGOLIN Lineage Format](https://cov-lineages.org/resources/pangolin/output.html) ist bei Widersprüchen authoritativ.  

### Qualitätsmanagement  

Die Daten, die durch DESH erhoben wurden, durchliefen die Qualitätskontrolle (QC) der IGS am RKI nach veröffentlichten Kriterien (siehe: [rki.de - DESH Qualitaetskriterien.pdf](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Qualitaetskriterien.pdf?__blob=publicationFile)). Zusätzlich wird für alle Sequenzen, inklusive IMSSC2 Proben, eine bioinformatische QC der Sequenz mit [PRESIDENT: PaiRwisE Sequence IDENtiTy](https://github.com/hoelzer-lab/president) durchgeführt mit einen Identitäts-Grenzwert von 70% und einen N-Grenzwert von 20%. Die Metadaten-QC überprüft die Metadaten auf fehlerhafte Daten und Eingaben, die die weitere Verarbeitung beeinflussen würden.
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

Die SARS-CoV-2-Sequenzdaten werden im Hauptverzeichnis unter "SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz" bereitgestellt.   

>[SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/SARS-CoV-2-Sequenzdaten_Deutschland.fasta.xz)  
 
#### Struktur der Sequenzdaten  

Die bereitgestellte Datei enthält Sequenzeinträge, die nach dem FASTA-Format strukturiert sind. In diesem Format beginnt jeder Eintrag mit einer kurzen Beschreibung, auch Kopfzeile oder "description line" genannt. Diese Zeile wird durch ein ">"-Zeichen am Zeilenanfang gekennzeichnet. Nach der Kopfzeile folgt die Sequenz selbst, die eine Abfolge von Nukleinsäuren im IUB/IUPAC Format darstellt  

Jede Sequenz endet mit dem Beginn eines neuen Sequenzeintrages, gekennzeichnet durch eine neue Kopfzeile, oder, im Falle des letzten Sequenzeintrages, mit dem Ende der Datei.  

In den bereitgestellten Sequenzdaten entspricht die Kopfzeile der SEQUENCE.ID, was eine einfache Verknüpfung mit den bereitgestellten Metadaten erlaubt.  

* Kopfzeile: ">\<IGS_ID\> version=\<version\>"
* Nukleinsäuresequenz: IUB/IUPAC Standard  

Daraus ergibt sich beispielhaft folgende Struktur einer .fasta-Datei:  

```fasta
>IGS-101XX-CVDP-XX version=1
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNACCAACCAACTTTCGATCTCTT...  
>IGS-101YY-CVDP-YY version=0
NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNACCAACTCTCGGCTGCATGCT...  
```
#### Komprimierung der Sequenzdaten   

Die SARS-CoV-2-Sequenzdaten werden als [xz-komprimierte](https://en.wikipedia.org/wiki/XZ_Utils) [.fasta](https://en.wikipedia.org/wiki/FASTA_format) Datei bereitgestellt. Daraus ergibt sich die Dateiendung .fasta.xz. Es werden Linux Zeilenumbrüche verwendet.  

* Zeichensatz: UTF-8  
* Komprimierung: [.xz](https://en.wikipedia.org/wiki/XZ_Utils)  
* Enthaltenes Dateiformat: [.fasta](https://de.wikipedia.org/wiki/FASTA-Format)  
* Zeilenumbrüche: Linux Zeilenumbrüche  

Die Dateien können auf gängigen Betriebssystemen, beispielsweise mit den Programmen [7zip](https://www.7-zip.org/) oder [XZ Utils](https://tukaani.org/xz/), entpackt werden. Die Komprimierung wird vorgenommen, da insbesondere die .fasta-Dateien mehrere Gigabyte (GB) groß sind.   

### Sequenzmetadaten

Die Sequenzmetadaten werden in der "SARS-CoV-2-Sequenzdaten_Deutschland.tsv.xz" bereitgestellt. Diese Daten enthalten ebenfalls die zugeordneten Viruslinien.  

>[SARS-CoV-2-Sequenzdaten_Deutschland.tsv.xz](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/SARS-CoV-2-Sequenzdaten_Deutschland.tsv.xz)  

#### Variablen und Werte  

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "SARS-CoV-2-Sequenzdaten_Deutschland", "lang": "de"} -->

Die Datei [SARS-CoV-2-Sequenzdaten_Deutschland.tsv](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/SARS-CoV-2-Sequenzdaten_Deutschland.tsv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_SARS-CoV-2-Sequenzdaten_Deutschland.json](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/schemas/tableschema_SARS-CoV-2-Sequenzdaten_Deutschland.json) hinterlegt:
> [tableschema_SARS-CoV-2-Sequenzdaten_Deutschland.json](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/schemas/tableschema_SARS-CoV-2-Sequenzdaten_Deutschland.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable                              | Typ     | Ausprägungen                                      | Beschreibung                                                                                                                                                                                                                                                                                                              |
|:--------------------------------------|:--------|:--------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| igs_id                                | string  |                                                   | Ein eindeutiger Identifikator der Sequenzdaten und Metadaten zusammenführt. Dieser Identifikator wird als Teil der FASTA ID in den Sequenzdaten genutzt (Beispiel: `IGS-10099-CVDP-01A2C74B-54A8-47B1-B7E4-6562C6231234`).                                                                                                |
| date_of_sampling                      | date    | Format: `YYYY-MM-DDTHH:MM:SS`                     | Datum der Probeentnahme im ISO 8601 Format ohne Zeitzone (d.h. `YYYY-MM-DDThh:mm:ss`)                                                                                                                                                                                                                                     |
| sequencing_platform                   | string  |                                                   | Die verwendete Sequenzierungs-Plattform auf Basis der von ENA zugelassenen Ontologie (siehe [ena](https://ena-docs.readthedocs.io/en/latest/submit/reads/webin-cli.html#permitted-values-for-platform)).                                                                                                                  |
| sequencing_reason                     | string  | Werte: `random`, `requested`, `clinical`, `other` | Grund für die Durchführung der Sequenzierung `random`: Die Probe  wurde randomisiert genommen. `requested`: Die Probe wurde aufgrund von Bedenken/Verdacht auf eine neue Variante oder Vergleichbares genommen. `clinical`: Die Probe kommt aus einem klinischem Umfeld. `other`: Der Grund it keiner der oben genannten. |
| isolation_source                      | string  |                                                   | [DEMIS Vokabular](https://simplifier.net/rki.demis.laboratory/materialcvdp)                                                                                                                                                                                                                                               |
| lab_sequence_id                       | string  |                                                   | Vom Labor genutzte FASTA ID in verschlüsselter Form                                                                                                                                                                                                                                                                       |
| date_of_submission                    | date    | Format: `YYYY-MM-DDTHH:MM:SS`                     | Datum des Eingangs des Genoms am RKI im ISO 8601 Format ohne Zeitzone  (d.h. `YYYY-MM-DDThh:mm:ss`)                                                                                                                                                                                                                       |
| version                               | integer | Werte: `≥0`                                       | Version der Sequenz startend mit 0                                                                                                                                                                                                                                                                                        |
| prime_diagnostic_lab.demis_lab_<br>id | string  |                                                   | Identifikationsnummer  des primärdiagnostischen Labors (z.B. `DEMIS-10099`)                                                                                                                                                                                                                                               |
| prime_diagnostic_lab.postal_<br>code  | string  |                                                   | Postleitzahl des primärdiagnostischen Labors (z.B. `50858`)                                                                                                                                                                                                                                                               |
| sequencing_lab.demis_lab_id           | string  |                                                   | Identifikationsnummer  des sequenzierenden Labors (z.B. `DEMIS-10099`)                                                                                                                                                                                                                                                    |
| sequencing_lab.postal_code            | string  |                                                   | Postleitzahl des sequenzierenden Labors (z.B. `50858`)                                                                                                                                                                                                                                                                    |
| lineages                              | string  |                                                   | Pangolin Zuordnung im JSON-Format (z.B. `[{'method': 'PANGOLIN_LATEST', 'classification_version': 'PUSHER-v1.28.1', 'tool_version': '4.3', 'lineage': 'BA.2', '@qc_notes': 'Ambiguous_content:0.02', '@is_designated': False, '@qc_status': 'pass', '@conflict': 0.0, '@note': 'Usher placements: BA.2(1/1)'}]`)          |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "SARS-CoV-2-Entwicklungslinien_berichtet", "lang": "de"} -->

Die Datei [SARS-CoV-2-Entwicklungslinien_berichtet.tsv](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/SARS-CoV-2-Entwicklungslinien_berichtet.tsv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_SARS-CoV-2-Entwicklungslinien_berichtet.json](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/schemas/tableschema_SARS-CoV-2-Entwicklungslinien_berichtet.json) hinterlegt:
> [tableschema_SARS-CoV-2-Entwicklungslinien_berichtet.json](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/schemas/tableschema_SARS-CoV-2-Entwicklungslinien_berichtet.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable              | Typ    | Ausprägungen   | Beschreibung                                                                  |
|:----------------------|:-------|:---------------|:------------------------------------------------------------------------------|
| LINEAGE               | string |                | Zugewiesene Pangolin Lineage                                                  |
| WHO_LABEL             | string |                | Name der Virusvariante, der  von der World Health Organisation vergeben wurde |
| CONTRIBUTING_LINEAGES | string |                | Pangolin Lineages, die von der Lineage abstammen                              |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "SARS-CoV-2-Entwicklungslinien_zu_Varianten", "lang": "de"} -->

Die Datei [SARS-CoV-2-Entwicklungslinien_zu_Varianten.tsv](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/SARS-CoV-2-Entwicklungslinien_zu_Varianten.tsv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_SARS-CoV-2-Entwicklungslinien_zu_Varianten.json](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/schemas/tableschema_SARS-CoV-2-Entwicklungslinien_zu_Varianten.json) hinterlegt:
> [tableschema_SARS-CoV-2-Entwicklungslinien_zu_Varianten.json](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/schemas/tableschema_SARS-CoV-2-Entwicklungslinien_zu_Varianten.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable              | Typ    | Ausprägungen        | Beschreibung                                                                            |
|:----------------------|:-------|:--------------------|:----------------------------------------------------------------------------------------|
| LINEAGE               | string |                     | Zugewiesene Pangolin Lineage                                                            |
| WHO_LABEL             | string |                     | Name der Virusvariante, der  von der World Health Organisation vergeben wurde           |
| CONTRIBUTING_LINEAGES | string |                     | Pangolin Lineages, die von der Lineage abstammen                                        |
| COLOR                 | any    |                     | Veraltete Variable. Ist nicht mehr relevant und wird persepektivisch entfernt.          |
| variant_category      | string | Werte: `VOC`, `VOI` | WHO Einstufung der Variante als VOC (variant of concern) oder VOI (variant of interest) |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->


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

> [Metadaten/](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/)    

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar.   
 
> [Metadaten/zenodo.json](https://github.com/robert-koch-institut/SARS-CoV-2-Sequenzdaten_aus_Deutschland/blob/main/Metadaten/zenodo.json)  

In der zenodo.json ist neben der Publikationsdatum (`"publication_date"`) auch der Datenstand in folgendem Format enthalten (Beispiel):  

```
  "dates": [
    {
      "start": "2023-09-11T15:00:21+02:00",
      "end": "2023-09-11T15:00:21+02:00",
      "type": "Created",
      "description": "Date when the Dataset was created"
    }
  ],
```    

## Hinweise zur Nachnutzung der Daten  

Offene Forschungsdaten des RKI werden auf [Zenodo.org](http://Zenodo.org/), [GitHub.com](http://GitHub.com/), [OpenCoDE](https://gitlab.opencode.de) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:  

- https://zenodo.org/communities/robertkochinstitut  
- https://github.com/robert-koch-institut  
- https://gitlab.opencode.de/robert-koch-institut  
- https://edoc.rki.de/  
 
### Lizenz  

Der Datensatz "SARS-CoV-2-Sequenzdaten aus Deutschland" ist lizenziert unter  der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede Person hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/LICENSE) bzw. [LIZENZ](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/LIZENZ) Datei des Datensatzes.  
