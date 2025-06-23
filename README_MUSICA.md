# 🎵 Cómo Agregar Música de Fondo al Tetris

## 📁 Opción 1: Archivo Local MP3

### 1. Descarga una música de Tetris

Puedes encontrar la música clásica de Tetris (Korobeiniki) en:

- YouTube (descarga como MP3)
- Sitios de música libre
- Archivos de música retro

### 2. Coloca el archivo en tu proyecto

```
tetris_js/
├── index.html
├── Tablero.js
├── Tetrimino.js
└── tetris_theme.mp3  ← Coloca tu archivo aquí
```

### 3. Activa la música en el código

En `index.html`, busca estas líneas y descoméntalas:

```javascript
// En la función inicializarAudio()
// cargarMusica('tetris_theme.mp3');
// reproducirMusica();
```

Cámbialas por:

```javascript
// En la función inicializarAudio()
cargarMusica("tetris_theme.mp3");
reproducirMusica();
```

## 🌐 Opción 2: URL en Línea

Si prefieres usar una URL en línea, puedes usar:

```javascript
cargarMusica("https://ejemplo.com/tetris_theme.mp3");
```

## 🎮 Controles de Música

- **Botón 🎵**: En la esquina superior derecha para activar/desactivar
- **Volumen**: Automáticamente al 30% para no molestar
- **Loop**: La música se repite automáticamente

## 📝 Ejemplo Completo

```javascript
// En la función inicializarAudio()
cargarMusica("tetris_theme.mp3");
reproducirMusica();
```

## 🎵 Recomendaciones de Música

- **Korobeiniki** (tema clásico de Tetris)
- **Música 8-bit** retro
- **Música electrónica** suave
- **Música libre de derechos** de autor

## ⚠️ Notas Importantes

- El archivo debe estar en formato MP3
- El archivo debe estar en la misma carpeta que `index.html`
- Algunos navegadores requieren interacción del usuario para reproducir audio
- La música se activará automáticamente al hacer clic o presionar una tecla

¡Listo! Tu Tetris tendrá música de fondo profesional. 🎵

## Mejoras recientes

- Se corrigió un bug donde el tetrimino dejaba de caer al girar la pieza.
- Ahora el juego cuenta con una pantalla de inicio que muestra el título, instrucciones y controles.
- Mejoras visuales en la interfaz y en la experiencia de usuario.
- El código está más comentado y es más fácil de entender y modificar.
