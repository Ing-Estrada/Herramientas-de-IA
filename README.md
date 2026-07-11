# 🧰 Herramientas de IA — Biblioteca de Prompts Técnicos

Colección organizada de prompts técnicos profesionales y reutilizables para herramientas de inteligencia artificial: generación de código, video, imagen, audio, música, documentos y contenido.

## 📖 Cómo usar esta biblioteca

1. Navega a la categoría que necesitas.
2. Abre el archivo `.txt` del prompt.
3. Reemplaza los campos `[ENTRE CORCHETES]` con tu información.
4. Pega el prompt en la herramienta de IA correspondiente (Claude, ChatGPT, Gemini, Midjourney, Suno, Runway, etc.).

> **Convención:** los prompts en español están diseñados para IAs de texto/código. Los prompts en inglés están optimizados para generadores de imagen y video, que responden mejor en ese idioma.

## 📂 Estructura del repositorio

```
Prompts/
├── 01-Programacion/
│   ├── Desarrollo-Web/          → Dashboards administrativos, e-commerce completo
│   ├── Backend-APIs/            → Microservicios, autenticación segura JWT
│   ├── Scripts-Automatizacion/  → Automatización de documentos, web scraping ético
│   ├── Bases-de-Datos/          → Diseño de modelos, optimización SQL
│   ├── IoT-Embebidos/           → Firmware ESP32, dashboards IoT en tiempo real
│   ├── Calidad-Codigo/          → Code review, debugging, testing
│   └── Documentacion-Tecnica/   → README profesional, documentación de APIs
│
├── 02-Video/
│   ├── Estilos-Cinematograficos/ → Cyberpunk Neon, Wes Anderson, Animación Ghibli
│   └── Formatos-Contenido/       → Video educativo, reels verticales, corporativo
│
├── 03-Imagen/
│   ├── Estilos-Fotograficos/    → Retrato corporativo, producto e-commerce, gastronomía
│   └── Diseno-Grafico/          → Logos, isométricos 3D, infografías
│
├── 04-Audio-Musica/
│   ├── Generos-Musicales/       → Vallenato, cumbia, balada pop, jingle publicitario
│   ├── Voz-Locucion/            → Locución comercial, narración documental, podcast
│   └── Diseno-Sonoro/           → Música de fondo instrumental
│
├── 05-Documentos-Ofimatica/     → PowerPoint, informes ejecutivos, Excel automatizado
├── 06-Educacion-Academico/      → Exámenes con rúbrica, guías, planes de clase, estado del arte
├── 07-Marketing-Contenido/      → Calendarios de contenido, copywriting, email marketing
├── 08-Analisis-Datos/           → EDA con Python, visualización de datos
├── 09-Meta-Prompts/             → Mejorador y generador de prompts
│
├── Desarrollo Web/              → Colección original (landing page EVAN)
├── Estilos de Videos/           → Colección original (8 estilos cinematográficos)
├── Estilos de Imagenes/         → Colección original (10 estilos fotográficos)
└── Musica/                      → Colección original (salsa y merengue)
```

> Las carpetas originales del repositorio se conservan intactas. Las categorías numeradas (01–09) agrupan los prompts nuevos.

## 🏗️ Anatomía de un prompt técnico

Los prompts de esta biblioteca siguen una estructura común:

| Sección | Propósito |
|---|---|
| **Rol** | Asigna a la IA una especialidad experta relevante |
| **=== CONTEXTO ===** | Información del proyecto con placeholders `[VARIABLES]` |
| **=== REQUISITOS ===** | Especificaciones técnicas numeradas y verificables |
| **=== ENTREGABLES ===** | Qué debe producir exactamente la IA |
| **Restricciones** | Qué NO debe hacer (evita alucinaciones y malas prácticas) |

## ✍️ Contribuir

Para agregar un nuevo prompt: ubícalo en la categoría correcta, usa nombre descriptivo en el archivo, mantén la estructura de secciones `=== ===` y usa `[CORCHETES]` para las partes variables.

---
Mantenido por [Ing-Estrada](https://github.com/Ing-Estrada)
