1) Entwicklungsumgebung einrichten
* Maven 2 installieren (http://maven.apache.org/)
* Spring Toolsuite installieren (http://www.springsource.org/downloads/sts)
* Activiti Plugin für Eclipse installieren (Update Site: http://activiti.org/designer/update/)

2) Projekt bauen
* Kommondozeile: "mvn clean install" im Projekt Root-Verzeichnis

3) Projekt in Spring Toolsuite importieren
* "Import > Existing Maven Projects" (Projekt Root-Verzeichnis auswählen)
* Projekt "activiti-tweets-process" per "Run as > Run on Server" auf dem VMWare vFabric tc Server deployen

4) Projekt aufrufen
* Activiti Tweets Demo Frontend: http://localhost:8080/activiti-tweets-process/
* Activiti Explorer: http://localhost:8080/activiti-tweets-process/activiti-explorer (Login: kermit / kermit)