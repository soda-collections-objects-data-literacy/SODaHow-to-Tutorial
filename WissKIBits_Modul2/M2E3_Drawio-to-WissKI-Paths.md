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

Einheit 3: **Automatische Pfadgenerierung: Konsistenz prüfen und WissKI Pathbuilder-Datei erzeugen**

Dauer: ~ 25 Min.

Lernziele

* WissKI Pathbuilder als Werkzeug zur Entwicklung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0804)
* unter Anleitung die Datenkonvertierung einer Visualisierungssoftware in ein nachnutzbares Dateiformat anwenden. (LZ-ID SODa\_02\_005\_0298a)
* unter Anleitung ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung benennen und anwenden. (LZ-ID SODa\_02\_005\_0317 und LZ-ID SODa\_02\_005\_0318)
* unter Anleitung WissKI Pathbuilder als Werkzeug zum Import einer domänenspezifischen Ontologiestruktur (Pathbuilder-XML-Datei im WissKI-Pathbuilder) anwenden. (LZ-ID SODa\_03\_007\_0818)
* unter Anleitung die importierte domänenspezifische Ontologiestruktur im WissKI-Pathbuilder analysieren. (LZ-ID SODa\_03\_007\_0819)
  
---

## Der WissKI Pathbuilder

Der Pathbuilder bildet die **Implementierungsschicht von WissKI**.

Anstelle klassischer, relationaler Datenbanktabellen arbeitet WissKI mit semantischen Pfaden, die aus Klassenbeziehungen konstruiert werden. 

Diese **Pfade definieren die interne Domänenontologie von WissKI** und steuern, wie Daten erfasst, gespeichert, verknüpft und abgefragt werden.

Im Gegensatz zu einer Ontologie (z.B. in RDF oder OWL), die Klassen und Beziehungen nur beschreibt, übersetzt der Pathbuilder diese semantischen Strukturen in konkrete Pfade und Pfadgruppen, die in WissKI für folgende Zwecke genutzt werden:

* Aufbau und Verwaltung des RDF-Wissensgraphen,
* ontologiekonforme Datenspeicherung und -abfrage
* Strukturierung der Dateneingabeformulare in Drupal.

Aus jeder semantischen Beziehungskette - also Sequenz aus Klassen und Beziehungen - wird im Pathbuilder ein Pfad.

Mehrere **zusammengehörige Pfade werden zu Pfadgruppen organisiert**, die wiederum Entitäten (z. B. Personen, Objekte, Ereignisse) repräsentieren.

<table>
  <tr>
    <td><img src="../assets/pathbuilder.jpg" alt="WissKI Pathbuilder" width="75%"></td>
  </tr>
</table>

---

## Workflow vom Domänenontologie-Diagramm zu WissKI-Pfaden

| Schritt | Aktion                                |
| -------- | ------------------------------------ |
| 1        | Draw.io-Modell als .xml-Datei exportieren.  |
| 2        | Draw.io.xml-Datei in WissKI Pathbuilder-Web Service laden. |
| 3        | Prüfen ob Ontologiestruktur valide ist. |
| 4        | WissKI Pathbuilder XML generieren. |
| 5        | Pathbuilder XML-Datei in WissKI importieren.   |
| 6        | Pfadstruktur prüfen. |

Dieser Prozess überbrückt die Lücke zwischen der Modellierung einer Domänenontologie und der Erstellung des Pathbuilders in WissKI, indem das semantische draw.io-Modell über eine Transformationspipeline automatisch in WissKI-Pfade umgewandelt wird.

---

## Praktische Aufgabe (Gruppenarbeit– 20 Min.)

Teil 1 

| Nr. | Schrittbeschreibung |
| --- | ------------------- |
| 1 | "Draw.io diagrams to WissKI pathbuilders" Web Service öffnen |
| x | Beispiel-Draw.io-XML-Datei herunter laden |
| x | Beispiel-Draw.io-XML-Datei in "Upload draw.io XML file for conversion to WissKI Pathbuilder XML:" hochladen |
| 2 | Linkadresse von Beispiel output Pathbuilder-XML kopieren|
| 3 | In WissKI einloggen |
| 4 | Prüfen, ob in WissKI bereits CIDOC CRM geladen ist, siehe „Configuration/Ontology/Default WissKI Distillery Adapter“ |
| 5 | Zu „Configuration/Pathbuilder“ navigieren |
| 6 | Neuen Pathbuilder hinzufügen „Add Pathbuilder“, Name vergeben und speichern |
| 7 | Unter „Pathbuilder Definition Import“ zuvor kopierte Link-Adresse einfügen und „Import“ klicken |
| 8 | Die erzeugten semantischen Pfade prüfen |
| 9 | Ergebnis: WissKI Pathbuilder auf Basis des eigenen Domänenmodells |



### Ressourcen

* [Draw.io diagrams to WissKI pathbuilders Web Service](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/)
* [CIDOC CRM](http://erlangen-crm.org/240307/)
* [Games ontology](http://games.m-e-g-a.org/game_domain.rdf)
* ([Beispiel-Draw.io-XML-Datei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.xml)) funktioniert gerade nicht
* ([Beispiel-Draw.io-Diagramm](https://drive.google.com/file/d/1CzgpEMxGYmfUgI2LUh0J-cbfsfW82T3f/view?usp=sharing))
* ([Beispiel output Pathbuilder-XML-Datei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput.xml))
  

---

## Vorteile der draw.io → Pathbuilder-XML-Pipeline

Diese Pipeline wandelt draw.io-Ontologiediagramme automatisch in WissKI-Pathbuilder-XML-Dateien um und bietet mehrere Vorteile:

* **Zeiteffizienz** – beseitigt den manuellen Konvertierungsaufwand  
* **Ontologie-Wiederverwendung** – nutzt vorhandene Ontologielogik  
* **Konsistenz** – gewährleistet eine einheitliche Struktur über Dateien hinweg  
* **Semantische Integrität** – bewahrt die ursprüngliche Bedeutung und Beziehungen  

---

## Hintergrund: Wie die Pipeline funktioniert

Der [FORTH-ICS-Webdienst](https://isl.ics.forth.gr/gnm_services/):

* analysiert draw.io-Diagramme über eine **JSON-Konfiguration**  
* erkennt **semantische Pfade** von einem **zentralen Ontologieknoten** aus  
* überprüft die **syntaktische Gültigkeit** anhand der Ontologiedateien  
* exportiert die Pfade als **WissKI Pathbuilder XML**


---







