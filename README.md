# Twilight Reborn
RPG táctico en bucle temporal (pixel-art). Cada ciclo reinicia el mundo, pero la aldea recuerda tus decisiones. Prototipo jugable web/PWA.


## Características
- 🎯 Combate por turnos con estados y ventaja de terreno
- ⏳ Bucle temporal: eventos que cambian entre ciclos
- 🏘️ Aldea que evoluciona (NPCs, tiendas, rumores)
- 💾 Guardado ligero (local) y slots de partida
- 📱 PWA instalable (offline básico)

## Stack
- Frontend: React + TypeScript + Vite
- Estado/escenas: (p. ej.) XState/Zustand (o módulo propio)
- Render: canvas/WebGL (motor propio o librería)
- Assets: Sprite sheets (PNG/WebP), SFX (WAV/OGG)

## Empezar
```bash
npm i
npm run dev
