# HARDSTYLE HERO 🎵

Een Guitar Hero-achtig spel voor hardstyle muziek met een mobiele controller.

## Spelen via GitHub Pages

**Desktop spelscherm:** `https://JOUWGEBRUIKERSNAAM.github.io/JOUWREPONAAM/`  
**Mobiele controller:** `https://JOUWGEBRUIKERSNAAM.github.io/JOUWREPONAAM/hardstyle_mobile.html`

## GitHub Pages instellen

1. Maak een nieuw repository aan op github.com (bijv. `hardstyle-hero`)
2. Upload deze 3 bestanden:
   - `index.html`
   - `hardstyle_hero.html`
   - `hardstyle_mobile.html`
3. Ga naar **Settings → Pages → Source: main branch → / (root)**
4. Wacht ~1 minuut, dan is het live op `https://JOUWGEBRUIKERSNAAM.github.io/hardstyle-hero/`

## Hoe te spelen

1. Open het spelscherm op je computer
2. Upload een hardstyle track (MP3/WAV)
3. Plaats beats op de kicks in de editor
4. Klik **▶ SPELEN**
5. Klik **📱** rechtsonder voor de verbindingscode
6. Open de mobiele controller op je iPhone, voer de code in
7. Schud je telefoon of tik de grote knop op elke kick!

## Mobiele controller (iOS)

- Sta bewegingssensortoegang toe als gevraagd
- Schud je telefoon op de kick **of** tik de grote roze knop
- Stel de gevoeligheid in met de slider

## Techniek

- Communicatie via WebSocket relay (socketsbay.com)
- Geen server nodig — werkt puur via de browser
- Beats worden handmatig geplaatst via de waveform editor
