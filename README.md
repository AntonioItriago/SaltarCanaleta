# SaltarCanaleta
🎮 Telegram Mini App (TMA) de un juego estilo Endless Runner 2D sincronizado con el ritmo de la música. Construido con HTML5, Phaser 3 y Telegram Web Apps API.
# 🏃‍♂️ Saltar la Canaleta — Telegram Mini App

**Saltar la Canaleta** es un juego *endless runner* 2D de acción rítmica diseñado para ejecutarse nativamente como una **Telegram Mini App (TMA)**. Los jugadores deben saltar obstáculos urbanos al ritmo de pistas musicales en constante aceleración.

---

## 🎮 Características Principales

* **Juegos Instantáneos:** Integración fluida con el SDK de Telegram Web Apps (sin instalaciones).
* **Mecánica Rítmica:** Generación de obstáculos sincronizada con los BPM (beats por minuto) de la música.
* **Sistema de Monetización:**
  * **Rewarded Ads:** Opción de revivir una vez por partida tras ver un anuncio.
  * **Interstitial Ads:** Muestra de anuncios a intervalos configurables (cada 2 minutos acumulados).
* **Leaderboard en Tiempo Real:** Tabla de clasificación global para competir con otros usuarios de Telegram.
* **Diseño Responsive:** Optimizado para la experiencia táctil en pantallas móviles.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5 Canvas, Phaser 3 / PixiJS, Howler.js (Audio Web).
* **Integración Telegram:** `@telegram-apps/sdk` / `telegram-web-app.js`.
* **Backend:** Node.js / Express (Gestión de puntajes y autenticación de `initData`).
* **Monetización:** SDK Adsgram / Monetag para Telegram Mini Apps.
