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

Modul 2: **Vom Diagramm zu Pfaden – erläutern und anwenden**

Einheit 1: **Ablauf und Warm-up**  

**Dauer:** ~ 15 Min.

---

## Begrüßung


> Willkommen zu **SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
> 
> Dieses How-to-Tutorial bietet eine praxisorientierte Einführung in die **Arbeit und Analyse mit strukturierten Forschungsdaten** – von der ersten Beschreibung eines Sammlungsobjekts bis zur semantisch belastbaren Modellstruktur (**Datenmodell am Beispiel entwickeln und implementieren**).
>
> Im Modul 2: **Vom Diagramm zu Pfaden – erläutern und anwenden** wird das entworfene Datenmodell in Modul 1 in ein CIDOC CRM-basierte Pfadstruktur überführt:
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

## Ablauf des Moduls


**Modul 2: 90 Min.**


| Einheit | Inhalt | Zeit |
|--------|--------|------|
| 1 | Willkommen & Warm-up | 15 Min. |
| 2 | Visualisierung eines Domänenontologie-Diagramms | 25 Min. |
| 3 | WissKI Pathbuilder-Datei erzeugen | 25 Min. |
| 4 | Weiterführende Modulthemen| 5 Min. |
| 5 | Austausch & Feedback | 15 Min. |


---

## Lernziele

Lernende können... 

* Draw.io zur Repräsentation der Domänenontologie unter Anleitung anwenden (LZ-ID 03\dataModeling_soda0001).
* CIDOC CRM zur Beschreibung eigener Resourcen anwenden (LZ-ID 03\dataModeling_soda0002)
* Attributwerte an vordefinierten Klassen benennen und anwenden (LZ-ID 03\dataModeling_soda0002).
* Domänenontologie-Diagramm als XML-Datei aus Draw.io exportieren (LZ-ID 03\dataModeling_soda0003).
* das Konvertierungstool "gnm_service: Draw.io diagrams to WissKI pathbuilders" nutzen (LZ-ID 03\dataModeling_soda0004).
* eine Pathbuilder-XML-Datei in WissKI importieren (LZ-ID 03\dataModeling_soda0005).
* Gruppen und Pfade im Pathbuilder überprüfen (LZ-ID 03\dataModeling_soda0006).

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
