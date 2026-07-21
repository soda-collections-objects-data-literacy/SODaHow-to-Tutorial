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

Einheit 1: **Grundbegriffe konzeptueller Wissensmodellierung**  

**Dauer:** ca. XX Min.

**Lernziele:**

Teilnehmende können...
* Begriff Domäne benennen. (LZ-ID SODa\_03\_007\_0824)
* Begriff Konzept benennen. (LZ-ID SODa\_03\_007\_0821)
* Begriff Ereignis benennen. (LZ-ID SODa\_03\_007\_0822)
* Begriff Beziehung benennen. (LZ-ID SODa\_03\_007\_0823)
*
* Begriff semantische Modellierung benennen. (LZ-ID SODa\_03\_007\_0825)
* <!--* evtl. Begriff Attribut benennen.-->

---

## Einführung: Von der konzeptuellen Analyse zur semantischen Modellierung 

In dieser Einheit wird die konzeptuelle Wissensmodellierung innerhalb einer Domäne als Grundlage der semantischen Datenmodellierung vorgestellt.

- In den Geisteswissenschaften, GLAM-Institutionen und Forschungssammlungen wird mit **komplexen Objekt- und Kontextdaten** gearbeitet, die historische, kulturelle und soziale Bedeutungen tragen (z. B. Provenienz, Beziehungen, Interpretationen).
- Tabellen können zwar Daten beschreiben und erfassen, aber in erster Linie nur Eigenschaften (Attribute) - mit Tabellen lässt sich kein Wissen modellieren. Beziehungen, Bedeutungen und Kontexte bleiben dabei unsichtbar.
- Genau hier wird **semantische Datenmodellierung** relevant: Sie ermöglicht es, Wissen ontologiebasiert **strukturiert und interoperabel** darzustellen.
- Die Daten werden auf diese Weise sowohl **technisch als auch inhaltlich langfristig interpretierbar und damit wissenschaftlichen Qualitätskritierien entsprechend nachnutzbar**. [1]
- Semantisches Modellieren ist **nicht nur technisch**, sondern vor allem ein **konzeptioneller Prozess**, der **methodisches Denken** erfordert. Er ist disziplinübergreifend und erfordert gleichzeitig **fachwissenschaftliches Wissen und Modellierungskompetenz**. [1]
- **WissKI** (Wissenschaftliche Kommunikationsinfrastruktur) unterstützt diesen Prozess, indem es **Ontologien, Modellierung und Dateneingabe und -speicherung** miteinander verbindet.

---

## Grundbegriffe semantischer Modellierung

Bevor Wissen formal modelliert werden kann, muss zunächst geklärt werden, **welches Wissen innerhalb einer Domäne relevant ist und wie es konzeptuell geordnet werden kann.** Eine **Domäne** bezeichnet einen Wertebereich [2] für den Wissen beschrieben und modelliert wird. In der semantischen Datenmodellierung versteht man darunter den fachlichen Wissensbereich, dessen Konzepte, Ereignisse und Beziehungen erfasst und formal repräsentiert werden.

---

## Begriffsdefinition

Auf konzeptueller Ebene lassen sich folgende Elemente innerhalb einer Domäne identifizieren:

- **Konzepte** sind zentrale Einheiten einer Domäne. Dazu gehören beispielsweise Objekte, Personen, Orte, Materialien oder Institutionen
- **Ereignisse** sind Vorgänge, durch die Konzepte miteinander verbunden werden oder durch die sich Informationen über Konzepte ergeben. Beispiele sind Herstellung, Erwerb, Fund, Restaurierung, Ausstellung oder Nutzung.
- **Beziehungen** beschreiben die semantische Verknüpfung zwischen Konzepten und Ereignissen. Beispiele sind "wurde hergestellt von", "befindet sich in", "wurde restauriert durch" oder "ist Teil von".

Die Identifikation und Strukturierung dieser Elemente bildet die Grundlage der semantischen Modellierung. Erst wenn die relevanten Konzepte, Ereignisse, Beziehungen einer Domäne verstanden sind, können sie in ein formales Datenmodell überführt werden.

---

## Aktivierung und Input: Wissen einer Sammlung konzeptuell ordnen

**Arbeitsform:** Impulsfrage / Blitzfrage im Plenum / Clustering  
**Materiel:** keines  
**Zeit:** XX Min.  

In dieser Aufgabe geht es darum, Kernkonzepte, -ereignisse und -beziehungen der eigenen Sammlung zu identifizieren.

1. Blitzrunde im Plenum:
Denkt an ein typisches Objekt aus eurer Sammlung: Welche Information muss zwingend dokumentiert sein, damit Forschung möglich wird?

2. Clustering
Die Aussagen wird sichtbar an einem [Board](https://miro.com/app/board/uXjVGKauOtE=/) in 3 Spalten zugeordnet:

- Konzepte (Objekt, Person, Ort, Zeit…)
- Ereignisse (Herstellung, Nutzung, Erwerb, Fund…)
- Beziehungen (Rollen, Zugehörigkeiten, Teil-von, identisch mit…)

**Hinweis:**
- Jede Person nennt genau 1 Punkt: „Für uns ist unverzichtbar, dass …“
- z.B. „… eine eindeutige Identifizierung durch z. B. Signatur-/Inventarnummer möglich ist.

---

## Ergebnis

- „… der Herstellungs-/Entstehungskontext klar ist.“
- „… Akteur:innen und Rollen unterscheidbar sind.“
- „… Provenienzereignisse nachvollziehbar sind.“
- „… Ort und Zeit belastbar sind.“
- „… Unsicherheiten (Hypothesen) abbildbar sind.“
- „… eine eindeutige Identifizierung durch z. B. Signatur-/Inventarnummer möglich ist.“
  
---

## Zusammenfassung

Anforderungen aus der Sammlungspraxis bilden die Grundlage, um in diesem Modul 1 zentrale Konzepte, Ereignisse und Beziehungen zu identifizieren und daraus ein konsistentes, nachvollziehbares Domänenmodell und -diagramm zu entwickeln. 

---

## Ausblick

In der nächsten Einheit ...

---

## Bibliographie

[2] Lexikon der Informatik S, 257


<!-- 
## Domäne
"Wertebereich"
Allgemeine Definition: "das Kollektiv, der Bereich, die Menge zulässiger Werte oder Ausprägungen eines Attributs; also der Wertebereich;" (Lexikon der Informatik S, 257)

Attribut: Merkmal/Eigenschaft eines Objekts, das einen bestimmten Wert (aus einer festgelegten Domäne) annehmen kann. (Lexikon der Informatik, S. 77)

## Semantisches Datenmodell
Ein semantisches Datenmodell ist ein konzeptueller, formaler Rahmen, der die Bedeutung von Daten durch die Definition von Konzepten und Begriffen, ihre Relationen und Regeln innerhalb eines Wissensbereichs beschreibt. Es dient nicht der Darstellung konkreter Daten, sondern stellt dar, wie Daten aus einem bestimmten Wissensbereich und Kontext verstanden, interpretiert und miteinander in Beziehung gesetzt werden."

## semantische Modellierung 
"Semantische Datenmodellierung bezeichnet den Prozess, Konzepte, Begriffe und Relationen eines Wissensbereichs zu identifizieren, zu strukturieren und zu formalisieren." 
"Semantische Datenmodellierung beschreibt Begriffe und Konzepte sowie deren Beziehungen in Form eines semantischen Netzes, meist als gerichteter Graph mit:
  Knoten: repräsentieren Begriffe und Konzepte
  Kanten: repräsentieren semantische Beziehungen zwischen Begriffen und Konzepten
Semantische Datenmodellierung erfordert
Fachwissenschaftliche Kompetenz: Welche fachspezifischen Phänomene, Begriffe, Konzepte und Beziehungen sind bedeutsam und was bedeuten sie bzw. was sollen sie bedeuten (in speziellen Kontexten)?
Modellierungskompetenz: Wie repräsentiere ich fachspezifische Bedeutungsinhalte abstrahiert, strukturiert und formal in einem Modell, das sowohl interpretierbar, als auch technisch nutzbar ist?
Zusammenarbeit zwischen Forscher:innen bzw. Fachexpert:innen, Datenmodellierer:innen (und IT)

-->













