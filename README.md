# 🧮 Projektpriorisierung – Schulprojekte effizient bewerten

Diese Web-App hilft Schulen dabei, Projekte nach einem klaren Entscheidungsbaum zu priorisieren. Sie basiert auf einem strukturierten Bewertungsmodell, das behördliche Vorgaben, Schulprogrammanbindung und Aufwand/Nutzen-Kriterien berücksichtigt.

## 🚀 Funktionen

- Priorisierung von Projekten in 4 Stufen (Priorität 1–4)
- Automatische Bewertung nach:
  - Behördlicher Vorgabe / Schulleitung
  - Relevanz für das Schulprogramm
  - Erwartetes Potential (Output)
  - Entwicklungs- und Implementierungsaufwand
- Berechnung eines normierten Wertes (0–5) zur Prioritätszuweisung
- JSON-Export der Bewertungsergebnisse
- Lokale Speicherung im Browser

## 🛠️ Nutzung

1. Öffne die App im Browser:  
   👉 [Projektpriorisierung starten](https://pfeiffse.github.io/projektpriorisierung/)

2. Fülle das Formular aus:
   - Projektname und Beschreibung
   - Ja/Nein-Fragen zur Vorgabe und Schulprogramm
   - Skalenbewertung (0–2) für Aufwand und Nutzen

3. Klicke auf **„Berechnen“** – die App zeigt:
   - Priorität (1–3)
   - Einzelwerte und Gesamtwert
   - JSON-Ausgabe zum Speichern

4. Optional: Lade die Bewertung als `.json` herunter

## 📦 Projektstruktur

- `priorisierung.html` – die vollständige Web-App (HTML + JS + CSS in einer Datei)
- Keine externen Abhängigkeiten, keine Server nötig

## 🧠 Hintergrund

Die Bewertungslogik basiert auf einem Entscheidungsbaum, der in Schulen zur Projektbewertung eingesetzt wird. Ziel ist eine transparente, nachvollziehbare Priorisierung bei begrenzten Ressourcen.

## 📄 Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Nutzung und Anpassung sind ausdrücklich erlaubt.

---

**Erstellt von:** [Sebastian Pfeiffer](https://github.com/pfeiffse)  
**Letzte Aktualisierung:** 08.11.2025
