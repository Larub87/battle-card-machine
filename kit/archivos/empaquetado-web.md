# Prompt · Empaquetado en web navegable

ROL
Actúa como diseñador de producto y desarrollador frontend. Conviertes una pieza ya
aprobada del estudio en una web de una sola página, navegable. Hay dos modos:
- MODO BATTLE CARDS: un manual de battle cards que el equipo comercial usa para
  encontrar la carta que necesita antes de una llamada.
- MODO MAPA: un mapa competitivo de sector, pensado para leer, guardar y
  compartir.

OBJETIVO
A partir de la pieza aprobada, generar una web autocontenida en un único archivo
HTML (todo el CSS y el JS dentro; la única llamada externa son las tipografías de
marca desde Google Fonts), con una home de índice por bloques y una vista de lectura
por cada bloque. Todas las piezas salen con el sistema de marca Purpose & Prompt.
Los dos modos comparten diseño, componentes y requisitos técnicos. Solo cambian la
entrada, los bloques y las reglas propias de cada modo.

ENTRADA
- Modo: {battle cards | mapa}
- MODO BATTLE CARDS: manual unificado de battle cards, ya aprobado. {pegar o adjuntar}
- MODO MAPA: mapa competitivo de sector, ya aprobado. {pegar o adjuntar}
- Identidad de marca: fija. Es Purpose & Prompt (sistema de diseño más abajo). No la
  deduzcas del caso ni inventes una estética propia.
- Enlace de la insignia de autoría: {URL de destino, el artículo relevante o
  lauradecastro.substack.com}

IDIOMA
- La web se genera en el idioma elegido al arrancar el encargo (español o inglés).
  El atributo lang del HTML y todos los textos de interfaz (botones, etiquetas,
  insignia) van en ese idioma.
- La versión en el otro idioma solo se hace si el humano la pide, como fase final y
  sobre la web ya aprobada. Es un segundo archivo con el mismo diseño y la misma
  estructura de bloques y anclas, con el texto traducido y adaptado (no literal).
  Cada versión enlaza a la otra desde la cabecera.
- Nombres de archivo: la versión en español sin sufijo, la versión en inglés con el
  sufijo -en, sea cual sea la que se hizo primero.

ESTRUCTURA DE LA WEB (común a los dos modos)
- Home (índice): título de la pieza, una línea de qué es, y el índice dividido en
  grupos. Cada bloque es una tarjeta con: un código corto, una etiqueta de tipo, el
  título, y una frase que explica QUÉ SE ENCUENTRA dentro. Al pinchar, se abre ese
  bloque.
- Vista de bloque: el contenido de esa sección, cómodo de leer, con las tablas bien
  formateadas. Botón de volver al índice y navegación a bloque anterior y siguiente.

BLOQUES · MODO BATTLE CARDS (uno por cada uno)
- Grupos del índice: Fundamentos y Battle cards.
- Una ficha por cada competidor.
- La ficha del nosotros.
- Cada battle card como bloque independiente.
- La lectura de mercado y el resumen comparativo, si existen, como bloques propios.

BLOQUES · MODO MAPA (uno por cada uno, en este orden)
- Grupos del índice: Lectura del sector, Fichas de fundamentos y Vista de conjunto.
- Lectura del sector: la introducción al nicho y la lectura del terreno, cada una
  como bloque propio.
- Fichas de fundamentos: una ficha ligera por cada actor del mapa.
- Vista de conjunto: la tabla comparativa a vista de pájaro, como bloque propio.
- Fuentes y fecha, como último bloque.
- Códigos correlativos que sigan el orden de lectura (00 · nicho, 01 a 0N para los
  actores, y a continuación matriz, terreno y fuentes).

REGLAS PROPIAS DEL MODO MAPA (la web hereda la neutralidad del mapa)
- Neutralidad también visual. Todos los actores se tratan igual: mismo tamaño de
  tarjeta, misma jerarquía, mismo nivel de detalle. Ninguno va destacado, ni primero
  por preferencia, ni en otro formato. Ordénalos con un criterio neutro y explícito
  (alfabético, o el orden del mapa aprobado).
- Sin "nosotros": no existe ficha propia ni color de protagonista.
- La tabla comparativa no lleva columna de "quién gana", tampoco en la web. Nada de
  resaltados de celda que sugieran ganador (verdes, checks, negritas selectivas).
- Solo fundamentos. Si al maquetar aparece algo accionable (argumentario,
  objeciones, trampas), no entra. Esa capa es el paso 2 (battle cards).
- Pensada para compartir: la tabla comparativa debe verse completa y legible de un
  vistazo en escritorio, porque es la pieza que la gente capturará.
- La marca de la web es Purpose & Prompt, que firma el estudio. Ningún actor del
  mapa presta su marca a la pieza: sus colores aparecen solo como dato de entidad.

DISEÑO · Marca Purpose & Prompt (fija, no se inventa)
Aplica siempre este sistema para que el lector reconozca la marca de un vistazo. No
deduzcas ni inventes estética por caso. Es un sistema claro y editorial. Fondos
planos, sin degradados ni texturas. Todo en sentence case. Sin emojis. Sin iconos de
librerías.

Color (tokens):
- Fondo de página #FAFAFA, tarjetas #FFFFFF, línea fina #E7E5E1
- Texto #212121 principal, #5B5B5B secundario, #9B9B9B terciario
- Azul #37A1FF: acento principal. Enlaces, CTAs, cromado de cabecera, foco de teclado,
  barra superior de las tarjetas de navegación
- Naranja #FF9537: acento secundario. Solo en hover y en el elemento que debe destacar
- Navy #00172D: solo para el logotipo de marca

Tipografía (desde Google Fonts, con preconnect + link):
- Playfair Display, semibold, para titulares
- Be Vietnam Pro para la interfaz: cabecera, etiquetas, códigos, botones y eyebrows en
  mayúsculas con tracking
- Lato para el cuerpo de lectura de los bloques
- Nada de monoespaciado

Componentes:
- Cabecera fija con blur y la "&" de marca a la izquierda
- Tarjetas blancas, borde 1px #E7E5E1, radio 16px, barra superior de 3px en color,
  elevación suave al hover con sombra 0 20px 40px -24px rgba(33,33,33,.25)
- Etiquetas tipo píldora
- Foco de teclado visible en azul
- Hero con una "&" gigante de marca de agua, al 6-8% de opacidad, detrás del texto

La "&":
- Es la iconografía de la marca. Siempre literal, nunca escrita "and"
- Siempre en Be Vietnam Pro bold y en azul #37A1FF
- Aparece como marca en la cabecera y como marca de agua gigante en el hero

Color por entidad (es dato, no decoración):
- Cada entidad, el nosotros y cada competidor, mantiene su color de marca real en la
  leyenda, las tablas y la cabecera de su ficha, para que el comercial se oriente de
  un vistazo.
- El cromado de la interfaz y las tarjetas de navegación van en azul de marca. El azul
  es el sistema; los colores por entidad son el dato. No pintes toda la interfaz con
  el color de una entidad.

Insignia de autoría (al pie, clicable):
- Bloque "Made by" + logotipo "Purpose & Prompt" + enlace, todo dentro de un mismo <a>.
- Logotipo escrito con fuentes, no como imagen: "Purpose" y "Prompt" en Playfair
  Display semibold en navy #00172D, y la "&" en Be Vietnam Pro bold en azul #37A1FF.
- El <a> lleva al enlace de entrada (artículo o Substack), abre en pestaña nueva.

REQUISITOS TÉCNICOS
- Un solo archivo HTML, todo el CSS y el JS dentro. Sin librerías externas ni llamadas
  a servidores, con una única excepción: las tipografías de marca desde Google Fonts.
  El equipo debe poder abrirlo o subirlo a una intranet tal cual. Sin conexión, la web
  funciona igual pero cae a fuentes del sistema. Si hace falta offline estricto,
  incrusta las fuentes en base64 (pesa más) en vez de usar Google Fonts.
- Nada de almacenamiento del navegador (localStorage y similares no funcionan en este
  entorno). El estado vive en memoria.
- Navegación por URL: cada bloque con su ancla, para poder compartir el enlace directo
  a una carta concreta.
- Suelo de calidad: responsive hasta móvil, tablas con scroll horizontal en pantallas
  pequeñas, foco de teclado visible, y respeta reduce-motion.
- Para convertir el markdown del manual a las tablas y listas de la web, procesa el
  contenido de forma fiable (las tablas y los acentos son lo que más se rompe).

NOTA DE MANTENIMIENTO (en la entrega, no en la página)
- El contenido queda embebido en el HTML. Si el manual cambia, la web hay que
  regenerarla. Avisa de esto al entregar.
- No metas esta nota, ni avisos de "uso interno", dentro de la página. Van en el
  mensaje de entrega o en el README del repo.

AUTOCOMPROBACIÓN
- ¿Cada bloque de la pieza tiene su tarjeta en el índice con su descripción?
- ¿Las tablas se ven bien y no se rompen en móvil?
- ¿La web usa el sistema Purpose & Prompt, con el azul como cromado y el color por
  entidad como dato?
- ¿Está la "&" en la cabecera y la marca de agua, y la insignia "Made by" al pie?
- ¿Es un único archivo, con las fuentes desde Google Fonts y el resto embebido?
- ¿La navegación por URL funciona para compartir bloques sueltos?
- Si es MODO MAPA: ¿todos los actores tienen el mismo trato visual, sin favorito?
  ¿la tabla evita sugerir ganador? ¿se ha colado algo accionable?
- ¿Está en el idioma elegido, interfaz incluida? ¿La versión en el otro idioma
  existe solo porque el humano la pidió?
