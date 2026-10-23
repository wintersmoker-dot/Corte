# Corte: editor de video para móvil

Editor de video que corre en el navegador del móvil y se instala como app (PWA). Los videos se procesan en tu dispositivo y, una vez instalada, funciona sin Internet.

## Publicarlo y probarlo
1. Crea un repositorio nuevo en GitHub y sube todos los archivos de esta carpeta (incluida `.github`).
2. En el repositorio: Settings > Pages > Source: **GitHub Actions**.
3. Espera a que termine la acción (pestaña Actions). La dirección será `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
4. Ábrela en el móvil.
   - iPhone: Safari > Compartir > Añadir a pantalla de inicio.
   - Android: Chrome > menú > Instalar app.
5. Abre la app una vez con Internet para que se guarde; después funciona sin conexión.

## Qué incluye
Importar video, foto y música; dividir, duplicar, mover, eliminar, deshacer y rehacer; velocidad, recorte, volumen y fundidos; escala, rotación, opacidad y voltear; filtros y ajustes de color; texto, fuentes y emojis; importar y exportar SRT; efectos de voz (robot, eco, megáfono); proporciones 9:16, 16:9, 1:1 y 4:5; exportación 720p, 1080p y 4K a 24, 30 o 60 FPS.

## Límites conocidos
- La exportación se graba en tiempo real: dura lo mismo que el video. Mantén la pantalla encendida.
- En iPhone los filtros de color pueden no verse.
- No guarda proyectos; al cerrar se pierde la edición.
- Faltan: subtítulos automáticos, quitar fondo, tracking, estabilización, keyframes, chroma key, máscaras, transiciones entre clips, grabar con cámara o voz en off, y voz aguda o grave. Varias requieren una app nativa.
- Sin probar en un teléfono real todavía.

## APK para Android
El flujo `Construir APK` compila el editor con Capacitor y publica `Corte.apk` en Releases:
https://github.com/wintersmoker-dot/Corte/releases/latest/download/Corte.apk
El APK es de depuración (firma de prueba). Al abrirlo, Android pedirá permitir instalar apps de este origen.
