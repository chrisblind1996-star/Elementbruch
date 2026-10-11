# Elementbruch – Die letzte Bastion
## Projektgedächtnis / verbindlicher Gesprächs- und Entscheidungsstand

**Stand der Rekonstruktion:** 11. Oktober 2026. Erstfassung aus wiederauffindbarem Gesprächskontext. Sie ersetzt keinen vollständigen verlorenen Chatverlauf. Wo Details unklar sind, steht dies ausdrücklich dabei.

## Zweck – unbedingt beachten
Dieses Dokument ist **kein reiner Code- oder Versions-Backup**. Es soll den **gemeinsamen Diskussionskontext** über Unterhaltungsabbrüche hinweg erhalten: Ideen, feste Entscheidungen, Begründungen, ausdrücklich abgelehnte Ideen, offene Fragen, Testfeedback und nächste Aufgaben. Der Nutzer möchte NICHT bei jedem neuen Chat alles wiederholen oder erneut bereits entschiedene Fragen beantworten.

Bei jeder künftigen Arbeit an Elementbruch:
1. Dieses Projektgedächtnis und relevante Spiel-Dateien im Repository zuerst lesen, sofern GitHub-Zugriff verfügbar ist.
2. Bereits vereinbarte Entscheidungen respektieren; nicht ungefragt wieder bei null anfangen.
3. Nach neuen **wesentlichen** Entscheidungen oder realisierten Änderungen das Protokoll im selben Arbeitsgang aktualisieren, möglichst zeitnah statt erst nach langen Aufgaben.
4. Bei Fehlern, fehlendem Zugriff oder abgebrochener Arbeit offen sagen, was NICHT gespeichert wurde. Keine automatische oder lückenlose Speicherung behaupten.
5. Wenn ein Detail nicht rekonstruiert werden kann, als 'ungeklärt' markieren, nicht ausdenken.

## Produktziel (vereinbart)
- Eigenständiges, hochwertiges **Tower-Defense-Spiel für Android**: „Elementbruch – Die letzte Bastion“.
- Zunächst direkt als HTML5-/Browser-Prototyp auf dem Smartphone testbar; langfristig Android-Version und mögliche Veröffentlichung/Monetarisierung.
- Von starken Vorbildern wie Kingdom Rush, Bloons TD, Thronefall und Dungeon Warfare lernen, aber **kein bloßes Nachbauen**; eigene Mechaniken und Identität.
- Bedienung smartphone-/touch-optimiert.
- Der Nutzer bevorzugt EINEN dauerhaft nutzbaren **Online-Spiel-Link** statt bei jedem Update neue ZIP-/HTML-Dateien herunterladen zu müssen. Keine wiederholten Download-Angebote.

## Grafik und Stimmung – entschieden
- **Variante 3** wurde am 11.10.2026 als vorläufig verbindlicher Zielstil akzeptiert.
- Düster, hochwertig, erwachsene Fantasy; Hybrid aus realistisch und handgemalt mit Kingdom-Rush-Lesbarkeit. Keine übertrieben knallige Kinder-Cartoon-Optik.
- Zauber, Feuer und Benutzeroberfläche dürfen gezielt kräftigere Farben haben, damit Spiel und Effekte gut lesbar bleiben.
- Diese Stilrichtung ist Zielbild; konkrete Spielgrafiken dürfen iterativ verbessert werden.

## Kampagne und Spielmechanik – bekannter Beschlussstand
- **15 individuell gestaltete Kampagnenkarten in 3 Kapiteln**, keine monotonen identischen Spiralkarten.
- Karten mit eigenen Wegen, Landschaften, Spezialeffekten und interaktiver Umgebung.
- **3 Schwierigkeitsgrade**, Fortschrittssterne und Spezialherausforderungen als Planung.
- **10 Turmarten** als bisherige Designvorgabe.
- Elementarsystem: **Feuer, Wasser, Eis, Blitz, Erde, Natur/Gift**; elementare Wechselwirkungen und Kombos (z. B. Wasser/Blitz, Feuer/Eis, Natur/Feuer) als wesentlicher Differenzierungsfaktor.
- Wellen, Gold, Basis-Lebenspunkte, Turmverbesserungen/Verkauf, Spezialangriffe, Helden und Bosse.
- Bekannte Boss-/Gegnernamen aus Planung: **Aschekoloss, Sturmfürst, Schattendrache, Schattenherrscher**. Präzise Zuordnung und Implementierungsstatus getrennt prüfen.

## Karten – aus vorherigem Gespräch zuverlässig rekonstruierbarer Ausschnitt
1. **Die Grenzwacht** – Waldwege mit Kurven und brennbaren Bäumen.
2. **Das brennende Dorf** – zwei Wege; Feuer-/Wasser-Interaktionen.
3. **Der Nebelwald** – Nebel, Tarngegner, Licht-/Blitz-Einsatz.
4. **Die zerbrochene Brücke** – interaktive Zugbrücke.
5. **Belagerung von Dornfels** – Aschekoloss; Eis gegen Rüstung.
6. **Das gefrorene Tal** – Feuer schmilzt Eis; Wasser + Blitz.
7. **Der verseuchte Sumpf** – Karte als Teil der 15 genannt; Spezialmechanik hier noch nicht vollständig rekonstruiert.
8.–15. **Vorher diskutiert, genaue Bezeichnungen und Eigenschaften in aktuell verfügbarem Kontext nicht vollständig gesichert**. Bei späterem Wiederfinden ergänzen; nichts erfinden.

## Bekannter Entwicklungsstand (unbedingt vom tatsächlichen Code unterscheiden)
- Am 10./11.10.2026 wurde ein HTML5-Prototyp aufgebaut; früherer Prototyp wird als v0.1 beschrieben.
- Eine spätere **v0.4.0** wurde am 11.10.2026 als `index.html` im Repository **gemeldet**, mit Überarbeitungen an Waldgrafik, Türmen, Gegnern, Feuer- und Partikeleffekten sowie „Die Grenzwacht“.
- **Wichtig:** Dies ist aus früheren Gesprächsaussagen rekonstruiert, kein Code-Audit. Tatsächliche Funktion, aktuelle Commit-Version, Umfang und Bugs bei nächster Arbeit im Repository prüfen.
- Repository: https://github.com/chrisblind1996-star/Elementbruch
- Wunsch: funktionierende neue Version nach Änderungen direkt online auf dem Handy öffnen.

## Ausdrücklich verworfene oder unerwünschte Vorgehensweisen
- Keine sich ständig wiederholenden Spiralkarten als allgemeines Kampagnenkonzept.
- Keine zu kindliche, knallbunte Cartoon-Standardgrafik.
- Keine reflexhaften ZIP-/HTML-Downloads zum Test jeder neuen Version.
- Nicht bei neuen Chats dieselben Grundlagen wieder diskutieren oder den Nutzer bitten, ganze Gespräche erneut aufzuschreiben.
- Nicht suggerieren, Code-Backups allein lösten das eigentliche Problem: verloren gehen auch Entscheidungen, Dialog, Gründe und abgelehnte Ideen.

## Offene Punkte und Prüfaufgaben
- Karten 8–15 aus belastbarer Quelle oder künftig neu bestätigtem Designstand vervollständigen.
- Den tatsächlich vorhandenen Code und GitHub-Pages-Link verifizieren: was funktioniert auf Android, was fehlt, was ist nur Konzept?
- Erweiterte Gegner, Türme, Talente, Kartenmechaniken und Balance vor Implementierung konkretisieren.
- Die Regeln für das fortlaufende Entscheidungsprotokoll in den **ChatGPT-Projektanweisungen** einmalig hinterlegen; diese GitHub-Datei alleine wird in normalen ChatGPT-Unterhaltungen NICHT garantiert automatisch gelesen.

## Laufendes Entscheidungsjournal
### 2026-10-11 – Projektkontinuität
- **Problem:** Mehrfach verschwanden während längerer ChatGPT-Bearbeitungen vollständige Gesprächsansichten. Hauptverlust ist das gemeinsame Diskussionswissen, nicht allein eine Programmdatei.
- **Entscheidung:** Ein extern lesbares Projektgedächtnis samt Begründungen und verworfenen Vorschlägen im vorhandenen GitHub-Repository führen.
- **Grund:** Bei neuen Chats soll der Nutzer nicht alles neu erklären müssen; der bestehende Plan soll schnell rekonstruierbar sein.
- **Grenze:** Nur tatsächlich geschriebene und bestätigte Inhalte sind dauerhaft erhalten. Nicht gespeicherte Nachrichten und abgebrochene Arbeiten können fehlen. Kein automatischer Zugriff ohne verfügbares Werkzeug und passenden Arbeitsablauf.

---
**Pflegeformat für künftige Entscheidungen:**
- Datum / Thema
- Was wurde besprochen?
- Was genau ist beschlossen? (oder nur Vorschlag)
- Warum / gewünschte Wirkung
- Was wurde ausdrücklich abgelehnt?
- Was wurde im Spiel umgesetzt und getestet?
- Was ist noch offen / nächster Schritt?

### 2026-10-11 – Prüfung der Projektgedächtnis-Einrichtung
- **Geprüft:** GitHub-Repository und `PROJEKTGEDAECHTNIS.md` sind über die verbundene GitHub-Schnittstelle lesbar. Auch `AGENTS.md` existiert und weist Entwickler/Agenten an, vor neuer Arbeit zuerst das Projektgedächtnis zu lesen und bei wesentlichen Änderungen zeitnah zu aktualisieren.
- **Zusätzlich vorhanden:** Projektanweisung für den ChatGPT-Projektkontext, zuerst GitHub und das Projektgedächtnis zu prüfen; beim vorliegenden Statuscheck wurde diese Anweisung erfolgreich angewendet.
- **Wichtige Klarstellung an den Nutzer:** Dies ist **keine** automatische, lückenlose Archivierung sämtlicher Chatnachrichten und **keine** Hintergrundsynchronisierung. Nur ausdrücklich in die GitHub-Datei geschriebene Gesprächsergebnisse bleiben dort gesichert. Bei Chatabbruch vor Speicherung kann Kontext weiterhin verloren gehen. Normale Chats greifen nicht allein wegen `AGENTS.md` garantiert darauf zu.
- **Weiterhin verbindlich:** Relevante Entwicklungsentscheidungen, verworfene Varianten, Begründungen und Testfeedback im laufenden Arbeitsgang speichern; beim Start neuer Entwicklungsaufgaben zunächst GitHub lesen. Schreibvorgänge und Erfolg jeweils prüfen.

### 2026-10-11 – Fehlende Live-Sicherung und strengere Checkpoints
- **Nutzerkritik:** Ein GitHub-Projektgedächtnis schützt die letzten fünf Minuten Diskussion nicht, wenn diese erst am Ende einer langen Aufgabe gespeichert würden. Genau dieser Verlust ist das Hauptproblem.
- **Neue Arbeitsvorgabe:** Relevante neue Anforderungen, Entscheidungen und Testbeobachtungen direkt **vor** längeren Arbeitsschritten im Projektgedächtnis committen; bei langen Aufgaben zusätzlich kleine GitHub-Zwischenstände für Code und Dokumentation, statt am Ende einmalig zu sichern. Entsprechend wurde `AGENTS.md` präzisiert.
- **Technische Grenze:** Keine wortwörtliche, lückenlose Hintergrund-Synchronisation des ChatGPT-Chats. Inhalt seit dem letzten erfolgreichen Commit bleibt bei einem Abbruch möglicherweise verloren. Nur bestätigte GitHub-Schreibvorgänge sind gesichert.
