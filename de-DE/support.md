# NULL//SIGNAL – Hilfe und Support

[English](../en-US/support.md)

## Kontakt

Für Fragen zum Spiel und technische Probleme erreichst du die Entwicklung über [NULL//SIGNAL auf GitHub Issues](https://github.com/LilaQ/null-signal-ios-issues/issues). Zum Schreiben benötigst du einen GitHub-Account. Bestehende Antworten kannst du ohne Anmeldung lesen.

Issues und Antworten sind öffentlich. Beschreibe das Problem mit App-Version, iOS-/iPadOS-Version, Gerätemodell und kurzen Schritten zur Wiederholung. Veröffentliche keine persönlichen Daten, Zahlungsbelege, Passwörter, Spielstanddateien, Screenshots oder Protokolle. Die App lädt keine Diagnosedaten für dich hoch. Für die Nutzung von GitHub gilt die [GitHub-Datenschutzerklärung](https://docs.github.com/de/site-policy/privacy-policies/github-general-privacy-statement).

## Einstieg und festgefahrene Operationen

NULL//SIGNAL ist ein fiktives, lokal simuliertes Hacker-Spiel. Befehle arbeiten ausschließlich mit der Spielwelt. Internetadressen oder echte Zugangsdaten gehören nicht ins Terminal.

- `help` zeigt das Befehlsverzeichnis; `help scan` erklärt zum Beispiel die Scan-Syntax.
- `phase`, `objectives` und `status` zeigen den aktuellen Auftrag und Zustand.
- `hint` gibt einen Hinweis. Lesen und Planen erhöhen den Alarm nicht.
- `retry confirm` setzt den aktuellen Lauf auf den letzten Phasen- oder Einstieg-Checkpoint zurück. Spätere Aktionen und Änderungen gehen dabei verloren; der Terminalverlauf bleibt erhalten.
- Abgeschlossene Operationen kannst du erneut spielen. Bereits erreichte Enden bleiben gespeichert.

Die Einstellungen erreichst du über `···`. Dort lassen sich Sprache, größere Schrift, Ton, Haptik und reduzierte Bewegung anpassen. Das Spiel unterstützt Deutsch und Englisch sowie eine Hardwaretastatur. Auf dem iPhone kannst du zwischen Terminal und Werkzeugansichten wechseln.

## Rig und neue Läufe

Unter **Einstellungen → Rig** wählst du Module für Core, Relay und Analyzer. 18 Spezialisierungen werden durch Kampagnenabschlüsse freigeschaltet, unabhängig vom erreichten Rang. Vorteile und Nachteile verändern die Alarmkosten bestimmter Aktionen. Die Basisausrüstung ist jederzeit kostenlos verfügbar.

Die Auswahl gilt für neue Läufe in Kampagne, Nebenaufträgen, Contracts und Training. `rig` zeigt die aktive Ausrüstung. Ein laufender Versuch behält sein Rig, auch nach `retry confirm`. Für einen vollständigen Neustart mit der neuen Auswahl gibst du `restart confirm` ein: Der laufende Versuch wird verworfen; erreichte Enden und die erste Kampagnenentscheidung bleiben erhalten. `man rig` erklärt die Einzelheiten.

## Freiwillige Mastery-Ränge

Nach einem neuen Abschluss erhältst du C, B, A oder S. `mastery` zeigt die Grenzwerte pro Ausgang; `man mastery` erklärt sie. Die Wertung berücksichtigt aktive Eingriffe, insgesamt erzeugten Alarm, Checkpoint-Neustarts und Hinweisaufrufe. Lesen, Syntaxfehler und Denkzeit zählen nicht. Hinweise beeinflussen nur den freiwilligen Rang, niemals Storyfortschritt oder reguläre Belohnungen. Im Archiv bleiben beste Mastery und niedrigster Spitzenalarm getrennt erhalten. Alte Läufe bekommen keinen geschätzten Rang; eine Wiederholung erfasst die benötigten Werte.

## Kostenlose Operationen und Kampagnenkauf

Die ersten acht Operationen sind kostenlos. Ein nicht verbrauchbarer In-App-Kauf schaltet die weiteren 17 dauerhaft frei. Es gibt kein Abo, keine Werbung und keine kaufbare Energie. Die Kampagne wird weiterhin durch Spielen freigeschaltet: Ein Kauf überspringt keine vorherigen Operationen.

Über **Einstellungen → Auftragsbörse** findest du außerdem 36 Nebenaufträge: zwölf kostenlos und 24 im selben Vollversionskauf enthalten. Jeder Auftrag nennt den erforderlichen Kampagnenabschluss. Gesperrte Briefings kannst du schon vorher lesen. Die Auftragsart lässt sich in der Börse wechseln. Nebenaufträge speichern ihre Läufe und Ausgänge unabhängig von der Kampagne.

Unter **Einstellungen → Contracts** stehen außerdem 50 wiederholbare Varianten bereit. Zwanzig sind kostenlos, 30 im Vollversionskauf enthalten. Die Varianten kombinieren verschiedene Zugangsmodelle mit unterschiedlichen Zielbedingungen. Der jeweils erforderliche Kampagnenabschluss steht am Contract. Auch diese Läufe besitzen eigene Spielstände und ein eigenes Archiv.

Die 15 **Übungsnetze** in den Einstellungen sind kostenlos und sofort wählbar. Ihre eigenen Spielstände verändern weder Kampagnenfortschritt noch Kampagnenerfolge.

Öffne **Vollversion → Käufe wiederherstellen**, wenn ein bereits gekaufter Zugang fehlt. Verwende den Apple-Account, mit dem du gekauft hast, und eine Verbindung zum App Store. Ein ausstehender Kauf wird nach Genehmigung automatisch übernommen. Bei einem Store-Ausfall bleiben kostenlose Operationen und von Apple lokal bestätigte Käufe spielbar. Neue Käufe und Wiederherstellungen benötigen eine Verbindung zum App Store.

Nach einer Erstattung oder einem anderen Wegfall der Kaufberechtigung ist der zusätzliche Inhalt gesperrt. Die zugehörigen Spielstände werden nicht gelöscht. Apple entscheidet über [Erstattungsanfragen](https://support.apple.com/de-de/118223).

## Spielstände und Daten

Fortschritt, Eingabeentwürfe, Verlauf und Einstellungen werden auf dem Gerät gespeichert. Die App bietet keine eigene Cloud-Synchronisierung und kein Spielkonto. Ein Kauf stellt den Zugang wieder her, aber keinen verlorenen Spielstand. Gerätebackups können App-Daten enthalten; ihre Wiederherstellung und Verfügbarkeit hängen von deinen Apple- bzw. Computer-Backupeinstellungen ab.

Bei einem gemeldeten Speicherfehler lösche die App nicht als ersten Schritt. Beschreibe zunächst die Fehlermeldung im Support, ohne Dateien anzuhängen. Die App versucht lesbare lokale Sicherungen zu verwenden und überschreibt einen unbekannten oder nicht lesbaren Spielstand nicht absichtlich.

Wenn du alle lokalen App-Daten entfernen möchtest, lösche die App über die iOS-/iPadOS-Einstellungen. **App auslagern** behält Dokumente und Daten und ist deshalb keine Datenlöschung. Bereits angelegte Gerätebackups verwaltest du separat in deinen Backup-Einstellungen. Das Löschen der App storniert keinen Kauf. Öffentlich verfasste GitHub-Beiträge werden dadurch ebenfalls nicht gelöscht.
