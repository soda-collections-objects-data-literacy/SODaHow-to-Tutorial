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

**Dauer:** ~ 10 Min.

Lernziel

* für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID SODa\_01\_010\_0190a)
* Domänenbegriff benennen und erläutern.

---

## Begrüßung

> Willkommen zu **SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
> 
> Dieses How-to-Tutorial bietet eine praxisorientierte Einführung in die **Arbeit und Analyse mit strukturierten Forschungsdaten** – von der ersten Beschreibung eines Sammlungsobjekts bis zur semantisch belastbaren Modellstruktur. Hierfür wird ein **Datenmodell an einem Beispiel entwickelt und implementiert**.
>
> Im Modul 1 **"Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären"** wird die **konzeptionelle Grundlage** für ein Datenmodell erarbeitet:
>
> Objektdaten und Kontextinformationen aus einem spezifischen Fachgebiet bzw. einer Domäne werden analysiert, Kernentitäten, Ereignisse und Beziehungen identifiziert und diese Schritt für
> Schritt in eine ontologiebasierte Struktur (z. B. mit CIDOC CRM) übersetzt.
> <!-- Objektdaten und Kontextinformationen aus einem spezifischen Fachgebiet bzw. einer Domäne werden analysiert, um zentrale Konzepte, Ereignisse und Beziehungen der Domäne zu identifizieren und begrifflich zu präzisieren. Schritt für Schritt werden sie anschließend in eine ontologische Struktur (z. B. mit CIDOC CRM übersetzt)  --> 
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

In Modul 1 wird die konzeptionelle Basis für ein Domänenmodell geschaffen. Aus der Sammlungsperspektive entsteht eine Modellperspektive.

* Objektdaten & deren Kontext werden analysiert.
* Kernentitäten von Objektdaten werden identifiziert und um Ereignisse und Beziehungen kontextualisiert.
<!-- Zentrale Konzepte der Objektdaten werden identifiziert und durch zugehörige Ereignisse und Beziehungen kontextualisiert.  --> 
<!-- Abgleich der identifizierten Domänenkonzepte, Ereignisse und Beziehungen mit entsprechenen Klassen (Entities) und Eigenschaften/Beziehungen (Properties) des CIDOC CRM  -->
* Daraus entsteht schrittweise eine ontologiebasierte Domänenstruktur bzw. -logik mit CIDOC CRM.
* Diese Domänenlogik wird visualisiert und dient als Grundlage für das sammlungsbezogene Datenmanagement und die -verwaltung in WissKI.

---

## Ablauf des Moduls

**Modul 1: 90 Min.**

| Einheit | Inhalt | Dauer |
|--------|--------|------|
| 1 | Ablauf und Zielsetzung | 10 Min. |
| 2 | Analyse-Workflow: Von der Forschungsfrage zur Graphenstruktur | 5 Min. |
| 3 | WissKI Kurzeinführung | 10 Min. |
| 4 | Strukturierte Daten mit CIDOC CRM | 10 Min. |
| 5 | Fachbereichs- bzw. Domänenanalyse: Kernentitäten, Ereignisse, Kontext - vom Objekt zur Hypothese | 30 Min. |
| 6 | Modellierung in Protégé: Konsistenzcheck und Erweiterungsstrategien | 10 Min. |
| 7 | Reflexion: Welche Datenanalysen sind möglich, welche nicht? | 5 Min. |
  
---

## Lernziele

Lernende können... 

* für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID SODa\_01\_010\_0190a) 
* Begriff Ontologie erläutern. (LZ-ID 03\_007\_0775)
* Begriff Entität benennen und erläutern. (LZ-ID SODa\_03\_007\_820 und SODa\_03\_007\_821)
* Relevanz von Ontologien erläutern. (03\_007\_0777)
* Aspekte von Ontologien benennen. (LZ-ID 03\_007\_0776)
* Methoden zur Entwicklung von Ontologien benennen. (LZ-ID 03\_007\_0784)
* einen Workflow für die semantische Modellierung als Datendokumentation benennen und anwenden. (LZ-ID SODa\_03\_001\_0626 und SODa\_03\_001\_0627) 
* das 5-Sterne-Modell für offene Daten benennen. (LZ-ID SODa\_01\_008\_0172)
* FAIR Prinzipien benennen. (LZ-ID 01\_007\_0117)
* geeignete Technologien zur Unterstützung der Anwendung der FAIR-Prinzipien benennen. (LZ-ID 01\_007\_0121)
* die spezifischen Funktionen und Anwendungsbereiche der Wissenschaftlichen Kommunikationsinfrastruktur WissKI benennen und erläutern. (LZ-ID SODa\_01\_010\_0191a und SODa\_01\_010\_0192a)
* WissKI Pathbuilder als Werkzeug zur Definition einer domänenspezifischen Ontologiestruktur bennenen und erläutern. (LZ-ID SODa\_03\_007\_0803 und LZ-ID SODa\_03\_007\_0804)
* die Methode der ereigniszentrierten Modellierung mit dem Referenzmodell CIDOC CRM erläutern. (LZ-ID SODa\_03\_007\_0785a)
* Leistungsfähigkeit und Effizienz von IT-Infrastrukturen für das sammlungsbezogene Forschungsdatenmanagement (FDM) mit der Wissenschaftlichen Kommunikationsinfrastuktur WissKI benennen. (LZ-ID SODa\_01\_010\_0202)
* Ontologien zur Beschreibung von Ressourcen bennen, erläutern und anwenden. (LZ-ID 03\_007\_0778, LZ-ID 03\_007\_0779 und LZ-ID 03\_007\_0780)
* Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0784a)
* Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa\_03\_007\_0780a)
* Nutzen des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0805)
* Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung benenen und erläutern. (LZ-ID SODa\_03\_007\_0806 und LZ-ID SODa\_03\_007\_0807)
* Datentyp-Eigenschaften des Referenzmodells CIDOC CRM benennen. (SODa\_03\_007\_0808) *überarbeiten*
* Software zur Erstellung von Ontologien benennen und anwenden. (SODa\_03\_007\_0809 und SODa\_03\_007\_0810)


---

## Voraussetzung

Folgende Grundkenntnisse werden vorausgesetzt:

*keine*

---

## Aktivierung und Input

**Impulsfrage**

Denkt an ein typisches Objekt aus eurer Sammlung: Welche Information muss zwingend dokumentiert sein, damit Forschung möglich wird?

**Blitzrunde im Plenum und Clustering**

* Jede Person nennt genau 1 Punkt: „Für uns ist unverzichtbar, dass …“
* z.B. „… eine eindeutige Identifizierung durch z. B. Signatur-/Inventarnummer möglich ist.

Die Aussagen wird sichtbar an einem [Board](https://miro.com/app/board/uXjVGKauOtE=/) in 3 Spalten zugeordnet:

* Entitäten (Objekt, Person, Ort, Zeit…)
<!-- Konzepte (Objekt, Person, Ort, Zeit)  -->
* Ereignisse (Herstellung, Nutzung, Erwerb, Fund…)
* Beziehungen / Kontext (Rollen, Zugehörigkeiten, Teil-von, identisch mit…)

---

### Lösungsbeispiele 

_Hilfestellung – nicht vorgeben_

* „… der Herstellungs-/Entstehungskontext klar ist.“
* „… Akteur:innen und Rollen unterscheidbar sind.“
* „… Provenienzereignisse nachvollziehbar sind.“
* „… Ort und Zeit belastbar sind.“
* „… Unsicherheiten (Hypothesen) abbildbar sind.“
* „… eine eindeutige Identifizierung durch z. B. Signatur-/Inventarnummer möglich ist.“
  
---

## Zusammenfassung

Anforderungen aus der Sammlungspraxis bilden die Grundlage, um in diesen Modul 1 zentrale Entitäten, Ereignisse und Beziehungen zu identifizieren und daraus ein konsistentes, nachvollziehbares Domänenmodell und Diagramm zu entwickeln.
<!-- Anforderungen aus der Sammlungspraxis bilden die Grundlage, um in diesen Modul 1 zentrale Konzepte, Ereignisse und Beziehungen zu identifizieren und daraus ein konsistentes, nachvollziehbares Domänenmodell und Diagramm zu entwickeln.  -->















