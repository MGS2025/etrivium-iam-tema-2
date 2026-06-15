# Tema 2 — Checklist de Validación

> **Título oficial**: La Constitución Española (II): La Organización territorial del Estado. Principios generales. La Administración Local. Las Comunidades Autónomas: los Estatutos de Autonomía.
> **Versión**: 1.0
> **Fecha**: 2026-06-15
> **Revisoras**: María + Ana (IAM)

---

## Cómo usar este checklist

Cada ítem se valora con:

- **OK** → el criterio se cumple sin cambios.
- **REVISAR** → necesita ajuste o aclaración (indicar qué).
- **NO** → no se cumple o es incorrecto. Justificar brevemente.

---

## 1. Fuentes y trazabilidad

- [ ] La fuente nuclear es el **Título VIII de la CE (arts. 137-158)**, coincidente con el PDF aportado por el cliente.
- [ ] El **alcance ampliado** (LBRL, LOFCA, EAM, Ley 22/2006) es adecuado y no excede el nivel C1. *(Decisión validada con María el 2026-06-15.)*
- [ ] Cada afirmación que reproduce texto constitucional está referenciada con `[CE, art. X]`.
- [ ] El desarrollo legal se identifica con la ley correspondiente (`[LBRL, art. X]`, etc.).
- [ ] Cada pregunta del banco y de los casos puede reconducirse a un artículo del Título VIII o a la legislación citada.

## 2. Estructura del contenido

- [ ] El `tema-2-indice.md` refleja fielmente la estructura de `tema-2-contenido.md`.
- [ ] Las 12 secciones cubren: introducción y modelo, principios generales, Estado autonómico, Administración Local, acceso a la autonomía, Estatutos, competencias, instituciones, control y coerción, financiación, Madrid y resumen.
- [ ] Los conceptos memorizables aparecen marcados como `[DATO CLAVE EXAMEN]`.
- [ ] Las reproducciones literales de la CE aparecen como `[CITA CONSTITUCIONAL]`.
- [ ] Los ejemplos del Ayuntamiento/Comunidad de Madrid están marcados como `[EJEMPLO AYTO MADRID]`.
- [ ] Los enlaces a otros temas se marcan como `[REFERENCIA CRUZADA]`.

## 3. Rigor jurídico

- [ ] La estructura del Título VIII es correcta: Cap. I (137-139), Cap. II (140-142), Cap. III (143-158).
- [ ] Los tres niveles del art. 137 son correctos: municipios, provincias y CCAA.
- [ ] La distinción autonomía política (CCAA) / autonomía administrativa (locales) / soberanía (pueblo) es correcta.
- [ ] La elección de Concejales (sufragio universal, igual, libre, directo y secreto) y de Alcalde (por Concejales o vecinos) es correcta [art. 140].
- [ ] La alteración de límites provinciales exige ley orgánica [art. 141.1].
- [ ] Los plazos y fracciones del acceso a la autonomía son correctos: 6 meses y 5 años (art. 143); 2/3 vs 3/4 de municipios (143 vs 151); referéndum en la vía 151.
- [ ] El contenido mínimo del Estatuto (art. 147.2: a-b-c-d) es correcto.
- [ ] El reparto 148 (22 materias CCAA) vs 149 (32 materias Estado) es correcto.
- [ ] Las tres cláusulas del art. 149.3 (residual, prevalencia, supletoriedad) son correctas.
- [ ] La mayoría del art. 155 (mayoría absoluta del Senado, previo requerimiento) es correcta.
- [ ] La constitución de la Comunidad de Madrid por el art. 144.a) (uniprovincial) es correcta.

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-2-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo (accesibilidad).
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.
- [ ] El contenido textual de los diagramas no contradice el temario.

## 5. Banco de 150 preguntas

- [ ] Las 150 preguntas tienen 3 opciones (a/b/c) y una única respuesta correcta verificable en el articulado.
- [ ] La distribución de la opción correcta entre A/B/C está equilibrada (~50/50/50) tras el balanceo automático.
- [ ] No hay preguntas ambiguas (dos respuestas plausibles).
- [ ] La plantilla de respuestas es coherente con las preguntas.
- [ ] La sección pedagógica de 20 preguntas incluye explicación y referencia al artículo.

## 6. Casos prácticos

- [ ] Los 6 casos mantienen escenario del Ayto/Comunidad de Madrid.
- [ ] Las cuestiones de cada caso suman 10 puntos.
- [ ] Cada caso tiene solución orientativa y criterios de evaluación.
- [ ] Las soluciones son coherentes con el articulado del Título VIII.

## 7. Nivel y adecuación al C1

- [ ] El nivel de profundidad es adecuado para oposición C1 (Técnico Auxiliar TIC).
- [ ] No hay sobrecarga doctrinal irrelevante.
- [ ] Se prioriza la memorización de artículos, plazos, mayorías y clasificaciones.
- [ ] Los ejemplos de Madrid son realistas y aportan valor aplicativo.

## 8. Estilo y forma

- [ ] Los ficheros `.md` usan encabezados coherentes.
- [ ] Las tablas están correctamente formateadas.
- [ ] Los callouts siguen los 4 tipos establecidos.
- [ ] La nomenclatura de artículos es consistente (`[CE, art. X]`).
- [ ] Se respeta el castellano sin errores ortográficos manifiestos (revisión hunspell es_ES).

## 9. Entregables HTML

- [ ] `index.html` es autosuficiente (sin CDN salvo la tipografía, sin scripts externos, sin iframes).
- [ ] Funciona offline al abrirlo en el navegador.
- [ ] Incluye las pestañas: Inicio, Contenido, Diagramas, Test, Casos, Validación y Fuentes.
- [ ] El motor de test penaliza correctamente (1/3 por fallo).
- [ ] El HTML es imprimible a PDF con estilo legible.
- [ ] El branding visual corresponde al Ayuntamiento de Madrid (#0055a0).

## 10. Consistencia inter-temas

- [ ] La referencia cruzada al **Tema 1** (introducción del Título VIII) es coherente.
- [ ] Las referencias a los **Temas 3 y 4** (organización del Ayuntamiento de Madrid) y **Tema 8** (Haciendas locales) son correctas.
- [ ] La paleta visual y el glosario se mantienen respecto a los temas administrativos ya entregados (T1).

---

## Observaciones generales

### Decisiones conscientes que conviene confirmar

1. **Alcance ampliado** (a diferencia del Tema 1, que se ciñó al texto constitucional). Validado con María el 2026-06-15: además del Título VIII, se incorpora la legislación de desarrollo imprescindible (LBRL, LOFCA, EAM, Ley 22/2006) sin doctrina académica.
2. **Banco de 150 preguntas + 20 pedagógicas y 6 casos prácticos**, replicando el formato del Tema 1 ya validado.
3. **Balanceo automático A/B/C** de las respuestas mediante permutación determinista en `build_t2.py` (evita el sesgo de "opción dominante").
4. **Sección 11 (Madrid)** incorporada por su valor para el puesto: Comunidad de Madrid (art. 144.a) + Ley de Capitalidad 22/2006.

### Material descartado conscientemente

- Doctrina académica y manuales comerciales: fuera de alcance.
- Jurisprudencia del TC sobre el Estado autonómico (SSTC 4/1981, 76/1983 LOAPA, 31/2010): citada solo puntualmente; puede ampliarse en v2 si se solicita.
- Estatutos de Autonomía de otras CCAA (salvo Madrid): fuera de alcance.

---

## Feedback de María

*Espacio reservado — rellenar tras revisión.*

| Ítem checklist | Estado | Observación |
|---|---|---|
|  |  |  |
|  |  |  |

---

## Feedback de Ana

*Espacio reservado — rellenar tras revisión.*

| Ítem checklist | Estado | Observación |
|---|---|---|
|  |  |  |

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
