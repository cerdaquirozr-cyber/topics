# Temas API (Privacy Sandbox) - Archivo Histórico y Demo

![Privacy Sandbox](https://via.placeholder.com/728x90?text=Privacy+Sandbox+Obsoleto)  
*(Imagen placeholder; puedes cambiarla por una captura o logo real si quieres)*

**¡Hola! Soy Ramón Cerda Quiroz (@RAMON_CERDA)**  
Este repositorio es mi fork personal del proyecto original de Google: **patcg-individual-drafts/topics** (ahora archivado).

### ¿Qué era la Topics API?
Era parte de la iniciativa **Privacy Sandbox** de Google para reemplazar las cookies de terceros con una forma más "privada" de hacer publicidad basada en intereses. El navegador (Chrome) infería temas generales de tus visitas (ej: "frutas", "automóviles", "música") y los compartía de forma limitada y con ruido para evitar rastreo individual.

- Propuesta inicial: 2021-2023  
- Experimentación: 2023-2025  
- **Deprecated y removida**: Octubre 2025 (Google retiró la mayoría de las APIs de Privacy Sandbox, incluyendo Topics, por baja adopción y problemas regulatorios).  
- Terceros cookies **siguen vivas** en Chrome (no se eliminaron como se planeaba).

### ¿Por qué conservo este repo?
Me interesó mucho el tema de privacidad en la web vs. publicidad digital. Lo forké para estudiarlo, hacer notas y como referencia histórica. Ahora sirve como:
- Archivo de la propuesta fallida.
- Demo educativo de cómo fallan las APIs obsoletas.
- Punto de partida para discutir alternativas actuales (first-party data, contextual ads, etc.).

### Contenido principal
- Archivos originales del borrador de Google (taxonomías, reuniones, specs).
- **probar-topics-api.html**: Un demo simple en HTML/JS que intenta llamar a `document.browsingTopics()`. En Chrome 2026 da error porque ya no existe.

### Cómo probar el demo
1. Abre `probar-topics-api.html` en tu navegador (o clica [aquí si usas GitHub Pages](#)).
2. Pulsa el botón → Verás un error como "browsingTopics is not a function" o similar.

### Notas mías (actualizado febrero 2026)
- Privacy Sandbox no funcionó: Baja adopción de anunciantes, críticas de privacidad (centralizaba poder en Google), y reguladores no lo avalaron del todo.
- Alternativas hoy: Publicidad contextual (sin rastreo), datos propios de sitios, machine learning en servidor, etc.
- Lección: La privacidad real en web es complicada y las soluciones mágicas no siempre cuajan.

Si te interesa el tema de privacidad digital, publicidad sin cookies o historia de la web, ¡contáctame en X @RAMON_CERDA!

Licencia: MIT (heredada del original, ver LICENSE).  
Última actualización: Febrero 2026.

¡Gracias por visitar! 👋
