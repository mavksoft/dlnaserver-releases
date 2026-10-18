<p align="center">
  <img src="./og.png" alt="DLNA Server" width="520">
</p>

<h1 align="center">DLNA Server for macOS</h1>

<p align="center">Trasforma il tuo Mac in un media server DLNA/UPnP completo.<br>Trasmetti la tua libreria di film a qualsiasi TV, console o lettore della rete — con metadati AI, locandine e TV in diretta.</p>

<p align="center">
  <a href="https://www.dlnaserver.com"><img src="https://img.shields.io/badge/website-dlnaserver.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dlnaserver-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dlnaserver-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS%2013+-black" alt="macOS 13+">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <strong>🇮🇹 Italiano</strong> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Questo repository pubblica solo release binarie ufficiali** — il codice sorgente è privato. Download firmati, checksum e feed di aggiornamento automatico.

## Download

| | |
|---|---|
| 📥 **Versione completa** | [Scarica l'ultimo DMG](https://github.com/mavksoft/dlnaserver-releases/releases/latest) — prova gratuita, licenza a vita 19,90 € |
| 🌍 **Sito ufficiale** | [www.dlnaserver.com](https://www.dlnaserver.com) — guide, assistenza e acquisto |
| 📱 **Lite** | Un'edizione Lite in sandbox è in arrivo sul Mac App Store |

## Che cos'è

DLNA Server trasforma la cartella dei film del Mac in un vero media server: film e serie appaiono sul televisore con locandina, trama e sottotitoli — niente da installare sulla TV. Tutto funziona in locale; la libreria non lascia mai il Mac.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funzionalità

- **Server DLNA/UPnP** — discovery SSDP, navigazione ContentDirectory, streaming HTTP a intervalli. Compatibile con TV Samsung/LG/Sony, VLC, Kodi, console…
- **Libreria con AI** — pulizia automatica dei nomi file, identificazione dei film, locandine, valutazioni, trailer e metadati nella tua lingua (ES/EN/FR/IT/DE/PT + lingue gestite da remoto).
- **TV in diretta e IPTV** — liste M3U e portali Xtream/Stalker, EPG, loghi dei canali e registrazione — totalmente indipendente dalla libreria DLNA.
- **Download integrati** — motore torrent (TorrServer) e client eD2k/eMule nativo.
- **Sottotitoli e copertine** — `.srt` esterni, tracce incorporate ed endpoint artwork DLNA per ogni riproduttore.
- **App da barra dei menu** — vive nella tray; continua a servire a finestra chiusa.
- **Player web locale** — guarda da qualsiasi browser, con posizione di ripresa.
- **Privacy prima di tutto** — la libreria non lascia mai il Mac; solo statistiche anonime opzionali.

## Come si usa

1. Scarica il DMG, trascina DLNA Server in Applicazioni e aprilo.
2. Scegli le cartelle con film, serie e musica.
3. L'icona appare nella barra dei menu — il server è già visibile in rete.
4. Sulla TV (o VLC/Kodi/console) cerca "DLNA Server" tra le sorgenti e sfoglia la libreria.
5. Opzionale: aggiungi una lista M3U nelle Impostazioni per la TV in diretta con guida EPG.

## Edizioni e prezzi

|  | Lite | Pro |
|---|---|---|
| **Prezzo** | Gratis | 19,90 € · acquisto unico |
| **Server DLNA** | ✓ | ✓ |
| **Libreria AI** | Limitata | Completa |
| **IPTV + EPG + registrazione** | — | ✓ |
| **Distribuzione** | Mac App Store (in arrivo) | DMG in questa pagina |

## Requisiti

macOS 13 (Ventura) o successivo · Apple Silicon e Intel (binario universale) · Firmato e notarizzato da Apple.

## Cosa contiene questo repository

- `DLNA-Server-<versione>.dmg` — installer firmato + notarizzato da trascinare in Applicazioni
- `DLNA-Server-<versione>.zip` — archivio di aggiornamento (firmato EdDSA) usato dall'auto-updater

[Ultima release](https://github.com/mavksoft/dlnaserver-releases/releases/latest)

## Domande frequenti

**Funziona con il mio televisore?**  
Se la TV supporta DLNA/UPnP (Samsung, LG, Sony — la maggior parte dal 2010) o usi VLC/Kodi/Fire TV, sì. Nulla da installare sulla TV.

**I miei film vengono caricati su un cloud?**  
No. Elaborazione e streaming avvengono nella rete locale. L'AI interroga database pubblici di metadati, ma i file non lasciano mai il Mac.

**La licenza è un abbonamento?**  
No. Pro è un acquisto unico da 19,90 € con aggiornamenti inclusi.

## Assistenza

- Sito: [www.dlnaserver.com](https://www.dlnaserver.com) · Assistenza: [/soporte](https://www.dlnaserver.com/soporte)
- Email: [support@it-systems.es](mailto:support@it-systems.es)

---
<p align="center"><sub>DLNA Server for macOS · © MavkSoft / IT-Systems</sub></p>
