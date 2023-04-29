# tg_taxsystem
**Kompatibilität:** FiveM Discord Webhook Script - ESX 1.9+

## Features
**tg_discordwebhook** ist ein Discord Webhook Script für die ESX Version 1.9+. Dieses Script ist hauptsächlich dafür da um einfache LOG's zu kreieren ohne komplizierten Code.
Features:
- SendTextToDiscord (Normale Text Nachricht schicken)
- SendEmbedToDiscord (Eine Embed Nachricht schicken)
- SendEmbedAndTextToDiscord (Normalen Text und Embed Nachricht schicken)

## Dokumentation

### SendTextToDiscord
`SendTextToDiscord(WebhookURL, WebhookName, message)`
\n**WebhookURL:** Die URL die du bekommst wenn du auf Discord eine WebHook Integration erstellst.
\n**WebhookName:** Der Name den der Bot haben soll wenn er diese Nachricht verschickt.
\n**message:** Die Nachricht die verschickt werden soll.

### SendEmbedToDiscord
`SendEmbedToDiscord(WebhookURL, WebhookName, color, titel, message, footer)`
\n**WebhookURL:** Die URL die du bekommst wenn du auf Discord eine WebHook Integration erstellst.
\n**WebhookName:** Der Name den der Bot haben soll wenn er diese Nachricht verschickt.
\n**color:** Der DECIMAL Farbcode der gewünschten Embed Farbe.
\n**title:** Der Titel der Embed Nachricht.
\n**message:** Die Nachricht die in der Embed stehen soll.
\n**footer:** Die Fußnachricht die in der Embed angezeigt werden soll.

### SendEmbedAndTextToDiscord
`SendEmbedAndTextToDiscord(WebhookURL, WebhookName, e_color, e_titel, e_message, e_footer, message)`
\n**WebhookURL:** Die URL die du bekommst wenn du auf Discord eine WebHook Integration erstellst.
\n**WebhookName:** Der Name den der Bot haben soll wenn er diese Nachricht verschickt.
\n**e_color:** Der DECIMAL Farbcode der gewünschten Embed Farbe.
\n**e_title:** Der Titel der Embed Nachricht.
\n**e_message:** Die Nachricht die in der Embed stehen soll.
\n**e_footer:** Die Fußnachricht die in der Embed angezeigt werden soll.
\n**message:** Die Nachricht die vor der Embed stehen soll.

### Tipps and Tricks:
**Decimal Farben:**
- Grün: `5763719`
- Rot:  `13374738`
- Gelb: `16318208`
- Blau: `1529599`

**Footer:**
- Footer Datum: `os.date("%d/%m/%Y %X")`

**Normale Nachricht:**
- Rolle Pingen: `<@&ROLE ID>` Bsp: `<@&809517188683792384>`


## Download
[[LINK]](https://github.com/LetsTiger/tg_discordwebhook/archive/refs/tags/v1.0.zip)

## Lizenz
Dieses Script kann verändert und für deinen Server genutzt werden. Es ist NICHT erlaubt dieses Script erneut zu veröffentlichen oder ähnliches.
