# ConCéntrate · Investigación Cualitativa

Juego académico en tiempo real con GitHub Pages + Firebase Realtime Database.

## Tecnologías
- GitHub Pages
- Firebase Authentication anónima
- Firebase Realtime Database
- HTML/CSS/JS

## Configuración
1. En Firebase Authentication, habilitar proveedor Anónimo.
2. En Realtime Database, publicar reglas para usuarios autenticados.
3. En GitHub: Settings > Pages > Deploy from a branch > main / root.

## Juego
- Máximo 20 equipos
- Máximo 5 integrantes por equipo
- 12 pares / 24 tarjetas
- +10 puntos por pareja
- +5 puntos por validación correcta
- El host puede abrir tarjetas
- Solo el dispositivo oficial responde validaciones
- Espectadores en solo lectura desde la interfaz

PIN inicial del host: 2026

> Nota: el PIN del host es una barrera de interfaz, no un secreto criptográfico. Antes de producción conviene endurecer reglas por rol/UID.
