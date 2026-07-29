# EU AI Act — Checklisten zur Umsetzung

## Für Betreiber (Deployer) und Anbieter (Provider)

**Rechtsstand: 29.07.2026 · Fassung 1.1**
Verordnung (EU) 2024/1689 in der Fassung der Verordnung (EU) 2026/1744 (Digital-Omnibus-Verordnung zur KI, in Kraft seit 27.07.2026).

---

## Wichtiger Hinweis

Diese Checklisten sind eine strukturierte Arbeitshilfe, keine Rechtsberatung. Ob eine Pflicht im konkreten Fall greift, hängt von Umständen ab, die hier nicht bekannt sind. Die Checklisten erheben keinen Anspruch auf Vollständigkeit für jeden denkbaren Anwendungsfall. Für rechtsverbindliche Auskünfte wenden Sie sich an eine Rechtsanwältin oder einen Rechtsanwalt.

## So arbeiten Sie mit den Checklisten

**Reihenfolge:** Beginnen Sie mit Checkliste 0 (Einstieg). Sie führt Sie zu den für Sie zutreffenden Listen.

**Spalten:** Jede Zeile enthält die Pflicht, die Fundstelle im Gesetz, das Fristdatum, ein Statusfeld, das erwartete Nachweisdokument und ein Feld für die verantwortliche Person.

**Statuswerte:** `offen` · `in Arbeit` · `erfüllt` · `nicht anwendbar` (mit Begründung)

**Kennzeichnung:** "n. F." bedeutet, dass die Vorschrift durch den Digital Omnibus im Juli 2026 geändert wurde. "UAbs." steht für Unterabsatz, "a. F." für alte Fassung, "ErwG" für Erwägungsgrund.

**Fristangaben:** Wo "gilt bereits" steht, ist die Pflicht bereits anwendbar. Wo ein Datum steht, ist das der Beginn der Anwendbarkeit.

> **Was "HR-Frist" bedeutet — bitte einmal lesen.** Der Gesetzgeber hat ausdrücklich nur Kapitel III Abschnitte 1, 2 und 3 verschoben. Für einige Pflichten außerhalb dieser Abschnitte (Konformitätsbewertung, Registrierung, Beobachtung nach dem Inverkehrbringen, Vorfallmeldung, Recht auf Erläuterung) folgt aus dem Wortlaut der 02.08.2026 als Geltungsbeginn. Diese Checklisten verwenden dafür die Angabe **"HR-Frist"** — also den jeweiligen Hochrisiko-Termin 02.12.2027 bzw. 02.08.2028. Das ist eine **Planungsannahme**, keine gesicherte gesetzliche Frist: Sie beruht darauf, dass diese Pflichten ohne anwendbaren Art. 6 praktisch leerlaufen. Die Annahme ist **nicht anwaltlich bestätigt**. Wer sich darauf stützt, sollte für das konkrete System dokumentieren: (1) welcher Wortlaut gilt, (2) welche Frist geplant wird, (3) ob und durch wen die Auslegung geprüft wurde.

---

# Checkliste 0 — Einstieg: Was betrifft mich?

| Nr. | Frage | Fundstelle | Wenn ja … |
|---|---|---|---|
| 0.1 | Setzen wir KI-Systeme ein oder planen wir das? | Art. 3 Nr. 1 | Weiter mit 0.2 |
| 0.2 | Nutzen wir das System **beruflich** (nicht rein privat)? | Art. 2 Abs. 10, Art. 3 Nr. 4 | Die Verordnung ist anwendbar |
| 0.3 | Sitzen wir in der EU **oder** wird die Ausgabe unseres Systems in der EU verwendet? | Art. 2 Abs. 1 lit. a–c | Die Verordnung ist anwendbar |
| 0.4 | Greift eine Ausnahme? (Militär/nationale Sicherheit, ausschließlich wissenschaftliche F&E, Entwicklung vor Markteinführung ohne Realtests) | Art. 2 Abs. 3, 6, 8 | Prüfen und dokumentieren |
| 0.5 | **Verwenden** wir ein KI-System in eigener Verantwortung? | Art. 3 Nr. 4 | → **Checkliste A (Betreiber)** |
| 0.6 | **Entwickeln** wir ein KI-System oder lassen es entwickeln und bringen es unter eigenem Namen in Verkehr? | Art. 3 Nr. 3 | → **Checkliste B (Anbieter)** |
| 0.7 | Könnten wir durch Eigenlabeling, wesentliche Veränderung oder Zweckänderung zum Anbieter werden? | Art. 25 Abs. 1 | → **Checkliste C (Rollenwechsel) — unbedingt prüfen** |
| 0.8 | Gilt für uns unabhängig von Rolle und Risikoklasse etwas? | Art. 4, Art. 5, Art. 50 | → **Checkliste D (Querschnitt) — gilt immer** |
| 0.9 | Steht das System im Zusammenhang mit einem Produkt nach **Anhang I**? Wenn ja: **Abschnitt A oder B?** | Anhang I, Art. 2 Abs. 2 n. F. | Abschnitt B → nur Art. 6 Abs. 1, Art. 60a, Art. 102–112 plus Sektorrecht; Checklisten A und B nicht anwenden |

> **Hinweis:** Die Rollen schließen sich nicht aus. Ein Unternehmen kann für ein System Betreiber und für ein anderes Anbieter sein. Die Prüfung erfolgt **pro System**, nicht pro Unternehmen.

---

# Checkliste D — Querschnittspflichten (gelten immer)

Diese Pflichten gelten unabhängig von Rolle und Risikoklasse. Sie sind der Ausgangspunkt jeder Umsetzung.

## D.1 KI-Kompetenz (Art. 4 n. F.)

| Nr. | Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| D.1.1 | Maßnahmen ergreifen, um die **Entwicklung** der KI-Kompetenz des Personals zu **unterstützen** | Art. 4 Abs. 1 n. F. | gilt seit 02.02.2025 | | Schulungskonzept, Teilnahmenachweise | |
| D.1.2 | Auch Personen einbeziehen, die **im Auftrag** mit Betrieb und Nutzung befasst sind (Dienstleister, Leiharbeit, Freelancer) | Art. 4 Abs. 1 n. F. | gilt seit 02.02.2025 | | Vertragsklauseln, Onboarding-Unterlagen | |
| D.1.3 | Maßstab an technischen Kenntnissen, Erfahrung, Aus-/Fortbildung, Einsatzkontext und betroffenen Personengruppen ausrichten | Art. 4 Abs. 1 n. F. | gilt seit 02.02.2025 | | Bedarfsanalyse je Rolle | |
| D.1.4 | Schulungsmaßnahmen und Teilnahme **dokumentieren** | (Nachweisführung, aus Art. 4 Abs. 1 abgeleitet) | laufend | | Schulungsregister | |

> **Was sich geändert hat:** Bis Juli 2026 musste "nach besten Kräften sichergestellt" werden, dass ein "ausreichendes Maß" an KI-Kompetenz vorliegt. Jetzt muss die **Entwicklung** der Kompetenz **unterstützt** werden; ein bestimmtes Niveau muss ausdrücklich **nicht** garantiert werden. Die Pflicht bleibt bestehen — der Vorschlag zu ihrer Streichung wurde nicht übernommen. *(Art. 4 Abs. 1 Satz 2 KI-VO n. F.)*

> **Nicht verwechseln:** Für Betreiber von Hochrisiko-Systemen gilt zusätzlich die strengere Anforderung des Art. 26 Abs. 2 (Kompetenz, Ausbildung **und Befugnis** der aufsichtführenden Personen). Diese Vorschrift wurde **nicht** geändert.

## D.2 Verbotene Praktiken (Art. 5)

| Nr. | Prüfpunkt — setzen wir ein System ein oder bieten wir eines an, das … | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| D.2.1 | … unterschwellige, manipulative oder täuschende Techniken einsetzt und dadurch erheblichen Schaden verursachen kann? | Art. 5 Abs. 1 lit. a | gilt seit 02.02.2025 | | Systembewertung | |
| D.2.2 | … Schutzbedürftigkeit wegen Alter, Behinderung oder sozialer/wirtschaftlicher Lage ausnutzt? | Art. 5 Abs. 1 lit. b | gilt seit 02.02.2025 | | Systembewertung | |
| D.2.3 | … Personen über einen Zeitraum sozial bewertet und dadurch kontextfremd oder unverhältnismäßig schlechterstellt (**Social Scoring**)? | Art. 5 Abs. 1 lit. c | gilt seit 02.02.2025 | | Systembewertung | |
| D.2.4 | … das Risiko einer Straftat **ausschließlich** aus Profiling oder Persönlichkeitsmerkmalen prognostiziert? | Art. 5 Abs. 1 lit. d | gilt seit 02.02.2025 | | Systembewertung | |
| D.2.5 | … Gesichtserkennungsdatenbanken durch **ungezieltes Scraping** aufbaut oder erweitert? | Art. 5 Abs. 1 lit. e | gilt seit 02.02.2025 | | Systembewertung | |
| D.2.6 | … **Emotionen am Arbeitsplatz oder in Bildungseinrichtungen** ableitet (außer aus medizinischen oder Sicherheitsgründen)? | Art. 5 Abs. 1 lit. f | gilt seit 02.02.2025 | | Systembewertung, ggf. Begründung der Ausnahme | |
| D.2.7 | … Personen biometrisch nach sensiblen Merkmalen kategorisiert (Rasse, politische Einstellung, Gewerkschaftszugehörigkeit, Religion/Weltanschauung, Sexualleben, sexuelle Ausrichtung)? | Art. 5 Abs. 1 lit. g | gilt seit 02.02.2025 | | Systembewertung | |
| D.2.8 | … biometrische **Echtzeit**-Fernidentifizierung im öffentlich zugänglichen Raum zu Strafverfolgungszwecken durchführt? | Art. 5 Abs. 1 lit. h, Abs. 2–7 | gilt seit 02.02.2025 | | Genehmigung, Meldungen | |
| D.2.9 | **NEU:** … realistische intime Darstellungen bestimmbarer Personen **ohne deren ausdrückliche Zustimmung** erzeugt oder manipuliert (NCII)? | Art. 5 Abs. 1 lit. ba n. F. | **ab 02.12.2026** | | Systembewertung, Schutzmaßnahmen | |
| D.2.10 | **NEU:** … Material i. S. v. Art. 2 lit. c und e der RL 2011/93/EU erzeugt oder manipuliert (CSAM)? | Art. 5 Abs. 1 lit. bb n. F. | **ab 02.12.2026** | | Systembewertung, Schutzmaßnahmen | |
| D.2.11 | **Für Anbieter generativer Systeme:** Ist die Erzeugung solcher Inhalte ein nach vernünftigem Ermessen **absehbares und reproduzierbares** Ergebnis ohne erhebliche technische Änderungen — und fehlen zumutbare, angemessene technische Schutzmaßnahmen? | Art. 5 Abs. 1a n. F. | **ab 02.12.2026** | | Red-Teaming-Bericht, Safety-Filter-Dokumentation | |
| D.2.12 | **Für Betreiber:** Verwenden wir ein System **zum Zweck** der Erzeugung solchen Materials? | Art. 5 Abs. 1a n. F. | **ab 02.12.2026** | | Nutzungsrichtlinie | |
| D.2.13 | Internes Verbot in Richtlinien verankert und kommuniziert? | (Organisationspflicht) | laufend | | KI-Richtlinie, Kommunikationsnachweis | |

> **Kein Bestandsschutz:** Die Übergangsregelung des Art. 111 Abs. 2 KI-VO n. F. steht ausdrücklich unter dem Vorbehalt des Art. 5. Für die neuen Verbote ist die Zeit bis zum 02.12.2026 die einzige Vorlaufzeit.

> **Sanktionsrahmen:** Bis 35.000.000 EUR oder 7 % des weltweiten Jahresumsatzes, je nachdem, was höher ist. Für KMU gilt der niedrigere Betrag; für kleine Midcap-Unternehmen gilt die Deckelung hier **nicht**. *(Art. 99 Abs. 3, 6 und 6a n. F.)*

## D.3 Transparenzpflichten (Art. 50) — ab 02.08.2026

| Nr. | Pflicht | Rolle | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|---|
| D.3.1 | Systeme mit **direkter Interaktion** mit Menschen so gestalten, dass die Interaktion mit einer KI erkennbar ist | Anbieter | Art. 50 Abs. 1 | 02.08.2026 | | UI-Hinweis, Screenshot | |
| D.3.2 | Ausgaben **synthetischer** Audio-, Bild-, Video- oder Textinhalte **maschinenlesbar** kennzeichnen | Anbieter | Art. 50 Abs. 2 | 02.08.2026 | | Wasserzeichen-/Metadatenkonzept | |
| D.3.3 | **Bestandssysteme** (in Verkehr vor 02.08.2026): Kennzeichnung nach Art. 50 Abs. 2 nachrüsten | Anbieter | Art. 111 Abs. 4 n. F. | **02.12.2026** | | Umsetzungsplan, Release-Nachweis | |
| D.3.4 | Bei **Emotionserkennung** oder **biometrischer Kategorisierung**: betroffene Personen über den Betrieb informieren | Betreiber | Art. 50 Abs. 3 | 02.08.2026 | | Informationstext, Aushang | |
| D.3.5 | Bei **Deepfakes**: offenlegen, dass Inhalte künstlich erzeugt oder manipuliert wurden | Betreiber | Art. 50 Abs. 4 UAbs. 1 S. 1 | 02.08.2026 | | Kennzeichnungsrichtlinie | |
| D.3.6 | Bei künstlerischen/satirischen/fiktionalen Werken: geeignete Offenlegung, die den Werkgenuss nicht beeinträchtigt | Betreiber | Art. 50 Abs. 4 UAbs. 1 S. 3 | 02.08.2026 | | Kennzeichnungsrichtlinie | |
| D.3.7 | Bei **KI-Texten zu Angelegenheiten von öffentlichem Interesse**: offenlegen — außer bei menschlicher Überprüfung mit redaktioneller Verantwortung | Betreiber | Art. 50 Abs. 4 UAbs. 2 | 02.08.2026 | | Redaktionsrichtlinie, Verantwortlichkeitsregelung | |
| D.3.8 | Informationen **spätestens bei der ersten Interaktion**, klar, eindeutig und barrierefrei bereitstellen | beide | Art. 50 Abs. 5 | 02.08.2026 | | Barrierefreiheitsprüfung | |

> **Wichtig zur Übergangsfrist:** Sie gilt **nur für Art. 50 Abs. 2** und **nur für Systeme, die vor dem 02.08.2026 in Verkehr gebracht wurden**. Die Absätze 1, 3 und 4 gelten ab dem 02.08.2026 ohne Schonfrist. *(Art. 111 Abs. 4 KI-VO n. F.)*

> **Sanktionsrahmen:** Bis 15.000.000 EUR oder 3 %. *(Art. 99 Abs. 4 lit. g)*

## D.4 Organisatorische Grundlagen

| Nr. | Maßnahme | Bezug | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| D.4.1 | **KI-Inventar** aufbauen und laufend pflegen (auch eingebettete KI in eingekaufter Software) | Voraussetzung aller Pflichten | laufend | | Inventarliste (Blatt 01 der Arbeitshilfe) | |
| D.4.2 | Rolle **je System** bestimmen und dokumentieren | Art. 3 Nrn. 3, 4; Art. 25 | laufend | | Rollenzuordnung (Blatt 02) | |
| D.4.3 | Risikoklasse **je System** bestimmen und dokumentieren | Art. 5, 6, 50 | laufend | | Einstufungsdokumentation (Blatt 03) | |
| D.4.4 | Interne **KI-Richtlinie** erlassen (zulässige Nutzung, Freigabeprozess, Verbote, Meldewege) | Organisationspflicht | laufend | | Richtlinie, Freigabeprotokoll | |
| D.4.5 | Verantwortlichkeiten benennen (KI-Beauftragte oder gleichwertige Funktion) | Organisationspflicht | laufend | | Bestellung, Funktionsbeschreibung | |
| D.4.6 | **Lieferantenverträge** prüfen: Rollenabgrenzung, Informations- und Mitwirkungspflichten, Zugang zu technischer Dokumentation und Protokollen | Art. 25 Abs. 2 n. F., Art. 26 | laufend | | Vertragsklauseln, Vertragsregister | |
| D.4.7 | **Datenschutz koppeln:** Verarbeitungsverzeichnis, Erforderlichkeit einer DSFA nach Art. 35 DSGVO prüfen | Art. 26 Abs. 9, Art. 27 Abs. 4 n. F. | laufend | | DSFA, Verzeichnis | |
| D.4.8 | **Mitbestimmung** prüfen (Betriebsrat, Beteiligungsrechte nach nationalem Recht) | Art. 2 Abs. 11, Art. 26 Abs. 7 S. 2 KI-VO i. V. m. nationalem Betriebsverfassungsrecht | vor Einführung | | Beteiligungsnachweis | |
| D.4.9 | **Turnus für Rechtsstands-Review** festlegen (die Rechtslage ist in Bewegung) | — | laufend | | Review-Protokoll | |
| D.4.10 | **Beschwerdeeingänge einplanen:** Jede Person kann bei der Marktüberwachungsbehörde Beschwerde einlegen — internen Prozess für behördliche Rückfragen vorsehen | Art. 85 | gilt ab 02.08.2026 | | Eskalationsprozess | |
| D.4.11 | Prüfen, ob wir zusätzlich **Einführer** (Art. 23) oder **Händler** (Art. 24) sind — diese Rollen haben eigene Pflichten, die in diesen Checklisten nicht abgebildet sind | Art. 3 Nrn. 6 und 7, Art. 23, Art. 24 | HR-Frist | | Rollenprüfung | |

---

# Checkliste A — Betreiber (Deployer)

## A.0 Vorprüfung

| Nr. | Prüfpunkt | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| A.0.1 | Ist das System **hochriskant** (Art. 6 Abs. 1 mit Anhang I oder Abs. 2 mit Anhang III)? | Art. 6 | | Einstufungsdokumentation | |
| A.0.2 | Falls Anhang III: Greift der **Ausnahmefilter** des Art. 6 Abs. 3? Er setzt **kumulativ** voraus: (1) **kein erhebliches Risiko** für Gesundheit, Sicherheit oder Grundrechte **und** (2) mindestens eine der vier Bedingungen (eng gefasste Verfahrensaufgabe / Verbesserung abgeschlossener menschlicher Tätigkeit / Mustererkennung ohne Ersetzung menschlicher Bewertung / vorbereitende Aufgabe). Eine Bedingung allein genügt **nicht**. | Art. 6 Abs. 3 UAbs. 1 und 2 | | Begründete Bewertung zu beiden Voraussetzungen | |
| A.0.3 | **Sperre prüfen:** Nimmt das System **Profiling** natürlicher Personen vor? Dann gilt es **immer** als hochriskant — der Ausnahmefilter ist ausgeschlossen. | Art. 6 Abs. 3 UAbs. 3 | | Bewertung | |
| A.0.4 | Wenn das System **nicht** hochriskant ist: Gelten Transparenzpflichten (Art. 50) oder Verbote (Art. 5)? | Art. 5, 50 | | Bewertung | |
| A.0.5 | Falls Anhang I: **Welcher konkrete Rechtsakt** aus Anhang I ist einschlägig, und steht er in **Abschnitt A oder Abschnitt B**? Solange das offen ist, keine Frist und keine Pflichtenliste als gesichert behandeln. | Anhang I, Art. 2 Abs. 2 n. F. | | Rechtsaktbestimmung mit Nummer und Abschnitt | |
| A.0.6 | Falls Abschnitt B: Diese Checkliste ist **nicht** anwendbar. Maßgeblich sind Art. 6 Abs. 1, Art. 60a, Art. 102–112 KI-VO und das jeweilige Sektorrecht. | Art. 2 Abs. 2 n. F. | | Zuordnung zum Sektorrecht | |
| A.0.7 | Ist die Einstufung **juristisch bestätigt**? Festhalten: Ja / Nein / offen, Datum, prüfende Person. Ohne Bestätigung gilt jede Frist als Planungsannahme. | (Nachweisführung) | | Prüfvermerk mit Datum und Prüfer | |

> **Die Pflichten unter A.1 bis A.7 gelten für Hochrisiko-KI-Systeme ab dem 02.12.2027 (Anhang III) bzw. 02.08.2028 (Anhang I Abschnitt A).** *(Art. 113 Abs. 3 lit. c KI-VO n. F.)* Die Vorlaufzeit ist bewusst zu nutzen — Risikomanagement, Aufsichtsorganisation und Nachweisführung lassen sich nicht kurzfristig aufbauen.

> **Reichweite der Verschiebung — Planungsannahme, nicht gesicherte Frist:** Art. 113 Abs. 3 lit. c KI-VO n. F. verschiebt ausschließlich **Kapitel III Abschnitte 1, 2 und 3** (Art. 6–27, ohne Art. 6 Abs. 5). **Nicht** vom Wortlaut erfasst sind Kapitel III Abschnitt 5 (Art. 40–49: Konformitätsbewertung, Konformitätserklärung, CE, Registrierung), Kapitel IX (Art. 72, 73, 86) und Kapitel IV (Art. 50). Diese gelten seit dem 02.08.2026. In der Praxis greifen sie erst, sobald ein System nach dem verschobenen Art. 6 als hochriskant einzustufen ist — das ist eine vertretbare, aber **nicht zwingende und nicht anwaltlich bestätigte** Auslegung. Die Angabe "HR-Frist" in den folgenden Tabellen steht unter diesem Vorbehalt. Vor Inbetriebnahme eines konkreten Systems ist die Frage zu prüfen; halten Sie Ergebnis, Datum und Prüfer fest.

> **Anhang I Abschnitt A oder B? Zuerst klären — dann weiterarbeiten.** Bestimmen Sie den konkreten Rechtsakt aus Anhang I und den Abschnitt, in dem er gelistet ist.
> **Abschnitt A** (u. a. Spielzeug, Aufzüge, ATEX, Funkanlagen, Druckgeräte, Seilbahnen, PSA, Gasverbrennungsgeräte, Medizinprodukte, In-vitro-Diagnostika): volles Kapitel III ab 02.08.2028 — vorbehaltlich delegierter Rechtsakte nach Art. 2 Abs. 13 KI-VO n. F. (bis 02.08.2027).
> **Abschnitt B** (Zivilluftfahrt, Kraftfahrzeuge, Schiffsausrüstung, Eisenbahn und seit Juli 2026 die **Maschinenverordnung (EU) 2023/1230**): Es gelten nach Art. 2 Abs. 2 KI-VO n. F. **nur Art. 6 Abs. 1, Art. 60a und Art. 102–112** — Art. 57, 58 und 59 zusätzlich, soweit das Sektorrecht die Hochrisiko-Anforderungen übernommen hat. **Achtung:** "Kapitel III gilt nicht" wäre zu grob — **Art. 6 Abs. 1 gilt weiter**, das System bleibt also ein Hochrisiko-KI-System im Sinne der Verordnung. Die Checklisten A und B sind auf die Pflichtenteile für solche Systeme **nicht** anzuwenden; maßgeblich ist das jeweilige Sektorrecht (bei Maschinen: Anhang III der VO (EU) 2023/1230, delegierter Rechtsakt mit Geltung ab 02.08.2028).
> **Noch offen:** Solange der Abschnitt nicht bestimmt ist, dürfen weder eine Frist noch eine Pflichtenliste als gesichert behandelt werden.

## A.1 Verwendung gemäß Betriebsanleitung

| Nr. | Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| A.1.1 | **Geeignete technische und organisatorische Maßnahmen** treffen, um die Verwendung entsprechend der beigefügten Betriebsanleitung sicherzustellen | Art. 26 Abs. 1 | HR-Frist | | TOM-Konzept, Arbeitsanweisung | |
| A.1.2 | Betriebsanleitung des Anbieters beschaffen, auswerten und intern verfügbar machen | Art. 26 Abs. 1 i. V. m. Art. 13 | HR-Frist | | Ablage, Verteilnachweis | |
| A.1.3 | Zweckbestimmung des Systems dokumentieren und Abweichungen ausschließen | Art. 26 Abs. 1, Art. 25 Abs. 1 lit. c | HR-Frist | | Zweckbeschreibung | |

> **Achtung:** Art. 26 Abs. 1 verlangt mehr als bloßes Unterlassen von Verstößen. Es müssen aktiv technische und organisatorische Maßnahmen eingerichtet werden.

## A.2 Menschliche Aufsicht

| Nr. | Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| A.2.1 | Menschliche Aufsicht **natürlichen Personen** übertragen | Art. 26 Abs. 2 | HR-Frist | | Benennung, Funktionsbeschreibung | |
| A.2.2 | Diese Personen verfügen über die erforderliche **Kompetenz** | Art. 26 Abs. 2 | HR-Frist | | Qualifikationsnachweis | |
| A.2.3 | Diese Personen verfügen über die erforderliche **Ausbildung** | Art. 26 Abs. 2 | HR-Frist | | Schulungsnachweis | |
| A.2.4 | Diese Personen verfügen über die erforderliche **Befugnis** — sie dürfen tatsächlich eingreifen und den Betrieb stoppen | Art. 26 Abs. 2 | HR-Frist | | Kompetenzregelung, Eskalationsordnung | |
| A.2.5 | Erforderliche **Unterstützung** (Zeit, Werkzeuge, Zugriff) bereitstellen | Art. 26 Abs. 2 | HR-Frist | | Ressourcenplanung | |
| A.2.6 | Aufsichtsmaßnahmen des Anbieters aus der Betriebsanleitung umsetzen | Art. 26 Abs. 1 und 3 | HR-Frist | | Umsetzungsdokumentation | |

## A.3 Eingabedaten

| Nr. | Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| A.3.1 | Sicherstellen, dass Eingabedaten der **Zweckbestimmung entsprechen** — soweit die Daten unserer Kontrolle unterliegen | Art. 26 Abs. 4 | HR-Frist | | Datenkonzept | |
| A.3.2 | Sicherstellen, dass Eingabedaten **ausreichend repräsentativ** sind | Art. 26 Abs. 4 | HR-Frist | | Repräsentativitätsprüfung | |
| A.3.3 | Abgrenzen und dokumentieren, welche Eingabedaten unserer Kontrolle unterliegen | Art. 26 Abs. 4 | HR-Frist | | Datenflussdiagramm | |

## A.4 Überwachung, Meldung, Aussetzung

| Nr. | Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| A.4.1 | Betrieb **anhand der Betriebsanleitung überwachen** | Art. 26 Abs. 5 S. 1 | HR-Frist | | Monitoring-Konzept, Auswertungen | |
| A.4.2 | Bei relevanten Erkenntnissen den **Anbieter nach Art. 72 informieren** | Art. 26 Abs. 5 S. 1 | HR-Frist | | Meldeprotokoll | |
| A.4.3 | Bei Grund zur Annahme eines Risikos i. S. d. Art. 79 Abs. 1: **unverzüglich** Anbieter oder Händler **und** Marktüberwachungsbehörde informieren **und die Verwendung aussetzen** | Art. 26 Abs. 5 S. 2 | HR-Frist | | Eskalations- und Stoppverfahren | |
| A.4.4 | Bei **schwerwiegendem Vorfall**: unverzüglich **zuerst den Anbieter**, dann Einführer/Händler und Marktüberwachungsbehörden informieren | Art. 26 Abs. 5 S. 3 | HR-Frist | | Vorfallmeldeverfahren | |
| A.4.5 | Ist der Anbieter nicht erreichbar: Meldung nach Art. 73 entsprechend | Art. 26 Abs. 5 S. 4 | HR-Frist | | Verfahrensbeschreibung | |
| A.4.6 | **Finanzinstitute:** Überwachungspflicht gilt als erfüllt bei Einhaltung der internen Governance-Vorgaben nach Finanzdienstleistungsrecht | Art. 26 Abs. 5 UAbs. 2 | HR-Frist | | Governance-Nachweis | |

## A.5 Protokolle (Logs)

| Nr. | Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| A.5.1 | Automatisch erzeugte Protokolle aufbewahren — soweit sie unserer Kontrolle unterliegen | Art. 26 Abs. 6 UAbs. 1 | HR-Frist | | Log-Archiv | |
| A.5.2 | Aufbewahrungsdauer: **der Zweckbestimmung angemessen, mindestens sechs Monate** — sofern Unions- oder nationales Recht nichts anderes bestimmt | Art. 26 Abs. 6 UAbs. 1 | HR-Frist | | Löschkonzept | |
| A.5.3 | Datenschutzrechtliche Löschfristen abgleichen (können kürzer **oder** länger sein) | Art. 26 Abs. 6 i. V. m. DSGVO | HR-Frist | | Abgleichdokumentation | |
| A.5.4 | **Finanzinstitute:** Protokolle als Teil der Dokumentation nach Finanzdienstleistungsrecht führen | Art. 26 Abs. 6 UAbs. 2 | HR-Frist | | Dokumentationsnachweis | |

> **Sechs Monate sind die Untergrenze, nicht die Regeldauer.** Maßgeblich ist der der Zweckbestimmung angemessene Zeitraum.

## A.6 Information von Beschäftigten und Betroffenen

| Nr. | Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| A.6.1 | **Vor** Inbetriebnahme oder Verwendung am Arbeitsplatz: **Arbeitnehmervertreter** informieren | Art. 26 Abs. 7 S. 1 | HR-Frist | | Informationsschreiben, Protokoll | |
| A.6.2 | **Vor** Inbetriebnahme oder Verwendung am Arbeitsplatz: **betroffene Arbeitnehmer** informieren | Art. 26 Abs. 7 S. 1 | HR-Frist | | Informationsschreiben, Verteilnachweis | |
| A.6.3 | Nationale Vorschriften und Gepflogenheiten zur Unterrichtung beachten (Mitbestimmung bleibt unberührt) | Art. 26 Abs. 7 S. 2, Abs. 3 | HR-Frist | | Beteiligungsnachweis | |
| A.6.4 | Bei **Anhang-III-Systemen**, die Entscheidungen über natürliche Personen treffen **oder unterstützen**: betroffene Personen informieren | Art. 26 Abs. 11 S. 1 | HR-Frist | | Informationstext, Prozessbeschreibung | |
| A.6.5 | Anspruch auf **Erläuterung der Entscheidung** vorbereiten: Rolle des KI-Systems im Entscheidungsprozess und wichtigste Entscheidungselemente erklärbar machen. Gilt nur für **Anhang-III-Systeme außer Nr. 2** (kritische Infrastruktur) und nur bei Entscheidungen mit **rechtlicher Auswirkung oder ähnlich erheblicher Beeinträchtigung** | Art. 86 Abs. 1 | 02.08.2026, praktisch mit HR-Frist | | Erläuterungsvorlage, Prozess | |

> **Zu A.6.4:** Die Pflicht greift auch, wenn das System die Entscheidung nur **unterstützt** — nicht erst bei voller Automatisierung.

> **Zu A.6.5:** Art. 86 ist **subsidiär**: Er gilt nur, soweit das Recht nicht anderweitig im Unionsrecht festgelegt ist (praktisch relevant: Art. 22 i. V. m. Art. 13–15 DSGVO). *(Art. 86 Abs. 3)*

## A.7 Registrierung, Zusammenarbeit, Datenschutz

| Nr. | Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| A.7.1 | **Öffentliche Stellen:** Registrierungspflichten nach Art. 49 erfüllen | Art. 26 Abs. 8 S. 1 | HR-Frist | | Registrierungsbestätigung | |
| A.7.2 | **Öffentliche Stellen:** Ist das System **nicht** in der EU-Datenbank registriert, von der Verwendung absehen und Anbieter oder Händler informieren | Art. 26 Abs. 8 S. 2 | HR-Frist | | Prüfprotokoll | |
| A.7.3 | Informationen des Anbieters nach Art. 13 für eine ggf. erforderliche **Datenschutz-Folgenabschätzung** verwenden | Art. 26 Abs. 9 | HR-Frist | | DSFA | |
| A.7.4 | Mit den zuständigen Behörden bei allen Maßnahmen zum System **zusammenarbeiten** | Art. 26 Abs. 12 | HR-Frist | | Ansprechpartner, Verfahren | |
| A.7.5 | **Nur bei nachträglicher biometrischer Fernidentifizierung zu Strafverfolgungszwecken:** Genehmigung vorab oder **spätestens binnen 48 Stunden** einholen; bei Ablehnung Verwendung mit sofortiger Wirkung einstellen und Daten löschen; jede Verwendung in der Akte dokumentieren; Jahresberichte an Marktüberwachungs- und Datenschutzbehörde | Art. 26 Abs. 10 | HR-Frist | | Genehmigungen, Löschprotokolle, Jahresberichte | |
| A.7.6 | **n. F.:** Verarbeitung besonderer Kategorien personenbezogener Daten zur Erkennung und Korrektur von Verzerrungen. Für **Betreiber** gilt **Art. 4a Abs. 2**: zusätzlich zu sämtlichen Bedingungen des Abs. 1 lit. a–f muss die Verarbeitung **unbedingt erforderlich** sein im Hinblick auf Verzerrungen, die Gesundheit und Sicherheit beeinträchtigen, negative Auswirkungen auf Grundrechte haben oder zu unionsrechtlich verbotener Diskriminierung führen können. Aus der Erlaubnis folgt **keine Pflicht** zur Bias-Prüfung. | Art. 4a Abs. 2 i. V. m. Abs. 1 KI-VO n. F. | gilt seit 27.07.2026 | | Erforderlichkeitsprüfung, Schutzvorkehrungen, Verarbeitungsverzeichnis-Eintrag mit Begründung (Abs. 1 lit. f) | |
| A.7.7 | **Abgrenzung:** Art. 4a ist **keine allgemeine Rechtsgrundlage** und **ersetzt keine datenschutzrechtliche Prüfung**. Die Bedingungen gelten ausdrücklich *zusätzlich* zu DSGVO, VO (EU) 2018/1725 und RL (EU) 2016/680. Verantwortlichkeit, Zweckbindung, Betroffenenrechte und ggf. DSFA gesondert prüfen. | Art. 4a Abs. 1 UAbs. 1 KI-VO n. F.; Art. 9 DSGVO | gilt seit 27.07.2026 | | Datenschutzrechtliche Bewertung | |

> **Sprachfassungshinweis zu A.7.1/A.7.2:** Der amtliche deutsche Text des Art. 26 Abs. 8 nennt nur Organe, Einrichtungen und sonstige Stellen **der Union**. Der amtliche englische Text nennt zusätzlich "public authorities", also auch nationale Behörden. Für öffentliche Stellen in Deutschland ist vorsorglich von der weiteren Lesart auszugehen. Ob ein Corrigendum ergangen ist, wurde nicht verifiziert.

## A.8 Grundrechte-Folgenabschätzung (nur bestimmte Betreiber)

| Nr. | Prüfpunkt / Pflicht | Fundstelle | Frist | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|---|
| A.8.1 | **Sind wir überhaupt verpflichtet?** Verpflichtet sind: Einrichtungen des öffentlichen Rechts; private Einrichtungen, die öffentliche Dienste erbringen; Betreiber von Systemen nach Anhang III Nr. 5 lit. b (Kreditwürdigkeit) und lit. c (Lebens-/Krankenversicherung) | Art. 27 Abs. 1 S. 1 | vor Inbetriebnahme | | Zuständigkeitsprüfung | |
| A.8.2 | **Ausnahme:** Systeme nach Anhang III Nr. 2 (kritische Infrastruktur) sind nicht erfasst | Art. 27 Abs. 1 S. 1 | — | | Bewertung | |
| A.8.3 | Beschreibung der **Verfahren**, in denen das System zweckentsprechend verwendet wird | Art. 27 Abs. 1 lit. a | vor Inbetriebnahme | | GRFA-Dokument | |
| A.8.4 | Beschreibung von **Zeitraum und Häufigkeit** der Verwendung | Art. 27 Abs. 1 lit. b | vor Inbetriebnahme | | GRFA-Dokument | |
| A.8.5 | **Kategorien betroffener Personen und Personengruppen** ermitteln | Art. 27 Abs. 1 lit. c | vor Inbetriebnahme | | GRFA-Dokument | |
| A.8.6 | **Spezifische Schadensrisiken** für diese Gruppen bewerten — unter Berücksichtigung der Anbieterinformationen nach Art. 13 | Art. 27 Abs. 1 lit. d | vor Inbetriebnahme | | GRFA-Dokument | |
| A.8.7 | Umsetzung der **menschlichen Aufsicht** entsprechend der Betriebsanleitung beschreiben | Art. 27 Abs. 1 lit. e | vor Inbetriebnahme | | GRFA-Dokument | |
| A.8.8 | **Maßnahmen bei Risikoeintritt** festlegen, einschließlich interner Unternehmensführung und **Beschwerdemechanismen** | Art. 27 Abs. 1 lit. f | vor Inbetriebnahme | | GRFA-Dokument, Beschwerdeverfahren | |
| A.8.9 | Bei ähnlichen Fällen: auf frühere GRFA oder auf Folgenabschätzungen des Anbieters stützen | Art. 27 Abs. 2 S. 2 | — | | Verweisdokumentation | |
| A.8.10 | Bei Änderungen der Elemente aus Abs. 1: GRFA **aktualisieren** | Art. 27 Abs. 2 S. 3 | laufend | | Änderungshistorie | |
| A.8.11 | Ergebnisse der **Marktüberwachungsbehörde** mitteilen (ausgefülltes Muster nach Abs. 5) — Befreiung möglich im Fall des Art. 46 Abs. 1 | Art. 27 Abs. 3 S. 1 und 2 | nach Durchführung | | Übermittlungsnachweis | |
| A.8.12 | **n. F.:** Soweit eine Pflicht bereits durch eine DSFA nach Art. 35 DSGVO erfüllt ist, **Verweise** auf die einschlägigen Abschnitte oder die einschlägigen **Teile** der DSFA aufnehmen | Art. 27 Abs. 4 n. F. | — | | Verweisstruktur | |
| A.8.13 | **n. F.:** Muster-Fragebogen des **Büros für Künstliche Intelligenz** verwenden, sobald verfügbar | Art. 27 Abs. 5 n. F. | sobald verfügbar | | Muster, Ausfüllung | |

> **Was sich geändert hat:** Bisher "ergänzte" die Grundrechte-Folgenabschätzung die DSFA. Jetzt ist ausdrücklich zugelassen, Verweise oder Teile zu übernehmen. Die eigenständige Prüfung entfällt dadurch **nicht**. Zuständig für das Muster ist nun das KI-Büro statt der Kommission. *(VO (EU) 2026/1744, Art. 1 Nr. 13)*

---

# Checkliste B — Anbieter (Provider) von Hochrisiko-KI-Systemen

> **Anwendbarkeit:** Die Pflichten dieser Checkliste gelten ab dem **02.12.2027** für Systeme nach Anhang III und ab dem **02.08.2028** für Systeme nach Anhang I. *(Art. 113 Abs. 3 lit. c KI-VO n. F.)* Der Aufbau von Risikomanagement, Qualitätsmanagement und technischer Dokumentation braucht Vorlauf — die Frist ist knapper, als sie wirkt.

## B.0 Einstufung und Vorprüfung

| Nr. | Prüfpunkt | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.0.1 | **Weg A:** Ist das System Sicherheitsbauteil eines Anhang-I-Produkts oder selbst ein solches Produkt **und** muss dieses durch Dritte konformitätsbewertet werden? | Art. 6 Abs. 1 lit. a und b | | Einstufungsdokumentation | |
| B.0.2 | **n. F.:** Erfüllt das Bauteil eine **Sicherheitsfunktion** — ist seine Zweckbestimmung, Risiken für Gesundheit und Sicherheit abzuwenden oder zu mindern? | Art. 3 Nr. 14 n. F. | | Bewertung | |
| B.0.3 | **n. F.:** Dient das System **ausschließlich** nicht sicherheitsrelevanten Aspekten (Nutzerunterstützung, Leistungsoptimierung, Leistungseffizienz, Automatisierung, Benutzerfreundlichkeit, Qualitätskontrolle)? Dann **kein** Sicherheitsbauteil. | Art. 6 Abs. 1a n. F. | | Bewertung | |
| B.0.4 | **n. F. — Gegenprobe:** Würde ein Ausfall oder eine Fehlfunktion Gesundheit und Sicherheit gefährden? Dann **doch** Sicherheitsbauteil. | Art. 6 Abs. 1b n. F. | | Bewertung | |
| B.0.5 | **n. F.:** Wird das Produkt nur wegen **anderer Risiken als Gesundheit und Sicherheit** drittgeprüft (z. B. Funkfrequenzen, elektromagnetische Interferenzen)? Dann ist Art. 6 Abs. 1 lit. b **nicht** erfüllt. | Art. 6 Abs. 1c n. F. | | Bewertung | |
| B.0.6 | **Weg B:** Fällt das System unter einen der acht Bereiche des Anhangs III? | Art. 6 Abs. 2, Anhang III | | Einstufungsdokumentation | |
| B.0.7 | Falls Anhang III: Greift der **Ausnahmefilter** nach Art. 6 Abs. 3 (eine der vier Bedingungen **und** kein erhebliches Risiko)? | Art. 6 Abs. 3 | | Begründete Bewertung | |
| B.0.8 | **Sperre:** Nimmt das System **Profiling** vor? Dann immer hochriskant. | Art. 6 Abs. 3 UAbs. 3 | | Bewertung | |
| B.0.9 | Bei Berufung auf Art. 6 Abs. 3: Bewertung **vor** Inverkehrbringen/Inbetriebnahme **dokumentieren** | Art. 6 Abs. 4 S. 1 | | Bewertungsdokument mit Datum | |
| B.0.10 | Bei Berufung auf Art. 6 Abs. 3: dennoch **Registrierung nach Art. 49 Abs. 2** vornehmen | Art. 6 Abs. 4 S. 2 | | Registrierungsbestätigung | |
| B.0.11 | Dokumentation auf Verlangen der zuständigen nationalen Behörden vorlegen | Art. 6 Abs. 4 S. 3 | | Bereitstellungsverfahren | |
| B.0.12 | Falls Weg A: **Konkreten Rechtsakt aus Anhang I benennen und Abschnitt bestimmen (A oder B).** Bei **Abschnitt B** gelten von der KI-VO nur Art. 6 Abs. 1, Art. 60a und Art. 102–112 — diese Checkliste ist dann nicht anwendbar; maßgeblich ist das Sektorrecht (bei Maschinen: Anhang III der VO (EU) 2023/1230, delegierter Rechtsakt ab 02.08.2028). | Anhang I; Art. 2 Abs. 2 n. F.; VO (EU) 2026/1744 Art. 1 Nr. 41 und Art. 3 | | Rechtsaktbestimmung mit Nummer und Abschnitt | |
| B.0.13 | Bei **Abschnitt A**: delegierte Rechtsakte nach Art. 2 Abs. 13 KI-VO n. F. beobachten (Frist der Kommission: 02.08.2027) — sie können die Anwendung der Art. 9–15 und 17–25 beschränken. | Art. 2 Abs. 13 n. F. | | Beobachtungsvermerk | |
| B.0.14 | Ist die Einstufung **juristisch bestätigt**? Ja / Nein / offen, mit Datum und prüfender Person festhalten. | (Nachweisführung) | | Prüfvermerk | |

> **Häufiger Irrtum:** Art. 6 Abs. 3 und Abs. 4 wurden durch den Digital Omnibus **nicht** geändert. Die Registrierungspflicht bei Selbsteinstufung als nicht-hochriskant besteht fort. Gestrichen wurden lediglich zwei Angaben im Registrierungsformular (Anhang VIII Abschnitt B Nrn. 7 und 9).

## B.1 Risikomanagementsystem (Art. 9)

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.1.1 | Risikomanagementsystem einrichten, anwenden, dokumentieren und aufrechterhalten — als **kontinuierlicher iterativer Prozess** über den gesamten Lebenszyklus | Art. 9 Abs. 1 und 2 | | RMS-Dokumentation | |
| B.1.2 | **Bekannte und vorhersehbare Risiken** für Gesundheit, Sicherheit und Grundrechte bei bestimmungsgemäßer Verwendung ermitteln und analysieren | Art. 9 Abs. 2 lit. a | | Risikoanalyse | |
| B.1.3 | Risiken bei **vernünftigerweise vorhersehbarer Fehlanwendung** abschätzen und bewerten | Art. 9 Abs. 2 lit. b | | Fehlanwendungsanalyse | |
| B.1.4 | Weitere Risiken auf Grundlage der Daten aus dem **Beobachtungssystem nach Art. 72** bewerten | Art. 9 Abs. 2 lit. c | | Auswertungsberichte | |
| B.1.5 | **Geeignete und gezielte Risikomanagementmaßnahmen** ergreifen | Art. 9 Abs. 2 lit. d | | Maßnahmenkatalog | |
| B.1.6 | Systeme **erproben**, um geeignete Maßnahmen zu ermitteln und die Einhaltung der Anforderungen zu prüfen | Art. 9 Abs. 6–8 | | Testberichte | |
| B.1.7 | Besondere Berücksichtigung von Auswirkungen auf **Personen unter 18 Jahren** und andere schutzbedürftige Gruppen | Art. 9 Abs. 9 | | Bewertung | |

## B.2 Daten und Daten-Governance (Art. 10)

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.2.1 | Trainings-, Validierungs- und Testdatensätze unterliegen geeigneten **Daten-Governance-Verfahren** | Art. 10 Abs. 2 | | Governance-Konzept | |
| B.2.2 | Datensätze sind **relevant, hinreichend repräsentativ und so weit wie möglich fehlerfrei und vollständig** im Hinblick auf die Zweckbestimmung | Art. 10 Abs. 3 | | Datenqualitätsbericht | |
| B.2.3 | Berücksichtigung der **geografischen, kontextbezogenen, verhaltensbezogenen und funktionalen Rahmenbedingungen** des Einsatzes | Art. 10 Abs. 4 | | Kontextanalyse | |
| B.2.4 | Untersuchung auf mögliche **Verzerrungen (Bias)**, die Gesundheit, Sicherheit, Grundrechte oder Diskriminierungsfreiheit beeinträchtigen | Art. 10 Abs. 2 lit. f und g | | Bias-Prüfbericht | |
| B.2.5 | **n. F.:** Als **Anbieter eines Hochrisiko-Systems** dürfen besondere Kategorien personenbezogener Daten zur Erkennung und Korrektur von Verzerrungen verarbeitet werden, soweit das im Einklang mit Art. 10 Abs. 2 lit. f und g **unbedingt erforderlich** ist und **sämtliche** Bedingungen des Art. 4a Abs. 1 lit. a–f erfüllt sind. **Art. 10 Abs. 5 a. F. wurde gestrichen.** Anwendbar seit 27.07.2026 — also bereits vor der HR-Frist. | Art. 4a Abs. 1 KI-VO n. F. (VO (EU) 2026/1744, Art. 1 Nrn. 6 und 9) | | Rechtsgrundlagenprüfung, Löschkonzept (lit. e), Begründung im Verarbeitungsverzeichnis (lit. f) | |
| B.2.6 | **Abgrenzung:** Die Bedingungen des Art. 4a gelten **zusätzlich** zu DSGVO, VO (EU) 2018/1725 und RL (EU) 2016/680 — sie ersetzen die datenschutzrechtliche Prüfung nicht. | Art. 4a Abs. 1 UAbs. 1 KI-VO n. F. | | Datenschutzrechtliche Bewertung | |

## B.3 Technische Dokumentation (Art. 11, Anhang IV)

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.3.1 | Technische Dokumentation **vor** Inverkehrbringen/Inbetriebnahme erstellen und **aktuell halten** | Art. 11 Abs. 1 | | Technische Dokumentation | |
| B.3.2 | Allgemeine Beschreibung des Systems (Zweckbestimmung, Anbieter, Versionen, Interaktion mit Hard-/Software) | Anhang IV Nr. 1 | | Doku Kapitel 1 | |
| B.3.3 | Detaillierte Beschreibung der Systemelemente und des Entwicklungsprozesses | Anhang IV Nr. 2 | | Doku Kapitel 2 | |
| B.3.4 | Detaillierte Informationen zur **Überwachung, Funktionsweise und Kontrolle** | Anhang IV Nr. 3 | | Doku Kapitel 3 | |
| B.3.5 | Beschreibung der **Eignung der Leistungskennzahlen** | Anhang IV Nr. 4 | | Doku Kapitel 4 | |
| B.3.6 | Detaillierte Beschreibung des **Risikomanagementsystems** | Anhang IV Nr. 5 | | Doku Kapitel 5 | |
| B.3.7 | Beschreibung relevanter **Änderungen** über den Lebenszyklus | Anhang IV Nr. 6 | | Änderungshistorie | |
| B.3.8 | Liste der angewandten **harmonisierten Normen** oder Beschreibung alternativer Lösungen | Anhang IV Nr. 7 | | Normenliste | |
| B.3.9 | Kopie der **EU-Konformitätserklärung** | Anhang IV Nr. 8 | | Konformitätserklärung | |
| B.3.10 | Beschreibung des Systems zur **Leistungsbewertung nach dem Inverkehrbringen**, einschließlich des Plans nach Art. 72 Abs. 3 | Anhang IV Nr. 9 | | PMM-Plan | |
| B.3.11 | **KMU und kleine Midcap-Unternehmen (n. F.):** vereinfachtes Formular der Kommission nutzen — notifizierte Stellen **müssen** es akzeptieren | Art. 11 Abs. 1 UAbs. 2 n. F. | | Formular | |

## B.4 Aufzeichnung und Protokollierung (Art. 12, 19)

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.4.1 | System so gestalten, dass Ereignisse über die Lebensdauer **automatisch protokolliert** werden | Art. 12 Abs. 1 | | Logging-Konzept | |
| B.4.2 | Protokollierung ermöglicht die Ermittlung von Risikosituationen i. S. d. Art. 79 Abs. 1 und wesentlichen Änderungen | Art. 12 Abs. 2 lit. a | | Konzept | |
| B.4.3 | Protokollierung erleichtert die **Beobachtung nach dem Inverkehrbringen** | Art. 12 Abs. 2 lit. b | | Konzept | |
| B.4.4 | Protokollierung ermöglicht die **Betriebsüberwachung durch Betreiber** nach Art. 26 Abs. 5 | Art. 12 Abs. 2 lit. c | | Konzept | |
| B.4.5 | Vom Anbieter kontrollierte Protokolle **aufbewahren** — angemessener Zeitraum, mindestens sechs Monate | Art. 19 | | Archivkonzept | |

## B.5 Transparenz gegenüber Betreibern (Art. 13)

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.5.1 | Betrieb hinreichend transparent gestalten, damit Betreiber die Ausgaben angemessen interpretieren und verwenden können | Art. 13 Abs. 1 | | Konzept | |
| B.5.2 | **Betriebsanleitung** in geeigneter digitaler oder anderer Form beifügen — prägnant, vollständig, korrekt, klar, relevant, barrierefrei, verständlich | Art. 13 Abs. 2 | | Betriebsanleitung | |
| B.5.3 | Inhalte: Identität und Kontaktdaten des Anbieters; Merkmale, Fähigkeiten und Leistungsgrenzen; Zweckbestimmung; Genauigkeits-, Robustheits- und Cybersicherheitsniveau; bekannte vorhersehbare Umstände mit Risikofolge; ggf. Angaben zu Eingabedaten | Art. 13 Abs. 3 lit. a–b | | Betriebsanleitung | |
| B.5.4 | Angaben zu **menschlicher Aufsicht**: technische Maßnahmen zur Interpretationserleichterung | Art. 13 Abs. 3 lit. d | | Betriebsanleitung | |
| B.5.5 | Angaben zu erwarteter **Lebensdauer, Wartung und Pflege**, einschließlich Software-Updates | Art. 13 Abs. 3 lit. e | | Betriebsanleitung | |
| B.5.6 | Beschreibung der **Protokollierungsmechanismen** | Art. 13 Abs. 3 lit. f | | Betriebsanleitung | |

## B.6 Menschliche Aufsicht (Art. 14)

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.6.1 | System so gestalten, dass es während der Verwendung **wirksam durch Menschen beaufsichtigt** werden kann | Art. 14 Abs. 1 | | Designdokumentation | |
| B.6.2 | Aufsichtsmaßnahmen **eingebaut** und/oder als vom Betreiber umzusetzende Maßnahmen **festgelegt** | Art. 14 Abs. 3 | | Konzept, Betriebsanleitung | |
| B.6.3 | Befähigung, die Fähigkeiten und Grenzen des Systems zu **verstehen** und die Funktionsweise zu **überwachen** | Art. 14 Abs. 4 lit. a | | Konzept | |
| B.6.4 | Bewusstsein für **Automatisierungsbias** ermöglichen | Art. 14 Abs. 4 lit. b | | Konzept, Schulungsunterlagen | |
| B.6.5 | Ausgaben **richtig interpretieren** können | Art. 14 Abs. 4 lit. c | | Konzept | |
| B.6.6 | Möglichkeit, die Verwendung **zu unterlassen, zu ignorieren, zu überschreiben oder umzukehren** | Art. 14 Abs. 4 lit. d und e | | Konzept | |
| B.6.7 | Möglichkeit, den Betrieb mit einer **Stopptaste** oder einem vergleichbaren Verfahren zu unterbrechen | Art. 14 Abs. 4 lit. e | | Funktionsnachweis | |
| B.6.8 | Bei biometrischer Identifizierung nach Anhang III Nr. 1 lit. a: **Vier-Augen-Prinzip** — keine Maßnahme allein aufgrund der Identifizierung ohne gesonderte Überprüfung und Bestätigung durch mindestens zwei Personen. Die Norm richtet sich als Gestaltungsanforderung an den Anbieter, formuliert aber eine Handlungsschranke, die der **Betreiber** einzuhalten hat. | Art. 14 Abs. 5 | | Verfahrensbeschreibung | |

## B.7 Genauigkeit, Robustheit, Cybersicherheit (Art. 15)

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.7.1 | Angemessenes Maß an **Genauigkeit, Robustheit und Cybersicherheit** über den gesamten Lebenszyklus | Art. 15 Abs. 1 | | Testberichte | |
| B.7.2 | **Genauigkeitsgrade und Metriken** in der Betriebsanleitung angeben | Art. 15 Abs. 3 | | Betriebsanleitung | |
| B.7.3 | Widerstandsfähigkeit gegen **Fehler, Störungen und Unstimmigkeiten** — technische Redundanz, Backup, Fail-Safe | Art. 15 Abs. 4 | | Architekturdokumentation | |
| B.7.4 | Bei Systemen, die nach dem Inverkehrbringen weiterlernen: **Rückkopplungsschleifen** (Bias durch Ausgaben als künftige Eingaben) minimieren | Art. 15 Abs. 4 UAbs. 3 | | Konzept | |
| B.7.5 | Widerstandsfähigkeit gegen **Angriffe** — insbesondere Data Poisoning, Model Poisoning, adversarial examples, Model Evasion, Vertraulichkeitsangriffe, Modellmängel | Art. 15 Abs. 5 | | Sicherheitskonzept, Penetrationstest | |
| B.7.6 | **n. F.:** Konformitätsvermutung für Cybersicherheit über die Cyberresilienz-Verordnung (EU) 2024/2847 prüfen | Art. 42 Abs. 3 n. F. | | Nachweis | |

## B.8 Qualitätsmanagementsystem (Art. 17)

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.8.1 | QMS einrichten, das die Einhaltung der Verordnung sicherstellt — systematisch, geordnet, in Form schriftlicher Regeln, Verfahren und Anweisungen | Art. 17 Abs. 1 | | QMS-Handbuch | |
| B.8.2 | Strategie zur Einhaltung der Regulierung, einschließlich Konformitätsbewertung und Änderungsmanagement | Art. 17 Abs. 1 lit. a | | QMS-Kapitel | |
| B.8.3 | Verfahren für Konzeption, Entwicklung, Qualitätskontrolle und Qualitätssicherung | Art. 17 Abs. 1 lit. b–d | | QMS-Kapitel | |
| B.8.4 | Prüf-, Test- und Validierungsverfahren einschließlich Zeitpunkten | Art. 17 Abs. 1 lit. e | | QMS-Kapitel | |
| B.8.5 | Technische Spezifikationen, Normen, Verfahren zur Datenverwaltung | Art. 17 Abs. 1 lit. f–g | | QMS-Kapitel | |
| B.8.6 | **Risikomanagementsystem** nach Art. 9 | Art. 17 Abs. 1 lit. g | | QMS-Kapitel | |
| B.8.7 | System zur **Beobachtung nach dem Inverkehrbringen** nach Art. 72 | Art. 17 Abs. 1 lit. h | | QMS-Kapitel | |
| B.8.8 | Verfahren zur **Meldung schwerwiegender Vorfälle** nach Art. 73 | Art. 17 Abs. 1 lit. i | | QMS-Kapitel | |
| B.8.9 | Kommunikation mit Behörden, Aufzeichnungsführung, Ressourcenmanagement, Rechenschaftsrahmen | Art. 17 Abs. 1 lit. j–m | | QMS-Kapitel | |
| B.8.10 | Umsetzung **im Verhältnis zur Größe der Organisation** — für KMU und kleine Midcap-Unternehmen ausdrücklich vorgesehen | Art. 17 Abs. 2 n. F. | | Begründung der Skalierung | |
| B.8.11 | **Nur KMU einschließlich Start-ups (n. F.):** vereinfachtes QMS nach Art. 63 Abs. 1 — Bedingung: keine Partnerunternehmen oder verbundenen Unternehmen i. S. d. Empfehlung 2003/361/EG. **Kleine Midcap-Unternehmen sind hier nicht erfasst.** Die Vereinfachung befreit **nicht** von den Anforderungen der Art. 9–15, 72 und 73 (Art. 63 Abs. 2). | Art. 63 Abs. 1 n. F., Art. 63 Abs. 2 | | Nachweis der Unternehmensstruktur | |

## B.9 Konformitätsbewertung, Erklärung, CE, Registrierung

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.9.1 | Zutreffendes **Konformitätsbewertungsverfahren** bestimmen. **Achtung:** Die Wahl zwischen interner Kontrolle (Anhang VI) und notifizierter Stelle (Anhang VII) besteht **nur bei Anhang III Nr. 1 (Biometrie)**. Bei **Anhang III Nrn. 2–8** — also auch Beschäftigung und Kreditwürdigkeit — ist stets die interne Kontrolle nach Anhang VI vorgeschrieben. Bei Anhang I Abschnitt A gilt das Verfahren des Sektorrechts. | Art. 43 Abs. 1, 2 und 3 n. F. | | Verfahrensentscheidung | |
| B.9.2 | Verfahren **vor** Inverkehrbringen/Inbetriebnahme durchführen | Art. 16 lit. f | | Bewertungsunterlagen | |
| B.9.3 | Bei **wesentlicher Veränderung**: erneute Konformitätsbewertung | Art. 43 Abs. 4 | | Änderungsbewertung | |
| B.9.4 | **EU-Konformitätserklärung** ausstellen (Inhalte nach Anhang V), 10 Jahre aufbewahren | Art. 47 | | Konformitätserklärung | |
| B.9.5 | **CE-Kennzeichnung** anbringen — am System oder auf Verpackung bzw. in beigefügter Dokumentation | Art. 48 Abs. 1–3 | | Nachweis | |
| B.9.6 | Ggf. **Identifizierungsnummer der notifizierten Stelle** anbringen, auch in Werbematerial angeben | Art. 48 Abs. 4 | | Nachweis | |
| B.9.7 | System in der **EU-Datenbank registrieren**. **Achtung zum Anwendungsbereich:** Art. 49 Abs. 1 gilt nur für **Anhang-III-Systeme mit Ausnahme der Nr. 2** (kritische Infrastruktur — diese werden nach Art. 49 Abs. 5 auf nationaler Ebene registriert). Für **Anhang-I-Systeme** besteht keine EU-Datenbank-Registrierung nach Art. 49 Abs. 1. | Art. 49 Abs. 1 und 5, Art. 16 lit. i | | Registrierungsbestätigung | |
| B.9.8 | Bei Selbsteinstufung als nicht-hochriskant nach Art. 6 Abs. 3: Registrierung nach **Art. 49 Abs. 2** | Art. 49 Abs. 2, Art. 6 Abs. 4 | | Registrierungsbestätigung | |
| B.9.9 | **Dokumentation 10 Jahre aufbewahren:** technische Dokumentation, QMS-Dokumentation, genehmigte Änderungen, Entscheidungen notifizierter Stellen, EU-Konformitätserklärung | Art. 18 | | Archivkonzept | |

## B.10 Nach dem Inverkehrbringen

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.10.1 | **Beobachtungssystem nach dem Inverkehrbringen** einrichten und dokumentieren, angemessen zur Art der Technologie und zu den Risiken | Art. 72 Abs. 1 | | PMM-System | |
| B.10.2 | **Plan für die Beobachtung** erstellen (Teil der technischen Dokumentation nach Anhang IV) | Art. 72 Abs. 3 | | PMM-Plan | |
| B.10.3 | **n. F.:** Leitlinien und Muster der Kommission für den PMM-Plan berücksichtigen, sobald verfügbar (Frist der Kommission: 02.09.2027) | Art. 72 Abs. 3 n. F. | | Muster | |
| B.10.4 | Bei **Nichtkonformität**: unverzüglich Korrekturmaßnahmen — in Einklang bringen, vom Markt nehmen, deaktivieren oder zurückrufen — und Händler, Betreiber, Bevollmächtigte und Einführer informieren | Art. 20 Abs. 1 | | Verfahren, Meldeprotokoll | |
| B.10.5 | Bei Risiko i. S. d. Art. 79 Abs. 1: unverzüglich Ursachen untersuchen und Marktüberwachungsbehörden sowie ggf. notifizierte Stelle unterrichten | Art. 20 Abs. 2 | | Untersuchungsbericht | |
| B.10.6 | **Meldung schwerwiegender Vorfälle — Regelfall:** unmittelbar nach Feststellung des kausalen Zusammenhangs oder der naheliegenden Wahrscheinlichkeit, **spätestens 15 Tage** nach Kenntniserlangung | Art. 73 Abs. 2 | | Meldeverfahren | |
| B.10.7 | **Meldung — weitverbreiteter Verstoß oder schwerwiegende Störung kritischer Infrastruktur:** unverzüglich, **spätestens zwei Tage** | Art. 73 Abs. 3 | | Meldeverfahren | |
| B.10.8 | **Meldung — Tod einer Person:** unverzüglich, **spätestens zehn Tage** | Art. 73 Abs. 4 | | Meldeverfahren | |
| B.10.9 | Nach der Meldung unverzüglich Untersuchungen einschließlich Risikobewertung und Korrekturmaßnahmen durchführen; das System **nicht** so verändern, dass eine spätere Ursachenbewertung beeinträchtigt wird, bevor die Behörden unterrichtet sind | Art. 73 Abs. 6 | | Untersuchungsbericht | |
| B.10.10 | Mit den zuständigen Behörden **zusammenarbeiten**, Informationen und Dokumentation bereitstellen | Art. 21 | | Ansprechpartner, Verfahren | |

## B.11 Weitere Anbieterpflichten

| Nr. | Pflicht | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| B.11.1 | Name, eingetragener Handelsname oder Marke und Kontaktanschrift auf dem System, der Verpackung oder in der Begleitdokumentation angeben | Art. 16 lit. b | | Kennzeichnung | |
| B.11.2 | **Barrierefreiheitsanforderungen** nach den Richtlinien (EU) 2016/2102 und (EU) 2019/882 erfüllen | Art. 16 lit. l | | Barrierefreiheitsnachweis | |
| B.11.3 | **Anbieter aus Drittstaaten:** schriftlich bevollmächtigten Vertreter in der Union benennen — **vor** Bereitstellung auf dem Unionsmarkt | Art. 22 Abs. 1 | | Mandat | |
| B.11.4 | Dem Bevollmächtigten die erforderlichen Unterlagen zur Verfügung stellen | Art. 22 Abs. 2 und 3 | | Übergabenachweis | |

---

# Checkliste C — Rollenwechsel: Wann wird ein Betreiber zum Anbieter?

> **Warum diese Checkliste wichtig ist:** Der Rollenwechsel löst die vollständigen Anbieterpflichten nach Art. 16 aus — Risikomanagement, technische Dokumentation, Konformitätsbewertung, CE-Kennzeichnung, Registrierung. Er tritt kraft Gesetzes ein, nicht durch Entscheidung. Wer ihn nicht bemerkt, ist unbemerkt nicht konform.

## C.1 Die drei Auslöser

| Nr. | Auslöser | Fundstelle | Zutreffend? | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| C.1.1 | **Eigenlabeling:** Wir versehen ein bereits in Verkehr gebrachtes oder in Betrieb genommenes Hochrisiko-System mit unserem Namen oder unserer Handelsmarke | Art. 25 Abs. 1 lit. a | | Produktkennzeichnung, Vertragslage | |
| C.1.2 | **Wesentliche Veränderung:** Wir verändern ein Hochrisiko-System wesentlich, und es bleibt hochriskant | Art. 25 Abs. 1 lit. b | | Änderungsdokumentation | |
| C.1.3 | **Zweckänderung:** Wir ändern die Zweckbestimmung eines nicht als hochriskant eingestuften Systems — **ausdrücklich auch eines KI-Systems mit allgemeinem Verwendungszweck** — so, dass es zum Hochrisiko-System wird | Art. 25 Abs. 1 lit. c | | Zweckdokumentation | |
| C.1.4 | **Produkthersteller:** Wir bringen ein Hochrisiko-KI-System zusammen mit unserem Produkt unter unserem Namen oder unserer Handelsmarke in Verkehr oder nehmen es in Betrieb | Art. 25 Abs. 3 | | Produkt- und Vertragsdokumentation | |

## C.2 Typische Praxisfälle — bitte einzeln prüfen

| Nr. | Fallgestaltung | Bewertungshinweis | Fundstelle | Zutreffend? |
|---|---|---|---|---|
| C.2.1 | Wir bauen auf einem allgemeinen Sprachmodell ein Werkzeug zur **Bewerbervorauswahl** | Anhang III Nr. 4 lit. a → Hochrisiko; Zweckänderung → wir werden Anbieter | Art. 25 Abs. 1 lit. c, Anhang III Nr. 4 | |
| C.2.2 | Wir setzen ein Standardwerkzeug zur **Leistungs- oder Verhaltensüberwachung** von Beschäftigten ein | Anhang III Nr. 4 lit. b → Hochrisiko | Anhang III Nr. 4 lit. b | |
| C.2.3 | Wir integrieren ein zugekauftes Modell in unser Produkt und vertreiben es **unter unserer Marke** | Eigenlabeling → wir werden Anbieter | Art. 25 Abs. 1 lit. a | |
| C.2.4 | Wir **fine-tunen** ein zugekauftes Hochrisiko-System auf eigene Daten | Prüfen: wesentliche Veränderung i. S. d. Art. 3 Nr. 23? | Art. 25 Abs. 1 lit. b, Art. 3 Nr. 23 | |
| C.2.5 | Wir nutzen ein System für einen **anderen Zweck als vom Anbieter vorgesehen** | Prüfen: Zweckänderung ins Hochrisiko? Zugleich Verstoß gegen Art. 26 Abs. 1 | Art. 25 Abs. 1 lit. c, Art. 26 Abs. 1 | |
| C.2.6 | Wir bauen ein internes Werkzeug zur **Kreditwürdigkeitsprüfung** | Anhang III Nr. 5 lit. b → Hochrisiko; zusätzlich Grundrechte-Folgenabschätzung nach Art. 27 | Anhang III Nr. 5 lit. b, Art. 27 Abs. 1 | |
| C.2.7 | Wir entwickeln ein System **für den Eigengebrauch** und nehmen es selbst in Betrieb | "Inbetriebnahme" erfasst ausdrücklich den Eigengebrauch → Anbieterrolle möglich | Art. 3 Nr. 11, Art. 3 Nr. 3 | |

## C.3 Folgen und Absicherung

| Nr. | Pflicht / Maßnahme | Fundstelle | Status | Nachweis | Verantwortlich |
|---|---|---|---|---|---|
| C.3.1 | Bei Eintritt eines Auslösers: **vollständige Anbieterpflichten nach Art. 16** übernehmen → Checkliste B abarbeiten | Art. 25 Abs. 1 | | Umsetzungsplan | |
| C.3.2 | **n. F.:** Vom Erstanbieter die konkretisierten Mitwirkungsleistungen einfordern: technische Unterlagen, Information über bekannte Einschränkungen und Fehlerarten, gezielter technischer Zugang auch zu Test- und Validierungszwecken | Art. 25 Abs. 2 n. F. | | Vertragsklausel, Anforderungsschreiben | |
| C.3.3 | Prüfen, ob der Erstanbieter **eindeutig festgelegt** hat, dass sein System nicht in ein Hochrisiko-System umgewandelt werden darf — dann entfällt seine Mitwirkungspflicht | Art. 25 Abs. 2 n. F. | | Vertrag, Nutzungsbedingungen | |
| C.3.4 | **n. F.:** Ausnahme prüfen für Dritte, die Instrumente, Dienste oder Komponenten (außer GPAI-Modellen) unter freier und quelloffener Lizenz bereitstellen | Art. 25 Abs. 4 n. F. | | Lizenzprüfung | |
| C.3.5 | **Vertraglich absichern:** Rollenabgrenzung, Zugang zu technischer Dokumentation und Protokollen, Informationspflichten bei Änderungen, Mitwirkung bei Konformitätsbewertung | Art. 25 Abs. 1 lit. a und Abs. 2 n. F. | | Vertragsklauseln | |
| C.3.6 | **Freigabeprozess** einrichten: Jede Zweckänderung, jedes Fine-Tuning und jedes Eigenlabeling durchläuft eine dokumentierte Rollenprüfung | Organisationspflicht | | Freigabeverfahren, Protokolle | |

> **Bußgeldrisiko:** Verstöße gegen Art. 25 Abs. 2 und 4 sind seit Juli 2026 ausdrücklich bußgeldbewehrt — bis 15.000.000 EUR oder 3 %. *(Art. 99 Abs. 4 lit. da KI-VO n. F.)*

---

# Anhang: Fristenübersicht auf einen Blick

| Datum | Was | Betrifft |
|---|---|---|
| 02.02.2025 | KI-Kompetenz (Art. 4), Verbote (Art. 5) | **gilt bereits** — alle |
| 02.08.2025 | GPAI-Pflichten, Governance, Sanktionen | **gilt bereits** — GPAI-Anbieter, alle |
| **27.07.2026** | Digital Omnibus in Kraft; Art. 102–110 KI-VO anwendbar; **Art. 4a (Bias-Erkennung mit besonderen Datenkategorien) anwendbar** | alle |
| **02.08.2026** | **Transparenzpflichten (Art. 50)**, Art. 101 | **alle** |
| **02.12.2026** | **Neue Verbote NCII/CSAM (Art. 5 lit. ba, bb)** | **alle** |
| **02.12.2026** | **Kennzeichnung generativer Bestandssysteme (Art. 50 Abs. 2)** | **Anbieter generativer Systeme** |
| 02.08.2027 | KI-Reallabore einsatzbereit; GPAI-Bestandsmodelle konform | Mitgliedstaaten, GPAI-Anbieter |
| **02.12.2027** | **Hochrisiko-Pflichten Anhang III** | **Anbieter und Betreiber** |
| **02.08.2028** | **Hochrisiko-Pflichten Anhang I Abschnitt A.** Für Abschnitt B gelten nur Art. 6 Abs. 1, Art. 60a und Art. 102–112 (Art. 2 Abs. 2 n. F.); dort greift das Sektorrecht | **Anbieter und Betreiber** |
| 28.01.2028 | Frist für Benennungsanträge notifizierter Stellen | notifizierte Stellen |
| 02.08.2030 | Hochrisiko-Bestandssysteme in Behördennutzung | öffentliche Stellen |
| 31.12.2030 | KI in IT-Großsystemen nach Anhang X | Unionsstellen |

---

# Anhang: Bußgeldrahmen

| Verstoß gegen | Höchstbetrag | Prozentsatz | Fundstelle |
|---|---|---|---|
| Art. 5 (verbotene Praktiken) | 35.000.000 EUR | 7 % | Art. 99 Abs. 3 |
| Art. 16 (Anbieter), Art. 22 (Bevollmächtigte), Art. 23 (Einführer), Art. 24 (Händler), **Art. 25 Abs. 2 und 4 (n. F.)**, Art. 26 (Betreiber), Art. 31/33/34 (notifizierte Stellen), Art. 50 (Transparenz) | 15.000.000 EUR | 3 % | Art. 99 Abs. 4 lit. a–g |
| Falsche, unvollständige oder irreführende Auskünfte | 7.500.000 EUR | 1 % | Art. 99 Abs. 5 |
| GPAI-Anbieter (durch die Kommission) | 15.000.000 EUR | 3 % | Art. 101 Abs. 1 |
| Zwangsgeld des KI-Büros (n. F.) | — | bis 5 % der durchschnittlichen Tageseinnahmen bzw. des durchschnittlichen weltweiten Jahresumsatzes im vorangegangenen Geschäftsjahr **pro Tag** | Art. 75c n. F. |

Es gilt jeweils der **höhere** Betrag. Für **KMU einschließlich Start-ups** gilt bei allen drei Stufen des Art. 99 der **niedrigere** Betrag (Art. 99 Abs. 6). Für **kleine Midcap-Unternehmen** gilt der niedrigere Betrag nur bei den Absätzen 4 und 5 — **nicht** bei Art. 5 (Art. 99 Abs. 6a n. F.).

---

*Fassung 1.1 · Erstellt am 29.07.2026 · Rechtsstand: 29.07.2026*
*Diese Checklisten ersetzen keine Rechtsberatung im Einzelfall. Nutzung unter CC BY 4.0 — bei Weitergabe bitte Rechtsstand und vorgenommene Änderungen kennzeichnen.*
*Vollständiges Quellenverzeichnis mit Prüfstatus: `QUELLEN.md` — <https://github.com/thomas-lauer/eu-ai-act/blob/main/QUELLEN.md>*
