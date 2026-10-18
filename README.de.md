<p align="center">
  <img src="./og.png" alt="DLNA Server" width="520">
</p>

<h1 align="center">DLNA Server for macOS</h1>

<p align="center">Verwandle deinen Mac in einen vollwertigen DLNA/UPnP-Medienserver.<br>Streame deine Filmbibliothek auf jeden Fernseher, jede Konsole oder jeden Player im Netzwerk — mit KI-Metadaten, Postern und Live-TV.</p>

<p align="center">
  <a href="https://www.dlnaserver.com"><img src="https://img.shields.io/badge/website-dlnaserver.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dlnaserver-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dlnaserver-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS%2013+-black" alt="macOS 13+">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/dlnaserver-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/dlnaserver-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <strong>🇩🇪 Deutsch</strong> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Dieses Repository veröffentlicht ausschließlich offizielle Binär-Releases** — der Quellcode ist privat. Signierte Downloads, Prüfsummen und Auto-Update-Feeds.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/dlnaserver-releases/main/icons/apple.svg' width='15' style='vertical-align:-2px' alt='apple'> **Vollversion** | [Neuestes DMG laden](https://github.com/mavksoft/dlnaserver-releases/releases/latest) — kostenlose Testversion, lebenslange Lizenz 19,90 € |
| <img src='https://www.dlnaserver.com/assets/img/logo.png' width='15' style='vertical-align:-2px'> **Website** | [www.dlnaserver.com](https://www.dlnaserver.com) — Anleitungen, Support und Kauf |
| <img src='https://raw.githubusercontent.com/mavksoft/dlnaserver-releases/main/icons/appstore.svg' width='15' style='vertical-align:-2px' alt='appstore'> **Lite** | Eine Sandbox-Lite-Edition ist für den Mac App Store unterwegs |

## Was ist das

DLNA Server verwandelt den Filmordner deines Macs in einen echten Medienserver: Filme und Serien erscheinen auf dem Fernseher mit Poster, Inhalt und Untertiteln — ohne dass etwas auf dem TV installiert werden muss. Alles läuft lokal; deine Bibliothek verlässt den Mac nie.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funktionen

- **DLNA/UPnP-Server** — SSDP-Discovery, ContentDirectory-Browsing, HTTP-Range-Streaming. Kompatibel mit Samsung/LG/Sony-TVs, VLC, Kodi, Konsolen…
- **KI-Bibliothek** — automatische Dateinamen-Bereinigung, Filmerkennung, Poster, Bewertungen, Trailer und Metadaten in deiner Sprache (ES/EN/FR/IT/DE/PT + remote verwaltete Sprachen).
- **Live-TV & IPTV** — M3U-Listen und Xtream/Stalker-Portale, EPG, Senderlogos und Aufnahme — völlig unabhängig von der DLNA-Bibliothek.
- **Integrierte Downloads** — Torrent-Engine (TorrServer) und nativer eD2k/eMule-Client.
- **Untertitel & Artwork** — externe `.srt`, eingebettete Spuren und DLNA-Artwork-Endpunkte für jedes Wiedergabegerät.
- **Menüleisten-App** — lebt im Tray; streamt weiter bei geschlossenem Fenster.
- **Lokaler Web-Player** — aus jedem Browser schauen, mit Fortsetzungsposition.
- **Privatsphäre zuerst** — deine Bibliothek verlässt den Mac nie; nur optionale, anonyme Nutzungsstatistik.

## So wird es verwendet

1. DMG laden, DLNA Server nach Programme ziehen und öffnen.
2. Ordner mit Filmen, Serien und Musik auswählen.
3. Das Symbol erscheint in der Menüleiste — der Server ist bereits im Netzwerk sichtbar.
4. Am Fernseher (oder VLC/Kodi/Konsole) unter Quellen nach "DLNA Server" suchen und die Bibliothek durchstöbern.
5. Optional: eine M3U-Liste in den Einstellungen für Live-TV mit EPG hinzufügen.

## Editionen & Preise

|  | Lite | Pro |
|---|---|---|
| **Preis** | Kostenlos | 19,90 € · Einmalkauf |
| **DLNA-Server** | ✓ | ✓ |
| **KI-Bibliothek** | Begrenzt | Voll |
| **IPTV + EPG + Aufnahme** | — | ✓ |
| **Vertrieb** | Mac App Store (demnächst) | DMG auf dieser Seite |

## Voraussetzungen

macOS 13 (Ventura) oder neuer · Apple Silicon & Intel (Universal Binary) · Von Apple signiert und notarisiert.

## Was dieses Repository enthält

- `DLNA-Server-<Version>.dmg` — signiertes + notarisiertes Installationsprogramm
- `DLNA-Server-<Version>.zip` — EdDSA-signiertes Update-Archiv für den In-App-Updater

[Neueste Version](https://github.com/mavksoft/dlnaserver-releases/releases/latest)

## Häufige Fragen

**Funktioniert es mit meinem Fernseher?**  
Wenn dein TV DLNA/UPnP unterstützt (Samsung, LG, Sony — die meisten seit 2010) oder du VLC/Kodi/Fire TV nutzt: ja. Auf dem Fernseher ist nichts zu installieren.

**Werden meine Filme irgendwo hochgeladen?**  
Nein. Verarbeitung und Streaming laufen im lokalen Netz. Die KI fragt öffentliche Metadatenbanken ab, aber deine Dateien verlassen den Mac nie.

**Ist die Lizenz ein Abo?**  
Nein. Pro ist ein Einmalkauf für 19,90 € mit inbegriffenen Updates.

## Support

- Website: [www.dlnaserver.com](https://www.dlnaserver.com) · Support: [/soporte](https://www.dlnaserver.com/soporte)
- E-Mail: [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>DLNA Server for macOS · © MavkSoft / IT-Systems</sub></p>
