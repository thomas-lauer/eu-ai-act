# EU AI Act — verständlich erklärt

Ein Dokumentenpaket zur EU-KI-Verordnung für Unternehmen: eine verständlich und praxisnah geschriebene Beschreibung, Umsetzungs-Checklisten für Anbieter und Betreiber und eine Excel-Arbeitshilfe.

**Rechtsstand: 29.07.2026 · Fassung 1.1** — Verordnung (EU) 2024/1689 in der Fassung der Verordnung (EU) 2026/1744 (Digital-Omnibus-Verordnung zur KI, in Kraft seit 27.07.2026).

> **Keine Rechtsberatung.** Siehe [DISCLAIMER.md](DISCLAIMER.md). **Lizenz:** CC BY 4.0 — siehe [LICENSE](LICENSE).

---

## Die drei Dokumente

| Datei | Was drin ist | Für wen |
|---|---|---|
| **01 Beschreibung** (.docx) | Was der AI Act regelt, für wen er gilt, die Risikostufen als Prüfmodell, die Rollen, was wann gilt, GPAI, Transparenzpflichten, häufige Irrtümer, Glossar | Geschäftsführung, Fachbereiche, alle, die einen Überblick brauchen |
| **02 Checklisten** (.docx) | Abhakbare Pflichtenlisten mit Fundstelle, Frist, Status, Nachweis und Verantwortlichem — für Betreiber, Anbieter, Rollenwechsel und Querschnittspflichten | Umsetzungsverantwortliche |
| **03 Arbeitshilfe** (.xlsx) | Zehn Blätter: Anleitung, KI-Inventar, Rollen-Check, Risiko-Einstufung, Pflichten-Matrix (90 Pflichten), Maßnahmenplan, Dashboard, Quellen, Register und ein ausgefülltes Beispiel | Wer die Umsetzung steuert und nachweisen muss |

Die Word-Dokumente sind zweistufig aufgebaut: Der Haupttext ist bewusst einfach geschrieben, die juristische Fundstelle steht jeweils direkt darunter. Wer nur wissen will, was zu tun ist, überspringt sie; wer prüfen oder zitieren will, findet dort den Beleg.

Unter [`markdown/`](markdown/) liegen dieselben Inhalte als Markdown — direkt auf GitHub lesbar.

---

## Womit Sie anfangen

1. **Inventar** — alle KI-Systeme erfassen, auch eingebettete in eingekaufter Software (Blatt 01)
2. **Rolle bestimmen** — Anbieter oder Betreiber? Achtung bei Art. 25 (Blatt 02)
3. **Risiko einstufen** — verboten → hochriskant (bei Anhang I: Abschnitt A oder B?) → transparenzpflichtig → gering (Blatt 03)
4. **Pflichten ableiten** und terminieren (Blatt 04)
5. **Nachweise aufbauen** — was nicht dokumentiert ist, lässt sich im Prüffall nicht belegen

---

## Was sich im Juli 2026 geändert hat

Der Digital Omnibus wurde am 24.07.2026 im Amtsblatt veröffentlicht und trat am 27.07.2026 in Kraft. Die wichtigsten Punkte:

- **Hochrisiko-Pflichten verschoben:** Anhang III auf den **02.12.2027**, Anhang I Abschnitt A auf den **02.08.2028**
- **Zwei neue Verbote ab 02.12.2026** — nicht-einvernehmliche intime Darstellungen und CSAM
- **KI-Kompetenz (Art. 4) abgeschwächt**, aber nicht gestrichen: Die Pflicht verschiebt sich vom Ergebnis auf den Prozess
- **Für Anhang I Abschnitt B** (u. a. Maschinen, Kraftfahrzeuge, Eisenbahn) gelten nur noch Art. 6 Abs. 1, Art. 60a und Art. 102–112 — die Anforderungen laufen über das Sektorrecht
- **Neuer Art. 4a** für die Bias-Erkennung, anwendbar seit 27.07.2026; Art. 10 Abs. 5 wurde gestrichen
- **Erweiterte Durchsetzungsbefugnisse** des KI-Büros samt Zwangsgeldern (Art. 75a–75d)

**Was sich nicht geändert hat:** Die Verbote gelten weiter, die Transparenzpflichten starten planmäßig am 02.08.2026, die GPAI-Pflichten gelten seit August 2025, und die Sanktionsvorschriften wurden nicht mitverschoben.

---

## Quellen

Die wesentlichen rechtlichen Aussagen sind mit einer Fundstelle im amtlichen Text belegt; organisatorische Empfehlungen und Beispiele sind als solche gekennzeichnet. Das vollständige Register mit Abrufdaten, Prüfstatus und Prüfdatum steht in [QUELLEN.md](QUELLEN.md).

Grundlage sind die amtlichen deutschen Volltexte der Verordnungen (EU) 2024/1689 und (EU) 2026/1744. Wo eine Angabe nicht verifiziert werden konnte, ist das ausdrücklich vermerkt.

---

## Qualitätssicherung

Das Paket wurde in zwei Runden unabhängig geprüft — jeweils mit dem Auftrag, Fehler zu finden, nicht die Arbeit zu bestätigen.

**Runde 1 (v1.0):** zwei KI-Agenten in der Rolle eines Rechtsexperten, 52 Befunde, davon 4 kritische; alle eingearbeitet.

**Runde 2 (v1.1):** ChatGPT, 30 Befunde. Jeder wurde einzeln gegen den amtlichen Verordnungstext gehalten — **zwei Rechtsbefunde erwiesen sich dabei als sachlich unzutreffend** und wurden mit Wortlautzitat zurückgewiesen; die übrigen sind ganz oder teilweise eingearbeitet.

Die Einstufungslogik der Arbeitsmappe ist gegen 16 Fallkonstellationen automatisiert getestet.

Prüfbericht und Änderungsnachweis liegen im Entwicklungs-Repository: **[eu-ai-act-dev](https://github.com/thomas-lauer/eu-ai-act-dev)**. Dort finden sich auch die Quelltexte und die Skripte, mit denen die Dokumente erzeugt werden.

---

## Was Sie beim Weitergeben beachten sollten

Die Inhalte stehen unter **CC BY 4.0** und dürfen frei verwendet, angepasst und weitergegeben werden. Bitte nennen Sie dabei den **Rechtsstand** und kennzeichnen Sie **vorgenommene Änderungen** — eine veränderte Fassung ohne Kennzeichnung bildet die hier dokumentierte Prüfung nicht mehr ab. Einzelheiten in [LICENSE](LICENSE).

---

## Aktualität

Der Rechtsstand ist in Bewegung. Prüfen Sie vor jeder Verwendung, ob eine neuere Fassung vorliegt — die Versionsbezeichnung nennt immer den Rechtsstand, auf den sich die Dokumente beziehen.
