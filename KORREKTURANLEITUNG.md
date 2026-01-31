# KORREKTURANLEITUNG: Schritt-für-Schritt

**Datei:** Kaan_Vorname_UPM_WS2025.tex  
**Zeitaufwand:** 30-45 Minuten  
**Ziel:** Belegarbeit auf 19-20 Punkte bringen

---

## SCHRITT 1: LaTeX-Datei öffnen

Öffnen Sie die Datei `Kaan_Vorname_UPM_WS2025.tex` in einem Texteditor (z.B. VS Code, TeXstudio, Notepad++).

---

## SCHRITT 2: Kopf- und Fußzeilen korrigieren (KRITISCH)

**Finden Sie Zeilen 20-24:**

```latex
\pagestyle{fancy}
\fancyhf{}
\fancyhead[L]{\small Technisch-Ökologische-Analyse von e-Bikes}
\fancyhead[R]{\small\thepage}
\renewcommand{\headrulewidth}{0.4pt}
```

**Ersetzen Sie durch:**

```latex
\pagestyle{fancy}
\fancyhf{}
\fancyhead[L]{\small Kaan [IHR NACHNAME]}  % Autor statt Titel
\fancyfoot[R]{\small\thepage}               % Seitenzahl in Fußzeile
\renewcommand{\headrulewidth}{0.4pt}
\renewcommand{\footrulewidth}{0pt}
```

**Wichtig:** Ersetzen Sie `[IHR NACHNAME]` durch Ihren echten Nachnamen!

---

## SCHRITT 3: Platzhalter auf Deckblatt ausfüllen (KRITISCH)

**Finden Sie Zeilen 50-53:**

```latex
\textbf{Vorgelegt von:} & Kaan [Nachname]\\
\textbf{Matrikelnummer:} & [Matrikelnummer]\\
\textbf{E-Mail:} & [E-Mail Adresse]\\
\textbf{Studiengang:} & [Studiengang]\\
```

**Ersetzen Sie durch Ihre echten Daten (Beispiel):**

```latex
\textbf{Vorgelegt von:} & Kaan Mustermann\\
\textbf{Matrikelnummer:} & 123456\\
\textbf{E-Mail:} & s123456@htw-berlin.de\\
\textbf{Studiengang:} & Betriebswirtschaftslehre\\
```

---

## SCHRITT 4: Überschriften verlängern (EMPFOHLEN)

**Finden Sie Zeile 73:**

```latex
\section{Einleitung}
```

**Ersetzen Sie durch:**

```latex
\section{Einleitung und Problemstellung}
```

**Finden Sie Zeile 129:**

```latex
\section{Fazit}
```

**Ersetzen Sie durch:**

```latex
\section{Fazit und Ausblick}
```

---

## SCHRITT 5: Datei speichern

Speichern Sie die Datei `Kaan_Vorname_UPM_WS2025.tex`.

---

## SCHRITT 6: PDF kompilieren

Öffnen Sie ein Terminal/Kommandozeile im Verzeichnis der LaTeX-Datei und führen Sie aus:

```bash
pdflatex Kaan_Vorname_UPM_WS2025.tex
pdflatex Kaan_Vorname_UPM_WS2025.tex
```

**Warum zweimal?** Das erste Mal erstellt das PDF, das zweite Mal aktualisiert das Inhaltsverzeichnis.

**Alternative:** Verwenden Sie Ihren LaTeX-Editor (TeXstudio, Overleaf, etc.) und klicken Sie auf "Compile" oder "Build".

---

## SCHRITT 7: PDF überprüfen

Öffnen Sie die neu erstellte `Kaan_Vorname_UPM_WS2025.pdf` und prüfen Sie:

- [ ] Deckblatt: Alle Platzhalter ersetzt?
- [ ] Seite II (Inhaltsverzeichnis): Kopfzeile zeigt Ihren Namen (nicht den Titel)?
- [ ] Seite 1 (Einleitung): Kopfzeile zeigt Ihren Namen, Fußzeile zeigt Seitenzahl?
- [ ] Überschriften: "Einleitung und Problemstellung" und "Fazit und Ausblick"?

---

## SCHRITT 8: Eigenständigkeitserklärung unterschreiben (KRITISCH)

### Option A: Klassisch (empfohlen)

1. **Drucken Sie Seite 6-7 aus** (die Seiten mit der Eigenständigkeitserklärung)
2. **Tragen Sie handschriftlich ein:**
   - Ort (z.B. "Berlin")
   - Datum (z.B. "30.01.2026")
3. **Unterschreiben Sie handschriftlich** im Feld "Unterschrift"
4. **Scannen Sie die Seite(n) ein** (300 DPI empfohlen)
5. **Ersetzen Sie die Seite(n) im PDF:**
   - Mit Adobe Acrobat Pro: "Seiten organisieren" → Seite ersetzen
   - Mit PDF-Tools online: z.B. smallpdf.com, ilovepdf.com
   - Oder: PDF aufteilen, gescannte Seite einfügen, wieder zusammenfügen

### Option B: Digital (falls HTW akzeptiert)

1. Verwenden Sie ein Tool für digitale Signaturen:
   - Adobe Sign
   - DocuSign
   - SignNow
2. Fügen Sie Ihre digitale Unterschrift im PDF hinzu
3. Tragen Sie Ort und Datum ein

---

## SCHRITT 9: Datei umbenennen (EMPFOHLEN)

**Aktuell:** `Kaan_Vorname_UPM_WS2025.pdf`

**Sollte sein:** `[IhrNachname]_[IhrVorname]_UPM_WS2025.pdf`

**Beispiel:** `Mustermann_Kaan_UPM_WS2025.pdf`

```bash
mv Kaan_Vorname_UPM_WS2025.pdf Mustermann_Kaan_UPM_WS2025.pdf
```

---

## SCHRITT 10: Finale Überprüfung

Öffnen Sie Ihre finale PDF und prüfen Sie diese Checkliste:

- [ ] **Deckblatt:** Alle Daten ausgefüllt (kein `[...]`)?
- [ ] **Kopfzeile:** Zeigt Ihren Namen (nicht den Titel)?
- [ ] **Fußzeile:** Zeigt die Seitenzahl?
- [ ] **Seitennummerierung:** Römisch II für Inhaltsverzeichnis, Arabisch 1,2,3... für Haupttext?
- [ ] **Überschriften:** "Einleitung und Problemstellung" und "Fazit und Ausblick"?
- [ ] **Eigenständigkeitserklärung:** Mit Ort, Datum und Unterschrift versehen?
- [ ] **Dateiname:** Enthält Ihren echten Namen (nicht "Kaan_Vorname")?
- [ ] **Dateigröße:** Unter 10 MB? (Ihre aktuelle: ~132 KB ✅)
- [ ] **PDF öffnet sich fehlerfrei?**

---

## SCHRITT 11: Abgabe

1. Loggen Sie sich im HTW-System ein
2. Navigieren Sie zum Abgabebereich für Unternehmens- und Personalmanagement
3. Laden Sie Ihre PDF-Datei hoch
4. Bestätigen Sie die Abgabe
5. **WICHTIG:** Speichern Sie die Bestätigungs-E-Mail oder machen Sie einen Screenshot!

**Deadline:** 01. Februar 2026, 23:55 Uhr

**Tipp:** Geben Sie die Arbeit **mindestens 1-2 Tage vor Deadline** ab, um Zeit für unerwartete Probleme zu haben!

---

## OPTIONAL: HTW-Logo einfügen

Falls Sie das offizielle HTW Berlin Logo haben:

**Finden Sie Zeile 36 (im Deckblatt-Bereich):**

```latex
\vspace*{2cm}

{\Large\bfseries HTW Berlin}\\[0.5cm]
```

**Fügen Sie VOR dieser Zeile ein:**

```latex
\vspace*{2cm}
\includegraphics[width=5cm]{htw_logo.png}\\[1cm]

{\Large\bfseries HTW Berlin}\\[0.5cm]
```

**Wichtig:** Die Datei `htw_logo.png` muss im selben Verzeichnis wie die .tex-Datei liegen.

---

## ZUSAMMENFASSUNG DER ÄNDERUNGEN

| Zeile | Alt | Neu | Priorität |
|-------|-----|-----|-----------|
| 20-24 | Titel in Kopfzeile, Seitenzahl in Kopfzeile | Autor in Kopfzeile, Seitenzahl in Fußzeile | 🔴 KRITISCH |
| 50-53 | Platzhalter `[...]` | Echte Daten | 🔴 KRITISCH |
| 73 | `\section{Einleitung}` | `\section{Einleitung und Problemstellung}` | 🟡 EMPFOHLEN |
| 129 | `\section{Fazit}` | `\section{Fazit und Ausblick}` | 🟡 EMPFOHLEN |
| Seite 6-7 | Keine Unterschrift | Mit Unterschrift | 🔴 KRITISCH |

---

## HILFE BEI PROBLEMEN

### LaTeX kompiliert nicht?

**Fehlermeldung:** `! Undefined control sequence.`
- **Lösung:** Prüfen Sie, ob alle Backslashes `\` vorhanden sind
- **Lösung:** Prüfen Sie, ob alle geschweiften Klammern `{}` geschlossen sind

**Fehlermeldung:** `! File htw_logo.png not found.`
- **Lösung:** Entfernen Sie die Zeile mit `\includegraphics` oder platzieren Sie die Logo-Datei im richtigen Verzeichnis

### PDF zeigt alte Inhalte?

- **Lösung:** Löschen Sie alle Hilfsdateien (`.aux`, `.log`, `.toc`) und kompilieren Sie neu
- **Terminal:**
  ```bash
  rm *.aux *.log *.toc *.out
  pdflatex Kaan_Vorname_UPM_WS2025.tex
  pdflatex Kaan_Vorname_UPM_WS2025.tex
  ```

### Seite 6-7 ersetzen funktioniert nicht?

- **Online-Tool:** Verwenden Sie https://www.ilovepdf.com/de/pdf_zusammenfuegen
  1. Laden Sie Seite 1-5 hoch (erste PDF)
  2. Laden Sie Ihre gescannte Eigenständigkeitserklärung hoch (zweite PDF)
  3. Laden Sie Seite 8-9 hoch (falls vorhanden)
  4. Klicken Sie auf "PDF zusammenfügen"

---

## ZEITPLAN

| Aufgabe | Zeit |
|---------|------|
| LaTeX-Änderungen | 10 Min |
| PDF kompilieren | 2 Min |
| PDF prüfen | 5 Min |
| Seite ausdrucken | 5 Min |
| Unterschreiben & scannen | 10 Min |
| Seite ersetzen im PDF | 10 Min |
| Finale Prüfung | 5 Min |
| **GESAMT** | **~45 Min** |

---

**Viel Erfolg!** 🎓

Bei Fragen zu den Korrekturen, sehen Sie in die Dateien:
- `GUTACHTEN_BELEGARBEIT.md` - Vollständiges Gutachten
- `PRUEFUNGSERGEBNIS.md` - Zusammenfassung
