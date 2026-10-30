<a id="inicio"></a>

<div align="center">

# Tu primera página web

### De una idea a una página con HTML y CSS

**Aprende · Experimenta · Crea**

![HTML5](https://img.shields.io/badge/HTML5-Estructura-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Estilo-1572B6?style=for-the-badge&logo=css&logoColor=white)
![Duración planificada](https://img.shields.io/badge/Plan-60_minutos-334155?style=for-the-badge)
![Modalidad](https://img.shields.io/badge/Modalidad-100%25_online-0F766E?style=for-the-badge)

Un navegador. Cinco lecciones. Tu primera creación para la web.

[**Comenzar**](#primeros-pasos) · [**Ver las lecciones**](#lecciones) · [**Proyecto final**](#proyecto) · [**Repositorio**](https://github.com/AGROFLET/webdev-course-nexaweb)

</div>

---

Curso introductorio para estudiantes de secundaria de **12 a 17 años**, sin experiencia previa en programación. Construirás una página de perfil ficticio mientras aprendes a organizar contenido con HTML y darle estilo con CSS.

**Duración planificada:** 60 minutos, distribuidos en cinco lecciones de aproximadamente 12 minutos. La duración real se completará después de editar los videos.

**Prerrequisitos:** ninguno. Solo necesitas un navegador y conexión a Internet. No debes instalar programas ni utilizar una terminal.

**Repositorio público:** [AGROFLET/webdev-course-nexaweb](https://github.com/AGROFLET/webdev-course-nexaweb).

> [!IMPORTANT]
> **Material en preparación.** los ejemplos iniciales y resueltos están preparados. Los videos, enlaces a prácticas precargadas, duración real y evidencias de participación están pendientes de incorporación. Este documento es el plan del curso; los campos `[PENDIENTE]` deben completarse antes de la entrega.

## Explora el curso

[Aprendizajes](#aprendizajes) · [Primeros pasos](#primeros-pasos) · [Lecciones](#lecciones) · [Ayuda](#ayuda) · [Proyecto](#proyecto) · [Archivos](#archivos) · [Recursos](#recursos) · [Equipo](#equipo)

```text
01  DESCUBRE       02  ORGANIZA       03  AÑADE        04  DISEÑA       05  CREA
    La web    →       HTML      →       Contenido →      CSS     →      Tu perfil
    12 min            12 min            12 min           12 min         12 min
```

**Tiempo planificado: 5 × 12 minutos = 60 minutos.** Puedes avanzar a tu ritmo y repetir cada práctica.

<a id="aprendizajes"></a>

## Lo que vas a lograr

Al finalizar podrás:

1. Explicar la diferencia entre contenido HTML y presentación CSS.
2. Reconocer etiquetas, elementos y atributos, y distinguir `head` de `body`.
3. Organizar una página con encabezados, párrafos y secciones.
4. Añadir listas, imágenes con texto alternativo y enlaces.
5. Aplicar selectores, colores, tipografía, márgenes, relleno y bordes.
6. Personalizar una página y corregir errores básicos observando la vista previa.

<a id="primeros-pasos"></a>

## Empieza en tu navegador

Las demostraciones se realizan exclusivamente en un **editor online gratuito**. No necesitas WebStorm, VS Code, Node.js ni otros programas instalados.

1. Abre el enlace de práctica precargada de la lección. Esos enlaces se incorporarán en cada sección y en las descripciones de YouTube.
2. Mientras se publican, puedes abrir un editor online y copiar los ejemplos desde GitHub: `html.txt` al archivo o panel HTML y `css.txt` al archivo o panel CSS.
3. En el editor de paneles separados, pega solo el contenido de `body` en HTML. Si el editor muestra un archivo completo `index.html`, conserva `<!DOCTYPE html>`, `html`, `head` y `body`, y pega el fragmento dentro de `body`.
4. Si trabajas con archivos separados, guarda el CSS en `style.css` y comprueba que `head` contiene `<link rel="stylesheet" href="./style.css">`.
5. Observa la vista previa, realiza el reto y compara tu resultado con `completed-examples` después de intentarlo.

**Opciones de editor mencionadas en el enunciado:** [CodePen](https://codepen.io/pen/), [JSFiddle](https://jsfiddle.net/) y [Replit](https://replit.com/). Antes de publicar las prácticas, el equipo debe comprobar cuál permite el recorrido gratuito previsto y qué pasos de acceso necesita. No se afirma que todos funcionen sin cuenta.

Los archivos `vista-previa.html` reúnen el HTML y CSS en una página completa de consulta. El curso no exige descargarlos ni abrir archivos locales.

<a id="lecciones"></a>

## Tu ruta de aprendizaje

La planificación original reserva aproximadamente cinco minutos para explicación visual y siete para demostración. Se propone integrar preguntas, pausas y comprobación dentro de esos doce minutos, evitando una exposición larga sin práctica.

<a id="leccion-01"></a>

### 01 · La web a nuestro alrededor — 12 minutos

**Objetivo:** reconocer qué es una página web y crear un título y un párrafo.

**Conceptos:** navegador, sitio web y página web; HTML organiza contenido y CSS controla su presentación. HTML es un lenguaje de marcado y CSS un lenguaje de estilos.

<details>
<summary>⏱️ Guía de ritmo para esta lección</summary>

0–2, explorar una página conocida; 2–5, explicar contenido y estilo con una analogía visual; 5–9, escribir `h1` y `p`; 9–11, pausa de práctica; 11–12, comprobar y conectar con la siguiente lección.

</details>

- 🎬 **Ver la lección · YouTube no listado:** [PENDIENTE: enlace real].
- 💻 **Abrir la práctica precargada:** [PENDIENTE: enlace real].
- ⏱️ **Duración real del video:** [PENDIENTE].
- 📂 **Punto de partida:** [HTML](starter-files/leccion-01/html.txt) · [CSS](starter-files/leccion-01/css.txt).
- 🔎 **Comparar con la solución:** [HTML](completed-examples/leccion-01/html.txt) · [CSS](completed-examples/leccion-01/css.txt).

> [!TIP]
> **Pausa y prueba:** cambia el título y escribe una frase sobre algo que te gustaría aprender. Utiliza datos ficticios.
>
> **Lo conseguiste si…** aparecen un encabezado y un párrafo; puedes señalar qué etiqueta genera cada uno.

[Volver a la ruta ↑](#lecciones)

---

<a id="leccion-02"></a>

### 02 · HTML: la estructura — 12 minutos

**Objetivo:** organizar el contenido con jerarquía y secciones.

**Conceptos:** etiqueta de apertura y cierre, elemento, atributo, anidamiento, `main`, `section`, `h1`, `h2` y `p`. Explicar en pantalla la estructura `<!DOCTYPE html>`, `html`, `head` y `body`, aunque el editor gestione parte de ella automáticamente. Mostrar `lang="es"` y `meta charset="UTF-8"` en un documento completo de referencia.

<details>
<summary>⏱️ Guía de ritmo para esta lección</summary>

0–2, recuperar el resultado anterior; 2–5, explicar estructura y etiquetas; 5–9, construir el perfil; 9–11, pausa de práctica; 11–12, revisar anidamiento y jerarquía.

</details>

- 🎬 **Ver la lección · YouTube no listado:** [PENDIENTE: enlace real].
- 💻 **Abrir la práctica precargada:** [PENDIENTE: enlace real].
- ⏱️ **Duración real del video:** [PENDIENTE].
- 📂 **Punto de partida:** [HTML](starter-files/leccion-02/html.txt) · [CSS](starter-files/leccion-02/css.txt).
- 🔎 **Comparar con la solución:** [HTML](completed-examples/leccion-02/html.txt) · [CSS](completed-examples/leccion-02/css.txt).

> [!TIP]
> **Pausa y prueba:** añade una sección «Lo que quiero aprender» con un encabezado `h2` y un párrafo.
>
> **Lo conseguiste si…** hay un título principal, subtítulos coherentes y etiquetas correctamente anidadas. El contenido visible está dentro de `body`.

[Volver a la ruta ↑](#lecciones)

---

<a id="leccion-03"></a>

### 03 · HTML: el contenido — 12 minutos

**Objetivo:** incorporar una lista, una imagen accesible y un enlace.

**Conceptos:** `ul`, `li`, `img`, `a` y atributos `src`, `alt` y `href`. La imagen presenta contenido y el enlace permite navegar: añadirlos no convierte la página en una aplicación con lógica JavaScript.

<details>
<summary>⏱️ Guía de ritmo para esta lección</summary>

0–2, observar el perfil; 2–5, explicar elementos y atributos; 5–9, añadir contenido; 9–11, pausa para personalizar; 11–12, probar el enlace y revisar el texto alternativo.

</details>

- 🎬 **Ver la lección · YouTube no listado:** [PENDIENTE: enlace real].
- 💻 **Abrir la práctica precargada:** [PENDIENTE: enlace real].
- ⏱️ **Duración real del video:** [PENDIENTE].
- 📂 **Punto de partida:** [HTML](starter-files/leccion-03/html.txt) · [CSS](starter-files/leccion-03/css.txt).
- 🔎 **Comparar con la solución:** [HTML](completed-examples/leccion-03/html.txt) · [CSS](completed-examples/leccion-03/css.txt).

> [!TIP]
> **Pausa y prueba:** personaliza tres pasatiempos ficticios y explica qué cambiaría si modificas `href` o `src`.
>
> **Lo conseguiste si…** la lista muestra tres elementos, la imagen tiene `alt` descriptivo y el enlace abre el destino previsto.

[Volver a la ruta ↑](#lecciones)

---

<a id="leccion-04"></a>

### 04 · CSS: dale estilo — 12 minutos

**Objetivo:** aplicar estilos generales y crear una tarjeta centrada.

**Conceptos:** selector, propiedad y valor; selectores de etiqueta y clase; `background-color`, `color`, `font-family`, `line-height`, `max-width`, `margin`, `padding`, `border` y `border-radius`.

<details>
<summary>⏱️ Guía de ritmo para esta lección</summary>

0–2, comparar una página con y sin CSS; 2–5, explicar reglas y clases; 5–9, aplicar estilos; 9–11, pausa para experimentar; 11–12, comprobar y resolver un selector que no coincide.

</details>

**Paso importante:** el HTML inicial contiene `<main>`. Antes de aplicar `.tarjeta`, cámbialo a `<main class="tarjeta">`. El punto pertenece al selector CSS; el valor del atributo HTML es `tarjeta`, sin punto. La solución de esta lección ya incluye ese cambio.

- 🎬 **Ver la lección · YouTube no listado:** [PENDIENTE: enlace real].
- 💻 **Abrir la práctica precargada:** [PENDIENTE: enlace real].
- ⏱️ **Duración real del video:** [PENDIENTE].
- 📂 **Punto de partida:** [HTML](starter-files/leccion-04/html.txt) · [CSS](starter-files/leccion-04/css.txt).
- 🔎 **Comparar con la solución:** [HTML](completed-examples/leccion-04/html.txt) · [CSS](completed-examples/leccion-04/css.txt).

> [!TIP]
> **Pausa y prueba:** cambia el fondo, el color del título y el borde; conserva texto legible.
>
> **Lo conseguiste si…** se observa la tarjeta centrada, la clase coincide con el selector y puedes distinguir `margin` de `padding`.

[Volver a la ruta ↑](#lecciones)

---

<a id="leccion-05"></a>

### 05 · Tu primera página web — 12 minutos

**Objetivo:** integrar lo aprendido, personalizar el perfil y detectar errores frecuentes.

**Conceptos:** `header`, `footer`, clases, jerarquía de títulos y estado `:hover`. Mostrar que el enlace también debe poder utilizarse con el teclado y que la página debe mantenerse legible al reducir la vista previa.

<details>
<summary>⏱️ Guía de ritmo para esta lección</summary>

0–2, presentar el objetivo final; 2–5, explicar las mejoras; 5–9, completar el perfil; 9–11, pausa de revisión y corrección; 11–12, comprobar el resultado y proponer próximos pasos.

</details>

- 🎬 **Ver la lección · YouTube no listado:** [PENDIENTE: enlace real].
- 💻 **Abrir la práctica precargada:** [PENDIENTE: enlace real].
- ⏱️ **Duración real del video:** [PENDIENTE].
- 📂 **Punto de partida:** [HTML](starter-files/leccion-05/html.txt) · [CSS](starter-files/leccion-05/css.txt).
- 🔎 **Comparar con la solución:** [HTML](completed-examples/leccion-05/html.txt) · [CSS](completed-examples/leccion-05/css.txt).

> [!TIP]
> **Pausa y prueba:** presenta un perfil ficticio con tus propios textos y colores; corrige a propósito un nombre de clase incorrecto y comprueba cómo cambia el resultado.
>
> **Lo conseguiste si…** la página integra encabezado, presentación, lista, imagen y enlace; conserva legibilidad en una vista estrecha y el enlace es accesible mediante Tab y Enter.

[Volver a la ruta ↑](#lecciones)

---

**Duración total real de los cinco videos:** [PENDIENTE: sumar después de la edición; objetivo aproximado de 60 minutos]. Las pausas que haga el estudiante pueden ampliar el tiempo de aprendizaje.

<a id="ayuda"></a>

## ¿Algo no funciona?

<details>
<summary>No aparece el contenido</summary>

revisa que lo hayas colocado en HTML o dentro de `body`, y actualiza la vista previa si tu editor lo requiere.

</details>

<details>
<summary>El CSS no cambia nada</summary>

revisa que se encuentre en el panel CSS o en `style.css` correctamente enlazado. Comprueba que `.tarjeta` corresponda a `class="tarjeta"`.

</details>

<details>
<summary>Una regla no se aplica</summary>

revisa llaves, dos puntos y punto y coma.

</details>

<details>
<summary>La estructura cambia inesperadamente</summary>

comprueba el cierre y anidamiento de etiquetas. `img` es un elemento vacío: no necesita `</img>`.

</details>

<details>
<summary>No carga una imagen</summary>

comprueba la URL de `src` y tu conexión. Conserva un `alt` que describa el contenido.

</details>

<details>
<summary>El enlace no abre el destino</summary>

revisa `href`, comillas y dirección completa.

</details>

<details>
<summary>Texto difícil de leer</summary>

evita colores con poco contraste y fuentes demasiado pequeñas.

</details>


<a id="proyecto"></a>

## Tu reto final

**El desafío:** transforma el ejemplo de Alex en un perfil ficticio con tus propias ideas.

Tu página debe incluir:

- Un encabezado principal y una presentación.
- Una sección «Sobre mí» y una lista de pasatiempos.
- Una imagen de ejemplo con texto alternativo y un enlace descriptivo.
- Una tarjeta centrada con colores, tipografía, espacio interior y bordes.

**Autoevaluación:** explica para qué sirven HTML y CSS; identifica una etiqueta, un atributo y un selector; cambia una regla y predice su efecto; encuentra y corrige un error; prueba el enlace y la vista estrecha.

> [!NOTE]
> **Crea con datos ficticios.** No publiques apellidos reales, colegio, dirección, teléfono, ubicación u otros datos personales. No necesitas usar fotografías propias.

<a id="archivos"></a>

## Encuentra cada archivo

```text
webdev-course-nexaweb/
├── README.md
├── starter-files/
│   └── leccion-01/ ... leccion-05/
│       ├── html.txt
│       ├── css.txt
│       └── vista-previa.html
├── completed-examples/
│   └── leccion-01/ ... leccion-05/
│       ├── html.txt
│       ├── css.txt
│       └── vista-previa.html
└── scripts/
    └── .gitkeep
```

`starter-files` contiene el punto de partida; `completed-examples`, el resultado de referencia. Los archivos CSS de las primeras tres lecciones están vacíos intencionalmente. `scripts` se conserva con `.gitkeep` porque este curso no utiliza JavaScript ni scripts de instalación. Los guiones de narración podrán incorporarse allí cuando se elaboren.

<a id="recursos"></a>

## Sigue explorando

- [MDN: HTML](https://developer.mozilla.org/es/docs/Web/HTML).
- [MDN: CSS](https://developer.mozilla.org/es/docs/Web/CSS).
- [MDN: aprender desarrollo web](https://developer.mozilla.org/es/docs/Learn_web_development).

<a id="equipo"></a>

## Elaboración en equipo

Esta sección identifica a los responsables académicos del material. Los ejemplos y videos deben conservarse sin branding ni referencias a sus autores.

- **Universidad:** Universidad Peruana de Ciencias Aplicadas.
- **Carrera:** Ingeniería de Software.
- **Período:** 202620.
- **Curso:** 1ASI0730 Aplicaciones Web.
- **NRC:** 16127.
- **Organización de GitHub:** AGROFLET.
- **Nombre del equipo para este curso:** [PENDIENTE: confirmar denominación; el repositorio existente utiliza nexaweb].
- **Líder del equipo:** [PENDIENTE: nombre real].
- **Fecha de entrega:** [PENDIENTE: fecha según el horario de la semana 12].

### Integrantes

- Alca Morán, César Alejandro — U20241F027.
- Centeno León, Adriano Samir — U20241D920.
- Rivas Méndez, Bernie Aarón — U20241F109.
- Rivas Castillo, Christoper Steven — U202323551.
- Tello Lima, Jose Alejandro — U202421618.

La lista corresponde al equipo documentado de AGROFLET; confirmar que sea también el equipo de este trabajo complementario.

### Resumen y evidencias de colaboración

**Material disponible:** ejemplos iniciales y resueltos para cinco lecciones, con HTML, CSS y vistas de referencia. Este README desarrolla el plan a partir de esos materiales. No acredita por sí mismo grabación, publicación o participación individual.

**Resumen del trabajo realizado en equipo:** [PENDIENTE: registrar reuniones, decisiones, distribución real de tareas, revisión cruzada y mejoras realizadas].

**Responsabilidades y evidencias por integrante:** [PENDIENTE: nombres, actividades efectivamente realizadas y enlaces a commits o Pull Requests]. No asignar aportes ni reconstruir un historial de trabajo que no ocurrió.

El líder elaborará el informe de participación en Word y PDF, usando las calificaciones previstas en el Anexo B: 20, 16, 13, 07 o 00, según la participación real.

<details>
<summary><strong>Control de publicación y entrega · para el equipo</strong></summary>

### Comprobación antes de entregar

- [ ] Publicar las carpetas y este README en el repositorio público.
- [ ] Sustituir todos los campos `[PENDIENTE]` con información comprobable.
- [ ] Grabar y publicar cinco videos no listados de 5 a 15 minutos cada uno; verificar un total aproximado de 60 minutos.
- [ ] Incluir narración, texto legible, anotaciones y pausas para practicar.
- [ ] Revisar cada práctica en un editor online gratuito y enlazarla también en la descripción del video.
- [ ] Comprobar contenido, enlaces, imagen y estilos antes de grabar, incluyendo el paso de `.tarjeta`.
- [ ] Verificar que no aparezcan nombres o branding de autores en el video o el código.
- [ ] Registrar los aportes reales del equipo mediante commits y evidencias de colaboración.
- [ ] Exportar este plan a PDF y revisar que sus enlaces funcionen.
- [ ] Entregar el informe de participación en DOCX y PDF y los artefactos correspondientes.

**Nombre del PDF del plan:** `upc-pre-202620-1asi0730-16127-Agroflet-course-plan.pdf`.

**Nombre del informe de participación:** `upc-pre-202620-1asi0730-16127-Agroflet-course-plan-performance.docx` y su versión `.pdf`, siguiendo el código del curso y el Anexo B. Si el docente exige otra denominación del equipo/startup, ajustar el segmento correspondiente.


</details>

---

<div align="center">

**Primero lo entiendes. Después lo pruebas. Finalmente lo haces tuyo.**

[Volver al inicio ↑](#inicio) · [Comenzar la lección 01 →](#leccion-01)

</div>
