<!--
author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk ()

email: c.hastik@igsd-ev.de

email: g.schwenk@igsd-ev.de

version:  v1

language: DE

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/liascript-oers/refs/heads/main/resources/SODa-Logo_full.svg
link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODa_WissKI-ISWC25Bits/refs/heads/main/soda.css

license: CC BY 4.0

comment: Dieser Text erscheint als Info innerhalb der Liascript-Module oben rechts hinter dem (i) und sollte den Inhalt des Moduls kurz beschreiben. Vorschlag: Mirco-Content zum Lernziel "Lernende können FAIR-Prinzipien erläutern". Dieses Modul ist Teil eines Einführungskurses zum Forschungsdatenmanagement, der von “OER.Net UAG FDM-Basiskurs” auf Grundlage der Lernzielmatrix zum FDM entwickelt wurde. Der Basiskurs entwickelt das Konzept der EduBricks weiter und ist als “Arbeitsgruppe 3: Einbettung und Vernetzung des modularen und skalierbaren Konzeptes” zudem Teil der NFDI-Sektion Education and Training.

title: Template für die Erarbeitung eines Micro-Contents anhand eines Lernziels für generischen FDM-Basiskurs

description: Dieses Template wurde als Vorlage für die Entwicklung von Microlearning-Content zum Themenbereich Forschungsdatenmanagement (FDM) in Orientierung an Lernzielen der [Lernzielmatrix zum Forschungsdatenmanagement (FDM)](https://zenodo.org/records/15025246) entwickelt.

keywords: FDM, Forschungsdatenmanagement, Forschungsdaten, Lernziel, Micro-Content

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: noch unveröffentlicht

LearningResourceType: SODa How-to-Tutorial

-->


# SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 1: **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Einheit 1: **Willkommen und Ablauf**  

**Dauer:** ~ 15 Min.

Lernziel

die Infrastruktur WissKi benennen (neu)
---

## Begrüßung

> Willkommen zu **SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
> 
> Dieses How-to-Tutorial bietet eine praxisorientierte Einführung in die **Arbeit und Analyse mit strukturierten Forschungsdaten** – von der ersten Beschreibung eines Sammlungsobjekts bis zur semantisch belastbaren Modellstruktur.
>
> Im **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären** wir die konzeptionelle Grundlage für ein Datenmodell erarbeitet:
>
> Objektdaten und Kontextinformationen werden analysiert, Kernentitäten, Ereignisse und Beziehungen identifiziert und diese Schritt für Schritt in eine ontologiebasierte Struktur (z. B. mit CIDOC CRM) übersetzt.
>
> Ziel ist es, die fachliche Domänenlogik so zu klären, dass sie später konsistent modelliert, implementiert und abfragbar wird.
>
> Das Modul ist als **How-to-Tutorial** für die **Wissenschaftliche Kommunikationsiunfrastruktur WissKI** konzipiert und folgt dem Prinzip Learning by Doing:
>
> An einem Beispiel wird aus der Sammlungsperspektive eine Modellperspektive erarbeitet und so die Grundlage für die Visualisierung in einem Diagramm und die spätere Umsetzung in WissKI geschaffen.
>
> In den weiterführenden Einheiten wird dieser anleitende Ansatz um selbstgesteuerte Lernphasen ergänzt, in denen das eigene Wissen vertieft, eigene Forschungsdaten modelliert und die erlernten Methoden auf individuelle Forschungskontexte anwendendet werden können.

---

## Ablauf des Moduls


**Modul 1: 90 Min.**


| Einheit | Inhalt | Zeit |
|--------|--------|------|
| 1 | Willkommen und Ablauf | 15 Min. |
| 2 | Analyse-Workflow: Von der Forschungsfrage zur Graphenstruktur | 5 Min. |
| 3 | WissKI Kurzeinführung | 10 Min. |
| 4 | Strukturierte Daten mit CIDOC CRM | 15 Min. |
| 5 | Domänenanalyse: Kernentitäten, Ereignisse, Kontext - vom Objekt zur Hypothese | 20 Min. |
| 6 | Modellierung in Protégé: Konsistenzcheck und Erweiterungsstrategien | 10 Min. |
| 7 | Reflexion: Welche Analysen sind möglich, welche nicht? | 5 Min. |

---

## Lernziele

Lernende können... 

* für das SAMMLUNGSBEZOGENE Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID 01_010_0190) 
* Begriff Ontologie erläutern (LZ-ID 03_007_0775)
* Aspekte von Ontologien benennen. (LZ-ID 03_007_0776)
* Methoden zur Entwicklung von Ontologien benennen (LZ-ID 03_007_0784)
* einen Workflow für die Datendokumentation entwickeln (LZ-ID 03_001_0616 neu -modellierung anwenden) 
* die fünf Stufen des 5-Sterne-Modells für offene Daten benennen. (LZ-ID 01_008_0158)
* FAIR Prinzipien benennen. (LZ-ID 01_007_0117)
* geeignete Technologien zur Unterstützung der Anwendung der FAIR-Prinzipien benennen. (LZ-ID 01_007_0121)
* die spezifischen Funktionen und Anwendungsbereiche (inter)nationaler IT-Infrastrukturen = der Wissenschaftlichenh Kommunikatiojnsinfrastruktur WissKI = benennen und erläutern. (01_010_0191 und _0192)
* Werkzeuge (WissKI Pathbuilder) zur Entwicklung von Ontologien bennenen und erläutern (neu? siehe Methoden zur Entwicklung von Ontologien benennen und erläutern LZ-ID 03_007_0784 und _0785)
* das Prinzip der ereigniszentrierten Modellierung mit CIDOC CRM erklären (neu ? siehe unter Anleitung Methoden zur Entwicklung von Ontologien anwenden LZ-ID 03_007_0786 oder Aspekte von Ontologien benennen LZ-ID 03_007_0776)
* Relevanz und Nutzen von WissKI benennen (neu ? Leistungsfähigkeit und Effizienz von IT-Infrastrukturen für das SAMMLUNGSBEZOGENE Forschungsdatenmanagement (FDM) ) analysieren und bewerten (?) 01_010_0195 und _0196)
* Ontologie zur Beschreibung von Ressourcen bennen, erläutern, anwenden. 03_007_0778, 03_007_0779, 03_007_0780
* Modellierungsstrategie(n) benennen. (neu ? oder eigenständig Methoden zur Entwicklung von Ontologien anwenden LZ-ID 03_007_0787)
* Scope Notes als Entscheidungsgrundlage anwenden. (neu eigenständig Methoden zur Entwicklung von Ontologien anwenden LZ-ID 03_007_0787))
* Relevanz und Nutzen von CIDOC CRM benennen und erläutern (neu es gibt nur die Relevanz von Ontologien erläutern LZ-ID 03_007_0777)
* Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) benenen und erläutern (neu - Thema Datendokumentation oder Metadaten oder Datenqualität?)
* Datentyp-Eigenschaften in CIDOC CRM benennen (und erläuetern) (neu? Kategorien von Datentypen benennen und erläutern LZ-ID 02_002_0212 und _0213)
* Software zur Erstellung von Ontologien benennen und anwenden (neu es gibt nur Softwares zur Evaluation von Ontologien)


---

## Voraussetzung

Folgende Grundkenntnisse werden vorausgesetzt:


---

## Erwartungsabfrage

Interaktive Mentimeter-Umfrage zur Erfassung von Erwartungen, Vorkenntnissen und bisherigen Erfahrungen mit WissKI und semantischer Datenmodellierung.

<img src="../img/Erwartungsabfrage.png" alt="Mentimeter Umfrage" style="width:400px; height:auto;">

### Fragen 

* Was erwarten Sie von diesem Tutorial?
* Welche Datenkompetenzen bringen Sie mit?
* Welche Erfahrungen mit WissKI bringen Sie mit?
* Welche Erfahrungen haben Sie im Bereich semantische Datenmodellierung?
* Mit welchen Herausforderungen waren Sie bisher bei der Erstellung von Domänenontologien konfrontiert?

---

## Speed-Dating (Alternativ)

**Ziel:** 

* Aktivierung
* Austausch
* Vernetzung.

**Ablauf:**

1. Bitte stehen Sie alle auf.
2. Finden Sie eine Person, die Sie noch nicht kennen.
3. Interviewen Sie sich gegenseitig — je 30 Sekunden pro InterviewerIn.
4. Wechseln Sie nach jeder Runde die Partner:innen.

**Fragen:**

1. Wie heißen Sie und woher kommen Sie?
2. Welche Sprachen sprechen Sie?
3. Nennen Sie einen Fun Fact über sich.

**Beispiele für Fun Facts:**

- Sie haben versucht, Ihre Küche in OWL zu modellieren.
- Ihr Haustier heißt *SPARQL*.

- Sie sammeln japanischen Whisky oder Pokémon-Karten.


