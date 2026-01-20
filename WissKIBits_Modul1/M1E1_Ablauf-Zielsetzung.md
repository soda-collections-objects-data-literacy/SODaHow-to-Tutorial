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

* für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID SODa_01_010_0190a) 

---

## Begrüßung

> Willkommen zu **SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
> 
> Dieses How-to-Tutorial bietet eine praxisorientierte Einführung in die **Arbeit und Analyse mit strukturierten Forschungsdaten** – von der ersten Beschreibung eines Sammlungsobjekts bis zur semantisch belastbaren Modellstruktur. Hierfür wird ein**Datenmodell am Beispiel entwickelt und implementiert**.
>
> Im Modul 1 **"Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären"** wird die konzeptionelle Grundlage für ein Datenmodell erarbeitet:
>
> Objektdaten und Kontextinformationen werden analysiert, Kernentitäten, Ereignisse und Beziehungen identifiziert und diese Schritt für Schritt in eine ontologiebasierte Struktur (z. B. mit CIDOC CRM) übersetzt.
>
> Ziel ist es, die fachliche Domänenlogik so zu erfassen, dass sie später konsistent modelliert, implementiert und abfragbar ist.
>
> Das Modul ist als **How-to-Tutorial** für die **Wissenschaftliche Kommunikationsiunfrastruktur WissKI** konzipiert und folgt dem Prinzip Learning by Doing:
>
> An einem Beispiel wird aus der Sammlungsperspektive eine Modellperspektive erarbeitet und so die Grundlage für die Visualisierung als Diagramm und die spätere Umsetzung in WissKI geschaffen.
>
> In den weiterführenden Einheiten wird dieser anleitende Ansatz um selbstgesteuerte Lernphasen ergänzt, in denen das eigene Wissen vertieft, eigene Forschungsdaten modelliert und die erlernten Methoden auf individuelle Forschungskontexte anwendendet werden können.

---

## Zielsetzung des Moduls

In Modul 1 wird die konzeptionelle Basis geschaffen. Aus der Sammlungsperspektive entsteht eine Modellperspektive.

* Objektdaten & deren Kontext werden analysiert.
* Kernentitäten von Objektdaten werden identifiziert und um Ereignisse und Beziehungen kontextualisiert.
* Daraus entsteht schrittweise in eine ontologiebasierte Domänenstruktur mit CIDOC CRM.
* Diese Domänenlogik wird visualisiert und dient als Grundlage für das sammlungsbezogene Datenmanagement und die -verwaltung in WissKI.

---

## Ablauf des Moduls

**Modul 1: 90 Min.**


| Einheit | Inhalt | Dauer |
|--------|--------|------|
| 1 | Ablauf und Zielsetzung | 15 Min. |
| 2 | Analyse-Workflow: Von der Forschungsfrage zur Graphenstruktur | 5 Min. |
| 3 | WissKI Kurzeinführung | 10 Min. |
| 4 | Strukturierte Daten mit CIDOC CRM | 15 Min. |
| 5 | Domänenanalyse: Kernentitäten, Ereignisse, Kontext - vom Objekt zur Hypothese | 20 Min. |
| 6 | Modellierung in Protégé: Konsistenzcheck und Erweiterungsstrategien | 10 Min. |
| 7 | Reflexion: Welche Analysen sind möglich, welche nicht? | 5 Min. |

---

## Lernziele

Lernende können... 

* für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID SODa_01_010_0190a) 
* Begriff Ontologie erläutern. (LZ-ID 03_007_0775)
* Aspekte von Ontologien benennen. (LZ-ID 03_007_0776)
* Methoden zur Entwicklung von Ontologien benennen. (LZ-ID 03_007_0784)
* einen Workflow für die semantische Modellierung als Datendokumentation benennen und anwenden. (LZ-ID SODa_03_001_0626 und SODa_03_001_0627) 
* die fünf Stufen des 5-Sterne-Modells für offene Daten benennen. (LZ-ID 01_008_0158)
* FAIR Prinzipien benennen. (LZ-ID 01_007_0117)
* geeignete Technologien zur Unterstützung der Anwendung der FAIR-Prinzipien benennen. (LZ-ID 01_007_0121)
* die spezifischen Funktionen und Anwendungsbereiche der Wissenschaftlichen Kommunikatiojnsinfrastruktur WissKI benennen und erläutern. (LZ-ID SODa_01_010_0191a und SODa_01_010_0192a)
* WissKI Pathbuilder als Werkzeug zur Definition einer domänenspezifische Ontologiestruktur bennenen und erläutern. (LZ-ID SODa_03_007_0803 und LZ-ID SODa_03_007_0804)
* die Methode der ereigniszentrierten Modellierung mit dem Referenzmodell CIDOC CRM erläutern. (LZ-ID SODa_03_007_0785a)
* Leistungsfähigkeit und Effizienz von IT-Infrastrukturen für das sammlungsbezogene Forschungsdatenmanagement (FDM) ) mit der Wissenschaftlichen Kommunikationsinfrastuktur WissKI benennen. (LZ-ID SODa_01_010_0202)
* Ontologie zur Beschreibung von Ressourcen bennen, erläutern, anwenden. (LZ-ID 03_007_0778, 03_007_0779, 03_007_0780)
* Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa_03_007_0784a)
* Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa_03_007_0780a)
* Nutzen des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa_03_007_0805)
* Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung benenen und erläutern. (LZ-ID SODa_03_007_0806 und LZ-ID SODa_03_007_0807)
* Datentyp-Eigenschaften des Referenzmodells CIDOC CRM benennen. (SODa_03_007_0808) *überarbeiten*
* Software zur Erstellung von Ontologien benennen und anwenden. (SODa_03_007_0809 und SODa_03_007_0810)


---

## Voraussetzung

Folgende Grundkenntnisse werden vorausgesetzt:


---

## Aktivierung und Input

**Impulsfrage**

Denkt an ein typisches Objekt aus eurer Sammlung/Forschung: Welche Information muss zwingend korrekt modelliert sein, damit die Forschung funktioniert?

**Blitzrunde im Plenum**

* Jede Person nennt genau 1 Punkt: „Für uns ist unverzichtbar, dass …“

### Lösungsbeispiele 

_Hilfestellung – nicht vorgeben_

* „… der Herstellungs-/Entstehungskontext klar ist.“
* „… Akteur:innen und Rollen unterscheidbar sind.“
* „… Provenienzereignisse nachvollziehbar sind.“
* „… Ort und Zeit belastbar sind.“
* „… Unsicherheiten (Hypothesen) abbildbar sind.“

**Live-Clustering**

Die Aussagen werden sichtbar an einem Board in 3 Spalten geschrieben:

* Entitäten (Objekt, Person, Ort, Zeit…)
* Ereignisse (Herstellung, Nutzung, Erwerb, Fund…)
* Beziehungen / Kontext (Rollen, Zugehörigkeiten, Teil-von, identisch mit…)

---

## Zusammenfasung

Sammlungsspezifische Anforderungen und Kontexte bilden die Grundlage, um in Modul 1 aus Sammlungsinformationen ein konsistentes, erklärbares Domänenmodell und Diagramm zu entwickeln.

--- 

## Alternative Aktivierungsmethoden

### Erwartungsabfrage

Interaktive Mentimeter-Umfrage zur Erfassung von Erwartungen, Vorkenntnissen und bisherigen Erfahrungen mit WissKI und semantischer Datenmodellierung.

<img src="../img/Erwartungsabfrage.png" alt="Mentimeter Umfrage" style="width:400px; height:auto;">

### Fragen 

* Was erwarten Sie von diesem Tutorial?
* Welche Datenkompetenzen bringen Sie mit?
* Welche Erfahrungen mit WissKI bringen Sie mit?
* Welche Erfahrungen haben Sie im Bereich semantische Datenmodellierung?
* Mit welchen Herausforderungen waren Sie bisher bei der Erstellung von Domänenontologien konfrontiert?

---

### Speed-Dating (Alternativ)

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












