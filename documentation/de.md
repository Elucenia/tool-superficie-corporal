<!-- ELUCENIA technical documentation · superficie-corporal · de · no clinical/professional/rights approval -->

# Körperoberfläche und BMI

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/superficie-corporal)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Gewicht

`peso`

kg · Bereich: 2–350

### Körpergröße

`altura`

cm · Bereich: 40–240

## Fassung der Methode

Mosteller 1987 √(cm×kg/3600); DuBois 1916 Faktor 0,007184, Exponenten 0,425/0,725; separater BMI

## Dokumentierte Formel

Mosteller: Körperoberfläche (m²) = √(Größe \[cm\] × Gewicht \[kg\] ÷ 3600)

DuBois: Körperoberfläche (m²) = 0,007184 × Gewicht0,425 × Größe0,725

BMI = Gewicht ÷ Größe² (m)

## Grenzen und Population

Geben Sie Körpergröße in cm und Gewicht in kg ein; das Ergebnis ist eine geschätzte Körperoberfläche in m², nicht der BMI. Mosteller und Du Bois sind unterschiedliche Gleichungen, keine direkten Oberflächenmessungen. Die zitierte ASCO-Leitlinie 2012 behandelt die Dosierung zytotoxischer Chemotherapie bei adipösen Erwachsenen mit Krebs und erfasst nicht die neuartigen zielgerichteten Wirkstoffe jener Ausgabe. Die Oberflächenberechnung bestimmt weder Dosis, Obergrenze der Körperoberfläche noch Indikation: Die Entscheidung muss dem jeweiligen Protokoll und Medikament folgen, ohne aus dieser Referenz universelle Grenzen abzuleiten.

## Referenzen

- [Mosteller RD. Simplified calculation of body-surface area. N Engl J Med, 1987.](https://doi.org/10.1056/NEJM198710223171717)

- [Griggs JJ et al. Appropriate chemotherapy dosing for obese adult patients with cancer: American Society of Clinical Oncology clinical practice guideline. J Clin Oncol, 2012.](https://doi.org/10.1200/JCO.2011.39.9436)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
