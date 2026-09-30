# Jellyfin (mod) para Fire TV

Versión modificada **no oficial** de [Jellyfin Android TV](https://github.com/jellyfin/jellyfin-androidtv) (v0.19.10) para uso personal. Añade dos cosas al reproductor:

- **Desfase de subtítulos**: adelantar o retrasar los subtítulos (pasos de 0,1 s y 1 s) mientras se reproduce.
- **Información del medio**: códec, resolución, HDR, bitrate, audio, subtítulos y método de reproducción.

Se instala como app aparte ("Jellyfin (mod)"), junto a la oficial.

**Descarga directa (Downloader en el Fire TV):**
https://github.com/egroj78/jellyfin-mod/releases/latest/download/jellyfin-mod.apk

## Aviso

- No es un proyecto oficial de Jellyfin ni está respaldado por ellos.
- Los cambios se han desarrollado principalmente con IA (Claude, de Anthropic).
- Sin soporte: úsala bajo tu responsabilidad.

## Código fuente y licencia

Jellyfin Android TV se distribuye bajo la **GNU GPL v2.0**, y esta versión modificada también (ver [LICENSE](LICENSE)).

- Código original: https://github.com/jellyfin/jellyfin-androidtv (etiqueta v0.19.10)
- Cambios realizados: [jellyfin-firetv.patch](jellyfin-firetv.patch)
- Compilación: [.github/workflows/build.yml](.github/workflows/build.yml) descarga el código original, aplica el parche y genera el APK.

Para recompilar: pestaña *Actions* → "Compilar Jellyfin (mod) para Fire TV" → *Run workflow*.
