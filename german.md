# Datenschutz- und Sicherheitsinformationen
Um den Bot ordnungsgemäß zu betreiben, speichern wir einige Informationen über Server und Benutzer. Im Folgenden finden Sie eine Liste der Informationen, die wir speichern, und warum sie gespeichert werden.

## Die von uns gespeicherten Daten
- **Benutzer IDs:** Wir speichern diese Informationen, um Vorschläge mit dem Benutzer zu verknüpfen, der sie vorgeschlagen hat, damit der Bot den Benutzer, der den Vorschlag eingereicht hat, anzeigen kann. Zusätzlich werden sie verwendet, um eine Liste blockierter Benutzer in jedem Server und global zu speichern. 
- **Kanal IDs:** Wir speichern diese Informationen, damit der Bot weiß, wohin er verschiedene Nachrichten senden soll, wie zum Beispiel Nachrichten, die auf die Überprüfung von Vorschlägen warten, Vorschlagsnachrichten, abgelehnte Vorschlagsnachrichten und Protokollnachrichten.
- **Rollen IDs:** Wir speichern diese Informationen, um Serveradministratoren zu ermöglichen, Rollen zu konfigurieren, die bestimmte Berechtigungen auf dem Bot haben (Mitarbeiter, Administrator, blockierte Rollen usw.).
- **Server IDs:** Wir speichern diese Informationen, um Serverkonfigurationen und Vorschläge an ihre jeweiligen Server zu binden.
- **Webhook URLs:** Wir speichern diese Informationen, um sicherzustellen, dass das Protokollieren über Webhooks funktioniert - es wird nur eine URL gespeichert, und zwar die URL des Webhooks, der von dem Bot erstellt wird, wenn das Protokollieren konfiguriert ist.
- **Server Emotes:** Wir speichern die Namen/IDs der Server-Emotes, wenn ein Server ein Emote als Reaktions-Emote im Vorschlags-Feed konfiguriert.
- **Eingereichte Vorschläge/Kommentare:** Wir speichern den Inhalt von Nachrichten, die als Vorschläge und Kommentare eingereicht werden, damit der Bot Daten zu jedem Vorschlag hat.
- **URLs von Anhängen:** Wir speichern die URLs von Dateien, die zu den Vorschlägen als Anhang eingereicht werden, um das Anhangs-Feature möglich zu machen.\
Wir protokollieren die **verwendeten Befehle und die Server, zu denen der Bot hinzugefügt oder entfernt wird**, zu Analysezwecken.
Außerdem speichern wir Informationen zu Trello-Boards, die mit dem Bot verbunden sind, sowie Aktionen wie die Erstellung von Karten und Kommentare, die über den Bot auf diesen Boards vorgenommen werden.

## Warum wir die Daten brauchen & Wie wir die Daten verwenden
Diese Daten werden im gesamten Bot verwendet, um ihn zu betreiben. Ohne die Speicherung der oben genannten Daten wäre es nicht möglich, dass Suggester funktioniert. Die von uns gesammelten Daten werden ausschließlich für die oben genannten Zwecke verwendet und nichts anderes. Wir werden die gespeicherten Informationen niemals an unautorisierte Benutzer weitergeben.
 
## Sicherheit
Alle Daten und Bot-Services sind durch Authentifizierung geschützt, und der Zugriff ist auf eine kleine Teilmenge von Benutzern beschränkt (Entwickler und, für einige Daten, Mitarbeiter von Suggester). Wenn Sie der Meinung sind eine Schwachstelle/Sicherheitslücke in einem unserer Systeme gefunden zu haben, dann posten Sie sie **nicht** in einem öffentlichen Chat. Schreiben Sie eine Direktnachricht an einen Entwickler (`brightness` oder `index.ts`) mit den Informationen und wir werden eine Untersuchung einleiten.

## Anderes
Bots, die dabei helfen, den Suggester-Discord-Server zu verwalten, speichern ebenfalls einige Informationen:\
**VoteBoat#1330**: Ihre Benutzer ID und die Anzahl an Abstimmungen, welche Sie auf den jeweiligen Webseiten getätigt haben\
**i18n#1614**: Inhalte, die als Übersetzungen für Zeichenfolgen bereitgestellt werden, sowie Ihre Benutzer ID für Berechtigungszwecke\
**Suggester Modmail#5646**: Direktnachrichten, die an den Bot gesendet werden, Ihr Benutzername, Ihren Spitznamen (falls vorhanden), das Datum Ihrer Kontenerstellung und das Kontenalter (nur wenn/wenn Sie den Bot kontaktieren, indem Sie ihm eine Direktnachricht senden)\
**Support#8828**: Dieser Bot hat sein eigenes Dokument, welches Sie [hier](https://suggester.js.org/#/support-bot-privacy) finden können

## Anliegen
Falls Sie irgendwelche Bedenken hinsichtlich der von uns gespeicherten Daten oder der Funktionen des Bots haben, kontaktieren Sie bitte ein Mitglied des Suggester-Teams über den [Support-Server](https://suggester.js.org/support).
Es würde uns freuen etwaige Anliegen Ihrerseits zu klären.

**Wenn Sie möchten, dass Ihre Daten aus unseren Systemen entfernt werden, kontaktieren Sie bitte einen der oben aufgeführten Entwickler, um Ihnen behilflich zu sein.**
