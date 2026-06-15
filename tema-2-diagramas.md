# Tema 2 — Catálogo de Diagramas

> **Título oficial**: La Constitución Española (II): La Organización territorial del Estado. Principios generales. La Administración Local. Las Comunidades Autónomas: los Estatutos de Autonomía.
>
> **Versión**: 1.0
> **Fecha**: 2026-06-15
> **Formato**: SVG inline (zero-dependencias, escalable, imprimible)
> **Paleta**: Ayuntamiento de Madrid #0055a0 (primario) + #d13c3c (alertas) + #2d8659 (ventajas) + #e89822 (callouts)

---

## Índice de diagramas

| ID  | Título                                                  | Sección | Tipo |
|-----|---------------------------------------------------------|---------|------|
| D1  | Los tres niveles de organización territorial            | § 1     | Árbol |
| D2  | Principios generales del Título VIII (arts. 137-139)    | § 2     | Comparativa |
| D3  | Características del Estado autonómico                    | § 3     | Mapa conceptual |
| D4  | La Administración Local (arts. 140-142)                 | § 4     | Árbol |
| D5  | El Municipio: gobierno y elección (art. 140)            | § 4.1   | Esquema |
| D6  | Vías de acceso a la autonomía: art. 143 vs art. 151     | § 5     | Comparativa |
| D7  | Contenido mínimo del Estatuto (art. 147.2)              | § 6.2   | Caja |
| D8  | Reparto competencial: art. 148 vs art. 149              | § 7     | Comparativa |
| D9  | Organización institucional autonómica (art. 152)        | § 8     | Esquema |
| D10 | Control de las CCAA y coerción estatal (arts. 153-155)  | § 9     | Flowchart |
| D11 | Financiación autonómica (arts. 156-158)                 | § 10    | Mapa |
| D12 | Madrid: los tres niveles en la ciudad                   | § 11    | Árbol |

---

## D1 · Los tres niveles de organización territorial

**Sección**: § 1 — Introducción
**Propósito**: Mostrar los tres niveles del art. 137 y su tipo de autonomía.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="Los tres niveles de organización territorial del Estado: Estado, Comunidades Autónomas y Entidades Locales">
  <style>
    .d1-root{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d1-box{fill:#ffffff;stroke:#0055a0;stroke-width:1.5}
    .d1-t{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d1-h{font:700 13px system-ui,sans-serif;fill:#003d73;text-anchor:middle}
    .d1-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .d1-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="270" y="20" width="160" height="46" rx="8" class="d1-root"/>
  <text x="350" y="40" class="d1-t">ESTADO</text>
  <text x="350" y="57" class="d1-t" style="font-weight:400;font-size:11px">soberanía · art. 137</text>
  <line x1="350" y1="66" x2="350" y2="100" class="d1-l"/>
  <line x1="130" y1="120" x2="130" y2="100" class="d1-l"/>
  <line x1="350" y1="120" x2="350" y2="100" class="d1-l"/>
  <line x1="570" y1="120" x2="570" y2="100" class="d1-l"/>
  <line x1="130" y1="100" x2="570" y2="100" class="d1-l"/>
  <rect x="40" y="120" width="180" height="64" rx="8" class="d1-box"/>
  <text x="130" y="145" class="d1-h">Comunidades</text>
  <text x="130" y="162" class="d1-h">Autónomas</text>
  <text x="130" y="178" class="d1-s">autonomía POLÍTICA (legislan)</text>
  <rect x="260" y="120" width="180" height="64" rx="8" class="d1-box"/>
  <text x="350" y="153" class="d1-h">Provincias</text>
  <text x="350" y="170" class="d1-s">entidad local + división</text>
  <rect x="480" y="120" width="180" height="64" rx="8" class="d1-box"/>
  <text x="570" y="153" class="d1-h">Municipios</text>
  <text x="570" y="170" class="d1-s">unidad básica</text>
  <rect x="260" y="230" width="380" height="58" rx="8" fill="#e8f0f8" stroke="#0055a0" stroke-width="1.5"/>
  <text x="450" y="255" class="d1-h">ENTIDADES LOCALES</text>
  <text x="450" y="273" class="d1-s">autonomía ADMINISTRATIVA (no legislan) · arts. 140-142</text>
  <line x1="350" y1="184" x2="350" y2="230" class="d1-l"/>
  <line x1="570" y1="184" x2="570" y2="230" class="d1-l"/>
  <text x="130" y="320" class="d1-s" style="font-style:italic">La soberanía es única (pueblo español); la autonomía es poder limitado para los intereses propios.</text>
</svg>
```

---

## D2 · Principios generales del Título VIII (arts. 137-139)

**Sección**: § 2 — Principios generales
**Propósito**: Asociar cada artículo del Capítulo I con su principio.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="Principios generales del Título VIII: autonomía artículo 137, solidaridad artículo 138, igualdad artículo 139">
  <style>
    .d2-col{stroke-width:2}
    .d2-h{font:700 15px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d2-a{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d2-t{font:13px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .d2-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="30" y="30" width="200" height="56" rx="8" fill="#0055a0"/>
  <text x="130" y="55" class="d2-a">Art. 137</text>
  <text x="130" y="75" class="d2-h">AUTONOMÍA</text>
  <rect x="30" y="100" width="200" height="180" rx="8" fill="#fff" stroke="#0055a0" class="d2-col"/>
  <text x="130" y="135" class="d2-t">Municipios, provincias</text>
  <text x="130" y="153" class="d2-t">y CCAA gozan de</text>
  <text x="130" y="171" class="d2-t">autonomía para gestionar</text>
  <text x="130" y="189" class="d2-t">sus intereses</text>
  <text x="130" y="225" class="d2-s">CCAA: autonomía política</text>
  <text x="130" y="243" class="d2-s">Local: autonomía admin.</text>
  <rect x="250" y="30" width="200" height="56" rx="8" fill="#2d8659"/>
  <text x="350" y="55" class="d2-a">Art. 138</text>
  <text x="350" y="75" class="d2-h">SOLIDARIDAD</text>
  <rect x="250" y="100" width="200" height="180" rx="8" fill="#fff" stroke="#2d8659" class="d2-col"/>
  <text x="350" y="135" class="d2-t">Equilibrio económico</text>
  <text x="350" y="153" class="d2-t">adecuado y justo entre</text>
  <text x="350" y="171" class="d2-t">territorios</text>
  <text x="350" y="207" class="d2-s">atención al hecho insular</text>
  <text x="350" y="243" class="d2-s">sin privilegios entre</text>
  <text x="350" y="261" class="d2-s">Estatutos (138.2)</text>
  <rect x="470" y="30" width="200" height="56" rx="8" fill="#e89822"/>
  <text x="570" y="55" class="d2-a">Art. 139</text>
  <text x="570" y="75" class="d2-h">IGUALDAD</text>
  <rect x="470" y="100" width="200" height="180" rx="8" fill="#fff" stroke="#e89822" class="d2-col"/>
  <text x="570" y="135" class="d2-t">Mismos derechos y</text>
  <text x="570" y="153" class="d2-t">obligaciones en todo</text>
  <text x="570" y="171" class="d2-t">el territorio</text>
  <text x="570" y="225" class="d2-s">unidad de mercado:</text>
  <text x="570" y="243" class="d2-s">libre circulación de</text>
  <text x="570" y="261" class="d2-s">personas y bienes</text>
</svg>
```

---

## D3 · Características del Estado autonómico

**Sección**: § 3 — El modelo de Estado autonómico
**Propósito**: Mapa conceptual de los rasgos del modelo territorial.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="Características del Estado autonómico español: principio dispositivo, asimetría, unidad e indisolubilidad, prohibición de federación">
  <style>
    .d3-c{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d3-n{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d3-ct{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d3-h{font:700 12px system-ui,sans-serif;fill:#003d73;text-anchor:middle}
    .d3-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .d3-l{stroke:#0055a0;stroke-width:1;fill:none}
  </style>
  <line x1="350" y1="180" x2="170" y2="80" class="d3-l"/>
  <line x1="350" y1="180" x2="530" y2="80" class="d3-l"/>
  <line x1="350" y1="180" x2="170" y2="285" class="d3-l"/>
  <line x1="350" y1="180" x2="530" y2="285" class="d3-l"/>
  <ellipse cx="350" cy="180" rx="92" ry="44" class="d3-c"/>
  <text x="350" y="175" class="d3-ct">ESTADO</text>
  <text x="350" y="194" class="d3-ct" style="font-weight:400;font-size:11px">AUTONÓMICO</text>
  <rect x="60" y="52" width="220" height="56" rx="8" class="d3-n"/>
  <text x="170" y="76" class="d3-h">Principio dispositivo</text>
  <text x="170" y="94" class="d3-s">cada territorio decide acceso y techo</text>
  <rect x="420" y="52" width="220" height="56" rx="8" class="d3-n"/>
  <text x="530" y="76" class="d3-h">Asimetría inicial</text>
  <text x="530" y="94" class="d3-s">vía 143 vs vía 151</text>
  <rect x="60" y="258" width="220" height="56" rx="8" class="d3-n"/>
  <text x="170" y="282" class="d3-h">Unidad e indisolubilidad</text>
  <text x="170" y="300" class="d3-s">art. 2 CE</text>
  <rect x="420" y="258" width="220" height="56" rx="8" class="d3-n"/>
  <text x="530" y="282" class="d3-h">No federación</text>
  <text x="530" y="300" class="d3-s">prohibida (art. 145.1)</text>
</svg>
```

---

## D4 · La Administración Local (arts. 140-142)

**Sección**: § 4 — La Administración Local
**Propósito**: Estructurar los entes locales con garantía constitucional.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="La Administración Local: municipio artículo 140, provincia artículo 141, isla, y haciendas locales artículo 142">
  <style>
    .d4-root{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d4-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d4-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d4-h{font:700 13px system-ui,sans-serif;fill:#003d73;text-anchor:middle}
    .d4-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .d4-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="250" y="20" width="200" height="46" rx="8" class="d4-root"/>
  <text x="350" y="40" class="d4-t">ADMINISTRACIÓN LOCAL</text>
  <text x="350" y="57" class="d4-t" style="font-weight:400;font-size:11px">Capítulo II · arts. 140-142</text>
  <line x1="350" y1="66" x2="350" y2="92" class="d4-l"/>
  <line x1="130" y1="110" x2="130" y2="92" class="d4-l"/>
  <line x1="350" y1="110" x2="350" y2="92" class="d4-l"/>
  <line x1="570" y1="110" x2="570" y2="92" class="d4-l"/>
  <line x1="130" y1="92" x2="570" y2="92" class="d4-l"/>
  <rect x="40" y="110" width="180" height="76" rx="8" class="d4-box"/>
  <text x="130" y="135" class="d4-h">MUNICIPIO</text>
  <text x="130" y="153" class="d4-s">art. 140 · personalidad</text>
  <text x="130" y="169" class="d4-s">jurídica plena</text>
  <rect x="260" y="110" width="180" height="76" rx="8" class="d4-box"/>
  <text x="350" y="135" class="d4-h">PROVINCIA</text>
  <text x="350" y="153" class="d4-s">art. 141 · Diputaciones</text>
  <text x="350" y="169" class="d4-s">límites: ley orgánica</text>
  <rect x="480" y="110" width="180" height="76" rx="8" class="d4-box"/>
  <text x="570" y="135" class="d4-h">ISLA</text>
  <text x="570" y="153" class="d4-s">art. 141.4 · Cabildos</text>
  <text x="570" y="169" class="d4-s">(Canarias) y Consejos</text>
  <rect x="120" y="240" width="460" height="70" rx="8" fill="#fdf4e4" stroke="#e89822" stroke-width="1.5"/>
  <text x="350" y="268" class="d4-h" style="fill:#a8650f">HACIENDAS LOCALES · art. 142</text>
  <text x="350" y="288" class="d4-s">Suficiencia financiera: tributos propios + participación en</text>
  <text x="350" y="303" class="d4-s">los del Estado y de las CCAA · (desarrollo: TRLRHL → Tema 8)</text>
</svg>
```

---

## D5 · El Municipio: gobierno y elección (art. 140)

**Sección**: § 4.1 — El Municipio
**Propósito**: Esquema del Ayuntamiento y la forma de elección.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 340" role="img" aria-label="Gobierno municipal: el Ayuntamiento integrado por Alcalde y Concejales; los Concejales elegidos por sufragio universal y el Alcalde por los Concejales o los vecinos">
  <style>
    .d5-root{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d5-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d5-t{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d5-h{font:700 13px system-ui,sans-serif;fill:#003d73;text-anchor:middle}
    .d5-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .d5-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="270" y="20" width="160" height="46" rx="8" class="d5-root"/>
  <text x="350" y="48" class="d5-t">AYUNTAMIENTO</text>
  <line x1="350" y1="66" x2="350" y2="86" class="d5-l"/>
  <line x1="200" y1="104" x2="200" y2="86" class="d5-l"/>
  <line x1="500" y1="104" x2="500" y2="86" class="d5-l"/>
  <line x1="200" y1="86" x2="500" y2="86" class="d5-l"/>
  <rect x="110" y="104" width="180" height="58" rx="8" class="d5-box"/>
  <text x="200" y="138" class="d5-h">ALCALDE</text>
  <rect x="410" y="104" width="180" height="58" rx="8" class="d5-box"/>
  <text x="500" y="138" class="d5-h">CONCEJALES</text>
  <rect x="110" y="210" width="180" height="86" rx="8" fill="#e8f5ee" stroke="#2d8659" stroke-width="1.5"/>
  <text x="200" y="238" class="d5-h" style="fill:#1f5e3f">Elegido por</text>
  <text x="200" y="258" class="d5-s">los Concejales</text>
  <text x="200" y="275" class="d5-s">o por los vecinos</text>
  <rect x="410" y="210" width="180" height="86" rx="8" fill="#e8f5ee" stroke="#2d8659" stroke-width="1.5"/>
  <text x="500" y="234" class="d5-h" style="fill:#1f5e3f">Elegidos por sufragio</text>
  <text x="500" y="253" class="d5-s">universal, igual, libre,</text>
  <text x="500" y="270" class="d5-s">directo y secreto</text>
  <text x="500" y="287" class="d5-s">(vecinos del municipio)</text>
  <line x1="200" y1="162" x2="200" y2="210" class="d5-l"/>
  <line x1="500" y1="162" x2="500" y2="210" class="d5-l"/>
</svg>
```

---

## D6 · Vías de acceso a la autonomía: art. 143 vs art. 151

**Sección**: § 5 — Acceso a la autonomía
**Propósito**: Comparar la vía ordinaria y la vía rápida.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="Comparación de las vías de acceso a la autonomía: vía ordinaria artículo 143 y vía rápida artículo 151">
  <style>
    .d6-hb{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d6-r{font:600 12px system-ui,sans-serif;fill:#003d73;text-anchor:start}
    .d6-v{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .d6-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="40" y="20" width="180" height="42" rx="8" fill="#0055a0"/>
  <text x="130" y="40" class="d6-hb">Vía ORDINARIA</text>
  <text x="130" y="56" class="d6-hb" style="font-weight:400;font-size:11px">art. 143 (lenta)</text>
  <rect x="480" y="20" width="180" height="42" rx="8" fill="#2d8659"/>
  <text x="570" y="40" class="d6-hb">Vía RÁPIDA</text>
  <text x="570" y="56" class="d6-hb" style="font-weight:400;font-size:11px">art. 151 (privilegiada)</text>
  <text x="350" y="100" class="d6-r" text-anchor="middle" style="fill:#777">Municipios en la iniciativa</text>
  <rect x="40" y="110" width="180" height="40" rx="6" fill="#e8f0f8"/>
  <text x="130" y="135" class="d6-v">2/3 de municipios</text>
  <rect x="480" y="110" width="180" height="40" rx="6" fill="#e8f5ee"/>
  <text x="570" y="135" class="d6-v">3/4 de municipios</text>
  <text x="350" y="178" class="d6-r" text-anchor="middle" style="fill:#777">Referéndum de iniciativa</text>
  <rect x="40" y="188" width="180" height="40" rx="6" fill="#e8f0f8"/>
  <text x="130" y="213" class="d6-v">No exigido</text>
  <rect x="480" y="188" width="180" height="40" rx="6" fill="#e8f5ee"/>
  <text x="570" y="213" class="d6-v">Obligatorio</text>
  <text x="350" y="256" class="d6-r" text-anchor="middle" style="fill:#777">Techo competencial</text>
  <rect x="40" y="266" width="180" height="54" rx="6" fill="#e8f0f8"/>
  <text x="130" y="288" class="d6-v">Limitado (art. 148)</text>
  <text x="130" y="306" class="d6-s">amplía a los 5 años</text>
  <rect x="480" y="266" width="180" height="54" rx="6" fill="#e8f5ee"/>
  <text x="570" y="288" class="d6-v">Amplio (art. 149)</text>
  <text x="570" y="306" class="d6-s">desde el inicio</text>
  <rect x="250" y="110" width="200" height="210" rx="8" fill="#fff" stroke="#d1d7df" stroke-width="1"/>
  <text x="350" y="150" class="d6-s" style="font-weight:700;fill:#003d73">Ejemplos</text>
  <text x="350" y="180" class="d6-s">Ordinaria: la mayoría</text>
  <text x="350" y="197" class="d6-s">de CCAA (Madrid vía</text>
  <text x="350" y="214" class="d6-s">144.a + 143)</text>
  <text x="350" y="244" class="d6-s">Rápida: Cataluña, País</text>
  <text x="350" y="261" class="d6-s">Vasco, Galicia (DT 2.ª)</text>
  <text x="350" y="278" class="d6-s">y Andalucía (151)</text>
</svg>
```

---

## D7 · Contenido mínimo del Estatuto (art. 147.2)

**Sección**: § 6.2 — Naturaleza, contenido y reforma
**Propósito**: Fijar las cuatro letras del contenido obligatorio.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="Contenido mínimo del Estatuto de Autonomía según el artículo 147.2: denominación, territorio, instituciones y sede, competencias">
  <style>
    .d7-c{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d7-b{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d7-ct{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d7-let{font:700 16px system-ui,sans-serif;fill:#e89822;text-anchor:middle}
    .d7-h{font:700 13px system-ui,sans-serif;fill:#003d73;text-anchor:middle}
    .d7-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <ellipse cx="350" cy="160" rx="96" ry="48" class="d7-c"/>
  <text x="350" y="155" class="d7-ct">ESTATUTO</text>
  <text x="350" y="174" class="d7-ct" style="font-weight:400;font-size:11px">art. 147.2 · ley orgánica</text>
  <rect x="40" y="40" width="220" height="70" rx="8" class="d7-b"/>
  <text x="70" y="70" class="d7-let">a)</text>
  <text x="160" y="70" class="d7-h">Denominación</text>
  <text x="160" y="90" class="d7-s">según identidad histórica</text>
  <rect x="440" y="40" width="220" height="70" rx="8" class="d7-b"/>
  <text x="470" y="70" class="d7-let">b)</text>
  <text x="560" y="70" class="d7-h">Territorio</text>
  <text x="560" y="90" class="d7-s">delimitación</text>
  <rect x="40" y="210" width="220" height="70" rx="8" class="d7-b"/>
  <text x="70" y="240" class="d7-let">c)</text>
  <text x="160" y="240" class="d7-h">Instituciones y sede</text>
  <text x="160" y="260" class="d7-s">denominación y organización</text>
  <rect x="440" y="210" width="220" height="70" rx="8" class="d7-b"/>
  <text x="470" y="240" class="d7-let">d)</text>
  <text x="560" y="240" class="d7-h">Competencias</text>
  <text x="560" y="260" class="d7-s">asumidas + bases de traspaso</text>
</svg>
```

---

## D8 · Reparto competencial: art. 148 vs art. 149

**Sección**: § 7 — Distribución de competencias
**Propósito**: Contraponer las dos listas y las cláusulas de cierre.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="Reparto competencial: artículo 148 competencias asumibles por las Comunidades Autónomas, artículo 149 competencias exclusivas del Estado, y cláusulas de cierre del 149.3">
  <style>
    .d8-hb{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d8-s{font:11px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
    .d8-cl{font:700 12px system-ui,sans-serif;fill:#fff;text-anchor:middle}
  </style>
  <rect x="30" y="20" width="300" height="190" rx="10" fill="#fff" stroke="#0055a0" stroke-width="1.5"/>
  <rect x="30" y="20" width="300" height="40" rx="10" fill="#0055a0"/>
  <text x="180" y="46" class="d8-hb">Art. 148 — 22 materias (CCAA)</text>
  <text x="50" y="86" class="d8-s">• Organización del autogobierno (1.ª)</text>
  <text x="50" y="108" class="d8-s">• Ordenación territorio, urbanismo, vivienda (3.ª)</text>
  <text x="50" y="130" class="d8-s">• Agricultura, turismo, asistencia social</text>
  <text x="50" y="152" class="d8-s">• Museos y patrimonio de interés de la CA</text>
  <text x="50" y="174" class="d8-s">• Coordinación de policías locales (22.ª)</text>
  <text x="50" y="196" class="d8-s" style="font-style:italic;fill:#777">amplía al art. 149 a los 5 años (148.2)</text>
  <rect x="370" y="20" width="300" height="190" rx="10" fill="#fff" stroke="#d13c3c" stroke-width="1.5"/>
  <rect x="370" y="20" width="300" height="40" rx="10" fill="#d13c3c"/>
  <text x="520" y="46" class="d8-hb">Art. 149 — 32 materias (Estado)</text>
  <text x="390" y="86" class="d8-s">• Relaciones internacionales, Defensa (3.ª, 4.ª)</text>
  <text x="390" y="108" class="d8-s">• Administración de Justicia (5.ª)</text>
  <text x="390" y="130" class="d8-s">• Legislación mercantil, penal, civil, laboral</text>
  <text x="390" y="152" class="d8-s">• Bases régimen jurídico AAPP + proc. común (18.ª)</text>
  <text x="390" y="174" class="d8-s">• Seguridad pública (29.ª) · Hacienda general (14.ª)</text>
  <text x="390" y="196" class="d8-s" style="font-style:italic;fill:#777">competencia EXCLUSIVA del Estado</text>
  <rect x="80" y="250" width="540" height="86" rx="10" fill="#e89822"/>
  <text x="350" y="276" class="d8-cl">CLÁUSULAS DE CIERRE — art. 149.3</text>
  <text x="350" y="300" class="d8-cl" style="font-weight:400;font-size:12px">1. Residual: lo no atribuido al Estado → puede ser de las CCAA</text>
  <text x="350" y="320" class="d8-cl" style="font-weight:400;font-size:12px">2. Prevalencia del derecho estatal · 3. Supletoriedad "en todo caso"</text>
</svg>
```

---

## D9 · Organización institucional autonómica (art. 152)

**Sección**: § 8 — Organización institucional autonómica
**Propósito**: Mostrar el triángulo institucional y el TSJ.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 340" role="img" aria-label="Organización institucional autonómica del artículo 152: Asamblea Legislativa, Consejo de Gobierno, Presidente y Tribunal Superior de Justicia">
  <style>
    .d9-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d9-h{font:700 13px system-ui,sans-serif;fill:#003d73;text-anchor:middle}
    .d9-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .d9-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="250" y="30" width="200" height="64" rx="8" fill="#0055a0"/>
  <text x="350" y="58" class="d9-h" style="fill:#fff">ASAMBLEA LEGISLATIVA</text>
  <text x="350" y="78" class="d9-s" style="fill:#dbe7f3">sufragio universal · proporcional · legisla</text>
  <rect x="60" y="160" width="230" height="74" rx="8" class="d9-box"/>
  <text x="175" y="188" class="d9-h">PRESIDENTE</text>
  <text x="175" y="207" class="d9-s">elegido por la Asamblea,</text>
  <text x="175" y="222" class="d9-s">nombrado por el Rey</text>
  <rect x="410" y="160" width="230" height="74" rx="8" class="d9-box"/>
  <text x="525" y="188" class="d9-h">CONSEJO DE GOBIERNO</text>
  <text x="525" y="207" class="d9-s">funciones ejecutivas</text>
  <text x="525" y="222" class="d9-s">y administrativas</text>
  <line x1="350" y1="94" x2="350" y2="120" class="d9-l"/>
  <line x1="175" y1="160" x2="175" y2="120" class="d9-l"/>
  <line x1="525" y1="160" x2="525" y2="120" class="d9-l"/>
  <line x1="175" y1="120" x2="525" y2="120" class="d9-l"/>
  <text x="350" y="135" class="d9-s" style="font-style:italic">responsables políticamente ante la Asamblea</text>
  <rect x="200" y="270" width="300" height="56" rx="8" fill="#e8f5ee" stroke="#2d8659" stroke-width="1.5"/>
  <text x="350" y="296" class="d9-h" style="fill:#1f5e3f">TRIBUNAL SUPERIOR DE JUSTICIA</text>
  <text x="350" y="314" class="d9-s">culmina la organización judicial de la CA</text>
</svg>
```

---

## D10 · Control de las CCAA y coerción estatal (arts. 153-155)

**Sección**: § 9 — Control y coerción
**Propósito**: Cuatro vías de control + mecanismo del art. 155.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="Control de las Comunidades Autónomas según el artículo 153 por cuatro órganos y mecanismo de coerción del artículo 155">
  <style>
    .d10-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d10-h{font:700 12px system-ui,sans-serif;fill:#003d73;text-anchor:middle}
    .d10-s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .d10-c{fill:#0055a0}
  </style>
  <rect x="250" y="18" width="200" height="40" rx="8" class="d10-c"/>
  <text x="350" y="43" class="d10-h" style="fill:#fff">CONTROL · art. 153</text>
  <rect x="30" y="90" width="150" height="74" rx="8" class="d10-box"/>
  <text x="105" y="116" class="d10-h">Tribunal</text>
  <text x="105" y="132" class="d10-h">Constitucional</text>
  <text x="105" y="150" class="d10-s">normas con fuerza de ley</text>
  <rect x="200" y="90" width="150" height="74" rx="8" class="d10-box"/>
  <text x="275" y="116" class="d10-h">Gobierno</text>
  <text x="275" y="134" class="d10-s">funciones delegadas</text>
  <text x="275" y="150" class="d10-s">(dictamen C. de Estado)</text>
  <rect x="370" y="90" width="150" height="74" rx="8" class="d10-box"/>
  <text x="445" y="116" class="d10-h">Contencioso-</text>
  <text x="445" y="132" class="d10-h">administrativo</text>
  <text x="445" y="150" class="d10-s">admin. y reglamentos</text>
  <rect x="540" y="90" width="150" height="74" rx="8" class="d10-box"/>
  <text x="615" y="116" class="d10-h">Tribunal de</text>
  <text x="615" y="132" class="d10-h">Cuentas</text>
  <text x="615" y="150" class="d10-s">económico-presupuest.</text>
  <rect x="120" y="220" width="460" height="110" rx="10" fill="#fbeeed" stroke="#d13c3c" stroke-width="2"/>
  <text x="350" y="250" class="d10-h" style="fill:#a3271c;font-size:14px">COERCIÓN ESTATAL · art. 155</text>
  <text x="350" y="276" class="d10-s" style="font-size:12px">Incumplimiento grave o atentado al interés general →</text>
  <text x="350" y="296" class="d10-s" style="font-size:12px">1) requerimiento previo al Presidente de la CA</text>
  <text x="350" y="316" class="d10-s" style="font-size:12px">2) aprobación por MAYORÍA ABSOLUTA del Senado</text>
</svg>
```

---

## D11 · Financiación autonómica (arts. 156-158)

**Sección**: § 10 — La financiación autonómica
**Propósito**: Recursos y principios de la autonomía financiera.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 340" role="img" aria-label="Financiación autonómica: autonomía financiera del artículo 156, recursos del artículo 157 y Fondo de Compensación del artículo 158">
  <style>
    .d11-c{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d11-b{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d11-ct{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d11-s{font:11px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
    .d11-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <ellipse cx="160" cy="160" rx="110" ry="52" class="d11-c"/>
  <text x="160" y="152" class="d11-ct">AUTONOMÍA</text>
  <text x="160" y="170" class="d11-ct">FINANCIERA</text>
  <text x="160" y="188" class="d11-ct" style="font-weight:400;font-size:10px">art. 156 · coord. + solidaridad</text>
  <rect x="340" y="30" width="330" height="160" rx="8" class="d11-b"/>
  <rect x="340" y="30" width="330" height="34" rx="8" fill="#0055a0"/>
  <text x="505" y="53" class="d11-ct">Recursos · art. 157.1</text>
  <text x="360" y="88" class="d11-s">a) Impuestos cedidos y recargos</text>
  <text x="360" y="110" class="d11-s">b) Impuestos, tasas y contribuciones propias</text>
  <text x="360" y="132" class="d11-s">c) Transferencias del Fondo de Compensación</text>
  <text x="360" y="154" class="d11-s">d) Rendimientos de patrimonio</text>
  <text x="360" y="176" class="d11-s">e) Operaciones de crédito</text>
  <line x1="270" y1="160" x2="340" y2="110" class="d11-l"/>
  <rect x="340" y="220" width="330" height="84" rx="8" fill="#e8f5ee" stroke="#2d8659" stroke-width="1.5"/>
  <text x="505" y="248" class="d11-ct" style="fill:#1f5e3f">Fondo de Compensación · art. 158.2</text>
  <text x="505" y="272" class="d11-s" text-anchor="middle">Corrige desequilibrios interterritoriales</text>
  <text x="505" y="290" class="d11-s" text-anchor="middle">Lo distribuyen las Cortes Generales</text>
  <line x1="160" y1="212" x2="160" y2="262" class="d11-l"/>
  <line x1="160" y1="262" x2="340" y2="262" class="d11-l"/>
</svg>
```

---

## D12 · Madrid: los tres niveles en la ciudad

**Sección**: § 11 — Madrid
**Propósito**: Situar Estado, Comunidad de Madrid y Ayuntamiento.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="Los tres niveles territoriales en Madrid: el Estado por la capitalidad, la Comunidad de Madrid uniprovincial y el Ayuntamiento de Madrid de régimen especial">
  <style>
    .d12-b{stroke-width:1.5}
    .d12-h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d12-s{font:11px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d12-n{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="120" y="24" width="460" height="64" rx="8" fill="#0055a0" class="d12-b"/>
  <text x="350" y="50" class="d12-h">ESTADO — capital del Estado</text>
  <text x="350" y="72" class="d12-s">Madrid es sede de las instituciones del Estado (capitalidad)</text>
  <rect x="120" y="116" width="460" height="64" rx="8" fill="#2d8659" class="d12-b"/>
  <text x="350" y="142" class="d12-h">COMUNIDAD DE MADRID</text>
  <text x="350" y="164" class="d12-s">CA uniprovincial · art. 144.a) CE · EA: LO 3/1983</text>
  <rect x="120" y="208" width="460" height="76" rx="8" fill="#e89822" class="d12-b"/>
  <text x="350" y="234" class="d12-h">AYUNTAMIENTO DE MADRID</text>
  <text x="350" y="256" class="d12-s">Municipio de RÉGIMEN ESPECIAL</text>
  <text x="350" y="274" class="d12-s">Ley 22/2006 de Capitalidad y de Régimen Especial</text>
  <text x="350" y="304" class="d12-n" style="font-style:italic">Tres administraciones conviven en el territorio de la ciudad de Madrid</text>
</svg>
```
