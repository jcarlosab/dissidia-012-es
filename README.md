# Dissidia 012 [duodecim] Final Fantasy (PSP) — Traducción al español

Parche de traducción al español de España de la interfaz de **Dissidia 012 [duodecim] Final Fantasy** (PSP, versión europea *undub*, ULES01505).

> **Estado: v1.0-beta.** Toda la interfaz está traducida; falta revisar en partida algunas pantallas que se desbloquean tarde (Museo, Laberinto, Catálogo PP). Si encuentras un fallo, abre una [incidencia](../../issues/new/choose) con una captura.

## Qué incluye

La versión europea trae los diálogos en español, pero dejó en inglés casi toda la interfaz. Este parche la completa:

- Menús, opciones, ajustes de datos y todas las ventanas de ayuda y manuales.
- Personalización: equipo, accesorios y sus descripciones, habilidades, tabla de comandos, EX Burst y Modo EX.
- Modo Historia: selección de historias, capítulos, mapa del mundo, portales, informes y logros.
- Correo moguri (Mognet): las 177 cartas y sus respuestas.
- Museo, Creación (misiones propias y repeticiones), Consejos de combate, Laberinto, Catálogo PP, tienda, Modo Arcade y Modo Comunicación.
- Gráficos: botón «YES» → «SI».

Se mantienen en inglés, como en la versión oficial: nombres de ataques, personajes, lugares, invocaciones, armas y canciones. Los diálogos oficiales en español no se modifican. Algunos rótulos son imágenes y siguen en inglés (títulos de pantalla, «LOOK», «SET», «PLAY TIME»).

## Requisitos

Imagen ISO de la versión europea *undub*:

| Archivo | Tamaño | CRC32 | SHA-1 |
|---|---|---|---|
| `Dissidia_012_EUR_FULL_UNDUB.iso` | 1.741.168.640 bytes | `28c3baee` | `02d0d8642d0bb7aebd201b188e62d6f867717ec7` |

El parche no sirve para otras versiones (USA, europea sin *undub* u otros *undub*): comprueba el CRC32 antes de aplicarlo.

## Cómo aplicarlo

1. Descarga `Dissidia012_ES_v1.0-beta.xdelta` desde [Releases](../../releases).
2. Haz una copia de seguridad de la ISO.
3. Aplica el parche con **Delta Patcher** o **xdelta UI** (Windows), `xdelta3` (Linux/macOS).
   ```bash
   xdelta3 -d -s Dissidia_012_EUR_FULL_UNDUB.iso Dissidia012_ES_v1.0-beta.xdelta Dissidia012_ES.iso
   ```
4. Abre la ISO resultante en tu emulador (PPSSPP) o en la consola. Debe tener CRC32 `a8b5d0f0`.

Las partidas guardadas existentes siguen funcionando.

## Aviso

Este repositorio **no contiene el juego**. Necesitas tu propia copia. Dissidia 012 [duodecim] Final Fantasy © Square Enix, 2011. Traducción hecha por fans, sin ánimo de lucro.

## Créditos

- Traducción y pruebas: **jcarlosab**
