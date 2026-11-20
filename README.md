# ElemQuest

Prototipo de aplicación web gamificada para identificar y repasar los elementos de la tabla periódica. Está pensado para estudiantes universitarios de química general.

**Demo en línea:** https://TU-USUARIO.github.io/elemquest/

## Objetivo

Pasar del simple reconocimiento de elementos a su relación con las propiedades y la periodicidad, y favorecer la retención a largo plazo mediante práctica de recuperación y repetición espaciada.

## Modos de juego

| Modo | Descripción |
|---|---|
| **Detective** | Pistas progresivas (periodo y grupo, categoría, uso cotidiano, número atómico) para adivinar el elemento. Cuantas menos pistas se usen, más XP se obtiene. |
| **Relámpago** | Preguntas rápidas de símbolo, nombre y número atómico. |
| **Mi tabla** | Mapa de calor personal con el nivel de dominio (0 a 4) de cada elemento y su ficha informativa. |

## Mecánicas de aprendizaje y gamificación

- **Repaso espaciado (estilo Leitner):** un acierto sube un nivel de dominio y un fallo lo reinicia. Los elementos más débiles aparecen con mayor probabilidad.
- **XP y rangos:** Aprendiz, Alquimista, Químico/a y Mendeléyev.
- **Racha diaria** con un día de gracia para no penalizar en exceso.
- **Retroalimentación inmediata** con una breve explicación en cada respuesta.
- **Accesibilidad:** diseño adaptable a móvil, modo oscuro automático, navegación por teclado y niveles de dominio indicados con número además de color.

## Alcance actual del prototipo

- Incluye los primeros 36 elementos (H a Kr).
- No tiene cuentas de usuario, panel docente ni duelos en tiempo real.
- El progreso se guarda localmente en el navegador (`localStorage`) y no se envía a ningún servidor. No se recopilan datos personales.

## Uso

Es una página estática, sin dependencias ni proceso de compilación.

**Localmente:** descarga el repositorio y abre `index.html` en un navegador.

**Publicación con GitHub Pages:**
1. Sube `index.html` a la rama `main`.
2. En *Settings → Pages*, elige *Deploy from a branch*, rama `main` y carpeta `/ (root)`.
3. Abre la dirección que GitHub indica.

**Integración en Google Sites:** en *Insertar → Insertar → Por URL*, pega la dirección de GitHub Pages.

## Estructura

```
elemquest/
├── index.html   # aplicación completa (HTML, CSS y JavaScript)
└── README.md
```

## Hoja de ruta

- [ ] Ampliar a los 118 elementos y agregar lantánidos y actínidos.
- [ ] Modo "Arma la tabla" (arrastrar fichas a su casilla).
- [ ] Modo "Predice la tendencia" (electronegatividad, radio atómico).
- [ ] Panel docente con mapa de calor del grupo y exportación de resultados.
- [ ] Torneos por equipos en tiempo real.
- [ ] Integración con Moodle o Canvas.

## Cómo contribuir

Las sugerencias son bienvenidas. Abre un *issue* para reportar errores o proponer mejoras, o envía un *pull request* con una descripción breve del cambio. Si corriges o amplías datos de elementos, indica la fuente consultada.

## Licencia

Define aquí la licencia del proyecto (por ejemplo, MIT) y agrega el archivo `LICENSE` al repositorio.

## Autoría

Proyecto desarrollado por **TU NOMBRE** · TU INSTITUCIÓN · AÑO
