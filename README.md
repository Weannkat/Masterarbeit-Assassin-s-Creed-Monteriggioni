# Masterarbeit-Assassin-s-Creed-Monteriggioni

Dieses Repo beinhaltet die Dateien und Ergebnisse der räumlichen Untersuchung des realen und fiktiven Monteriggioni, die im Rahmen der Masterarbeit "„Assassin’s Creed“ als Spiegel der Realität?" erhoben wurden. Die Masterarbeit entstand im hochschulübergreifenden Studiengang "Digitale Methodik in den Geistes- und Kulturwissenschaften" an der Hochschule Mainz und der Johannes Gutenberg-Universität Mainz.

## Inhalte des Repositoriums

In diesem Github Repositorium sind folgende Daten zu finden:
- Masterarbeit (PDF Format)
- Wissenschaftliches Poster (begleitend zur Masterarbeit)
- Dateien der Website (begleitend zur Masterarbeit)
- QGIS-Datensätze
- Datensätze, die als Grundlage für die Analyse in *Isovists* dienten
- Bilder der Analyseergebnisse

## Nutzungshinweise

**Website**

Die Website wurde in Visual Studio Code mithilfe von Quarto erstellt. In dem Ordner "Website" finden sich alle Ordner und Quelldateien der Website, ebenso wie die HTML Dateien der einzelnen Unterseiten der Website (zu finden in dem Unterordner _site). Um die Website aufzurufen können, kann entweder der Unterordner _site heruntergeladen  und im Browser geöffnet werden, oder der gesamte Inhalt des "Website"-Ordners, um die Website über VS Code zu starten.
Letzteres erfordert die Installation des Quarto-Plugins in VS Code und den anschließenden Befehl "Quarto preview" im Terminal, um die Website im Localhost anzeigen zu lassen. Einen Installationsguide für Quarto finden Sie [hier](https://quarto.org/docs/get-started/).

**QGIS_Dateien**

In dem Ordner QGIS_Dateien sind die QGIS-Projekte hinterlegt, die im Rahmen dieser Arbeit während des Analyseprozesses entstanden sind. Zu finden sind sowohl die Projektdateien als auch die für die Georeferenzierung entstandenen Points-Dateien und die Geopackages mit diversen Analyselayern.
Sowohl in 'Monteriggioni AC Georeferenzierung' als auch in 'Monteriggioni AC Georeferenzierung2' wurde das reale Monteriggioni mit OSM aufgerufen und versucht zu georeferenzieren. 'Monteriggioni AC Georeferenzierung' zeichnet hier die ersten Versuche ab, in der in der zunächst falschen räumlichen Orientierung alle Transformationsarten getestet wurden. 'Monteriggioni AC Georeferenzierung2' ist der spätere zweite Versuch unter Einbezug der korrekten Orientierung der Stadt. Während verschiedener Georeferenzierungsversuche entstanden mehrere Points-Datensätze - sowohl mit der "korrekten" als auch der falschen Nord-Süd-Orientierung, die ebenfalls hochgeladen wurden.
Die Geopackage-Dateien beinhalten jeweils die Layer für die Untersuchungen innerhalb des realen (Monteriggioni_real.gpkg) und des fiktiven (Monteriggioni.gpkg) Monteriggioni. Diese Layer zeigen die Gebäudelayer, die als Grundlage für die Isovists-Analyse dienten, Punkt-Layer mit Informationen über Events, die dort stattfinden und markieren Polygon-Zonen, denen im Spiel besondere Merkmale zugewiesen wurden.

**Isovists_Dateien**

In diesem Ordner sind die mithilfe von *QGIS* enstandenen Datensätze hinterlegt, die für die *Isovists*-Analysen verwendet wurden.
*Isovists* kann sowohl SVGs als auch dxf-Dateien öffnen, wobei es mit letzterem hin und wieder Probleme hatte und leere Dataien im Arbeitsbereich erschienen sind (mit SVGs trat dieses Problem nicht auf). Da verschiedene Analysen vorgenommen wurden, wurden alle Rohdaten, die dafür verwendte wurden, in diesem Ordner hinterlegt. Das Kürzel AC oder real unterscheidet hierbei um welche Kastellversion es sich handelt.

Zusätzliche Informationen:
Monteriggioni_AC_SMml (= Stadtmauer mit Loch)
Monteriggioni_AC_durchgaenge (Version mit tatsächlichen Navigationsbegebenheiten im Spiel unter Einbezug der Durchgänge und Torbögen, da auf der Spielkarte die Dächer eingezeichnet sind und nicht das Straßennetzwerk)
Monteriggioni_AC_durchgaenge_treppen (Version, die die Treppenaufgänge als eigene Polygone beinhaltet, um einzelne Ebenen betrachten zu können)
Monteriggioni_real2_categorized (Reales Kastell, mithilfe von Inkscape wurden die Polygongruppen "Stadtmauer", "Gebäude" und "Mauern" gruppiert, um es für den Import in Isovists vorzubereiten)
Monteriggioni_real_vegetation (Reales Kastell unter Einbezug der Vegetation, die in QGIS anhand von Satellitenaufnahmen eingepflegt wurden)
Monteriggioni_real_vegetation_Schranke (Reales Kastell unter Einbezug der Vegetation und der Tatsache, dass eine "Mauer" in der Realität scheinbar eine Parkplatzschranke ist, die auf den Karten als Mauer markiert wurde)
