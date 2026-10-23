# Fotos instantáneas → PDF

Página web de un solo archivo (`instax-a4.html`) para acomodar fotos en formato Instax, Polaroid y otros tamaños sobre una hoja (A4 por defecto) y exportarlas a PDF listas para imprimir y recortar.

Todo funciona en el navegador. Las fotos **no se suben a ningún servidor**.

## Uso rápido

1. Abre `instax-a4.html` en un navegador moderno (Chrome, Edge, Firefox, Safari).
2. Elige la **plantilla** y el **tamaño de hoja**.
3. Pulsa **Agregar fotos** (puedes seleccionar varias) o arrástralas sobre la hoja. Se rellenan los espacios libres en orden.
4. Reencuadra cada foto arrastrándola dentro de su marco.
5. Pulsa **Descargar PDF**.

## Características

- **Plantillas** de tarjeta:

  | Plantilla | Tarjeta (mm) | Área de foto (mm) |
  |---|---|---|
  | Instax Mini | 54×86 | 46×62 |
  | Instax Cuadradas | 72×86 | 62×62 |
  | Instax Anchas | 108×86 | 99×62 |
  | Polaroid Clásica | 88×107 | 79×79 |
  | Polaroid Spectra | 101×103 | 92×73 (estimada) |
  | Photocard | 55×85 | sin marco |
  | Cuadrada | 62×62 | sin marco |
  | Tira fotomatón | 51×152 | sin marco |
  | Foto carnet | 35×45 | sin marco |
  | Personalizado | a elección | a elección |

- **Tamaños de hoja**: A4 (por defecto), Carta (216×279), Oficio Chile (216×330), A3, papel fotográfico 10×15 cm y 13×18 cm, y hoja personalizada.
- **Acomodo automático**: calcula cuántas tarjetas caben, las centra en la hoja y elige la orientación (vertical u horizontal) que aproveche mejor el espacio. También puedes forzar la orientación.
- **Reencuadre por foto**: arrastra la imagen dentro del marco (recorte tipo "cover").
- **Fondo personalizado por tarjeta**: color o imagen de fondo para el marco de cada foto, blanco por defecto. Hay botones para aplicar el mismo color o la misma imagen a todos los marcos.
- **Pie de foto**: texto en la parte inferior del marco de cada foto (solo con marco). Se escribe directamente en la tarjeta. Se puede elegir fuente (manuscrita, marcador, sencilla, serif, máquina de escribir), tamaño, alineación y color. El color automático usa blanco sobre fondos oscuros y gris oscuro sobre fondos claros. Hay un campo para poner el mismo texto en todas las tarjetas.
- **Modo sin marco**: la foto ocupa toda la tarjeta, con **sangrado** (la foto se extiende un poco más allá de la línea de corte) y **separación** configurable entre tarjetas.
- **Herramientas plegables**: un botón bajo las barras las oculta o las muestra para tener más espacio. Con las barras ocultas queda a la vista un botón para descargar el PDF.
- **Líneas de corte**: opcionales. Con marco se dibuja el contorno de cada tarjeta. Sin marco se dibujan marcas pequeñas en el margen de la hoja, fuera de la foto.

## Opciones de la barra superior

| Opción | Qué hace |
|---|---|
| Plantilla | Tamaño de la tarjeta y de la foto. |
| Hoja | Tamaño del papel. |
| Orientación | Automática, vertical u horizontal. |
| Margen mín. | Espacio libre mínimo en los bordes de la hoja (mm). Bájalo a 0 si tu impresora imprime sin bordes. |
| Líneas de corte | Muestra y exporta guías de corte. |
| Fondo / Color a todas | Aplica el color elegido a todos los marcos (y quita las imágenes de fondo). |
| Imagen a todas | Usa la misma imagen de fondo en todos los marcos. |
| Sin marco | La foto cubre toda la tarjeta. Se activa sola con las plantillas sin marco. |
| Sangrado | Cuánto sobresale la foto de la línea de corte en modo sin marco (mm). Por defecto 1. |
| Separación | Distancia entre líneas de corte de tarjetas vecinas en modo sin marco (mm). Por defecto 4. Mínimo efectivo: el doble del sangrado. |
| Agregar fotos / Vaciar | Carga varias fotos o quita todas. |
| Pie de foto: fuente, tamaño, color, alineación | Estilo común a todos los textos. Con "Color automático" el texto contrasta con el fondo de cada marco. |
| Texto a todas | Escribe el mismo texto en todas las tarjetas. Si el campo está vacío, borra todos los textos. |
| Descargar PDF | Genera el archivo. |

El espacio blanco visible entre dos fotos sin marco es la **separación menos el doble del sangrado**. Con los valores por defecto (4 y 1) quedan 2 mm.

Sobre cada tarjeta, al pasar el mouse:
- Con foto: **↻** reemplaza la imagen y **×** la quita.
- Con marco: aparecen el selector de color, **🖼** (imagen de fondo) y **⟲** (restablecer a blanco).

## Cómo se calcula el acomodo

Para una hoja de ancho `W` y alto `H`, un margen `m`, sangrado `b` y separación `g` (en modo sin marco; con marco `b = g = 0`):

```
columnas = floor((W − 2m − 2b + g) / (ancho_tarjeta + g))
filas    = floor((H − 2m − 2b + g) / (alto_tarjeta + g))
```

Se prueba en vertical y horizontal, y se elige la orientación con más tarjetas (en empate, vertical). El máximo por hoja es 30.

## Exportación a PDF

- El PDF tiene el tamaño exacto de la hoja elegida.
- Las fotos se recortan al área de foto y se incluyen como JPEG de calidad 0,93, a unos 12 píxeles por mm (alrededor de 300 dpi), o menos si la imagen original es más pequeña.
- Las imágenes de fondo se guardan a unos 8 píxeles por mm (alrededor de 200 dpi).
- Los pies de foto se dibujan como imagen dentro del PDF, para respetar la fuente elegida: se ven igual que en pantalla pero no se pueden seleccionar como texto.
- El nombre del archivo sigue el patrón `fotos-<plantilla>-<hoja>.pdf`, por ejemplo `fotos-mini-a4.pdf`.
- Para imprimir con medidas reales, usa **escala 100 %** (sin "ajustar a página") en el diálogo de impresión.

## Requisitos

- Navegador moderno.
- Conexión a internet al abrir la página, porque la librería [jsPDF](https://github.com/parallax/jsPDF) (versión 2.5.1) se carga desde cdnjs y las fuentes Caveat y Permanent Marker desde Google Fonts. Sin conexión, esas dos fuentes se reemplazan por otras similares del sistema. La vista previa funciona sin jsPDF, pero no se podrá descargar el PDF.

### Uso sin conexión

Descarga `jspdf.umd.min.js` de la versión 2.5.1, guárdalo junto al HTML y cambia esta línea:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
```

por:

```html
<script src="jspdf.umd.min.js"></script>
```

## Limitaciones conocidas

- Genera **una sola hoja** por PDF. Si cargas más fotos de las que caben, no se crea una segunda hoja.
- El fondo de cada marco queda asociado a la **posición** en la hoja, no a la foto. Si quitas o cambias una foto, el fondo se conserva. Al cambiar de plantilla o de hoja, las posiciones se reacomodan pero los fondos y fotos siguen la numeración de espacios.
- Las medidas de borde y de área de foto de las plantillas Cuadradas, Anchas, Polaroid Clásica y Spectra son aproximadas. Si no coinciden con tu película real, usa **Personalizado** y ajusta los valores.
- Los pies de foto no están disponibles en el modo sin marco, y el estilo (fuente, tamaño, color, alineación) es común a todas las tarjetas. Como los fondos, cada texto queda asociado a la posición en la hoja y no a la foto.
- No hay zoom ni giro por foto, solo desplazamiento dentro del marco.
- El proyecto no se guarda: al cerrar o recargar la página se pierden las fotos cargadas.

## Personalización

Todo está en el mismo archivo. Para agregar tamaños, edita estos objetos dentro del bloque `<script>`:

- `TEMPLATES`: cada plantilla define `cw`/`ch` (tarjeta), `pw`/`ph` (área de foto), `px`/`py` (borde izquierdo y superior), todo en mm. Agrega `frameless: true` si la foto debe cubrir toda la tarjeta.
- `PAPERS`: cada hoja define `w` y `h` en vertical, en mm.
- `MAXN`: máximo de tarjetas por hoja (30 por defecto).

## Estructura del código

| Parte | Función |
|---|---|
| `TEMPLATES`, `PAPERS` | Datos de plantillas y hojas. |
| `computeLayout()` | Calcula columnas, filas, orientación y posiciones. |
| `rebuild()` | Dibuja la hoja y las tarjetas en pantalla. |
| `render()` | Muestra las fotos y actualiza el contador. |
| `enableDrag()` | Reencuadre por arrastre. |
| `applyBg()` | Aplica el fondo de cada tarjeta. |
| Handler de exportación | Recorta con canvas y genera el PDF con jsPDF. |

## Créditos y licencias

- [jsPDF](https://github.com/parallax/jsPDF): licencia MIT.
- Instax es marca de Fujifilm y Polaroid es marca de Polaroid. Se nombran solo para indicar el tamaño de formato. Este proyecto no está afiliado ni respaldado por ellas.
- Los derechos de las fotos que cargues pertenecen a sus autores.
