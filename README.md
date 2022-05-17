# Robotic Process Automation mit UiPath

In dem Projekt werden konkrete, praxisorientierte RPA-Szenarien entwickelt und beispielhaft in 
der UIPath-Plattform umgesetzt. Die Ergebnisse des Projektes sind somit: 
- Beschreibung der RPA-Szenarien 
- Umsetzung in der UIPath-Plattform 
- Dokumentation der Umsetzung

Das aktuelle Ziel ist es ein vereinfachtes ERP mittels UIPath zu automatisieren. Hierfür sollen die Benutzeroberflächen
von Outlook, Excel und PDF Dokumenten unter Betracht gezogen werden. 

1.	Emails von Kunden im Mail Client (Outlook) einlesen **FATIH**<br/>
a. Hierbei muss beachtet werden, dass auch nur Mails von Kunden eingelesen werden und keine andere. Vorschlag: Der Benutzer kann eine Liste von Kunden angeben, wessen Emails eingelesen werden sollen <br/>
b.	Eventuell eine automatisierte Bestätigungsmail an den Kunden senden

2.	E-Mail-Anhang (Excel-Datei, PDF-Datei oder sogar Mail Inhalt) in spezifizierten Ordner (welcher der Benutzer angeben kann) abspeichern. **TODO**

&ensp; 3.1 WENN Excel-Datei **MERT + MARVIN**

- Berechnen, welche und wie viele Komponenten zur Herstellung der vom Kunden gewünschten Ware benötigt werden. Bsp: Ein Rollcontainer benötigt zur Herstellung 4 Roller, 20 Schrauben, 3 kleine Holzplatten, …
- Nachdem wir nun wissen wie viele Komponenten wir benötigen muss geprüft werden, ob wir diese im Lager haben. Es sollte dabei eine neue Excel Datei erstellt werden mit der Anzahl an Komponenten die nicht auf Lager sind und bei Lieferanten bestellt werden müssen => EXCEL Datei für Lieferanten

&ensp; 3.2 WENN PDF-Datei oder Mail Inhalt **FATIH + NILS** mit java; **JULIEN + MERT** mit understand_document_plugin von UIPath <br/>
- Gleiche Schritte wie oben, nur das vorher eine KI über den Text geworfen werden muss, welche vllt eine Excel Datei aus dem interpretierten Text entwirft.

4.	Excel Datei mit fehlenden Herstellungsteilen interpretieren und automatisierte Mails an den Lieferanten mit den benötigten Komponenten senden **FATIH´s Outlook Handling wiederverwenden**

**Michael** => PDF und Mail-Inhalte von Kunden und für Lieferanten erstellen + Schlüsselwörter für KI in .txt Datei vorbereiten
