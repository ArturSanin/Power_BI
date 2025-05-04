# A

## Abfrage (Power Query)
Eine Abfrage in Power BI (Power Query) ist eine Schritt-für-Schritt-Anweisung, mit der Daten aus einer Quelle geladen, transformiert und für das Datenmodell bereitgestellt werden. Jede Abfrage besteht aus einer Reihe von Transformationen, die als einzelne Schritte dargestellt werden. Abfragen können miteinander verknüpft, gefiltert, gruppiert oder kombiniert werden und dienen als Grundlage für die späteren Tabellen im Datenmodell.

## Aggregation
Aggregation ist der Vorgang, bei dem eine Datenmenge auf einen einzigen Wert zusammengefasst wird. Typische Aggregationen sind zum Beispiel das Summieren, Zählen, Ermitteln des Maximums oder Minimums.

## Aus Modell löschen
„Aus Modell löschen“ ist eine Option im Kontextmenü von Tabellen, Spalten oder Measures in Power BI. Mit dieser Funktion wird das ausgewählte Objekt dauerhaft aus dem Datenmodell entfernt. Diese Aktion löscht das Objekt nur aus dem Modell, nicht jedoch aus der Datenquelle. Sie ist besonders hilfreich zur Bereinigung und Optimierung des Datenmodells.


## Ausblenden
Ausblenden ist eine Funktionalität in Power BI, mit der Objekte des Datenmodells – wie Spalten, Tabellen, Measures – sowie Berichtselemente wie der Filterbereich oder einzelne Filterkarten für Endanwender unsichtbar gemacht werden können. Diese Funktion stellt sicher, dass nur relevante Elemente im Bericht oder Datenmodell sichtbar sind.



# B

## Berechnete Spalte
Eine mit einer DAX-Formel erstellte Spalte innerhalb einer Tabelle im Power BI-Datenmodell. 

## Berechnete Tabelle
Eine durch eine DAX-Formel erzeugte Tabelle, die im Power BI-Datenmodell wie eine normale Tabelle genutzt werden kann.

## Berichtsansicht
Die Berichtsansicht ist die visuelle Arbeitsfläche in Power BI Desktop, auf der interaktive Visualisierungen, Diagramme, KPIs und Dashboards erstellt werden. Hier werden Felder aus dem Datenmodell in Visuals platziert und das Layout des Berichts gestaltet.

## Beziehung
Eine Beziehung ist die Verknüpfung zwischen zwei Tabellen über Primär- und Fremdschlüssel. In Power BI ermöglicht sie das Filtern und Kombinieren von Daten aus mehreren Tabellen.

## Beziehungen verwalten
„Beziehungen verwalten“ ist eine Funktion in Power BI Desktop, mit der sich die Beziehungen zwischen Tabellen im Datenmodell anzeigen, bearbeiten, entfernen oder neu erstellen lassen. Die Funktion bietet eine übersichtliche Darstellung aller vorhandenen Verknüpfungen und unterstützt die strukturierte Verwaltung der Beziehungen im Datenmodell.

## Brückentabelle
Eine Brückentabelle ist eine Hilfstabelle im Datenmodell, die verwendet wird, um viele-zu-viele-Beziehungen zwischen zwei Tabellen – häufig einer Faktentabelle und einer Dimensionstabelle – korrekt abzubilden. Die Brückentabelle enthält in der Regel nur Schlüsselspalten.



# C

## Canvas 
Der Canvas ist der Bereich einer Berichtsseite in Power BI, in den Visualisierungen und andere Elemente eingefügt werden. Hier wird der Bericht visuell aufgebaut und gestaltet.

# D

## Datenbereich (Data Pane)
Der Datenbereich (engl. Data Pane) in Power BI Desktop ist der Bereich auf der rechten Seite der Benutzeroberfläche, in dem alle Tabellen, Spalten, Measures und Hierarchien des Datenmodells angezeigt werden. Aus diesem Bereich können Felder per Drag-and-drop in Visualisierungen gezogen werden. Der Datenbereich bietet direkten Zugriff auf alle Modellobjekte.

## DAX-Abfrageansicht
Die DAX-Abfrageansicht ist eine Spezialansicht für die Erstellung und Auswertung von DAX-Abfragen. Hier können benutzerdefinierte DAX-Statements geschrieben werden, um beispielsweise Berechnungen zu testen oder tiefergehende Analysen durchzuführen.

## Denormalisierung
Denormalisierung ist das Gegenstück zur Normalisierung. Dabei wird das Datenmodell abgeflacht, indem redundante Informationen in Tabellen aufgenommen werden. Ziel ist es, Abfragen zu vereinfachen und unter Umständen die Leistung zu verbessern.

## Dimensionstabelle
Eine Dimensionstabelle enthält beschreibende Informationen, die zur Einordnung, Filterung und Gruppierung der Fakten aus der Faktentabelle verwendet werden – z. B. Produktnamen, Kundendaten, Regionen oder Zeitangaben. Sie enthält mindestens eine Schlüsselspalte, die jede Zeile eindeutig identifiziert und mit der Faktentabelle verknüpft wird. Dimensionstabellen liefern den kontextuellen Rahmen für Analysen im Datenmodell.

## Drilldown
Drilldown ist eine Interaktionsfunktion in Power BI, mit der man in hierarchischen Daten von einer aggregierten Ebene (zum Beispiel Jahr) auf detailliertere Ebenen (zum Beispiel Quartal, Monat, Tag) navigieren kann. Durch Klicken auf ein Visual mit integrierter Hierarchie kann man sich schrittweise tiefer in die Datenstruktur hineinbewegen, um genauere Einblicke zu gewinnen. Drilldowns werden häufig bei Zeit-, Produkt- oder Geohierarchien eingesetzt.

# E

# F

## Faktentabelle
Eine Faktentabelle enthält die messbaren Werte (auch Fakten genannt) eines Unternehmens, wie zum Beispiel Umsätze, Kosten oder Mengen. Sie steht im Zentrum eines Datenmodells und ist über Schlüsselspalten mit Dimensionstabellen verknüpft. Die Faktentabelle wird hauptsächlich für Berechnungen und Analysen verwendet.

## Feld
Ein Feld ist eine einzelne Spalte innerhalb einer Tabelle. In Power BI wird der Begriff „Feld“ oft synonym mit „Spalte“ verwendet – insbesondere im Kontext von Visualisierungen.

## Filter auf Berichtsebene
Ein Filter auf Berichtsebene ist ein Filter, der sich auf alle Seiten eines Power BI-Berichts auswirkt. Er wird im Filterbereich im Abschnitt „Filter für alle Seiten“ konfiguriert und beeinflusst sämtliche Visuals in allen Seiten des Berichts.

## Filter auf Seitenebene
Ein Filter auf Seitenebene ist ein Filter in Power BI, der sich ausschließlich auf eine einzelne Berichtsseite auswirkt. Er wird im Filterbereich unter dem Abschnitt „Filter für diese Seite“ konfiguriert und beeinflusst alle Visuals auf der jeweiligen Seite, jedoch nicht die übrigen Seiten des Berichts.
Diese Filterart eignet sich ideal für Seiten mit einem speziellen Fokus oder Zielpublikum.

## Flaches Schema
Ein flaches Schema ist ein Modellierungskonzept, bei dem alle Fakten und Dimensionen in einer einzigen, nicht normalisierten Tabelle zusammengeführt sind. Es gibt keine separaten Dimensionstabellen – alle Informationen befinden sich in einer zentralen Tabelle. Typische Beispiele für dieses Schema sind Excel- oder CSV-Datenquellen.

## Fremdschlüssel
Ein Fremdschlüssel ist eine Spalte oder eine Kombination mehrerer Spalten in einer Tabelle, die auf den Primärschlüssel einer anderen Tabelle verweist. Fremdschlüssel werden häufig in Faktentabellen verwendet, um diese mit den für die Analyse relevanten Dimensionstabellen zu verknüpfen.

# G

## Galaxieschema (Faktenkonstellationsschema)
Das Galaxieschema ist ein Modellierungskonzept, das aus mehreren Faktentabellen besteht, die sich gemeinsame Dimensionstabellen teilen. Diese gemeinsame Nutzung ermöglicht die Analyse unterschiedlicher Fakten entlang derselben Dimensionen.

## Granularität 
Die Granularität beschreibt das Detailniveau der Daten in einem Datenmodell oder einer Tabelle. So haben beispielsweise Tabellen, in denen jeder einzelne Umsatz erfasst wird, eine höhere Granularität (sind also detaillierter) als Tabellen, in denen Umsätze pro Tag zusammengefasst werden.
Durch Aggregation kann man von einer hohen Granularität zu einer niedrigeren Granularität gelangen – der umgekehrte Weg ist jedoch nicht möglich.
Daten mit hoher Granularität ermöglichen tiefere und präzisere Analysen, da sie mehr Kontext und Differenzierung bieten.

## Gruppieren nach (Power Query)
„Gruppieren nach“ ist eine Funktion im Power Query Editor, mit der Zeilen einer Tabelle nach dem Wert eines oder mehrerer Felder gruppiert werden. Dabei können Aggregationen wie Summe, Anzahl, Minimum oder Maximum auf andere Spalten angewendet werden. Diese Funktion wird häufig verwendet, um zusammengefasste Ansichten von Daten zu erstellen.

## Gruppierung 
Gruppierung ist ein Konzept, bei dem Datensätze nach bestimmten Merkmalen zusammengefasst werden, zum Beispiel nach Produkt, Region oder Zeitraum. Dies dient oft als Basis für Aggregationen.



# H

## Hierarchie
Eine Hierarchie in Power BI ist eine strukturierte Anordnung von Feldern innerhalb einer Tabelle, die eine logische Ebenenabfolge darstellt – zum Beispiel Jahr > Quartal > Monat > Tag oder Kontinent > Land > Region > Stadt. Hierarchien ermöglichen es, Drilldown-Analysen durchzuführen, also von einer höheren Detailebene zur nächsten zu navigieren. Sie verbessern die Benutzerfreundlichkeit und Analysefähigkeit von Berichten, da sie häufig genutzte Beziehungsebenen bündeln und logisch anordnen.

## Hybridtabelle
Eine Hybridtabelle in Power BI ist eine Tabelle, die mehrere Speichermodi kombiniert, typischerweise Import und DirectQuery. Dabei werden beispielsweise historische Daten importiert (für schnelle Abfragen) und aktuelle Daten per DirectQuery in Echtzeit abgefragt. Dies ermöglicht ein gutes Gleichgewicht zwischen Performance und Aktualität der Daten.

# I

## Import-Modus
Der Import-Modus ist ein Speichermodus, bei dem die Daten aus der Quelle in Power BI geladen und dort gespeichert werden. Alle Daten sind direkt im Power BI-Modell vorhanden, was eine schnelle Abfrageleistung ermöglicht, da keine Verbindung zur externen Quelle während der Nutzung erforderlich ist.

## Importmodell
Ein Importmodell ist ein Power BI-Datenmodell, bei dem alle Modelltabellen den Speichermodus „Import“ haben. In diesem Modelltyp werden alle Daten direkt in Power BI geladen und gespeichert.

## Inkrementelle Aktualisierung 
Die inkrementelle Aktualisierung ist eine Funktion in Power BI, mit der nur neue oder geänderte Daten einer Tabelle bei einer Aktualisierung geladen werden – anstatt die gesamte Tabelle jedes Mal neu zu importieren. Dies spart Ressourcen, reduziert Ladezeiten und ermöglicht die Verarbeitung von großen Datenmengen.

# J



# K

 ## Konnektor
Ein Konnektor in Power BI ist eine Verbindungslösung, mit der Power BI auf eine bestimmte Datenquelle zugreifen und Daten daraus laden kann. Damit können Daten aus einer Vielzahl von Datenquellen in das Power BI-Datenmodell integriert werden. 





# L

# M

## M (Power Query Formula Language)
M ist eine funktionale Programmiersprache, die speziell für Datenaufbereitung und ETL-Prozesse (Extract, Transform, Load) entwickelt wurde. Sie wird verwendet, um Transformationen von Datenquellen zu definieren, zu bearbeiten und zu speichern. M ist die Programmiersprache, die hinter dem Power Query Editor in Power BI steht. Alle Schritte, die im Power Query Editor durchgeführt werden, werden intern als M-Code gespeichert. 

## Measure (Kennzahl)
Ein Measure ist eine berechnete Kennzahl im Power BI-Datenmodell, die mithilfe der Formelsprache DAX erstellt wird.

## Modellansicht
Die Modellansicht visualisiert die Beziehungen zwischen Tabellen im Datenmodell. Hier lassen sich Beziehungen erstellen, bearbeiten oder löschen, Tabellen organisieren sowie Eigenschaften wie Sichtbarkeit oder Sortierreihenfolge festlegen.

# N 

## Normalisierung
Normalisierung ist ein Verfahren in der Datenmodellierung, bei dem Redundanzen (doppelte oder mehrfach gespeicherte Informationen) vermieden werden, indem Daten in mehrere logisch verknüpfte Tabellen aufgeteilt werden. Die Verknüpfung dieser Tabellen erfolgt über Primär- und Fremdschlüsselbeziehungen. Dabei enthält die normalisierte Tabelle einen Fremdschlüssel, der auf den Primärschlüssel einer anderen Tabelle verweist – jene Tabelle, in der die zuvor redundanten Informationen nur noch einmalig gespeichert sind.

# O  

# P  

## Partition
Eine Partition ist ein logisch abgegrenzter Teilbereich einer Tabelle, der separat geladen, verarbeitet und aktualisiert werden kann. Partitionen ermöglichen eine effizientere Datenverarbeitung, da nur bestimmte Teile einer Tabelle (z. B. aktuelle Daten) regelmäßig aktualisiert werden müssen, während andere (z. B. historische Daten) unverändert bleiben. In Power BI werden Partitionen vor allem bei großen Tabellen oder Hybridtabellen verwendet, um die Performance und Datenaktualität zu optimieren.

## Power Query Editor
Der Power Query Editor ist eine grafische Benutzeroberfläche in Power BI, mit der sich Daten importieren, bereinigen und transformieren lassen. Alle durchgeführten Transformationen werden im Hintergrund mit der Sprache M (Power Query Formula Language) aufgezeichnet und automatisiert ausgeführt, sobald die Daten aktualisiert werden.

## Primärschlüssel
Ein Primärschlüssel ist eine Spalte oder eine Kombination mehrerer Spalten, die jede Zeile einer Tabelle eindeutig identifiziert. In einer Dimensionstabelle dient der Primärschlüssel dazu, eine Beziehung zu anderen Tabellen – etwa einer Faktentabelle – herzustellen.



# Q  

# R  

# S  

## Schneeflockenschema
Ein Schneeflockenschema ist ein Modellierungskonzept, das dem Sternschema ähnelt. Im Gegensatz zum Sternschema können Dimensionstabellen im Schneeflockenschema weiter normalisiert sein und Beziehungen zu anderen Dimensionstabellen besitzen. 

## Semantische Modell
Ein semantisches Modell in Power BI besteht aus allen verknüpften Datenquellen, den Datentransformationen, den Beziehungen zwischen den Tabellen sowie allen Berechnungen (z. B. Measures und berechneten Spalten), die auf Basis dieser Daten erstellt wurden. Es bildet die Grundlage für die Erstellung von Berichten und die Analyse der Daten.

## Sternschema
Das Sternschema ist ein Modellierungskonzept, bei dem eine zentrale Faktentabelle mit einer oder mehreren Dimensionstabellen verknüpft ist. Die Dimensionstabellen dienen der Filterung und Gruppierung der Daten in der Faktentabelle. Diese Filterungen und Gruppierungen wirken sich direkt auf Measures aus, die auf der Faktentabelle basieren, und beeinflussen somit die Berechnung und Anzeige von Kennzahlen in Berichten.



# T

## Tabellarisches Modell 
Ein tabellarisches Modell ist ein Datenmodell, bei dem die Daten in Tabellen strukturiert und organisiert sind. In Power BI ist jedes Datenmodell ein tabellarisches Modell, da die Daten in Tabellen gespeichert und Beziehungen zwischen diesen Tabellen hergestellt werden.

## Tabellenansicht
Die Tabellenansicht zeigt die Daten der Tabellen im Power BI-Modell in tabellarischer Form. Sie dient zur Überprüfung von Daten, berechneten Spalten oder Measures und ist hilfreich für die Datenvalidierung und das Verständnis der zugrunde liegenden Daten.



# U  

# V  

## Visualisierungsbereich
Der Visualisierungsbereich in Power BI Desktop ist die rechte Seitenleiste, in der man Visualtypen auswählen, Formatierungen anpassen und Feldzuweisungen (Achsen, Werte, Legenden usw.) für das aktuell ausgewählte Visual konfigurieren kann.

# W  

# X  

# Y  

# Z  

## Zu Filtern hinzufügen
„Zu Filtern hinzufügen“ ist eine Option im Kontextmenü einer Spalte in Power BI. Mit dieser Funktion wird die ausgewählte Spalte automatisch dem Filterbereich hinzugefügt. Dabei kann ausgewählt werden, ob der Filter nur auf die aktuelle Berichtsseite oder auf alle Seiten des Berichts angewendet werden soll. Diese Funktion erleichtert das schnelle Erstellen von Seiten- oder Berichtfiltern.

