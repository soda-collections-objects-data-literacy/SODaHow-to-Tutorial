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

Modul 2: **Vom Diagramm zu Pfaden – erläutern, validieren und anwenden**

Einheit 1: **Ablauf und Zielsetzung**  

**Dauer:** ~ 15 Min.

Lernziel

* für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID SODa_01_010_0190a) 

---

## Begrüßung


> Willkommen zu **SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
> 
> Dieses How-to-Tutorial bietet eine praxisorientierte Einführung in die **Arbeit und Analyse mit strukturierten Forschungsdaten** – von der ersten Beschreibung eines Sammlungsobjekts bis zur semantisch belastbaren Modellstruktur (**Datenmodell am Beispiel entwickeln und implementieren**).
>
> Im Modul 2: **Vom Diagramm zu Pfaden – erläutern, validieren und anwenden** wird das entworfene Datenmodell in Modul 1 in ein CIDOC CRM-basierte Pfadstruktur überführt:
>
> Aus dem in *Draw.io* erstellten semantischen Modell wird eine *WissKI Pathbuilder*-Datei generiert. Auf diese Weise wird die konzeptionelle Domänenontologie in eine in WissKI nutzbare Graphstruktur überführt, die als Grundlage für die Arbeit und Analyse graphbasierten Forschungsdaten dient.  
>
> Ziel ist es, die fachliche Domänenlogik so präzise abzubilden, dass das Datenmodell konsistent umgesetzt, nachvollziehbar erweitert und gezielt abgefragt werden kann.
>
> Das Modul ist als **How-to-Tutorial** für die **Wissenschaftliche Kommunikationsiunfrastruktur WissKI** konzipiert und folgt dem Prinzip Learning by Doing:
>
> An einem Beispiel wird aus der Sammlungsperspektive eine Modellperspektive erarbeitet und so die Grundlage für die Visualisierung in einem Diagramm und die spätere Umsetzung in WissKI geschaffen.
>
> In den weiterführenden Einheiten wird dieser anleitende Ansatz um selbstgesteuerte Lernphasen ergänzt, in denen das eigene Wissen vertieft, eigene Forschungsdaten modelliert und die erlernten Methoden auf individuelle Forschungskontexte anwendendet werden können.

---

## Zielsetzung des Moduls

In Modul 2 wird die konzeptionelle Basis schrittweise eine Domänenlogik als Grundlage für das sammlungsbezogene Datenmanagement und die -verwaltung in WissKI überführt.
 

* Die Domänenlogik wird als semantisches Modell mit Pfaden in Draw.io visualisiert.
* Die Visualisierung wird auf syntaktische Gültigkeit anhand CIDCO-CRM überprüft und in ein nachnutzbares Dateiformat überführt.
* Die domänenspezifische Ontologiestruktur wird in die WissKI importiert, dort validiert und für die Analysen vorbereitet.

---

## Ablauf des Moduls


**Modul 2: 90 Min.**


| Einheit | Inhalt | Zeit |
|--------|--------|------|
| 1 | Ablauf und Zielsetzung | 15 Min. |
| 2 | Visualisierung der Domänenontologie in Draw.io | 25 Min. |
| 3 | Automatische Pfadgenerierung: Konsistenz prüfen und WissKI Pathbuilder-Datei erzeugen | 25 Min. |
| 4 | Validierung im Pathbuilder und erste Analyseabfragen | 5 Min. |
| 5 | Transfer und Nächste Schritte zur Datenanalyse | 15 Min. |


---

## Lernziele

Lernende können... 


* für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID SODa_01_010_0190a) 
* Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa_03_007_0811)
* Software zur Visualisierung einer Domänenontologie benennen und erläutern.(LZ-ID SODa_03_007_0812 und LZ-ID SODa_03_007_0813)
* Nutzen einer Software zur Visualisierung einer Domänenontologie benennen.(LZ-ID SODa_03_007_0814) 
* Software zur Visualisierung einer Domänenontologie unter Anleitung anwenden. (LZ-ID SODa_03_007_0815)
* Methoden zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware benennen. (LZ-ID SODa_03_007_0784b)
* Methoden zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware anwenden. (LZ-ID SODa_007_0816)
* Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa_03_007_0780a)
* Attributwerte an vordefinierten Klassen der Domänenontologie in einer Visualisierungssoftware anwenden. (LZ-ID SODa_03_007_0817)
* WissKI Pathbuilder als Werkzeug zur Entwicklung von Ontologien erläutern. (LZ-ID SODa_03_007_0804)
* unter Anleitung die Datenkonvertierung einer Visualisierungssoftware in ein nachnutzbares Dateiformat anwenden. (LZ-ID SODa_02_005_0298a)
* unter Anleitung ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung benennen und anwenden. (LZ-ID SODa_02_005_0317 und LZ-ID SODa_02_005_0318)
* unter Anleitung WissKI Pathbuilder als Werkzeug zum Import einer domänenspezifischen Ontologiestruktur (Pathbuilder-XML-Datei im WissKI-Pathbuilder) anwenden. (LZ-ID SODa_03_007_0818)
* unter Anleitung die importierte domänenspezifische Ontologiestruktur im WissKI-Pathbuilder analysieren. (LZ-ID SODa_03_007_0819)
* es fehlen noch zwei Lernziele in M2E4 


---

## Voraussetzung

Folgende Grundkenntnisse werden vorausgesetzt:

* WissKI und die Basisfunktionen sind grundlegend bekannt.
* Es gibt erst Erfahrung in der konzeptuellen Modellierung von Domänenontologien.
* Mit CIDOC CRM und Protegé wurde bereits gearbeitet.

Eine Einführung in diese Themen bietet Modul 1.

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
