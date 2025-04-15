# 💼  Coll@HBRS – Die Jobplattform für Studierende und Unternehmen der Region


Coll@HBRS ist eine webbasierte Kollaborationsplattform, die im Rahmen der Lehrveranstaltung Software Engineering 2 an der Hochschule Bonn-Rhein-Sieg konzipiert und entwickelt wurde. Ziel war es, eine zentrale Schnittstelle zwischen Studierenden der HBRS und Unternehmen aus der Region zu schaffen.

Das Projekt wurde in einem achtköpfigen Scrum-Team agil umgesetzt. Ergebnis ist ein erster funktionsfähiger Prototyp, der Studierenden und Unternehmen eine einfache und strukturierte Möglichkeit zur Vernetzung bietet.
<br>
<br>

## 🎯 Projektziel
Die Plattform soll den Austausch zwischen Studierenden, Unternehmen und Hochschulmitarbeitenden fördern. Im Fokus stehen:
<br>
<ul>
 <li>die Vermittlung von Praktika, Abschlussarbeiten und Berufseinstiegen</li>
 <li>der Austausch von Lernmaterialien</li>
 <li>studentische Dienstleistungen</li>
 <li>ein Empfehlungssystem und Bewertungstools zur Förderung von Vertrauen und Transparenz</li>
</ul>
<br>

## Funktionale Anforderungen:

<b> 👤 Nutzerprofile: </b>
<br>
<ul>
<li> Studierende, Unternehmen und Hochschulmitarbeitende können individuelle Profile mit persönlichen Daten, Interessen und Qualifikationen anlegen </li>
<li> Unternehmen können Stellenanzeigen veröffentlichen und gezielt nach passenden Studierenden suchen </li>
</ul>

<b> 🔎 Erweiterte Suche & Empfehlungen: </b>
<br>
<ul>
<li> Suche nach Profilen, Projekten oder Stellenanzeigen </li>
<li> Unternehmen erhalten Empfehlungen zu ähnlichen Studierendenprofilen </li>
</ul>

<b> ⭐ Bewertung & Benachrichtigung: </b>
<br>
<ul>
<li> Gegenseitige Bewertungen zwischen Studierenden und Unternehmen möglich </li>
<li> Echtzeit-Benachrichtigungen über neue Einträge (deaktivierbar) </li>
</ul>

<b> 🔐 Datenschutz & Sicherheit: </b>
<br>
<ul>
<li> Sicheres Login-System, verschlüsselte Datenübertragung </li>
<li> Profile können vollständig gelöscht werden </li>
</ul>
<br>

## 🧩 Technische Anforderungen:

<b> 🖥 Usability & UX: </b>
<br>
<ul>
<li> Intuitive Bedienbarkeit </li>
<li> Responsives Design für Desktop, Tablet und Mobile </li>
</ul>

<b> 🗄 Datenbank: </b>
<br>
<ul>
<li> IPostgreSQL-Datenbank der HBRS </li>
<li> JDBC/JPA-kompatibel, empfohlen wird das DAO-/Repository-Pattern </li>
</ul>

<b> 🧪 Codequalität & Testing: </b>
<br>
<ul>
<li> Intuitive Bedienbarkeit </li>
<li> Roundtrip-Tests zur Validierung der Datenbank </li>
</ul>

<b> 🚀 Deployment: </b>
<br>
<ul>
<li> Deployment erfolgt ausschließlich auf HBRS-Rechnern (SEPP-Umgebung) </li>
<li> Automatisiertes Deployment mit SEPP (kein manuelles Deployment) </li>
<li> Zugriff ausschließlich über OpenVPN </li>
</ul>
<br>

## 🧪 Eingesetzte Technologien

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

### Screenshot 1 - Login Page:

![mockup-coll@hbrs-1](https://github.com/user-attachments/assets/17738cbf-f39a-4589-9d68-25274f466416)

### Screenshot 2 - Pageflow der Plattform:

![Arbeitsprobe 6 - Jobplattform Coll@HBRS](https://github.com/user-attachments/assets/0e74ab3c-1184-4fea-9b01-d774919e5eef)

<br>
** Da dieses Projekt im Rahmen einer meiner Vorlesungen entstanden ist und wesentliche Bestandteile der zugrundeliegenden Abhängigkeiten nach ablauf von zwei Semestern nicht mehr für die Studierenden zugänglich sind, wird die Software nicht langfristig lauffähig bleiben. Dies gilt es zu berücksichtigen.
