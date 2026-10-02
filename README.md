# Philosophie lernen – Kenntnis & Anmaßung

Lern-App fürs Handy: Philosophie in kleinen Häppchen – die eigenen Quellen, Vertiefungen und ein allgemeiner Lernpfad.

**Live:** https://mvonulmerbach-ship-it.github.io/philo/

## Reiter

| Reiter | Fragen | Inhalt |
|---|---|---|
| 📕 Quellen | 600 | 20 Denker und Werke, je 30 Fragen (u. a. Taleb, Epiktet & Stoa, Frankl, Mill, Hayek, Arendt, Tocqueville, Nozick) |
| 📘 Vertieft | 1.025 | 41 Denker und Strömungen, je 25 Fragen (von Sokrates/Platon bis Nussbaum und Kuhn) |
| 🌍 Allgemein | 665 | 13 Gebiete: Überblick, Logik, Epochen, Ethik, Politische Philosophie, Wissenschafts-, Sprach- und Geistesphilosophie |

Insgesamt 2.290 Fragen in acht Fragetypen: Auswahl, Mehrfachauswahl, Wahr/Falsch, Ausreißer finden, Sortieren, Zuordnen, Lernkarte und Selbsttest.

## Funktionen

- **Alles gemischt** oder ein Thema wählen. Eine Runde hat bis zu 12 Fragen.
- In **Quellen** und **Vertieft** beginnen 47 Denker mit einer **Einweisung** (Name, Lebensdaten, Hauptwerke, Kurzfassung); danach folgen alle Fragen zu diesem Denker statt einer 12er-Runde.
- Im **Allgemein**-Pfad vor jedem Thema eine kurze **Lektion** („Direkt zu den Fragen“ überspringt sie).
- Nach jeder Antwort die Auflösung mit Erklärung; am Ende Ergebnis, Bestwert je Thema, Punkte (⭐) und Tagesserie (🔥).
- In der Fußleiste des Quiz: 📖 [Philosophie-Nachschlagewerk](https://mvonulmerbach-ship-it.github.io/philo-nachschlagewerk/) als Overlay.
- Hell/Dunkel oben rechts: ◐ System (Standard) · ☀️ Hell · 🌙 Dunkel.
- Lernstand, Punkte und Hell/Dunkel-Wahl liegen nur im Browser (`localStorage`, Schlüssel `philo_lern_v3`).

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | die ganze App (HTML, CSS, JavaScript, Fragen, Einweisungen) – ca. 1 MB |
| `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `icon-maskable.png` | Installation als App |
| `sw.js` | Service Worker für den Offline-Betrieb |

## Auf dem Handy installieren

Seite in Chrome öffnen → Menü ⋮ → „Zum Startbildschirm hinzufügen“ (Safari: Teilen → „Zum Home-Bildschirm“).

## Offline

Nach dem ersten Öffnen läuft die App ohne Netz (Service Worker, network first mit Cache als Rückfall). Das Philosophie-Nachschlagewerk im Overlay ist eine eigene App und braucht dafür Netz, solange es nicht selbst einmal geöffnet wurde.
