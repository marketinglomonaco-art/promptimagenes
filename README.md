# promptimagenes

Generadores de prompts de imagen de LOMONACO para Magnific (Nano Banana Pro), con la imagen corporativa del manual de marca.

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | Portada con enlaces a los generadores |
| `instantaneas.html` | Generador de imágenes LOMONACO: fotos con personas: quién, qué hace, plano, hora, percepción de valor, modelo de colchón y base |
| `ficha-producto.html` | Fichas de producto del colchón en set neutro, 2, 4 o 6 imágenes, por modelo |
| `imagnes-lm.html` | Primer generador "Luz de casa" |
| `instantaneas-camara.html` | Versión guardada con el plano de cámara en planta |

Cada archivo es una página HTML independiente. Con GitHub Pages activo: https://marketinglomonaco-art.github.io/promptimagenes/

## Versión activa

`instantaneas.html` es la versión de las 08:20 del 10/11, la que mejor resultado dio: dirección de arte, escena y producto en un solo prompt, con selector de plano y objetivo. `instantaneas-camara.html` guarda la versión con el plano de cámara en planta, por si se quiere recuperar.

## Corregir el colchón de una imagen ya generada

En el generador, la sección "Corregir el colchón" crea un prompt solo con los errores marcados. En Magnific: un segundo generador con la imagen buena conectada como entrada, las referencias del colchón y ese texto. El prompt principal no cambia.

## Anatomía del colchón (regla fija en los prompts)

- Forma: delante y detrás son los lados cortos; los laterales son los largos. Unos 30 cm de alto, con pillow top.
- Capas: arriba, pillow top con banda de acolchado vertical entre dos vivos; abajo, panel de jacquard blanco.
- Tapa: capitoné en rejilla de cojines redondos.
- Delante: nombre del modelo en versalitas sobre el logo LOMONACO, bordados en granate y centrados. Siempre los pies de la cama.
- Detrás: liso, sin texto. Cabecero y almohadas.
- Laterales: sin texto. Dos asas horizontales, con un cuadrado con X en cada extremo y ribete granate; la asa más cercana al frente lleva la M bordada.
- Cinta: una sola, granate con LOMONACO en crudo, en diagonal en la esquina derecha de delante.
- Color: todo blanco; el granate solo en bordado, cinta, ribetes de las asas y M (y el vivo en el Gran Natura).

## Errores que no se pueden repetir

- La cinta nunca en la esquina izquierda: siempre en la derecha de delante, aunque la izquierda sea la que mira a cámara.
- Nunca LOMONACO ni el nombre del modelo bordados en un lateral.
- Nunca asas en la parte de delante.
- El pillow top va cosido al colchón: nunca un topper suelto encima.
- Nunca inventar el tejido ni el capitoné: se copian de las referencias.
- Si una manta o una sábana tapa parte del colchón, no pasa nada.
- Texto siempre real: NATURA LÁTEX y LOMONACO letra a letra. Si no sale nítido, mejor tapado que inventado.
- Cámara solo donde hay referencia: frente, esquina delantera derecha, lateral derecho o desde arriba.
- Izquierda y derecha del colchón: siempre vistas desde los pies de la cama mirando al cabecero.
- La gente puede tumbarse en cualquier sentido, pero el colchón nunca gira: el frente con el texto siempre a los pies.
- Si una imagen es buena salvo el colchón: botón "Corregir colchón" y edición en Magnific con las mismas referencias.

## Reglas de fotografía del manual

Natural y sin filtros, sin viñetas, sin flash ni focos, nadie posa ni mira a cámara, luz de ventana o de lámpara.
