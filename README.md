# Willkommen auf der Informationsseite zum F+E-Projekt "Vet:ProVieh" der Hochschule Osnabrück

* * *

## Projektname:
  Vet:ProVieh - Business 4.0 Lösung für Veterinärmediziner zur Optimierung der Tiergesundheit 

## Projektlaufzeit:  
  3 Jahre (noch nicht gestartet)

## Projektleitung:
Prof. Dr.-Ing. Rainer Roosmann<br>
Professur für Software-Architektur und -Design, Hochschule Osnabrück<br>
Telefonnr.: +49 541 969 3346, E-Mail: [r.roosmann@hs-osnabrueck.de](mailto:r.roosmann@hs-osnabrueck.de)<br>

## Beteiligte Professoren der [Hochschule Osnabrück](https://www.hs-osnabrueck.de/):
* Prof. Dr. Rainer Roosmann: Software-Architektur, DevOps und Software-Entwicklung 
* Prof. Dr. Heiko Tapken: Datenmanagement und -analyse 
* Prof. Dr. Alfred Scheerhorn: IT-Security

## Kooperationspartner: 
* [Münch Gesellschaft für IT-Solutions mbh, Lohne](https://www.muench-its.de/)
* [Niedersächsisches Landesamt für Verbraucherschutz und Lebensmittelsicherheit, Oldenburg](http://www.laves.niedersachsen.de/startseite/)
* [Tierarztpraxis Stephan Göken, Emstek](https://tierarztpraxis-emstek.de/)
* [Tierärztliche Gemeinschaftspraxis WEK, Visbek](http://wek-visbek.de/)
* [iuk-Unternehmensnetzwerk e.V., Osnabrück](https://www.iukos.de/)

## Projektbeschreibung
Die Agrar- und Ernährungswirtschaft stellt in Niedersachsen einen starken Wirtschaftszweig dar, der mit ca. 14% zum Bruttoinlandsprodukt des Bundeslandes beiträgt. Während die Anzahl der landwirtschaftlichen Betriebe über die Jahre kontinuierlich zurückgeht, erhöht sich die Anzahl der gehaltenen Nutztiere pro Betrieb. Im Jahr 2014 betrug der Anteil der Nutztierhaltung Niedersachsens an den bundesdeutschen Gesamtzahlen 20,9% für Rindvieh, 31,4% für Schweine, 38,7% für Legehennen und 64,4% für Masthühner / -hähne.

Die Branchen dieses Wirtschaftszweiges stehen seit Jahren vor großen Herausforderungen aufgrund von Konzentrations-, Spezialisierungs- und Intensivierungsprozessen. Damit einher gehen Probleme im Bereich der Tiergesundheit, die u. a. auf diese Prozesse zurückzuführen sind. Die Medikamentierung und konkret der Einsatz von Antibiotika im Kampf gegen Infektionskrankheiten, wird aktuell kritisch beobachtet, da der Anteil an antibiotikaresistenten Bakterien für die meisten Bakterienstämme in den letzten Jahren zugenommen hat.

Wesentlichen Einfluss auf die Medikamentierung bei Nutztieren haben die 1.622 im Jahr 2015 in Niedersachsen niedergelassenen Tierärzte, da hier die nachhaltige tiergesundheitliche Betreuung erfolgt. Die Anforderungen an das Betreuungsmanagement der Tierärzte, von der Anwendung der Medikamente nach §58b Abs. 1 Nr. 1-4 AMG, bis hin zur Beratung der Landwirte bezüglich der Maßnahmen zur Reduzierung des Antibiotikaeinsatzes nach AMG §58d Abs. 2, werden immer komplexer. Es ist absehbar, dass die Anforderungen an die Tierärzte zukünftig weiter zunehmen.

Das Ziel dieses Projektes ist es, eine internetgestützte Business 4.0 Lösung für Nutztierpraxen aufzubauen, um diese bei der Erfüllung ihrer Aufgaben optimal zu unterstützen. Tierärzte / Tierarztpraxen stellen einen wichtigen Faktor in einer Qualitätslandwirtschaft dar und tragen zur Wahrung des Tierwohls, sowie zur Verminderung negativer Auswirkungen auf Mensch und Umwelt bei. Die aufzubauende Business 4.0 Umgebung soll auf die Optimierung der Tiergesundheit ausgerichtet sein. Konkret sollen Tierärzte bei der Dokumentation meldepflichtiger Medikamente und dem Beratungsmanagement zur Reduzierung des Antibiotikaeinsatzes in der Nutztierhaltung unterstützt werden. Neu entwickelte Software soll im Sinne einer Business 4.0 Lösung mit vorhandenen Softwareprodukten interagieren und eine Anwendung wie „aus einem Guss“ ermöglichen. Erkenntnisse und Ergebnisse dieses Forschungsprojektes werden kostenfrei und quelloffen zur Verfügung gestellt und sollen den Ausbau der digitalen Wirtschaft und das Innovationspotential in der Region vorantreiben.

Die zu erstellende Software soll es ermöglichen, a) Probleme bei der Nutztierhaltung zu identifizieren und zu analysieren, b) proaktive und reaktive Maßnahmen zu planen, zu überwachen und zu evaluieren, c) eine Wissensbasis aufbauen und d) auf dieser Basis Best-Practises für eine effektive und effiziente Beratung bei der Erstellung von Maßnahmenplänen zu generieren und bereitzustellen. Die Best-Practises können in Absprache der Nutztierpraxis mit dem Tierhalter verschiedenen Nutzergruppen zugänglich gemacht werden. Eine Bereitstellung erfolgreicher, anonymisierter Maßnahmen für bekannte, wiederkehrende Problemfälle kann u. a. über die vorhandene Internetplattform Aniplus (www.aniplus.de) erfolgen.

Zur Umsetzung der Business 4.0 Lösung für Veterinärmediziner wird eine Software-Architektur benötigt, die bestimmte Eigenschaften aufweist, konkret hinsichtlich der Wartbarkeit (speziell der Änderbarkeit), Performance (speziell der Skalierbarkeit), Sicherheit und Zuverlässigkeit (speziell der Verfügbarkeit und Resilience). Reaktive Microservices und Self-Contained-Systems stellen Stile dar, die als cloud-native Software-Architekturen genau diese Merkmale versprechen und deren Anwendung im Rahmen dieses Projekt untersucht werden sollen.

Die Einhaltung der definierten Eigenschaften ist allerdings nur über den massiven Einsatz von DevOps-Konzepten und Technologien, inkl. der Containierisierung (bspw. über Docker und entsprechenden Werkzeugen zur Integration und Verwaltung), zu gewährleisten. Zur Unterstützung von Software-Entwicklung, -Testing, -Deployment, -Betrieb und -Evolution ist eine Automatisierungsinfrastruktur initial aufzubauen, um wesentliche Aufgaben automatisch zu erfüllen.

Das Thema Sicherheit ist besonders hoch zu gewichten. Zwischen dem Tierhalter und dem Tierarzt herrscht ein Vertrauensverhältnis. Lassen sich bspw. Daten von Tierhaltern von nicht autorisierten Personen abfragen oder gar verfälschen, so kann dies enorme Auswirkungen, bis hin zum finanziellen Bankrott des betroffenen Unternehmens haben. Entsprechend ist das Qualitätsmerkmal „Sicherheit“ bei der Entwicklung der Vet:ProVieh Software auf unterschiedlichen Ebenen zu betrachten, um a) den Zugriff auf authentifizierte Nutzer (Personen und Rollen) zu beschränken, b) Datenintegrität zu gewährleisten, so dass Daten nicht unautorisiert und unbemerkt manipuliert werden können, c) Informationsvertraulichkeit zu gewährleisten, so dass nur autorisierte Nutzer konfigurierbare Sichten auf Informationen erlangen, sowie Aktionen ausführen können und d) Aktionen einzelnen Nutzern eindeutig zuzuordnen, um eine Verbindlichkeit durchgeführter Transaktionen zu garantieren.

Es ist zu erwarten, dass bei einem Erfolg der Business 4.0 Lösung für Veterninärmediziner sehr viele Daten verwaltet werden müssen. Zudem bedarf es zur optimalen und möglichst automatisierten Unterstützung der schon weiter oben genannten Aufgaben, nämlich
* Probleme bei der Nutztierhaltung zu identifizieren / analysieren / bewerten,
* proaktive und reaktive Maßnahmen zu planen / überwachen / evaluieren und 
* auf einer Wissensbasis Best-Practises abzuleiten, 

entsprechender Werkzeuge bzw. Systeme zur Datenanalyse. Im Rahmen dieses Projektes sollen die Themen Big-Data, Datenanalyse und Business Intelligence nur in soweit betrachtet werden, um Vorkehrungen für eine spätere Integration zu treffen und dies möglichst in der Software-Architektur vorzubereiten.

Bei weiteren Fragen zum Projekt, wenden Sie sich gerne an den [Projektleiter](mailto:r.roosmann@hs-osnabrueck.de).
