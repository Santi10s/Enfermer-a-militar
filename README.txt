OPO ENFERMERÍA MILITAR - PWA

Archivos:
- index.html
- questions 500.json
- manifest.json
- sw.js
- icon.svg

Para instalarla en iPhone:
1. Sube esta carpeta a un hosting HTTPS (GitHub Pages, Netlify, Vercel, Cloudflare Pages, etc.).
2. Abre la URL HTTPS en Safari.
3. Compartir > Añadir a pantalla de inicio.

Para ampliar preguntas:
- Edita/reemplaza questions.json manteniendo la estructura:
  {
    "id": 1,
    "area": "Inglés" | "Enfermería general" | "Enfermería militar",
    "subarea": "...",
    "q": "Pregunta",
    "opts": ["A","B","C","D"],
    "ans": 0,
    "exp": "Explicación",
    "passage": "Opcional"
  }

La app guarda estadísticas en localStorage del navegador.
