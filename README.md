# NIS2-Handbuch

Ein praxisnaher Leitfaden zur Umsetzung der **EU-Richtlinie 2022/2555 (NIS2)** in Unternehmen – mit Fokus auf die deutsche Umsetzung im BSI-Gesetz (BSIG).

## Worum geht's?

NIS2 verpflichtet deutlich mehr Unternehmen als bisher zu Maßnahmen in der IT-Sicherheit. Der Gesetzestext sagt aber nur, *was* umgesetzt werden muss, nicht *wie*. Dieses Handbuch soll diese Lücke schließen: Es erklärt die Anforderungen verständlich, zeigt pragmatische Wege zur Umsetzung und liefert zu jedem Thema eine **Checkliste**.

**Zielgruppe:** IT-Verantwortliche, IT-Sicherheitsbeauftragte und Geschäftsleitungen, vor allem in kleinen und mittleren Unternehmen, die NIS2 ohne großes Beraterbudget angehen wollen.

## Inhalt

- Betroffenheitsprüfung (Sektoren, Schwellenwerte, wichtige und besonders wichtige Einrichtungen)
- Verantwortung, Dokumentation, Bußgelder
- Asset- und Risikomanagement
- Schulungen und Geschäftsleitungsschulung
- Cyberhygiene, Authentifizierung und sichere Kommunikation
- Schwachstellen- und Patchmanagement
- Personalsicherheit und Zugriffskontrolle
- Sicherheit der Lieferkette
- Kryptografie
- Bewältigung von Sicherheitsvorfällen und Meldepflichten an das BSI
- Notfall-, Backup- und Krisenmanagement

## PDF bauen

Das Handbuch ist in LaTeX geschrieben. Zum Bauen brauchst du eine TeX-Distribution (z. B. TeX Live) mit `biber`:

```bash
latexmk -pdf NIS2_Handbuch.tex
```

Die Kapitel liegen einzeln unter [`Inhalt/`](Inhalt/), das Hauptdokument ist [`NIS2_Handbuch.tex`](NIS2_Handbuch.tex).

## Hinweis

Dieses Handbuch ist ein Orientierungsrahmen und **keine Rechtsberatung**. Es erhebt keinen Anspruch auf Vollständigkeit, und sektorspezifische Anforderungen werden nicht abgedeckt. Ob und wie stark dein Unternehmen betroffen ist, solltest du im Zweifel juristisch prüfen lassen.

## Mitmachen

Fehler gefunden oder einen Verbesserungsvorschlag? Issues und Pull Requests sind willkommen.

---

Autor: Nikolai Furmanczak · Version 0.3
