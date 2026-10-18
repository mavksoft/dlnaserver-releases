# Changelog — DLNA Server for macOS

All notable releases published in this repository.

## v1.1.12 — 2026-10-13

## DLNA Server v1.1.12

Official signed release for macOS 13+ (universal: Apple Silicon & Intel).

- `DLNA-Server-1.1.12.dmg` — drag-to-Applications installer (notarized)
- `DLNA-Server-1.1.12.zip` — EdDSA-signed auto-update archive

Docs: https://mavksoft.github.io/dlnaserver-releases/ · Website: https://www.dlnaserver.com

**Assets:** `DLNA-Server-1.1.12.dmg` · `DLNA-Server-1.1.12.zip`

## v1.1.11 — 2026-10-13

Las carátulas de películas y series IPTV ya no se descargan todas por adelantado (ocupaban decenas de GB): se piden solo al verlas y se comparten entre todos los usuarios desde dlnaserver.com. Al actualizar se libera el espacio de la caché antigua y de los vídeos temporales del reproductor web.

**Assets:** `DLNA-Server-1.1.11.dmg` · `DLNA-Server-1.1.11.zip`

## v1.1.10 — 2026-10-11

Menos CPU con catálogos IPTV grandes: al completar las fichas de películas y series ya no reescribe el catálogo entero (cientos de MB) cada pocos segundos; guarda solo lo nuevo y refresca el árbol DLNA como mucho cada 5 minutos.

**Assets:** `DLNA-Server-1.1.10.dmg` · `DLNA-Server-1.1.10.zip`

## v1.1.9 — 2026-10-11

Mucho menos consumo de CPU: la guía de TV (EPG) guarda para siempre las fichas ya resueltas en una base de datos local (antes se borraban y se volvían a pedir ~39.000 programas cada hora), solo descarga la guía cada 3 h y no la reprocesa si no cambió. Fix de la sincronización Xtream con portales que mandan números como texto.

**Assets:** `DLNA-Server-1.1.9.dmg` · `DLNA-Server-1.1.9.zip`

## v1.1.8 — 2026-10-10

Tabs por proveedor en el gestor de perfiles de Publicación (elegir qué sale de cada lista), visibilidad por fuente en el árbol DLNA, fix de categorías fusionadas que desaparecían.

**Assets:** `DLNA-Server-1.1.8.dmg` · `DLNA-Server-1.1.8.zip`

## v1.1.7 — 2026-10-09

Fix del gestor de visibilidad: las filas mostraban un descriptor de función en vez del nombre del país/categoría (interpolación sin llaves).

**Assets:** `DLNA-Server-1.1.7.dmg` · `DLNA-Server-1.1.7.zip`

## v1.1.6 — 2026-10-09

Gestor de visibilidad unificado (TV en vivo / Películas / Series por fuente), ocultos compactados a nivel grupo, nombres de respaldo, updater Sparkle reparado y numeración pública limpia sin build.

**Assets:** `DLNA-Server-1.1.6.dmg` · `DLNA-Server-1.1.6.zip`

## v1.1.5 — 2026-10-09

Gestor de visibilidad unificado (TV en vivo / Películas / Series por fuente), ocultos compactados a nivel grupo, nombres de respaldo en canales y VOD, barra de filtros corregida.

**Assets:** `DLNA-Server-1.1.5.dmg` · `DLNA-Server-1.1.5.zip`

## v1.1.4 — 2026-10-09

Gestor de países IPTV multi-columna: una columna por playlist, switches por país, cambios en lote al cerrar (un solo refresco).

**Assets:** `DLNA-Server-1.1.4.dmg` · `DLNA-Server-1.1.4.zip`

## v1.1.3 — 2026-10-09

IPTV: marca de fuente en todas las secciones — guia EPG, busqueda, grabaciones, player y fichas muestran de que lista viene cada contenido.

**Assets:** `DLNA-Server-1.1.3.dmg` · `DLNA-Server-1.1.3.zip`

## v1.1.2 — 2026-10-08

IPTV: canales Xtream via player_api — get.php se colgaba en paneles saturados; la lista se construye al instante desde la API (fallback a get.php si falla).

**Assets:** `DLNA-Server-1.1.2.dmg` · `DLNA-Server-1.1.2.zip`

## v1.1.1 — 2026-10-08

Fix: alta IPTV — URL pegada en "Pegar M3U" entra como lista (no como canal suelto), URLs sin http:// se auto-completan, timeout de listas Xtream grandes subido a 120s.

**Assets:** `DLNA-Server-1.1.1.dmg` · `DLNA-Server-1.1.1.zip`

## v1.1.0 — 2026-10-08

**Novedad — IPTV multi-perfil**: cada lista tiene color + badge propios, selector de fuentes (fusión/subconjunto/solo) en canales, EPG, VOD y series, gestor de países por lista y editor de nombre/color/etiqueta.

DMG firmado y notarizado por Apple · Universal (arm64 + Intel).

**Assets:** `DLNA-Server-1.1.0.dmg` · `DLNA-Server-1.1.0.zip`

## v1.0.9 — 2026-10-08

Fix: fork-spawned zombie processes could hold port 8200 forever. All process spawning now uses posix_spawn (no fork), plus a zombie-clone reaper and exclusive port binding.

**Assets:** `DLNA-Server-1.0.9.dmg` · `DLNA-Server-1.0.9.zip`

## v1.0.8 — 2026-10-05

Rotación del par Ed25519 de licencias — repara Pro de cortesía y activación con clave (el servidor nunca tuvo LIC_SIGN_SK).

**Assets:** `DLNA-Server-1.0.8.dmg` · `DLNA-Server-1.0.8.zip`

## v1.0.7 — 2026-10-04

Buscador con filtros de gente (actor/director/guionista/colección), conteo honesto y años uniformes · Series con ficha (portal + TMDB): reparto, creadores y filtros de gente · Pro de cortesía desde el panel · Métricas de adopción

**Assets:** `DLNA-Server-1.0.7.dmg` · `DLNA-Server-1.0.7.zip`

## v1.0.6 — 2026-10-04

- **VPN**: las interfaces túnel ya no secuestran el anuncio SSDP — la app detecta la VPN, prefiere siempre la LAN y pregunta si quieres emitir por el túnel (selector por nombre + badge en pantalla Servidor).
- **Buscador**: tipo de contenido en un toque (Todo/Biblioteca/TV/VOD/Series/EPG/Grabaciones) + filtros de género y categoría con buscador.
- **Torrents**: borrar es borrar (sin resucites por reintentos), timeouts en descargas colgadas y magnets muertos marcados "sin fuentes" en vez de parpadear.
- **VOD IPTV**: identificación por tmdb_id del portal + aviso si el contenido no coincide con la ficha.

**Assets:** `DLNA-Server-1.0.6.dmg` · `DLNA-Server-1.0.6.zip`

## v1.0.5 — 2026-10-03

Metadatos IPTV verificados por tmdb_id del portal + auditoría de contenido (duración). Toast global, Sparkle en español, ventana 94%.

**Assets:** `DLNA-Server-1.0.5.dmg` · `DLNA-Server-1.0.5.zip`

## v1.0.4 — 2026-10-03

Sparkle y dialogos del sistema en el idioma del Mac (es/en/fr/it/de/pt). Re-identificacion one-shot de todo el VOD de IPTV con el pipeline verificado (el ano del fichero es ley); el rescrape manual repara enlaces cacheados erroneos.

**Assets:** `DLNA-Server-1.0.4.dmg` · `DLNA-Server-1.0.4.zip`

## v1.0.3 — 2026-10-03

Pill de prueba integrada en la title bar, notificaciones tipo badge abajo-derecha y ventana al 94% de la pantalla.

**Assets:** `DLNA-Server-1.0.3.dmg` · `DLNA-Server-1.0.3.zip`

## v1.0.2 — 2026-10-03

Sin flash de cortina al arrancar, banner de trial compacto, menú lateral más denso, iptvSyncKey, targeting de promos por bundle.

**Assets:** `DLNA-Server-1.0.2.dmg` · `DLNA-Server-1.0.2.zip`

## v1.0.1 — 2026-10-02

Seguridad IPTV (sync por dispositivo con clave por instalación), fix de targeting en promos Lite/Full.

**Assets:** `DLNA-Server-1.0.1.dmg` · `DLNA-Server-1.0.1.zip`

## v1.0.0 — 2026-10-02

DLNA Server para macOS — edición Full/DMG. El DMG es la descarga manual (firmado+notarizado); el ZIP lo usa el auto-update Sparkle.

**Assets:** `DLNA-Server-1.0.0.dmg` · `DLNA-Server-1.0.0.zip`
