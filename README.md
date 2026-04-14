# Deutsch-Lernheft · Klasse 10

Lern-App zur Vorbereitung auf die Vergleichsarbeit Deutsch in Klasse 10.

## Modi

- **Sprint-Modus** — schnelles Abfragen mit gewichteter Auswahl (MC + Lückentext gemischt), findet Lücken gezielt
- **Lernen-Modus** — Spaced Repetition (FSRS-4.5) mit Merkwissen pro Thema, für langfristiges Behalten

## Lernwissenschaftliche Grundlagen

### Spacing — FSRS statt SM-2
Die App nutzt den **FSRS-4.5** Algorithmus (Ye, 2024) statt des älteren SM-2 (Wozniak, 1994). FSRS modelliert das Gedächtnis mit drei Komponenten: **Stabilität** (wie lange eine Erinnerung hält), **Schwierigkeit** (1–10) und **Abrufwahrscheinlichkeit** (berechnet über eine Power-Vergessenskurve). Ergebnis: ~30% weniger Wiederholungen bei gleicher Behaltensleistung.

### Active Recall
MC-Fragen zeigen zuerst nur die Frage — Optionen werden erst nach aktivem Nachdenken eingeblendet. Dieser zusätzliche Abrufversuch verdoppelt den Lerneffekt gegenüber reinem Wiedererkennen (Roediger & Butler, 2011). Lückentext fordert vollständige Produktion aus dem Gedächtnis (Desirable Difficulty, Bjork & Bjork, 2020).

### Interleaving
Im Lernen-Modus können Karten themenübergreifend gemischt werden. Aufeinanderfolgende Karten behandeln möglichst verschiedene Themen — der Kontextwechsel stärkt die Unterscheidungsfähigkeit bei ähnlichen Regeln um 20–50% (Rohrer, 2015).

### Dual-Process-Theorie
Sprint (System 1: schnell, automatisch) und Lernen (System 2: langsam, analytisch) basieren auf Kahnemans Zwei-Systeme-Modell (2011). Bewusst ohne Gamification — diagnostisches Feedback statt extrinsischer Motivation.

## Quellen

- Kahneman, D. (2011). *Thinking, Fast and Slow.* Farrar, Straus and Giroux.
- Bjork, R. A. (1994). Memory and metamemory considerations in the training of human beings.
- Bjork, R. A. & Bjork, E. L. (2020). Desirable difficulties in theory and practice.
- Wozniak, P. A. & Gorzelanczyk, E. J. (1994). Optimization of repetition spacing (SM-2).
- Ye, J. (2024). A stochastic shortest path algorithm for optimizing spaced repetition scheduling. FSRS-4.5.
- Roediger, H. L. & Butler, A. C. (2011). The critical role of retrieval practice in long-term retention.
- Rohrer, D. (2015). Interleaving helps students distinguish among similar concepts.

## Technik

Single-file HTML. Keine Abhängigkeiten außer Google Fonts. Alle Statistiken werden im `localStorage` des Browsers gespeichert (pro Gerät).

## Nutzung

Einfach `index.html` im Browser öffnen — oder über die GitHub-Pages-URL aufrufen.
