# Retro Flip Clock & Timer (PWA / Web App)

Reloj digital minimalista estilo *flip clock* (panel dividido mecánico), temporizador Pomodoro y cronómetro en un único archivo HTML autocontenido (HTML, CSS y JavaScript vainilla), sin librerías externas ni dependencias.

Diseñado principalmente para **pantallas móviles y reciclaje de smartphones antiguos** como relojes fijos de escritorio (compatible incluso con navegadores antiguos como Safari en iOS 10).

> **Nota de desarrollo:** Este proyecto fue desarrollado y estructurado con asistencia de Inteligencia Artificial utilizando **Gemini Argon**.

### Características
* **Modos integrados:** Reloj en tiempo real (12h/24h), temporizador con accesos rápidos (incluye presets Pomodoro) y cronómetro con vueltas.
* **Audio nativo:** Efectos de clic mecánico y alarma sintetizados mediante la Web Audio API (sin archivos de audio externos).
* **Optimizado para pantallas fijas:** 
  * Modo nocturno (*Dimmer*) para reducir la emisión de luz.
  * *Pixel-shift* automático periódico para mitigar retención de imagen en paneles LCD/OLED.
  * Ocultación automática de controles tras inactividad.
* **100% Offline & Portátil:** Funciona abriendo directamente el archivo `.html` en cualquier navegador móvil o de escritorio, y permite instalarse a pantalla completa como PWA / "Añadir a pantalla de inicio".
