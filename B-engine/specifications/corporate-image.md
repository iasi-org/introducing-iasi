# Corporate Image

## Metadata

| Field | Value |
|---|---|
| Type | specification |
| Template | visual |
| Status | draft |
| Sources | `A-inputs/externals/corporate-image.qmd`, `A-inputs/externals/business-case.qmd`, `A-inputs/internal/htmlslides.md` |

## Purpose

Definir la identidad visual que utilizará **Introducing IASI**.

No existe una imagen corporativa predefinida que deba aplicarse a la presentación, por lo que el proyecto necesita establecer un sistema visual coherente que permita construir sus slides sin tomar decisiones gráficas independientes en cada una de ellas.

La identidad debe apoyar una presentación técnica, profesional, limpia y fundamentalmente visual, manteniendo el contenido y el lenguaje visual bajo control de IASI.

## Scope

Esta especificación aplica a la identidad visual de **Introducing IASI**, incluyendo sus slides, diagramas y elementos gráficos asociados.

Debe proporcionar un lenguaje suficientemente definido para que nuevas slides puedan construirse de forma coherente sin rediseñar la presentación en cada ocasión.

Esta especificación no establece una identidad corporativa general para todo el ecosistema IASI.

La identidad definida podrá reutilizarse o evolucionar posteriormente hacia una identidad más amplia si existe una decisión explícita para ello.

## Requirements

### Visual identity

La presentación deberá disponer de una identidad visual propia y reconocible.

La identidad deberá:

- transmitir un carácter técnico y profesional;
- favorecer claridad y comprensión antes que ornamentación;
- mantener una estética limpia;
- permitir que las ideas y diagramas sean los elementos principales de la slide;
- evitar una apariencia determinada por estilos predeterminados del renderer utilizado.

### Typography

La identidad deberá definir:

- familia o familias tipográficas;
- jerarquía entre títulos, subtítulos, texto, etiquetas y elementos auxiliares;
- tamaños o escalas relativas;
- pesos y variantes permitidos;
- criterios de uso consistentes entre slides.

La tipografía deberá resultar legible en condiciones normales de presentación y no depender de grandes cantidades de texto para transmitir el contenido.

### Color

La identidad deberá definir:

- paleta principal;
- colores secundarios cuando sean necesarios;
- colores destinados a énfasis, relaciones o estados;
- colores de fondo;
- combinaciones permitidas de texto y fondo.

El uso del color deberá ser semánticamente consistente y mantener contraste suficiente para la lectura.

### Composition

La identidad deberá establecer principios para:

- márgenes;
- alineación;
- separación entre elementos;
- jerarquía visual;
- distribución del espacio;
- densidad máxima razonable de información;
- relación entre texto y elementos gráficos.

Las slides deberán favorecer el espacio visual y evitar composiciones propias de documentos o páginas web.

### Graphic language

Deberá definirse un tratamiento coherente para:

- cajas y contenedores;
- líneas y conectores;
- flechas;
- diagramas;
- iconos;
- imágenes, cuando se utilicen;
- resaltados;
- etiquetas y anotaciones.

Los diagramas deberán expresar relaciones reales del modelo presentado y no utilizarse como decoración.

Los elementos gráficos deberán ser simples siempre que una composición sencilla permita comunicar correctamente la idea.

### Consistency

La identidad deberá permitir mantener una apariencia coherente entre, al menos:

- portada;
- slides de concepto;
- slides narrativas;
- slides con diagramas;
- slides de transición o sección;
- slide final.

Una nueva slide deberá poder construirse aplicando las reglas definidas sin necesitar decisiones visuales fundamentales adicionales.

### Readability and accessibility

La identidad deberá:

- proporcionar contraste suficiente entre texto y fondo;
- conservar una jerarquía visual inequívoca;
- utilizar tamaños adecuados para presentación;
- evitar depender exclusivamente del color para transmitir información;
- mantener legibles textos, etiquetas y diagramas a distancia de presentación.

## Constraints

La identidad visual:

- no deberá estar determinada por HTMLSlides;
- no deberá depender conceptualmente de características exclusivas de un renderer;
- deberá poder reproducirse mediante otra tecnología de presentación;
- no deberá convertir la presentación en una página web o documento proyectado;
- deberá favorecer poco texto por slide;
- deberá permitir una narrativa progresiva;
- deberá mantener separados el lenguaje visual de IASI y la infraestructura utilizada para materializarlo.

HTMLSlides podrá implementar la identidad, pero no definirla.

## Acceptance Criteria

La especificación de identidad visual se considerará satisfecha cuando:

1. exista una definición explícita de tipografía;
2. exista una paleta de color definida;
3. existan reglas de composición y espaciado;
4. exista un lenguaje gráfico definido para diagramas y elementos visuales;
5. pueda construirse una portada coherente con la identidad;
6. pueda construirse una slide predominantemente textual sin introducir nuevas decisiones visuales fundamentales;
7. pueda construirse una slide con diagrama aplicando las mismas reglas;
8. dos slides creadas independientemente a partir de esta especificación resulten visualmente coherentes;
9. la identidad pueda describirse sin hacer referencia necesaria a HTMLSlides;
10. el resultado sea legible y utilizable en condiciones normales de presentación.

## Sources

- `A-inputs/externals/corporate-image.qmd`
- `A-inputs/externals/business-case.qmd`
- `A-inputs/internal/htmlslides.md`
- `EDR-20013`