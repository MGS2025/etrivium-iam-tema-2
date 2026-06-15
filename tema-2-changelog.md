# Tema 2 — Changelog

> **Título oficial**: La Constitución Española (II): La Organización territorial del Estado. Principios generales. La Administración Local. Las Comunidades Autónomas: los Estatutos de Autonomía.

---

## v1.0 — 2026-06-15 — Generación inicial completa

**Estado**: Pendiente de validación por María / Ana (IAM).

### Alcance y decisiones

- **Fuente nuclear**: Título VIII de la CE (arts. 137-158), a partir del PDF aportado por el cliente (`Tema 2.pdf`).
- **Alcance ampliado** (validado con María el 2026-06-15): se incorpora la legislación de desarrollo imprescindible — **LBRL 7/1985**, **LOFCA 8/1980**, **Estatuto de Autonomía de Madrid (LO 3/1983)** y **Ley 22/2006 de Capitalidad y de Régimen Especial de Madrid** — sin doctrina académica.
- **Formato de referencia**: Tema 1 (administrativo, ya validado): 150 preguntas tipo test + 20 pedagógicas + 6 casos prácticos + 12 diagramas SVG + 7 pestañas.

### Entregables generados

| Fichero | Contenido |
|---|---|
| `tema-2-indice.md` | Índice de 12 secciones + tablas de datos clave y dependencias |
| `tema-2-fuentes.md` | Registro Tier 1/2/3 + normas de citación |
| `tema-2-contenido.md` | Contenido teórico ampliado (12 secciones, 4 tipos de callout) |
| `tema-2-diagramas.md` | 12 diagramas SVG accesibles (paleta Ayto Madrid) |
| `tema-2-test.md` | 150 preguntas formato examen + plantilla + 20 pedagógicas comentadas |
| `tema-2-caso-practico.md` | 6 casos prácticos (Ayto/Comunidad de Madrid), 10 pts c/u |
| `tema-2-validacion.md` | Checklist de validación para María/Ana |
| `index.html` | Web autosuficiente con 7 pestañas y motor de test (penalización 1/3) |

### QA aplicado

- Refs cruzadas verificadas contra el temario oficial **BOAM 10.032** (T1, T3, T4, T6, T8).
- Balanceo automático A/B/C de las respuestas del test (permutación determinista con semilla).
- Revisión ortográfica (hunspell es_ES) sobre los `.md`.
- Verificación de los 150 ítems (3 opciones únicas + respuesta válida) y de los 12 SVG.

### Pendiente

- Validación de contenido por María / Ana (IAM).
- Confirmación del modelo de "imprimir progreso" (δ) común a todos los temas, pendiente de OK de Jesús.
