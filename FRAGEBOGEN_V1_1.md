# Erhebungsinstrument – Fragebogen Version 1.1

**Masterarbeit: Energievisualisierung im Wandel**  
**Stand:** 22. Oktober 2026 · **Status:** Entwurf zur Abstimmung mit dem Professor und für den Pretest  
**Versuchsdesign:** Vergleich von Variante A (klassisches Gebäudemanagement) und Variante B (hybride dialogbasierte Oberfläche). Jede Person bearbeitet **nur eine** zufällig zugewiesene Variante.

## Instruktion für Teilnehmende

> Im Folgenden sehen Sie eine beispielhafte Benutzeroberfläche zur Energieversorgung eines Gebäudes. Die angezeigten Werte sind simuliert. Bitte beantworten Sie die fünf Aufgaben mithilfe der Benutzeroberfläche. Sie können sich innerhalb der Oberfläche bewegen und die vorhandenen Funktionen nutzen. Wählen Sie bei jeder Aufgabe die aus Ihrer Sicht richtige Antwort. Nach dem Absenden folgt die nächste Aufgabe. Anschließend bewerten Sie die Gestaltung und Bedienbarkeit. Es gibt während der Bearbeitung keine Rückmeldung zur Richtigkeit. Die Teilnahme dauert voraussichtlich 10 bis 15 Minuten; die tatsächliche Dauer wird im Pretest geprüft.

**Vor dem produktiven Einsatz ergänzen:** Einwilligung und Datenschutzinformationen, Abbruchmöglichkeit, Kontakt zur Studienleitung, Speicherdauer und ggf. Angaben zu Vorerfahrungen. Diese Elemente sind noch nicht vollständig in der Pilotanwendung implementiert.

## A. Testaufgaben (eine richtige Antwort pro Aufgabe)

**1. Wie viel elektrische Leistung benötigt die Lüftung aktuell?**  
A. 5,0 kW  
B. 8,5 kW  
C. 12,0 kW

**2. Welcher Bereich benötigt aktuell die höchste elektrische Leistung?**  
A. Ladeinfrastruktur  
B. Heizung/Kühlung  
C. Lüftung

**3. Woher bezieht das Gebäude aktuell seine elektrische Leistung?**  
A. Ausschließlich aus der Solaranlage  
B. Ausschließlich aus dem Stromnetz  
C. Aus der Solaranlage und dem Stromnetz

**4. Wie viel elektrische Leistung benötigen Beleuchtung und Ladeinfrastruktur zusammen?**  
A. 12,0 kW  
B. 15,0 kW  
C. 18,5 kW

**5. Welche Aussage zur aktuellen Stromversorgung des Gebäudes ist richtig?**  
A. Die Solaranlage liefert mehr elektrische Leistung als das Stromnetz.  
B. Das Stromnetz liefert mehr elektrische Leistung als die Solaranlage.  
C. Beide liefern gleich viel elektrische Leistung.

## B. Gestaltung und Bedienbarkeit

**Instruktion:** Bitte bewerten Sie die Benutzeroberfläche, die Sie gerade verwendet haben. Für jede Aussage gilt: 1 = Stimme überhaupt nicht zu; 2 = Stimme eher nicht zu; 3 = Weder noch; 4 = Stimme eher zu; 5 = Stimme voll und ganz zu.

1. Die Benutzeroberfläche war übersichtlich gestaltet.
2. Die Anordnung der Informationen war für mich nachvollziehbar.
3. Die verwendeten Farben haben mich bei der Orientierung unterstützt.
4. Die Icons und Symbole waren verständlich.
5. Wichtige Informationen waren visuell gut hervorgehoben.
6. Die Menge der gleichzeitig angezeigten Informationen war angemessen.
7. Das visuelle Erscheinungsbild der Benutzeroberfläche war ansprechend.
8. Ich konnte mich innerhalb der Benutzeroberfläche gut orientieren.
9. Die benötigten Informationen ließen sich einfach aufrufen.
10. Die Bedienung der Benutzeroberfläche war für mich unkompliziert.

## C. Freiwillige offene Abschlussfrage

**Was hat Ihnen an der Benutzeroberfläche besonders gut gefallen und was würden Sie verbessern?**

## Lösungsschlüssel – nur für die Studienleitung

| Aufgabe | Lösung | Grundlage |
|---|---|---|
| 1 | B | Lüftung: 8,5 kW |
| 2 | B | Heizung/Kühlung: 12,0 kW (größte Verbrauchergruppe) |
| 3 | C | PV: 18,0 kW und Netzbezug: 24,5 kW |
| 4 | B | Beleuchtung: 5,0 kW + Ladeinfrastruktur: 10,0 kW = 15,0 kW |
| 5 | B | Netzbezug: 24,5 kW > PV-Erzeugung: 18,0 kW |

## Methodische Hinweise

- Die fünf Aufgaben bilden einen **aufgabenspezifischen Verständnisscore** (0–5 richtige Antworten); sie sind kein validierter allgemeiner Verständnistest.
- Bearbeitungszeiten werden pro Aufgabe gemessen; bei Unterbrechungen sind sie nur eingeschränkt interpretierbar.
- Die zehn Zustimmungsaussagen sind **selbst entwickelte Likert-Items**, keine validierte SUS-Skala. Eine Zusammenfassung zu einem Gesamtwert sollte erst nach fachlicher Prüfung begründet werden.
- Aufgabe 5 wurde nach einem Pilotdurchlauf von Version 1.8 von einer Prozentrechenaufgabe in einen einfachen Leistungsvergleich geändert. Ergebnisse verschiedener Aufgabenfassungen nicht ungeprüft zusammenfassen.
- Beide Varianten zeigen dieselben simulierten Daten; die UI-Konzepte unterscheiden sich hinsichtlich Informationsarchitektur, Darstellung und Interaktionsform. Einzelne Effekte können deshalb nicht isoliert kausal zugeordnet werden.
- Für die spätere Erhebung sind Einwilligung, Datenschutz, zentrale Speicherung, zufällige Zuweisung, ggf. Stichprobenmerkmale und Pretest noch zu klären.
