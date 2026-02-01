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

Modul 1: **Von der Sammlung zum Diagramm – verstehen und erklären**

Einheit 2: **Analyse-Workflow: Von der Forschungsfrage zur Graphenstruktur**  

**Dauer:** ~ 10 Min.

Lernziel: 

* Begriff Ontologie erläutern. (LZ-ID 03\_007\_0775)
* Begriff Entität benennen und erläutern. (LZ-ID SODa\_03\_007\_820 und SODa\_03\_007\_821)
* Relevanz von Ontologien erläutern. (03\_007\_0777)
* Aspekte von Ontologien benennen. (LZ-ID 03\_007\_0776)
* Methoden zur Entwicklung von Ontologien benennen. (LZ-ID 03\_007\_0784)
* einen Workflow für die semantische Modellierung als Datendokumentation benennen und anwenden. (LZ-ID SODa\_03\_001\_0626 und SODa\_03\_001\_0627) 

---

## Von der Datenanalyse zur semantischen Modellierung 

* In den Geisteswissenschaften, GLAM-Institutionen und Forschungssammlungen wird mit **komplexen Objekt- und Kontextdaten** gearbeitet, die historische, kulturelle und soziale Bedeutungen tragen (z. B. Provenienz, Beziehungen, Interpretationen).
* Tabellen können zwar Daten beschreiben und erfassen, aber in erster Linie nur Eigenschaften (Attribute) - mit Tabellen lässt sich kein Wissen modellieren. Beziehungen, Bedeutungen und Kontexte bleiben dabei unsichtbar.
* Genau hier wird **semantische Datenmodellierung** relevant: Sie ermöglicht es, Wissen ontologiebasiert **strukturiert und interoperabel** darzustellen.
* Die Daten werden auf diese Weise sowohl **technisch als auch inhaltlich langfristig interpretierbar und damit wissenschaftlichen Qualitätskritierien entsprechend nachnutzbar**. [1]
* Semantisches Modellieren ist **nicht nur technisch**, sondern vor allem ein **konzeptioneller Prozess**, der **methodisches Denken** erfordert. Er ist disziplinübergreifend und erfordert gleichzeitig **fachwissenschaftliches Wissen und Modellierungskompetenz**. [1]
* **WissKI** (Wissenschaftliche Kommunikationsinfrastruktur) unterstützt diesen Prozess, indem es **Ontologien, Modellierung und Dateneingabe und -speicherung** miteinander verbindet.
  
---

## Begriff „Ontologie“

Eine **Ontologie** ist eine **formale Beschreibung eines Ausschnitts der Welt** bzw. eine **formal definierte Wissensstruktur**, die festlegt,

* welche Arten von Dingen, sog. **Entitäten** (z. B. Objekt, Person, Ereignis, Ort, Zeit), es in einer Domäne, also einem spezifischen Fachgebiet gibt,
* wie diese Entitäten miteinander in Beziehung stehen,
* und welche Aussagen über sie sinnvoll sowie widerspruchsfrei modelliert werden können.

<!-- ## Begriff "Ontologie"
Eine Ontologie ist eine **formale Beschreibung eines Ausschnitts der Welt** bzw. eine **formal definierte Wissensstruktur**, die festlegt,

* welche **Konzepte** von Dingen (z. B. Objekt, Person, Ort, Zeit) und **Ereignisse** in einem Wissensbereich bzw. Fachbereich relevant sind,
* wie diese Konzepte miteinander **in Beziehung** stehen,
* und welche **Regeln** gelten, damit **Aussagen** über sie sinnvoll und widerspruchsfrei modelliert werden können.

Ontologien ermöglichen so ein gemeinsames Verständnis zentraler Phänomene, Konzepte und Strukturen in einem Fachbereich, sowohl für Menschen als auch für die maschinelle Verarbeitung.

## Begriff "Domänenontologie"

Eine Domänenontologie ist eine projekt oder -anwendungsspezifische Umsetzung einer Ontologie, die die Konzepte, Ereignisse und Beziehungen innerhalb eines konkreten Fach- oder Anwendungsbereichs (Domäne) beschreibt.-->


## Nutzen von Ontologien und weiterführende Definitionen

Ontologien helfen damit, fachliches Domänenwissen mit ihrer spezifischen Domänenlogik so zu dokumentieren, dass es maschinenlesbar, vergleichbar und nachnutzbar wird. Im Kontext der Semantic-Web-Technologien lässt sich eine Ontologie praktisch als Struktur verstehen, die u. a. Klassen (Typen/Kategorien von Entitäten), Eigenschaften (Properties) und Individuen bereitstellt und damit Aussagen über Ressourcen formal abbilden kann. [2]

<!--  Im Kontext der Semantic-Web-Technologien lässt sich eine Ontologie als Struktur verstehen, die insbesondere bereitstellt:

* Klassen: formale Repräsentation von Konzepten
* Eigenschaften (Properties): formale Repräsentation von Merkmalen oder Beziehungen zwischen Klassen und Instanzen
* Instanzen (Individuen): konkrete Ausprägungen von Klassen

Auf diese Weise ermöglichen Ontologien, Aussagen über Ressourcen formal abzubilden. [2] -->

Ontologien unterstützen damit die systematische und konsistente Repräsentation von Domänenwissen, sodass Informationen maschinenlesbar und für die Nachnutzung in unterschiedlichen Systemen anschlussfähig werden. [3]

Die bekannteste Definition beschreibt eine Ontologie als "eine explizite, formale Spezifikation einer Konzeptualisierung", d. h. sie beschreibt strukturierend, welche Konzepte in einem bestimmten spezifischen Fachgebiet oder Gegenstandsbereich relevant sind und welche Beziehungen zwischen ihnen bestehen. [4]

---

## Aspekte von Ontologien

Ontologien bestehen typischerweise aus folgenden Bausteinen:

* **Klassen** (z.B. Spiel, Person, Organisation, Ereignis)
* **Relationen** Eigenschaften/Properties (z.B. *hat Titel*, *wurde veröffentlicht von*)
* **Instanzen** (konkrete Dinge, z.B. *The Legend of Zelda: A Link to the Past*) 
* **Constraints / Modellannahmen** (z.B. welche Beziehungen beschreiben zulässig das Objekt)
* **Definitionen / Scope Notes** zur semantischen Präzisierung (z.B. in Referenzmodellen wie CIDOC CRM)

<!-- 
* **Klassen**
* **Eigenschaften/Relationen** (Properties)
* **Instanzen**
-->

---

## Methoden zur Entwicklung von Ontologien

Die Entwicklung einer Domänenontologie folgt typischerweise einem methodischen, mehrstufigen und iterativen Vorgehen. 

Dazu zählen u.a. die Erhebung zentraler Begriffe und Definitionen (sog. „ontology capture“), die Strukturierung von Konzepten in Klassen und Eigenschafen/Relationen sowie die kontinuierliche Prüfung und Überarbeitung des Domänenmodells im Hinblick auf Konsistenz und Nutzbarkeit. [4]

Die praktische Ontologieentwicklung wird dabei häufig als ein Prozess verstanden, der sowohl Domänenwissen als auch Anwendungsanforderungen integriert und schrittweise in eine formal nutzbare Wissensstruktur überführt.

Ontologien entstehen häufig durch eine Kombination aus:

* **Top-down-Modellierung:** Ausgehend von einem Referenzmodell (z.B. CIDOC CRM) erfolgt eine domänenspezifische Spezialisierung.
* **Bottom-up-Modellierung:** Aus vorhandenen Daten werden schrittweise Klassen und Eigenschaften/Relationen abgeleitet.
* **Competency Questions:** Die Modellierung erfolgt aus typischen Analyse- und Forschungsfragen heraus (z.B. „Welche Spiele haben Merkmal X?“)
* **Iteratives Prototyping:** Es wird ein Modell entworfen → überprüft → kontinuierlich mit Blick auf Konsistenz, Erweiterbarkeit und Abfragbarkeit angepasst.

---

## Workflow-Übersicht (Methode)


**Zielsetzung dieses Moduls ist es:**  

* Domänenwissen schrittweise in ein ontologiebasiertes Datenmodell zu übersetzen,
* Modellierungsentscheidungen nachvollziehbar zu dokumentieren,
* und die Grundlage für ein **konsistentes CIDOC-CRM-basiertes Diagramm** zu schaffen, das später in WissKI umgesetzt wird.

1. **Quellen/Objekt analysieren** – Welche Informationen liegen vor?
2. **Objektdaten analysieren** – Entitäten und Beziehungen im Datenbestand erkennen 
3. **Bedeutungen erfassen** – Konzepte und relevante Eigenschaften identifizieren
4. **Kernentitäten und Kontexte bestimmen** – Welche Dinge (Objekt/Person/Ort/Zeit/Organisation) sind relevant?
5. **Abgleich mit Ontologie (z.B. CIDOC CRM)** – Begriffe semantisch präzisieren und konsistent zuordnen
6. **Semantik modellieren** – Bedeutungen auf das Referenzmodell CIDOC CRM abbilden
7. **Ereignisse und Beziehungen formulieren (Graphlogik)** – Was passiert, wer ist beteiligt, wie hängt es zusammen?
8. **Datenpfade ersetellen** – WissKI-Pfade modellieren & Pathbuilder konfigurieren  
9. **Evaluieren & diskutieren** – Workflows reflektieren und Erfahrungen austauschen
10. **Umsetzung vorbereiten** – Grundlage für Diagramm und spätere Pfadstruktur (Modul 2) schaffen

<!-- 
2. **Objektdaten analysieren** - Konzepte, Ereignisse und Beziehungen im Datenbestand erkennen
3. **Bedeutungen erfassen** - Konzepte, Ereignisse und Beziehungen im Datenbestand identifizieren
4. **Zentrale Konzepte und Kontexte bestimmen** - Welche Dinge sind relevant?
5. **Ableich mit Ontologie (z. B. Referenzmodell CIDOC CRM)** - Konzepte, Ereignisse und Beziehungen semantisch präzisieren und konsistent zuordnen
7. **Eigenschaften (Properties) formulieren (Graphlogik)** - Was passiert, wer ist beteiligt, wie hängt es zusammen?
-->

---

## Beispielobjekt

Popkulturelle Objekte wie Computerspiele eignen sich didaktisch besonders gut, weil sie meist über klar dokumentierte Basisdaten verfügen (z.B. Titel, Erscheinungsjahr, Publisher, Plattform/Edition) und zugleich vielfältige, gut modellierbare Kontexte eröffnen (z.B. Beteiligte, Versionen, Serienzugehörigkeit, regionale Releases). 

So lässt sich anschaulich zeigen, wie aus scheinbar „einfachen“ Informationen durch präzise Entitäten, Ereignisse und Beziehungen eine belastbare Graphstruktur entsteht.
<!-- 
So lässt sich anschaulich zeigen, wie aus scheinbar „einfachen“ Informationen durch präzise Klassen (Entities) und Eigenschaften (Properties) eine belastbare Graphstruktur entsteht. -->

**Super Nintendo Entertainment System (SNES) Spiel: *The Legend of Zelda***

| Darstellung | Beschreibung |
|------------|--------------|
| **Objekt** | ![Zelda Spiel](../assets/zelda_smal.png) |
| **Semantische Annahme** | Titel des Objekts: *The Legend of Zelda: A Link to the Past* |
| **Draw.io Modell** | ![draw.io Diagramm](../assets/path.PNG) |
| **WissKI Pathbuilder** | ![WissKI Pathbuilder](../assets/pathbuilder.PNG) |


## Bibliographie
____________________________

[1] Fichtner, M. (2025). Grundlagen der Erzeugung und Verwaltung von Ontologiepfaden und ihre Anwendung (Doctoral thesis, Friedrich-Alexander-Universität Erlangen-Nürnberg, Technische Fakultät). https://doi.org/10.25593/open-fau-2143

[2] World Wide Web Consortium. (2012, December 11). OWL 2 Web Ontology Language Primer (Second Edition). W3C Recommendation. https://www.w3.org/TR/owl2-primer 

[3] Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

[4] Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

[5] Uschold, M., & King, M. (1995). Towards a Methodology for Building Ontologies.






















