**# 1. ¿Qué es HTML y cuál es su función en la web?** 

  R// HTML (HyperText Markup Language o "lenguaje de marcado de hipertexto")
  es el lenguaje estándar utilizado para crear y estructurar páginas web. 
  Funciona mediante etiquetas que definen el contenido y los elementos de
  una página, como texto, imágenes, enlaces, vídeos y otros recursos multimedia. 
  
  La función principal de HTML en la web es estructurar y organizar el contenido
  de las páginas para que los navegadores puedan interpretarlo y mostrarlo correctamente. 
  Actúa como el "esqueleto" o la base fundamental de cualquier sitio web.
  
--------------------------------------------------------------------------------------------------------------------------------------

**# 2. ¿Que es una etiqueta HTML y menciona las etiquetas más comunes?**

  R// Las etiquetas HTML (o "tags") son códigos utilizados para marcar el texto
  de una página web y dar instrucciones al navegador sobre cómo mostrarlo. 
  Son el lenguaje que estructura y define el contenido en un documento HTML.
  
  **Una etiqueta HTML contiene tres partes básicas:**
  
	  - Etiqueta de apertura: <etiqueta>
	  - Contenido: el texto o elemento
	  - Etiqueta de cierre: </etiqueta>

  ## Etiquetas HTML más comunes
  
  **### Estructura básica:**
  
	  - <!DOCTYPE> - Especifica la versión de HTML
	  - <html> - Define el inicio y final de la página
	  - <head> - Sección de encabezado (metadatos)
	  - <title> - Título de la página
	  - <body> - Contenido visible de la página

  **### Texto y formato:**
  
	  - <h1> a <h6> - Encabezados (títulos de diferentes niveles)
	  - <p> - Párrafo
	  - <strong> - Texto en negrita
	  - <em> - Énfasis (cursiva)
	  - <br> - Salto de línea

  **### Enlaces e imágenes:**
  
	  - <a> - Enlaces/hipervínculos
	  - <img> - Imágenes

  **### Listas:**
  
	  - <ul> - Lista desordenada
	  - <ol> - Lista ordenada
 	  - <li> - Elemento de lista

**### Organización:**

	  - <div> - División o contenedor
	  
--------------------------------------------------------------------------------------------------------------------------------------

**# 3. ¿Que es un atributo de una etiqueta HTML y menciona los más comunes?**

  R// Un atributo en HTML es una pieza de información adicional que se añade a
  una etiqueta (elemento) para configurar su comportamiento o aportar datos extra. 
  Los atributos se escriben dentro de la etiqueta de apertura, en forma de pares 
  nombre="valor" (aunque algunos atributos booleanos pueden aparecer sin valor). 
  Ejemplo simple: <input type="text" placeholder="Tu nombre"> — aquí type y placeholder son atributos.

**### Atributos mas comunes:**

	  - id: identificador único del elemento.
	  - class: clases para aplicar estilos CSS o seleccionar con JavaScript.
	  - style: estilos CSS en línea.
	  - title: texto informativo que aparece como tooltip.
	  - hidden: oculta el elemento.
	  - href: URL de destino (en <a>, <link>).
	  - src: ruta del recurso embebido (en <img>, <script>, <iframe>, etc.).
	  - name: nombre del campo enviado al servidor.
	  - type: tipo de input (text, password, email, submit, etc.).
	  - value: valor inicial o enviado.
	  
--------------------------------------------------------------------------------------------------------------------------------------

**# 4. ¿Qué es CSS y cómo se utiliza para el diseño web?**

  R// CSS (Cascading Style Sheets) es el lenguaje que controla la presentación visual de documentos
  escritos en HTML (o en otros lenguajes de marcado). Su objetivo es separar la estructura (HTML) 
  de la apariencia (colores, tipografías, tamaños, posiciones, animaciones, etc.), permitiendo diseñar 
  interfaces coherentes y adaptables.

  CSS en el flujo de trabajo separa la apariencia (colores, tipografías, tamaños, espacios, disposición y animaciones)
  de la estructura (HTML).Permitiendo asi adaptar el diseño según el tamaño de pantalla (responsive).
  Facilitar la reutilización y mantenimiento cuando los estilos están organizados en archivos.

**### Cómo se aplica en la práctica (pasos básicos):**

    1. Estructura el HTML (marca los elementos con etiquetas y clases). Ejemplo: <div class="card"><h3>	Título</h3><p>Texto</p></div>
	  2. Crea una hoja de estilos externa y enlázala desde el head: <link rel="stylesheet" 	href="estilos.css">
	  3. Escribe reglas CSS que apunten a selectores (etiquetas, clases, IDs, pseudo-clases). 	
    Ejemplo: .card { padding: 16px; background: #fff; border-radius: 8px; }
	
--------------------------------------------------------------------------------------------------------------------------------------

**# 5. ¿Que es una propiedad en CSS y menciona las propiedades más comunes?**

  R// Una propiedad en CSS es un aspecto de estilo que se aplica a un elemento (o conjunto de elementos) 
  mediante un selector; cada propiedad tiene uno o más valores y se escribe dentro de una regla CSS 
  separando propiedad y valor con dos puntos (por ejemplo: color: red;).
  Las propiedades, junto con selectores y valores, permiten dar formato y estilo visual al HTML.

**### Propiedades más comunes:**

	  - Listas: controlan el tipo de marcador, imágenes o colores de listas ordenadas y desordenadas y el 	estilo de sus ítems.
	  - Fuente (font): definen la tipografía, tamaño, estilo (normal/itálica), peso, etc.
	  - Bordes (border): permiten configurar el grosor, estilo y color de los bordes de elementos (tablas, 	imágenes, cajas, etc.).
	  - Texto (text): abarcan color, alineación, espaciado, transformación (mayúsculas/minúsculas), 	decoración, etc.
	  
--------------------------------------------------------------------------------------------------------------------------------------

**# 6. ¿Que es un selector en CSS y cuales tipos existen?**

  R// Un selector en CSS es la primera parte de una regla CSS: es el patrón que indica al navegador 
  qué elemento(s) del HTML serán el sujeto de las declaraciones de estilo. Por ejemplo, en la regla
  h1 { color: blue; }
  el selector es h1 y selecciona los elementos <h1>.

**### Principales tipos de selectores:**

  ####Selector de tipo (elemento):
  
	  - Selecciona elementos por su nombre de etiqueta.
	  - Ejemplo: p { color: red; } — selecciona todos los <p>.

  ####Selector de clase:
  
	  - Selecciona elementos que tienen una clase concreta.
	  - Ejemplo: .box { padding: 1rem; } — selecciona elementos con class="box".

  ####Selector de ID:
  
	  - Selecciona un elemento por su id único.
	  - Ejemplo: #unique { background: yellow; } — selecciona el elemento con id="unique".

  ####Selector universal:
  
	  - Selecciona todos los elementos.
	  - Ejemplo: * { box-sizing: border-box; }

--------------------------------------------------------------------------------------------------------------------------------------

**# 7. ¿Qué es JavaScript y cómo añade la interactividad a las páginas web?**

  R// JavaScript es un lenguaje de programación usado principalmente para añadir comportamiento
  dinámico e interactividad a las páginas web. Originalmente se ejecutaba en el navegador (lado del cliente),
  aunque hoy también se ejecuta en servidores (por ejemplo con Node.js). 
  A continuación resumo cómo funciona y cómo crea interactividad:

  **### Cómo añade interactividad:**
  
	  - El navegador carga la página y construye el DOM (Document Object Model): una representación en 	memoria de los elementos HTML.
	  - El motor JavaScript interpreta/compila y ejecuta el código JS incluido o enlazado en la página.
	  - El código JS escucha eventos (clics, teclas, movimientos del ratón, envío de formularios, carga de 	recursos, etc.).
	  - Cuando ocurre un evento, las funciones asociadas se ejecutan y pueden cambiar el DOM o aplicar 	estilos CSS dinámicamente.
	  - El navegador vuelve a pintar la página con esos cambios, mostrando la interactividad al usuario.
	  
--------------------------------------------------------------------------------------------------------------------------------------

**# 8. ¿Cuáles son los tipos de datos primitivos en Javascript?**

  R// En JavaScript los tipos de datos primitivos son:
  
    - string — cadenas de texto. Ejemplo: let s = "hola";
	  - number — números (enteros y de punto flotante). Ejemplo: let n = 3.14;
	  - bigint — enteros de precisión arbitraria. Ejemplo: let b = 123n;
	  - boolean — true o false. Ejemplo: let flag = true;
	  - undefined — valor que indica ausencia de valor asignado. Ejemplo: let x; // x es undefined
	  - symbol — identificadores únicos e inmutables. Ejemplo: const id = Symbol("miId");
	  - null — representa "ningún valor" (caso especial, considerado primitivo).
--------------------------------------------------------------------------------------------------------------------------------------

**# 9. ¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en Javascript?**
R//
	**### 1. if:**
	
	          - Sintaxis: if (condición) { /* código */ }
	          - Ejecuta el bloque solo si la condición es verdadera (truthy).
	          - Ejemplo: const age = 18; if (age >= 18) { console.log('Eres mayor de edad'); }

  **### 2. if...else y else if:**
  
	        - if...else ejecuta una ruta alternativa cuando la condición es falsa. if (cond) { /* si true / } 	else { / si false */ }
	        - Para más de dos opciones se encadenan else if: if (c1) { ... } else if (c2) { ... } else { ... }

  **### 3. switch:**
  
	        - Sintaxis para comparar un mismo valor con múltiples casos: 
            switch(valor) { case 'a': /* ... / 	break; case 'b': / ... / break; default: / ... */ }
	        - Atención al “fall-through”: si olvidas el break, la ejecución continúa al siguiente case.
	        - Útil cuando comparas muchas alternativas sobre la misma expresión; a veces if/else es más legible.

  **### 4. while (bucle condicional):**
  
	        - while (condición) { /* código */ }
	        - Ejecuta el bloque repetidamente mientras la condición sea true.
	        - Debes cambiar algo dentro del bucle para evitar bucles infinitos.
	        - Ejemplo: imprimir pares hasta 12 let n = 0; while (n <= 12) { console.log(n); n += 2; }

 **### 5. do...while:**
 
	        - do { /* código */ } while (condición);
	        - Ejecuta el bloque al menos una vez y luego evalúa la condición para repetir.
	        - Útil cuando quieres que se ejecute la comprobación después de una primera ejecución
            (por ejemplo, 	pedir input hasta que sea válido).

 **### 6. for (bucle con contador):**
 
	        - Forma compacta cuando conoces o controlas el número de iteraciones: 
            for (let i = 0; i < 10; i++) 	{ /* ... */ } // i inicializa; condición se evalúa cada iteración; expresión final actualiza i
	        - Ejemplo para calcular 2^10: let r = 1; for (let i = 0; i < 10; i++) { r *= 2; } console.log(r); // 	1024

 **## 7. break y continue:**
 
	        - break: sale inmediatamente del bucle (o switch).
	        - continue: salta el resto de la iteración actual y pasa a la siguiente.
        	- Ejemplo: buscar primer número divisible por 7 empezando en 20  
            for (let x = 20; ; x++) { if (x % 7 	=== 0) { console.log(x); break; } }.
			
--------------------------------------------------------------------------------------------------------------------------------------

**# 10. ¿Por qué es importante usar nombres significativos para variables y métodos?**

  R//Por qué importa:
  
	  - Mejoran la legibilidad: permiten entender la intención del código sin analizar cada línea.
	  - Facilitan el mantenimiento: cambios y depuraciones son más seguros y rápidos.
	  - Reducen errores: evitan confusiones sobre unidades o propósitos y previenen usos incorrectos.
	  - Mejoran la colaboración: sirven como contrato implícito entre desarrolladores y agilizan las 	revisiones.
	  - Hacen el código “auto‑documentado”: disminuyen la necesidad de comentarios que se vuelven 	obsoletos.
	  
--------------------------------------------------------------------------------------------------------------------------------------

**# 11. ¿Qué es una variable de entorno y por qué son importantes para Javascript o la programación en general?**

  R// Una variable de entorno es un par clave=valor que el sistema operativo (o el proceso que lanza tu aplicación) 
  pone a disposición del programa en tiempo de ejecución. No forma parte del código fuente: el programa lee esos valores
  cuando se ejecuta.

**### Por qué son importantes:**

	  - Separación de responsabilidades: mantienen la configuración fuera del código (p. ej. URLs, modos 	de ejecución),
      facilitando que el mismo binario/paquete funcione en dev, staging y producción sin 	cambiar código.
	  - Configuración por entorno: permiten cambiar comportamientos (servicios a usar, características 	habilitadas) 
      según el entorno sin redeployar código.
	  - Seguridad de secretos: evitan incrustar claves privadas, tokens o contraseñas en el repositorio; 
      así reducen el riesgo de fuga accidental.
	  - Portabilidad y automatización: facilitan la integración con plataformas de despliegue, 	
      contenedores y orquestadores que inyectan variables a los procesos.
	  
--------------------------------------------------------------------------------------------------------------------------------------

**# 12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?**

  R// Las Herramientas para desarrolladores de Chrome (Chrome DevTools) son un conjunto integrado de utilidades
  en el navegador que permiten inspeccionar, editar y depurar páginas web en tiempo real. 
  Con ellas puedes ver y modificar el DOM y CSS, depurar JavaScript, analizar y reproducir la actividad 
  de red, medir y optimizar el rendimiento (incluyendo métricas web esenciales), investigar problemas
  de memoria, probar funcionalidades de aplicación web, emular sensores/dispositivos y mucho más. 
  DevTools también incluye funciones de asistencia por IA (por ejemplo, sugerencias de código y análisis con Gemini), 
  paneles para rendimiento, red, consola, fuentes, y herramientas especializadas como Lighthouse.

**### Cómo acceder a DevTools:**

	  - Clic derecho sobre la página → “Inspeccionar” (o “Inspect”).
	  - Atajos de teclado:
		    - Windows / Linux: Ctrl + Shift + I o F12.
		    - macOS: ⌘ (Command) + ⌥ (Option) + I o F12 (según configuración).
	  - Menú de Chrome: Menú (tres puntos) → Más herramientas → Herramientas para desarrolladores.
	  
--------------------------------------------------------------------------------------------------------------------------------------


**# 13. ¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?**

  R// En el panel "Elements" de las herramientas de desarrollo puedes inspeccionar la estructura y
  el estilo de una página web para entender y modificar su apariencia y comportamiento en tiempo real.
    - Ver el DOM y resaltar elementos: muestra la estructura HTML de la página y permite resaltar visualmente cualquier elemento seleccionado.
	  - Inspeccionar y editar el HTML: puedes abrir y modificar nodos, atributos y texto directamente dentro del panel.
	  - Inspeccionar y editar CSS: permite ver las reglas CSS aplicadas a un elemento y cambiarlas al instante para probar estilos diferentes.
	  - Ver cambios en tiempo real: los cambios que hagas en HTML o CSS se aplican inmediatamente en la página para comprobar su efecto sin recargar.
	  - Probar y depurar el diseño: facilitas identificar problemas de maquetación y ajustar estilos para corregir el aspecto de componentes.
	  
--------------------------------------------------------------------------------------------------------------------------------------

**# 14. ¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil?**

  R// El panel Console de las herramientas de desarrollo te permite ver los mensajes que genera la página (errores, advertencias, logs) 
  y ejecutar JavaScript en el contexto de la página; es una herramienta clave para depurar, probar y explorar el 
  comportamiento de tu aplicación web en tiempo real.

  **### Qué se puede hacer en la Console:**
  
	  - Ver mensajes del navegador: muestra errores, advertencias, logs y mensajes de depuración.
	  - Ejecutar código JavaScript: puedes escribir y ejecutar expresiones y funciones directamente.
	  - Inspeccionar objetos y estructuras: expande objetos complejos devueltos por el código para 	explorarlos.
	  - Interactuar con elementos seleccionados: usa accesos rápidos 
      (por ejemplo $0 para el elemento 	actualmente inspeccionado) para manipular el DOM.
	  - Filtrar y buscar: filtra por tipo de mensaje (errores, warnings, info) o busca texto dentro del 	registro.
	  Conservar y exportar logs: conserva registros entre recargas o copia/exporta mensajes para análisis.
	  
--------------------------------------------------------------------------------------------------------------------------------------

**# 15. ¿Qué información se puede obtener del panel "Network" y por qué es importante?**

  R// El panel "Network" muestra todas las solicitudes de red que realiza una página web, incluyendo detalles como
  tipo de recurso, método, estado, tamaño y tiempos de carga. Permite ver encabezados, cuerpos de petición 
  y respuesta, y analizar la secuencia y duración de cada solicitud en una línea de tiempo visual (waterfall). 
  Es fundamental para diagnosticar problemas de carga lenta, errores en peticiones, optimizar el tamaño y caché 
  de recursos, depurar APIs, y probar el comportamiento en diferentes  condiciones de red. 
  También permite emular conexiones lentas y controlar la caché para pruebas más precisas.
