# Linktree-Webseite

Eine einfache, responsive Linktree-ähnliche Webseite mit HTML, CSS und JavaScript. Die Webseite bietet Platz für Links zu verschiedenen Websites und enthält eine Funktion zum Umschalten zwischen hellen und dunklen Designs.

## Inhaltsverzeichnis

- [Überblick](#überblick)
- [Funktionen](#funktionen)
- [Installation](#installation)
- [Verwendung](#verwendung)
- [Dateistruktur](#dateistruktur)
- [Anpassungen](#anpassungen)

## Überblick

Diese Webseite dient als persönlicher Linkhub, ähnlich wie Linktree. Der Benutzer kann sein Profilbild, seinen Namen, eine kurze Beschreibung und mehrere Links hinzufügen. Zudem kann das Design der Webseite zwischen einem hellen und einem dunklen Modus umgeschaltet werden.

## Funktionen

- **Profilbild und Beschreibung**: Einfaches Hinzufügen eines Bildes und einer Beschreibung.
- **Interaktive Links**: Links werden als Buttons dargestellt und öffnen sich in einem neuen Tab.
- **Dark Mode**: Mit einem Button kann zwischen hellem und dunklem Modus gewechselt werden.

## Installation

1. **Projektklonen oder Herunterladen**
   - Lade das Projekt als ZIP herunter oder klone es mit Git:
     ```bash
     git clone https://github.com/username/linktree-website.git
     ```
   
2. **Dateistruktur überprüfen**
   - Stelle sicher, dass sich alle Dateien (`index.html`, `styles.css`, `script.js`) und dein Profilbild (`profile.jpg`) im gleichen Verzeichnis befinden.

3. **Profilbild hinzufügen**
   - Ersetze die Datei `profile.jpg` durch dein eigenes Profilbild (mit demselben Dateinamen) oder ändere den Dateipfad in der HTML-Datei entsprechend.

## Verwendung

1. **Seite öffnen**
   - Öffne die `index.html`-Datei in deinem Webbrowser.
  
2. **Links und Details anpassen**
   - Bearbeite die Links und Beschreibung in der `index.html`, um sie an deine Anforderungen anzupassen.
  
3. **Dark Mode**
   - Drücke den "Toggle Theme"-Button, um zwischen dem hellen und dunklen Modus zu wechseln.

## Dateistruktur

- **index.html**: Enthält das Grundgerüst der HTML-Seite.
- **styles.css**: Stellt die Stile bereit und enthält sowohl helle als auch dunkle Designs.
- **script.js**: Enthält den JavaScript-Code für den Dark Mode-Schalter.

## Anpassungen

- **Links anpassen**: Füge deine eigenen Links in der HTML-Datei im Abschnitt `<section class="links">` hinzu.
- **Styling ändern**: Passe Farben und Abstände im `styles.css` an.
- **Profilbild und Name**: Ändere das `alt`-Attribut und den Dateinamen für dein Profilbild in `index.html` und passe den Namen und die Beschreibung in `<header>` an.

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Weitere Informationen findest du in der `LICENSE`-Datei.
