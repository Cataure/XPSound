# XPSound 🎧

**XPSound** es un reproductor de música local para Android con una estética retro inspirada en los sistemas clásicos de los años 90 y reproductores legendarios como Winamp. 

Diseñado para usuarios que almacenan su música en el dispositivo, incorporando filtrado inteligente para separar canciones de archivos de edición de vídeo o notas de voz.

---

## ✨ Características Principales

* **Estética Retro Auténtica:** Interfaz nostálgica con botones biselados en relieve 3D, tipografía monoespaciada y temas visuales contrastados.
* **Reproducción en Segundo Plano:** Motor de audio moderno impulsado por **AndroidX Media3 (ExoPlayer)** con servicio en primer plano para reproducción ininterrumpida con la pantalla bloqueada.
* **Controles en Notificaciones:** Tarjeta multimedia nativa en la barra de estado y en la pantalla de bloqueo.
* **Filtrado Inteligente de Audio:** Ignora automáticamente efectos de sonido, locuciones cortas (< 45 s) y notas de voz para mantener tu biblioteca limpia.
* **Gestión de Playlists & Favoritos:** Creación de listas personalizadas con soporte para nombres con emojis, canciones favoritas (*Liked Songs*) y opciones de edición/eliminación respaldadas en base de datos local **Room**.
* **Visor Osciloscopio:** Pantalla LCD central con visualizador de onda animado que acompaña la música.
* **Barra de Búsqueda Fija:** Búsqueda en tiempo real por título o artista accesible en todo momento.

---

## 🛠️ Stack Tecnológico

* **Lenguaje:** Kotlin
* **Interfaz de Usuario:** Jetpack Compose (Material 3 con estilos personalizados)
* **Motor Multimedia:** AndroidX Media3 (ExoPlayer & MediaSessionService)
* **Persistencia Local:** Room Database (SQLite)
* **Audio FX / Feedback:** SoundPool para respuestas táctiles y clics analógicos
* **Compatibilidad:** Android 7.0 (API 24) en adelante — Compatible con smartphones y tablets

---

## 📲 Instalación

Para instalar la aplicación directamente en cualquier dispositivo Android:
1. Descarga el archivo `XPSound.apk` desde la sección de versiones o releases.
2. Abre el archivo en tu teléfono y selecciona **Instalar**.
3. Concede los permisos de lectura de audio para que la app explore tu biblioteca local.
