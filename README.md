# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

✍️ Dorian Herzig

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 23.08.2022 | 0.02.1  | Erster Protokolleintrag |
| 30.08.2022 | 1.00.0    | Erstellen der Arbeit  |
|            |           |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

✍️ Random Number Generator

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Muss            | Funktion | Muss dem User die erwartet Zahl geben |
| 2    | Muss            | Funktion | Der User kann eine Zahl zwischen 1 und 100 eingeben |
| 3    | Kann            | Qualität | Das Program ist schön gestaltet |
| 4    | Kann            | Funktion | Wenn der User einen Text anstat eine Zahl eingibt |
| 5    | Rand            | Funktion | Die Webseite Funktioniert ohne Internet |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 4.1  | Eine zufällige Zahl ist gegeben | User schreibt:"Hallo das ist ein Testversuch" (nicht geeignet) "drückt enter" | Program reagiert:"Bitte geben Sie eine gültige Zahl ein zwischen 1 und 100" |
| 5.1  | Es besteht kein Internet zugang nach dem öffnen der Webseite = Die seite ladet nicht mehr | User schreibt:"24" "drückt enter" | Program reagiert nicht |
| 1.1  | Eine zufällige Zahl ist gegeben | User schreibt:"24" "druckt enter" | Program reagiert:"Falsch, die Zahl ist zu tief" | 
| 2.1  | Eine zufällige Zahl ist gegeben | User schriebt:"973" (nicht geeignet) "drückt enter" | Program reagiert:"Bitte geben Sie eine gültige Zahl ein zwischen 1 und 100" |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

<img width="538" alt="image" src="https://user-images.githubusercontent.com/110893245/186103486-be246774-cd9d-4f42-8217-25548566cf5f.png">


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 30.08.2022 |      | 150 min       |  80 min           |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.# Random-Number-Guesser
