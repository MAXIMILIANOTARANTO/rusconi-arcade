# 🎮 RUSCONI Arcade 80s·90s

**Experiencia web retro interactiva** con estética arcade de los 80s y 90s, mecánicas de juego reales, sistema de puntuación persistente y un emotivo overlay de "Campeón del Mundo".

## Características

- **Gameplay funcional**: Sistema de puntuación, high score persistente, botón de interacción principal.
- **Video inteligente**: Reproduce y hace loop automático.
- **Overlay Campeón**: Carga de foto personal + himno + confeti.
- **Mobile-first**: Diseño optimizado para teléfonos con safe areas.
- **PWA**: Se puede instalar como aplicación en el celular.
- **Persistencia**: El high score se guarda localmente.

## Cómo usarla

1. Abrí el link.
2. Tocá "TOCA PARA JUGAR".
3. Usá el botón **HIT THE BUNNY** para sumar puntos.
4. Tocá **VER CAMPEÓN** para abrir el overlay emotivo.
5. Cargá tu foto y el himno.

## Instalación como App (PWA)

1. Abrí el link en Chrome/Safari del celular.
2. Tocá los tres puntitos → **Agregar a pantalla de inicio**.
3. Listo. Se instala como aplicación nativa.

## Estructura del proyecto

```
rusconi-arcade/
├── index.html      # Experiencia completa
├── manifest.json   # Configuración PWA
├── sw.js           # Service Worker (PWA offline)
└── README.md       # Este documento
```

## Tecnología
- HTML + CSS + JavaScript vanilla
- Sin dependencias externas pesadas
- Totalmente soberana (todo corre en el dispositivo)

## Cómo modificarla (para agentes IA y humanos)

- `index.html` → Estructura + lógica principal
- `manifest.json` → Datos de la PWA
- `sw.js` → Lógica offline

**Regla**: Para agregar nuevas mecánicas de juego, editá la sección de JavaScript en `index.html`.

## Autor
Creado con Grok Iluminado para Maximiliano Taranto.

---

**Link de la experiencia:**
https://maximilianotaranto.github.io/rusconi-arcade/ (después de activar GitHub Pages)