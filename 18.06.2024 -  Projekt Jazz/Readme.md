# Jaz Zug Webseite - README

Willkommen zur offiziellen Webseite von Jaz Zug! Diese README-Datei enthält eine detaillierte Anleitung zur Einrichtung, Verwendung und Wartung der Webseite. Die Webseite bietet Informationen über unsere Events, Mitgliedschaft und andere Aktivitäten und ist sowohl auf Desktop- als auch auf mobilen Geräten gut zugänglich.

## Inhaltsverzeichnis

1. [Über das Projekt](#über-das-projekt)
2. [Technologien](#technologien)
3. [Installation](#installation)
4. [Struktur](#struktur)
5. [Verwendung](#verwendung)
6. [Beiträge](#beiträge)
7. [Kontakt](#kontakt)

## Über das Projekt

Die Webseite von Jaz Zug wurde entwickelt, um eine benutzerfreundliche Plattform zu bieten, die alle relevanten Informationen über den Verein und seine Aktivitäten enthält. Die Webseite umfasst eine Navigationsleiste, verschiedene Seiten, ein Mitgliedschaftsformular und eine eingebettete Google Maps-Karte, um den Standort des Vereins zu zeigen.

## Technologien

Diese Webseite wurde mit den folgenden Technologien erstellt:

- HTML5
- CSS3
- Bootstrap 5
- Google Fonts

## Installation

Um die Webseite lokal zu betreiben, folgen Sie bitte diesen Schritten:

1. **Öffnen Sie die `index.html`-Datei in Ihrem bevorzugten Browser**

## Struktur

Die Projektstruktur ist wie folgt organisiert:

```jaz-zug/
├── images/
│   ├── logo.svg
│   └── img.svg
├── index.html
├── page1.html
├── page2.html
├── page3.html
├── Readme.md
└── style.css

```

- **css/**: Enthält die CSS-Dateien für das Styling der Webseite.
- **images/**: Enthält Bilder, die auf der Webseite verwendet werden.
- **index.html**: Die Startseite der Webseite.
- **page1.html**, **page2.html**, **page3.html**: Weitere Seiten der Webseite.
- **README.md**: Diese Datei, die eine Anleitung für das Projekt enthält.

## Verwendung

### HTML-Struktur

Die Webseite besteht aus mehreren HTML-Dateien, darunter `index.html`, `page1.html`, `page2.html` und `page3.html`. Jede dieser Dateien enthält eine Navigationsleiste, die durch Bootstrap gestylt ist, und spezifische Inhalte für jede Seite.

### CSS-Styling

Die Styling-Regeln sind in der Datei `style.css` definiert. Hier einige wichtige Punkte:

- **body**: Setzt die Schriftart für die gesamte Seite auf Poppins.
- **h1**: Setzt die Schriftart für alle h1-Elemente auf Roboto.
- **.overlay-container**: Definiert das Layout für überlagerte Bilder und Texte.
- **.navbar-collapse**: Stellt sicher, dass die Navigationsleiste unterhalb der Navbar angezeigt wird.
- **Responsive Design**: Stellt sicher, dass die Webseite auf verschiedenen Bildschirmgrößen gut aussieht.

### Formulare

Das Mitgliedschaftsformular in der `index.html` kann leicht angepasst werden. Es enthält Felder für den Namen, die E-Mail-Adresse, Anfragen bezüglich Jazz und eine Nachricht.

### Google Maps Einbettung

Der Standort des Vereins wird durch eine Google Maps-Einbettung in der `index.html` angezeigt. Der Code für die Einbettung sieht wie folgt aus:

```html
<iframe
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2761.0197349196125!2d8.514889776252262!3d47.17205232237824!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x479aa20f4f931d3f%3A0x4c5c524adfd95e6c!2sJaz%20Zug!5e0!3m2!1sen!2sch!4v1687462287289!5m2!1sen!2sch"
    width="400" height="450" style="border:0;" allowfullscreen="" loading="lazy" id="embed-map"
    referrerpolicy="no-referrer-when-downgrade">
</iframe>
```

### Navigationsleiste

Die Navigationsleiste ist responsiv und enthält Links zu den verschiedenen Seiten der Webseite. Sie kann leicht durch Hinzufügen oder Entfernen von `<li>`-Elementen im `<ul class="navbar-nav">`-Abschnitt in jeder HTML-Datei angepasst werden.

## Beiträge

Beiträge zur Weiterentwicklung der Webseite sind willkommen! Um Änderungen vorzuschlagen oder Fehler zu melden, öffnen Sie bitte ein Issue im GitHub-Repository oder reichen Sie einen Pull-Request ein.

## Kontakt

Bei Fragen oder Anregungen wenden Sie sich bitte an uns:

- **Email**: info@jaz-zug.ch
- **Website**: [Jaz Zug](https://jaz-zug.ch/)
- **Adresse**:  Kirchenstrasse 7, 6300 Zug

Vielen Dank für Ihr Interesse an der Webseite von Jaz Zug! Wir hoffen, dass diese Anleitung hilfreich ist und freuen uns auf Ihre Beiträge und Rückmeldungen.

---

Dieses README wurde zuletzt aktualisiert am: [21.06.2024]