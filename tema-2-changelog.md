# Tema 2 — Changelog

> **Título oficial**: La Constitución Española (II): La Organización territorial del Estado. Principios generales. La Administración Local. Las Comunidades Autónomas: los Estatutos de Autonomía.

---

## v1.3 — 2026-10-01 — Revisión jurídica

**Estado**: aplicada la revisión jurídica de los temas 1-10. Textos normativos comprobados contra el BOE consolidado (CE, LBRL, LO 3/1983, LO 6/1982, LO 1/1995, Ley 22/2006).

### Cambios

- **Diagrama D6** (vías de acceso): la caja «Ejemplos» tapaba los rótulos centrales y el texto no cabía en su marco. La caja pasa a ocupar todo el ancho bajo las tres filas (viewBox 700×430) y los rótulos «Municipios en la iniciativa», «Referéndum de iniciativa» y «Techo competencial» quedan centrados (la clase CSS forzaba `text-anchor:start`).
- **Otros desbordes de diagramas**: D1 (nota inferior centrada en el lienzo), D9 (caja «Asamblea Legislativa» ensanchada) y D11 (dos líneas del Fondo de Compensación centradas en su caja). `qa_svg.py`: 0 desbordes y 0 colisiones.
- **Cajas**: «Dato clave examen» → **Dato clave** · «Cita constitucional» → **Cita normativa** · «Ejemplo Ayto Madrid» → **Ejemplo de aplicación en el Ayto** · «Referencia cruzada» → **Relación con otros temas**. Leyenda sin promesas sobre el test oficial.
- **Texto ceñido a la norma**: fuera las valoraciones fuera de cajas (p. ej. «uno de los grandes pilares», «a medio camino entre el Estado unitario y el federal», «de abajo arriba», «tiende a la homogeneización», «el reparto competencial es el núcleo», «mecanismo excepcional», «que de hecho han adoptado todas las CCAA»); los pasajes afectados se reescriben con el texto de los arts. 1.2, 2, 81.1, 143.1, 147.2.d, 148.2, 151.1, 152.1 y 155.1 CE, la DT 2.ª CE y los arts. 1, 3, 4.1, 7, 26, 29.3 y 41 LBRL.
- **Correcciones de fondo**: Navarra no se constituyó por el art. 144.a) (se quita); la autorización de Madrid es la LO 6/1982 (el Estatuto, la LO 3/1983); el art. 3.2 LBRL ya no incluye las entidades de ámbito inferior al municipio; la LBRL se cita por su preámbulo (art. 149.1.18.ª en relación con el 148.1.2.ª); el art. 155 no exige incumplimiento «grave»; los rasgos de la Ley 22/2006 se citan por sus arts. 5, 7, 9.1 y 22.1; publicación de la Ley 22/2006 corregida (BOE núm. 159, de 05/07/2006).
- **Citas de artículos**: «artículo» completo cuando forma parte de la oración y «art.» abreviado en el inciso entre paréntesis.
- **Correcciones comunes**: fuera las referencias al material del cliente (tabla Tier 2, PDF y DOCX de origen, trazabilidad al Tier 2), las validaciones «con María» y la promesa de examen; el temario oficial BOAM pasa a la tabla de fuentes oficiales.
- **Test**: 32 preguntas del banco reescritas como preguntas literales de la norma (doctrina, valoraciones, «principal ventaja», denominaciones doctrinales y datos no normativos) y 11 de las 20 pedagógicas; un distractor doctrinal sustituido. Respuestas correctas equilibradas 50/50/50 en el `.md` y plantilla regenerada.
- **Casos prácticos**: soluciones alineadas con el texto literal (DT 2.ª, art. 144.a y LO 6/1982, art. 149.1.18.ª, art. 155.1, concejo abierto según el art. 29.3 LBRL).

---

## v1.2 — 2026-09-06 — Ficha de extensión y tiempo de estudio

**Estado**: sin cambios de contenido. Solo se añade información sobre el propio tema.

**Motivo**: petición del IAM (Jesús Cuadrado, 02-09-2026) al validar el Tema 30. Acepta la extensión de los temas «compuestos» a condición de que se informe de «su extensión en palabras y tiempo estimado de estudio». Al revisarlo se vio que ese dato solo aparecía en 16 de los 40 temas, y que faltaba justo en los más largos.

### Alcance

- Ficha bajo la cabecera del tema, y al final de la pestaña Índice donde esa pestaña existe:
  - **Extensión**: ~4.300 palabras · 13 diagramas · 150 preguntas de test
  - **Tiempo estimado de estudio**: 10-12 horas (primera vuelta completa, sin contar repasos)
- La cifra de palabras de la tabla de entregables se sincroniza con la ficha, para que el tema no muestre dos recuentos distintos.
- Las horas salen de una fórmula común a los 40 temas, para que sean comparables entre sí: contenido a 1.500 palabras/hora (ritmo de estudio activo), diagramas a una hora por cada cinco y test a dos minutos por pregunta. Se publica como intervalo de dos horas.
- Generado con `_tools-qa/ficha_estudio.py`, idempotente y reejecutable tras cualquier regeneración con `build_tNN.py`.

---

## v1.1 — 2026-06-17 — Diagrama de definiciones (feedback María)

**Estado**: Pendiente de validación por María / Ana (IAM).

### Cambios

- **Nuevo diagrama D13** «Definiciones clave: entidades locales y Estatutos de Autonomía» (§ 4), a petición de María: ficha visual con las definiciones de **municipios**, **provincias**, **régimen especial (Ceuta y Melilla)** y **Estatutos de Autonomía**.
- Total de diagramas: **12 → 13**.
- `index.html` regenerado con `build_t2.py`; versión visible actualizada a **v1.1**.

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
