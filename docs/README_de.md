<h1 align="center">GameIndustry host Templates</h1>
<h3 align="center">Einzigartige Host Templates zur Verbesserung der eigenen Privatsphäre in Spielen, Webseiten und regulärer Software</h3>

<br />
	
<h3 align="center">
  <a href="https://github.com/KodoPengin/GameIndustry-hosts-Template/issues">Fehler melden</a>
  <span> · </span>
  Support: <a href="https://github.com/KodoPengin/GameIndustry-hosts-Template/discussions">Diskussionen</a>
  <span> · </span>
  <a href="../README.md">Englisch</a>
</h3>
 <p align="center">
    <a href="https://github.com/KodoPengin/GameIndustry-hosts-Template/watchers"><img alt="Watchers" src="https://img.shields.io/github/watchers/KodoPengin/GameIndustry-hosts-Template.svg?color=0088ff" /></a>
    <a href="https://github.com/KodoPengin/GameIndustry-hosts-Template/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/KodoPengin/GameIndustry-hosts-Template.svg?color=0088ff" /></a>
    <a href="https://github.com/KodoPengin/GameIndustry-hosts-Template/network/members"><img alt="Mitglieder" src="https://img.shields.io/github/forks/KodoPengin/GameIndustry-hosts-Template.svg?color=0088ff" /></a>
    <a href="https://github.com/KodoPengin/GameIndustry-hosts-Template/issues"><img alt="Gemeldete Fehler" src="https://img.shields.io/github/issues/KodoPengin/GameIndustry-hosts-Template.svg?color=0088ff" /></a>
    <a href="https://gameindustry.eu"><img alt="Webseite" src="https://img.shields.io/badge/webseite-online-blue?url=https%3A%2F%2Fgameindustry.eu?color=0088ff" /></a>
  </p>
<br />

## 📝 Projektbeschreibung
Business-Analysen, Spyware, Tracking-Cookies in Spielen und Clients und damit teilweise selbstlegitimierter Datenklau sind heutzutage weithin akzeptiert und oftmals nach "Friß oder Stirb" Prinzip dem Verbraucher aufgezwängt.

Die von mir veröffentlichten Hostdateien bieten einen verbesserten Schutz vor Tracking, Spyware, Telemetrie, Malware, Werbung und Weiterleitungen in Spielen, auf Webseiten und in regulären Programmen für Desktop und Mobilanwendungen.

Es werden keine Programme von Drittanbietern oder komplizierte und teure Installationsmedien (PI) benötigt.

### Besondere Merkmale:
- Funktioniert auf jedem Gerät. Systemweit
- Geblockte Einträge für über 1600 Spiele inklusiv der wichtigsten Gaming-Clients dieser Zeit
- Über 31000 Zeilen
- Regelmäßig aktualisiert
- Einträge für Software, Spiele, Webseiten und IoT
- Datenschutzverletzende Tech-Unternehmen wie Facebook werden blockiert
- Ein großer Teil der ausgehenden Verbindungen von Windows (xx) und Microsoft-Spielen wurde blockiert
- Keine Ausnahmen für große Unternehmen
- Modularer Aufbau - Nutze nur die Einträge die benötigt werden
- Alle Einträge sind nach Produktnamen, Herausgeber, Website und Firmennamen kategorisiert
- Kommentare und Zusatzinformationen zu einzelnen Einträgen (deutschsprachig)
- Verbindungen nach Produkt aufgelistet um den Konsumenten zu zeigen, welche Dinge zu welchem Produkt gehören
- Zusätzliche Ipv4 und Ipv6 Einträge, um diese bei Bedarf in der eigenen Firewall zu blockieren

### Host Versionen
- Haupt-Template: Software, Webseiten, Treiber, Technologiefirmen, Gaming Clients, Spiele und mehr
- Mini-Vorlage für Spiele: Blockiert die gängigsten Spiele-Analytics, Spyware, Werbung in PC-Spielen. Sonst nichts
- Gaming-Vollversion: Blockiert Telemetrie, Spielanalyse, Spyware und unnötige Verbindungen für Gaming-Clients und Spiele auf und für mehrere Plattformen.
- Android Mini-Template: Blockiert die gängigsten Spiele-Analytics, Werbung, Spyware und Werbedienste in Android-Spielen und Software
- Android Full-Template: Blockiert Telemetrie, Werbung, Spielanalyse, Spyware und unnötige Verbindungen für mehrere Android-Produkte. Ausnahmslos produktbezogen

## 📖 Installation
Bitte beachten, dass die Hosts je nach System schreibgeschützt sein können oder Root-Rechte erfordern
### Kopieren & Einfügen:
- Öffnen Sie die Datei auf Github, "Save as hosts" ohne Suffix... und kopieren Sie die Datei in eines der aufgeführten Verzeichnisse.
- Alternativ zum "Speichern unter" ist es auch möglich, den Seiteninhalt zu kopieren und in eine bestehende Datei einzufügen

Windows: %SystemRoot%\System32\drivers\etc\hosts<br>
Linux: /etc/hosts<br>
Android: /etc/hosts (a symbolic link to /system/etc/hosts)

## Einfach zu verwendende Setup-Datei:
Für eine einfache Nutzung wurde eine Host-Datei-Setup erstellt. Starte das Setup, wähle eine von 5 Vorlagen und installiere.<br>
Quelle: <a href="https://www.gameindustry.eu/de/downloads/">GameIndustry Downloads</a><br>

Unterstützt bisher: Deutsch, Englisch und Japanisch

### Screenshots:
<p float="left">
<img src="https://www.gameindustry.eu/images/git/Setup_Uebersicht.webp" alt="Gi-HostsInstaller">
</p>

## ⚠ Dinge die zu bedenken sind
Das Blockieren von Programmkomponenten bringt manchmal sowohl erwünschte als auch unerwünschte Erlebnisse mit sich. Hier sind ein paar Dinge zu beachten.

### Einige Programme können Probleme verursachen::
Da ich Verbindungen pro Produkt und damit auch doppelte Einträge festlege sowie "kritische" Prozesse (z.B. Windows Spyware, einige Aktivierungsdienste) strikt blockiere, können manchmal Schwierigkeiten auftauchen. Hersteller mögen diese Vorgehensweise natürlich nicht, ergreifen die Initiative und die Hosts kann so vom eigenen System gelöscht oder modifiziert werden.<br>
- Kaspsersky Internet Security erfordert eine Ausnahmeregel
- Microsoft Windows Defender erfordert eine Ausnahmeregel
- IoBIT Driver Booster löscht fast jeden AWS-Eintrag (Blockier die "FaultFixes.exe", um unerwünschte Hoständerungen zu verhindern)
- WiseCare ändert ebenfalls die Hosts
- Malwarebytes macht falsche Angaben, wenn bestimmte Einträge in der Datei vorkommen und ändert auch selbstständig die Hosts

Wenn eins der genannten Programme verwendet wird sollte darauf geachtet werden welche Rechte diesen Programmen zugestanden wird, warum Fehlermeldungen angezeigt werden und welche Dateien durch die Software verändert werden können.

Sicherheit bedeutet nicht automatisch Sicherheit in dem Sinne, wie wir sie uns als Endbenutzer vorstellen. Zumal Hersteller und Herausgeber, die uns Sicherheit versprechen, oft zu ihrem eigenen Vorteil arbeiten.

### Hinweis zu den GDS-Verbindungen der Valve Corporation - Okt. 2021
Dieser Service ist mittlerweile inaktiv. Einträge können ignoriert und durch "Suchen und Ersetzen"-Funktionen gelöscht werden. Es sind 400 Produkte betroffen.

## ❗ Hinweise:
Vorsichtig mit der Verwendung von Einträgen. Einige Einträge sind je nach Anwendung striktt und viele Dienste funktionieren möglicherweise nicht.

## 🐞 Bugs, Fehler, Fragen::
Auch ich bin nicht perfekt und es können sich falsche Einträge oder Rechtschreibfehler einschleichen. Wenn dies der Fall ist, zögere nicht, mich so schnell wie möglich zu kontaktieren - Bitte eröffne ein Ticket, kontaktiere mich in Steam oder über meine Website. Korrekturen (wenn nötig) werden schnell umgesetzt.

## 🔖 Unterstützung:
Für Menschen die mich und mein Projekt unterstützen möchten wurde eine <a href="https://gameindustry.eu/de/donations/">Spednenseite</a> eingerichtet. 

## © Copyright, Support & Lizenz
Hinter dem Projekt steht nur eine Person. Die Erstellung und Pflege der Listen hat mehrere Jahre und viel Geld gekostet und wurde von Grund auf aus dem Nichts aufgebaut.<br><br>
GameIndustry.eu ist die Originalquelle der veröffentlichten Host-Dateien. Wenn die Dateien (oder Komponenten) von irgendwo anders (vielleicht modifiziert) sind, sind sie nicht original und erhalten keinen Support.

Webseite & Support: <a href="https://www.gameindustry.eu">GameIndustry.eu</a> and <a href="https://www.gameindustry.eu/de/kontakt/">Kontaktseite</a><br>
Steam Gruppe & Support: <a href="https://steamcommunity.com/groups/penguindome/">Spyware in Games? No, thanks!</a>

Lizenz: <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons by-nc-sa 4.0</a>

## 🚨 Nachahmer und Diebe
Hochstapler und Diebe wie "Chef-Koch" können zur Hölle fahren. Die Arbeit anderer Leute zu benutzen und als eigene Schöpfung auszugeben, ist unter aller Sau. Vor allem dann, wenn man sich zu dumm anstellt und erwischen lässt.

Nicht umsonst gibt es Hinweise zu Lizenzen und Copyrights auf meinen veröffentlichten Inhalten.

Meldungen zu Verstößen können hier oder über die angegebenen Kontaktmöglichkeiten gepostet werden.

Vielen Dank
