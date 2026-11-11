# LetterBrain Releases

Repositorio para distribuir versiones de LetterBrain. **No contiene ni debe contener historiales de clientas, conversaciones, PIN, tokens ni datos locales.**

## Archivos
- `letterbrain-update.json`: versión vigente y enlace a la página de descargas.

## Publicar una versión
1. Crea un Release en https://github.com/Hellllbooooyxz/LetterBrain-Releases/releases/new
2. Usa un tag como `v2.1.5` y adjunta el ZIP de la extensión.
3. Actualiza `latestVersion` y `releaseNotes` en `letterbrain-update.json` en la rama `main`.

La extensión avisa cuando detecta una versión más nueva. Cuando está instalada mediante “Cargar descomprimida”, Chrome requiere que se descargue el ZIP, se reemplacen los archivos y se pulse “Recargar” en `chrome://extensions`.
