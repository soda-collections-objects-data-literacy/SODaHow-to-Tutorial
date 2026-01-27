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

Modul 2: **Vom Diagramm zu Pfaden – Erläutern und anwenden**

Einheit 2: **Visualisierung der Domänenontologie in Draw.io**  

**Dauer:** ~ 25 Min.

Lernziel

* Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
* Software zur Visualisierung einer Domänenontologie benennen und erläutern.(LZ-ID SODa\_03\_007\_0812 und LZ-ID SODa\_03\_007\_0813)
* Nutzen einer Software zur Visualisierung einer Domänenontologie benennen.(LZ-ID SODa\_03\_007\_0814) 
* Software zur Visualisierung einer Domänenontologie unter Anleitung anwenden. (LZ-ID SODa\_03\_007\_0815)
* Methoden zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware benennen. (LZ-ID SODa\_03\_007\_0784b)
* Methoden zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware anwenden. (LZ-ID SODa\_007\_0816)
* Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa\_03\_007\_0780a)
* Attributwerte an vordefinierten Klassen der Domänenontologie in einer Visualisierungssoftware anwenden. (LZ-ID SODa\_03\_007\_0817)


---

## Warum Draw.io ?

**Visualisierungen** sind ein bedeutender Zwischenschritt und ein wesentliches Werkzeug, um **Modellierungsentscheidungen zu kommunizieren, auszuhandeln und ein gemeinsames Verständnis semantischer Strukturen zu fördern.**

Das Modellieren in Draw.io ist **nicht nur eine visuelle Übung**. Das  Draw.io-Diagramm bildet die **Voraussetzung für die (halb-)automatisierte Pipeline** zur Erstellung eines **Pathbuilders** in WissKI.

Das Draw.io-Diagramm wird dabei als **XML-Datei** exportiert und enthält bereits strukturierte Informationen zu **Klassen, Relationen und Gruppen**. 

Dadurch kann es **automatisiert weiterverarbeitet** und in konsistente **WissKI-Pathbuilder-Strukturen** überführt werden.

---

## Draw.io unterstützt dabei...

* **Entitätsklassen und ihre Beziehungen** klar zu definieren,
* **Domänenlogik und semantische Zusammenhänge** sichtbar und diskutierbar zu machen,  
* Modelle **kollaborativ und transparent** zu entwickeln,  
* die **Ontologiestruktur vor dem Import in WissKI** zu prüfen,  
* und **semantische Entscheidungen** zu reflektieren und abzusichern.

Besonders in kollaborativen Projekten erleichtert Draw.io die **Abstimmung zwischen Fachexpert:innen, Datenmodellierenden und Entwickler:innen**, da semantische Entscheidungen visuell nachvollziehbar und dokumentierbar bleiben.

---

## Ausgangspunkt

In Modul 1 wurde die konzeptionelle Grundlage des Beispiel-Datenmodells entwickelt:

* In **Einheit 5** wurden *zentralen Entitäten und Beziehungen* am Beispiel eines Computerspiels identifiziert. 
* In **Einheit 6** wurde gezeigt, wie die Top-Level Ontologie CIDOC CRM um *domänenspezifische Subklassen* erweitert wird.  

Zur Orientierung und zum Nachlesen:

* Beispielobjekt:  
  https://github.com/soda-collections-objects-data-literacy/SODaHow-to-Tutorial/blob/main/WissKIBits_Modul1/M1E2_Analyse-Workflow.md#beispielobjekt
* Beispiele für Kernentitäten (Spielmerkmale und narrative Elemente):  
  https://github.com/soda-collections-objects-data-literacy/SODaHow-to-Tutorial/blob/main/WissKIBits_Modul1/M1E5_Dom%C3%A4nenanalyse.md#fokus-dieser-modellierungs%C3%BCbung

---

## Quiz: Beispielobjekt & Kernentitäten 

Wissen aus Modul 1 (E5/E6) wird aktiviert.

**Quizfragen** (Single Choice)

Welches Beispielobjekt wird im Modul verwendet? 

* [( )] Ein PC-Spiel: *Minecraft*
* [(x)] Ein SNES-Spiel: *The Legend of Zelda*
* [( )] Eine PlayStation-Konsole: *PS1*
* [( )] Ein Arcade-Automat: *Pac-Man*

Welche semantische Annahme wird im Beispiel explizit gemacht?

* [( )] Das Spiel ist „Open World“
* [(x)] Der Titel des Objekts wird als *The Legend of Zelda: A Link to the Past* festgelegt
* [( )] Das Spiel ist eine „Collector’s Edition“
* [( )] Die Plattform ist „PC“

**Quizfragen** (Multiple Choice)

Welche der folgenden Begriffe zählen zu den **Spielmerkmalen**?

* [(x)] Plattform
* [(x)] Genre
* [(x)] Edition/Version
* [( )] Spielbeschreibung
* [( )] Charaktere / Figuren

Welche der folgenden Begriffe zählen zu den **narrativen Elementen**?

* [(x)] Perspektive
* [(x)] Spielbeschreibung
* [(x)] Charaktere / Figuren
* [( )] Plattform
* [( )] Genre


---

## Von den Kernentitäten zur strukturierten Visualisierung

Die bisherigen Fragen haben verdeutlicht, welche Kernentitäten der Beispieldomäne relevant sind und wie sie fachlich eingeordnet werden können.

Im nächsten Schritt geht es nicht mehr um das Erkennen oder Benennen von Merkmalen, sondern darum, diese Auswahl in eine **formale Struktur** zu überführen:

* Welche Entitäten werden tatsächlich modelliert?
* Wie werden sie semantisch korrekt miteinander verknüpft?
* Wie entsteht daraus eine Struktur, die später als **Pfad im WissKI Pathbuilder** nutzbar ist?

Dazu wird das konzeptionelle Domänenmodell nun **visuell und formal in Draw.io** umgesetzt.  

Es entsteht ein semantisches Modell als Grundlage für die Erstellung von Pfaden im WissKI Pathbuilder, in dem die Kernentitäten und ihre Beziehungen der Beispieldomäne **auf Basis des CIDOC CRM** visualisiert werden.

---

### Beispielergebnis

<table>
  <tr>
    <td><img src="../img/SODa_Modul2.drawio.png" alt="Visuelle Repräsentation" width="100%"></td>
  </tr>
</table>

---

## Anforderungen an das Arbeiten mit Draw.io (Methoden)

* Es werden keine individuellen Instanzen abgebildet.
* Es werden die domänenspezifischen Subklassen aus der bereits erstellten Domänenontologie verwendet.
* Die semantischen Relationen sind aus dem CIDOC CRM abzuleiten.
* Es sind vollständige Pfade zu erstellen.
* Dem zentralen Startknoten, jedem Gruppenknoten und jedem Endknoten werden jeweils **element_id**, **group_name** und **name** zugewiesen.  

---

## Aufgabe (Partnerarbeit – 20 Min.)

Das bereitgestellte Diagramm enthält gezielte Lücken (fehlende Knoten/Beziehungen), die zu ergänzen sind. 

Lücken sind durch geeignete Klassen und passende Properties zu schließen; temporäre Platzhalter (???) sind nach der Ergänzung zu entfernen.

* Die vorbereitete Draw.io-Datei runterladen (hier: https://github.com/soda-collections-objects-data-literacy/SODa_WissKI-ISWC25Bits  in "contentConcept/assets"; Für Anfänger "Gruppe_A.drawio.xml" und für Experten "Gruppe_E.drawio.xml")
* Die heruntergeladene Draw.io-Datei in Draw.io importieren (hier: https://app.diagrams.net/)
* Das Domänenontologie-Diagramm vervollständigen
* Attributwerte an Startknoten, jedem Gruppenknoten und Endknoten prüfen

**Ressourcen**

* Domänenontologie: [http://games.m-e-g-a.org/game_domain.rdf](http://games.m-e-g-a.org/game_domain.rdf)
* Für semantische Beziehungen: PDF-Datei: [https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf](https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf) und HTML-Link: [https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html)


---






