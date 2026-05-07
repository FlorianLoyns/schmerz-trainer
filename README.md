# Schmerz-Trainer

**Schmerzskalen, OPQRST-Anamnese und WHO-Stufenschema interaktiv lernen — Lerntool für die Pflegeausbildung**

[![Lizenz: CC BY-NC-SA 4.0](https://img.shields.io/badge/Lizenz-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue)](https://florianloyns.github.io/schmerz-trainer/)
![Keine Abhängigkeiten](https://img.shields.io/badge/Abh%C3%A4ngigkeiten-keine-brightgreen)
![PWA](https://img.shields.io/badge/PWA-offline--f%C3%A4hig-teal)

Eine browser-basierte Suite für Pflege-Auszubildende — drei Module rund um das Thema Schmerz, jeweils mit Lern- und Test-Modus. Welche Skala passt zu welchem Patienten? Welche Aussage gehört zu welchem Buchstaben der OPQRST-Systematik? Welches Analgetikum gehört auf welche Stufe des WHO-Schemas? Alles lernen, üben und prüfen — ohne Login, ohne Tracking, offline-fähig.

**[Jetzt loslegen](https://florianloyns.github.io/schmerz-trainer/)**

## Drei Module

**Modul 1 — Schmerzskalen**
Sechs Skalen im Überblick: NRS (Numerische Ratingskala), VAS (Visuelle Analogskala), VRS (Verbale Ratingskala), Smiley/FPS-A (Faces Pain Scale), BESD (Beurteilung Schmerzen bei Demenz) und KUSS (Kindliche Unbehagens- und Schmerz-Skala). Jede Skala mit Anwendungsbereich, Vorgehen und Grenzen erklärt. Im Test-Modus: zwölf Patient*innen-Vignetten, in denen alle passenden Skalen ausgewählt werden müssen (Multi-Select — meist gibt es mehr als eine richtige Lösung).

**Modul 2 — OPQRST-Anamnese**
Die sechs Buchstaben der strukturierten Schmerzanamnese: **O**nset (Beginn), **P**rovokation/**P**alliation (was verstärkt/lindert?), **Q**ualität (wie fühlt sich der Schmerz an?), **R**egion/**R**adiation (wo, wohin strahlt er aus?), **S**everity (Stärke), **T**ime (zeitlicher Verlauf). Test-Modus: zwölf Patientenaussagen — welcher Buchstabe ist gemeint?

**Modul 3 — WHO-Stufenschema**
Die drei Stufen plus Adjuvanzien: Nicht-Opioide → schwache Opioide → starke Opioide, jeweils ergänzt durch Co-Analgetika. Mit Wirkstoff-Beispielen und Indikationen. Test-Modus: zehn klinische Situationen — welche Stufe ist die richtige Antwort?

## Didaktischer Aufbau

Jedes Modul folgt demselben Muster: zuerst **Lernen** (alle Skalen/Buchstaben/Stufen mit Beispielen durchblättern), dann **Test** (alle Fragen einmal durchgehen, Punkte sammeln, Auswertung am Ende mit prozentualem Score und Lerntipp). Die Module sind in sich abgeschlossen — Lernende können in einer Pause genau ein Modul üben, ohne den Rest mitnehmen zu müssen.

Die Test-Fragen sind bewusst nicht trivial: bei den Skalen muss meist mehr als eine korrekte Skala ausgewählt werden (z. B. NRS *und* VRS bei einem orientierten Erwachsenen), bei OPQRST überschneiden sich Provokation und Region klassisch in Patientenaussagen, und im WHO-Schema wird zwischen Adjuvans und Stufenwechsel unterschieden — alles realistische Stolperfallen aus Klausur und Praxis.

## Klinischer und prüfungsrelevanter Bezug

Schmerzeinschätzung gehört zu den Kerntätigkeiten in der Pflege: ohne korrekte Skala keine sinnvolle Verlaufsdokumentation, ohne strukturierte Anamnese keine vollständige Übergabe, ohne WHO-Schema keine fundierte Beurteilung der ärztlichen Verordnung. Alle drei Themen sind Pflichtstoff im Lernfeld „Pflegende erheben und erfassen den Pflegebedarf" sowie zentral für den Expertenstandard Schmerz und die Examensprüfung.

## Technik

- Einzelne HTML-Datei, Vanilla JavaScript, keine Frameworks, kein Build-Tool
- Kein externes CDN, keine Abhängigkeiten zur Laufzeit
- **PWA**: installierbar auf Desktop und Smartphone, offline-fähig via Service Worker
- Mobile-First-Layout mit `safe-area-inset` für iPhone-Notch und Home-Indicator
- Tab-Navigation zwischen den drei Modulen, persistente Theme-Wahl über `localStorage`
- DSGVO-konform: keine Tracker, keine externen Ressourcen, keine Datenübertragung

## Quellen

Inhalte aus dem Expertenstandard Schmerzmanagement in der Pflege (DNQP), dem WHO-Stufenschema (Cancer Pain Relief, WHO 1986/96, in der Pflege als didaktisches Standardmodell etabliert) sowie der OPQRST-Systematik (international etablierte Anamnese-Mnemonik). Die Skalen NRS, VAS, VRS, FPS-A, BESD und KUSS sind in der Pflegepraxis seit Jahrzehnten etablierte, frei verwendbare Instrumente.

## Impressum

Verantwortlich: Florian Loyns. Pflichtangaben nach § 5 DDG: [Impressum](https://florianloyns.github.io/Impressum/)

## Lizenz

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de) · Nutzen, anpassen und teilen — unter Namensnennung, nicht-kommerziell und unter gleichen Bedingungen.
