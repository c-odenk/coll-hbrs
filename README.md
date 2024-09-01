# Coll@HBRS | Jobplattform für Studierende der HBRS und Unternehmen aus der Region

<br>

Im Rahmen der Vorlesung "Software Engineering 2" sollte als Semesterprojekt ein Konzept sowie ein erster Prototyp für ein Kollaborationsportal für Studierende der Hochschule Bonn-Rhein-Sieg sowie Unternehmen aus der Region entwickelt werden.
<br>
<br>
Entwickelt wurde die Plattform in einem agilen 8er Team nach Scrum.
<br>
<br>
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![GitLab CI](https://img.shields.io/badge/gitlab%20ci-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-black?style=for-the-badge&logo=sonarqube&logoColor=4E9BCD)
![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)
<br>
<br>
## Aufgabenstellung für die Entwicklung der Kollaborationsplattform "Coll@HBRS:
Ziel war die Entwicklung einer Web-basierten Kollaborationsplattform für Studierende, Unternehmen und der HBRS. Die Plattform soll zur zentralen Anlaufstelle für die Vernetzung zwischen Studierenden und Unternehmen werden und die Suche nach Praktika, Masterarbeiten und beruflichen Einstiegsmöglichkeiten erleichtern. Darüber hinaus soll der Austausch von Lernmaterialien und studentischen Dienstleistungen ermöglicht werden.
<br>
<br>
## Anforderungsanalyse - Funktionale Anforderungen:

<b> Nutzendenprofile: </b>
<br>
<ul>
<li> Studierende, Unternehmen und Hochschulmitarbeiter können individuelle Profile erstellen, die persönliche Daten, fachliche Interessen, Fähigkeiten sowie ein Foto enthalten. </li>
<li> Unternehmen haben die Möglichkeit, grundlegende Unternehmensinformationen und Stellenanzeigen hochzuladen und gezielt nach passenden Studierendenprofilen zu suchen. </li>
</ul>

<b> Erweiterte Suchmöglichkeiten: </b>
<br>
<ul>
 <li> Nutzende können gezielt nach Stellenanzeigen, Projekten und Profilen suchen. </li>
 <li> Unternehmen können Benachrichtigungen über neue und passende Studierendenprofile erhalten. </li>
</ul>

<b> Empfehlungssystem: </b>
<br>
<ul>
 <li> Unternehmen sollen ähnliche Profile vorschlagen werden, basierend auf den bereits eingestellten Studierendenprofilen. </li>
</ul>

<b> Bewertungssystem: </b>
<br>
<ul>
 <li> Studierende und Unternehmen haben die Möglichkeit, sich gegenseitig zu bewerten, um Vertrauen und Transparenz innerhalb der Plattform zu fördern. </li>
</ul>

<b> Benachrichtigungssystem: </b>
<br>
<ul>
 <li> Nutzende erhalten Benachrichtigungen über neue Stellenanzeigen, passende Profile oder andere relevante Ereignisse. </li>
 <li> Nutzende können Benachrichtigungen nach Bedarf zeitweise deaktivieren. </li>
</ul>

<b> Datenschutz und Sicherheit: </b>
<br>
<ul>
 <li> Die Plattform muss ein sicheres Login-System bieten, einschließlich verschlüsselter Übertragung und Speicherung von Daten. </li>
 <li> Nutzende müssen jederzeit die Möglichkeit haben, ihre Profile vollständig zu löschen. </li>
</ul>
<br>

## Anforderungsanalyse - Technische Anforderungen:

<b> Usability und User Experience: </b>
<br>
<ul>
 <li> Die Plattform soll eine einfache und intuitive Bedienung gewährleisten. </li>
 <li> Eine responsive Gestaltung ermöglicht eine optimale Nutzung auf verschiedenen Geräten, einschließlich Smartphones, Tablets und Desktop-Computern. </li>
</ul>

<b> Datenbankanforderungen: </b>
<br>
<ul>
  <li> <b> Datenbank: </b> Alle persistenten Daten müssen in der PostgreSQL-Datenbank der Hochschule gespeichert werden. </li>
  <li> <b> Kompatibilität: </b> Die Datenbank ist kompatibel mit JDBC und JPA. Es wird empfohlen, das DAO-Pattern bzw. das Repository-Pattern für die Abbildung von SQL in Java zu verwenden.</li>
  <li> <b> Zugriffsinformationen: </b> Zugriffsparameter, Treiber und weitere technische Details können vom Scrum Master per E-Mail bei Hr. Ringhausen angefragt werden. </li>
</ul>

<b> Code-Qualität und Testing: </b>
<br>
<ul>
  <li> <b> Technische Schulden: </b> Analyse und Visualisierung technischer Schulden und Code-Smells sollen über das Tool SonarQube erfolgen. </li>
  <li> <b> Testing: </b> Es sollen Roundtrip-Tests durchgeführt werden, um die Datenbank zu validieren. </li>
  <li> <b> Zugriffsinformationen: </b> Zugriffsparameter, Treiber und weitere technische Details können vom Scrum Master per E-Mail bei Hr. Ringhausen angefragt werden. </li>
</ul>

<b> Deployment und Zugriff: </b>
<br>
<ul>
  <li> <b> Deployment-Umgebung: </b> Die Anwendung soll ausschließlich auf den Netzwerkrechnern der Hochschule Bonn-Rhein-Sieg (HBRS) deployt werden. </li>
  <li> <b> Automatisiertes Deployment: </b> Manuelles Deployment ist zu vermeiden; SEPP wird als Tool für das Deployment vorgeschlagen. </li>
  <li> <b> GitLab: </b> Für die Versionskontrolle soll ausschließlich das interne GitLab verwendet werden. Ein Clone des Vaadin-basierten Frameworks CarLook, das bereits Login-Funktionalitäten enthält, sollte erstellt und für das Projekt angepasst werden. </li>
   <li> <b> Externer Zugriff: </b> Externer Zugriff auf SEPP-Rechner erfolgt nur über OpenVPN. </li>
</ul>
<br>
<br>

### Screenshot 1 - Login Page:

![mockup-coll@hbrs-1](https://github.com/user-attachments/assets/17738cbf-f39a-4589-9d68-25274f466416)

### Screenshot 2 - Pageflow der Plattform:

![Arbeitsprobe 6 - Jobplattform Coll@HBRS](https://github.com/user-attachments/assets/0e74ab3c-1184-4fea-9b01-d774919e5eef)

<br>
** Da dieses Projekt im Rahmen einer meiner Vorlesungen entstanden ist und wesentliche Bestandteile der zugrundeliegenden Abhängigkeiten nach ablauf von zwei Semestern nicht mehr für die Studierenden zugänglich sind, wird die Software nicht langfristig lauffähig bleiben. Dies gilt es zu berücksichtigen.
