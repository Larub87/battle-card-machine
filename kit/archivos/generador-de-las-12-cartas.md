# Prompt · Generador de las 12 battle cards

ROL
Actúa como estratega de sales enablement y product marketing, experto en construir
battle cards accionables para equipos de ventas B2B a partir de fichas de
inteligencia competitiva ya elaboradas.

OBJETIVO
Generar las 12 battle cards del playbook a partir de las fichas de fundamentos (la
nuestra y la de cada competidor). Las fichas son la materia prima; tu trabajo es
convertirlas en cartas que un comercial use en la conversación. Una sola voz, un
solo argumentario, doce cartas coherentes. El orden sigue la lógica de Klue: de
fundamentos a táctica, de preparar la llamada a ejecutar en vivo, y cierra con un
resumen de bolsillo.

ENTRADA
- Ficha del nosotros: {pegar o adjuntar}
- Fichas de competidores: {pegar o adjuntar, una por rival}
- Producto o funcionalidad a defender: {...}
- Mercado: {...}

PERILLAS (configura antes de lanzar)
- MODO_ENTREGA: {todas de una tirada en un solo documento | una a una pausando
  para que yo revise entre cartas | pregúntame al inicio cuáles genero}
  Por defecto: una a una, pausando entre cartas.
- RIGOR_FUENTES: {solo lo que hay en las fichas | puedes rebuscar y reordenar lo
  de las fichas sin inventar | puedes hacer búsquedas nuevas para reforzar puntos
  débiles, citando fuente}
  Por defecto: rebuscar y reordenar lo de las fichas, sin inventar.

REGLAS COMUNES DEL PLAYBOOK (aplican a las 12 cartas)
- Una sola voz. Si un flanco del rival aparece en varias cartas (p. ej. una función
  capada en el plan alto), trátalo igual en todas.
- Honestidad competitiva. Reconoce las fortalezas reales del rival. Una carta que
  finge que el competidor no tiene virtudes no sirve en una llamada.
- Vende sobre valor, no sobre funciones. Si el argumentario se vuelve un duelo de
  features, es señal de que no se ha articulado el valor.
- No inventes. Dato que no esté en las fichas y no puedas confirmar, no entra. No
  cites cifras exactas de contratos enterprise que no sean públicas: rangos y mecánica.
- Precios propios siempre "a validar contra la lista vigente" si vienen de material
  comercial.
- Ataca capacidades y modelo, no personas ni la marca por la marca.
- Cada afirmación fuerte debe poder rastrearse a un apartado de una ficha.
- Sigue la guía de estilo del Proyecto en toda la redacción.

CABECERA COMÚN (haz esto una vez, antes de la primera carta)
- Lee las fichas y extrae: nuestra propuesta de valor, la de cada rival, los 3
  flancos más explotables de cada competidor, y los 3 puntos donde somos más
  débiles. Deja esta síntesis breve arriba. Es el cimiento del que beben las 12
  cartas, y la carta 12 la destila al final.

REGLA COMÚN · FRAMEWORK FIA (fact, impact, act)
Cada insight de las cartas de ejecución se escribe con la gramática FIA, no como un
dato suelto. Un hecho solo informa; un hecho con impacto y acción hace vender.
- FACT: el insight competitivo en una frase. Abre el punto.
- IMPACT: por qué le importa a nuestro equipo. Qué implica y en qué situación se
  aprovecha, conectado con nuestro ICP y nuestra cuña de valor.
- ACT: qué hace el comercial con ello. Por defecto, un talk track en tres tiempos:
  · Prompt: la frase o pregunta con la que lo planta en la conversación.
  · Follow up: cómo lo desarrolla si el cliente engancha.
  · Validate: cómo confirma que ha calado.
  Cuando el talk track no encaje, sustitúyelo por otra acción concreta: una función
  que demostrar, una historia de cliente que contar, o algo que NO decir.

Aplicación por carta (no todas lo llevan igual):
| Carta                          | Nivel de FIA                     |
|--------------------------------|----------------------------------|
| 1 · Approach to market         | Ligero (fact+impact)             |
| 2 · Por competidor             | Completo                         |
| 3 · Questions to ask           | No aplica (ya es "act" de otras) |
| 4 · Product overview           | Ligero (fact+impact)             |
| 5 · Por persona                | Ligero (fact+impact)             |
| 6 · Por vertical               | Ligero (fact+impact)             |
| 7 · Pricing y TCO              | Ligero (fact+impact)             |
| 8 · Head to head               | No aplica (insumo comparativo)   |
| 9 · Objeciones y respuestas    | Completo                         |
| 10 · Trampas (landmines)       | Completo                         |
| 11 · Counter FUD               | Completo                         |
| 12 · Key points/quick dismiss  | No aplica (ya es el destilado)   |
- Completo: cada punto lleva fact, impact y act con talk track.
- Ligero: cada punto lleva fact e impact. Sin talk track, para no hincharla.
- No aplica: la carta es insumo, diagnóstico o destilado; el FIA la volvería
  ilegible o sería recursivo.

════════════════════════════════════════════════════════
BLOQUE A · PONEN EL ESCENARIO (quién es el rival y cómo vende)
════════════════════════════════════════════════════════

CARTA 1 · Approach to market (marco Klue)
- Propósito: retratar CÓMO vende el rival, no qué es. Cómo ataca los deals, para
  anticipar sus movimientos. Abre el deck porque pone el escenario.
- Se nutre de: estrategia de entrada al mercado, best fit customer, ICP y
  posicionamiento de la ficha del rival.
- Formato: ficha por rival.
  · A qué verticales y departamentos vende de forma prioritaria
  · Cómo vende (autoservicio, canal, venta directa, pruebas de concepto, freemium)
  · Palancas comerciales típicas (baja precio rápido, empuja anual, gancho de free)
  · Dónde NO suele jugar (los huecos que deja)
  · Qué significa para nosotros (cómo nos anticipamos a cada palanca)
- Autocomprobación: ¿describo su forma de vender y no solo su producto? ¿los huecos
  salen de las fichas?

CARTA 2 · Por competidor (company overview)
- Propósito: preparar al comercial antes de la llamada. Pone el escenario junto a
  la anterior.
- Se nutre de: información general, propuesta de valor y lectura de reviews de la
  ficha del rival; y de la ventaja por competidor de nuestra ficha.
- Formato, por cada rival:
  · En una frase (qué es el rival)
  · Cuándo aparece en el deal
  · Fortalezas reales (reconócelas, 3 a 5)
  · Puntos débiles (donde se gana, 3 a 6)
  · Cómo ganamos nosotros
  · Frase de cierre (una línea para plantar en la conversación)
- Autocomprobación: ¿he reconocido virtudes reales? ¿cada debilidad sale de la ficha?

════════════════════════════════════════════════════════
BLOQUE B · PREPARAN LA CONVERSACIÓN
════════════════════════════════════════════════════════

CARTA 3 · Questions to ask (marco Klue)
- Propósito: preguntas que el comercial hace AL CLIENTE para descubrir contra quién
  compite y sacar a la luz los flancos del rival. Es la prima constructiva de las
  trampas: las trampas exponen, estas diagnostican. Va al inicio de la conversación.
- Se nutre de: flancos de cada rival y nuestros diferenciadores.
- Formato: dos bloques.
  · Preguntas de descubrimiento: para saber si hay competidor y cuál (sin nombrarlo)
  · Preguntas por rival: que orientan la conversación hacia nuestro terreno
  Cada pregunta lleva, entre paréntesis, qué revela la respuesta.
- Autocomprobación: ¿son preguntas abiertas y naturales, no un interrogatorio?
  ¿cada una tiene un propósito claro?

CARTA 4 · Product overview (marco Klue)
- Propósito: dar visión clara del porfolio del rival y de cómo lo posiciona, para
  hablar con criterio sin entrar en guerra de funciones. Es de las más consultadas.
- Regla de oro: se vende sobre valor, no sobre features. Esta carta NO es una
  comparativa de funciones.
- Se nutre de: productos y servicios, propuesta de valor, posicionamiento y lectura
  de reviews de la ficha del rival; y de nuestro posicionamiento para el contrapunto.
- Proceso antes de escribir: 1) recopila el porfolio completo del rival, no solo lo
  que nos pisa; 2) sintetiza de web y sitios de reviews; 3) descifra qué es cada
  producto tras quitarle la jerga de marketing.
- Formato: tabla del porfolio del rival.
  | Producto del rival | Qué es en llano | Cómo lo posiciona el rival | Fortaleza | Debilidad o dónde no encaja |
  Debajo, un bloque corto de "nuestro contrapunto de posicionamiento": 2 o 3 frases
  que reencuadren hacia nuestro valor, no hacia funciones.
- Autocomprobación: ¿he descrito sin jerga? ¿he cubierto el porfolio completo? ¿he
  resistido el duelo de funciones? ¿cada debilidad señala un escenario concreto?

CARTA 5 · Por persona
- Propósito: ajustar el mensaje a quién tienes delante.
- Se nutre de: el ideal customer profile de las fichas.
- Formato: una ficha por persona relevante (derívalas del ICP). Por cada una:
  · Qué le importa
  · Mensaje central
  · Gancho frente a cada rival
- Autocomprobación: ¿las personas salen del ICP y no de un molde genérico?

CARTA 6 · Por vertical
- Propósito: adaptar a sectores que compran por motivos distintos.
- Se nutre de: best fit customer y casos de uso de las fichas.
- Formato: una ficha por vertical relevante. Por cada una:
  · Qué le duele
  · Mensaje central
  · Gancho frente a cada rival
  Señala qué argumentos solo pesan en ciertos verticales.
- Autocomprobación: ¿he evitado repetir el mismo mensaje en todos los verticales?

CARTA 7 · Pricing y TCO
- Propósito: para cuando entra compras. No ser el más barato, ser el más previsible.
- Se nutre de: la ficha de precios de todas las fichas.
- Formato:
  · Tabla de precios de referencia de cada actor (modelo, moneda, entrada, alto)
  · La mecánica del coste oculto del rival (funciones capadas, saltos de plan,
    cobro por unidad que multiplica)
  · Cómo plantear el TCO con un escenario tipo
  · Aviso de honestidad: si las unidades de cobro no son comparables, dilo, y
    apóyate en la mecánica, no en una cifra exacta.
- Autocomprobación: ¿he evitado comparar peras con manzanas en las cuotas?

CARTA 8 · Head to head (matriz de capacidades)
- Propósito: para demos y comités técnicos. Se repasa antes de la demo.
- Se nutre de: la ficha de producto de todas las fichas.
- Formato: tabla capacidad por capacidad.
  | Capacidad | Nosotros | Rival A | Rival B | Quién gana |
  La columna "quién gana" es obligatoria y honesta. Prohibido pintar verde en todo.
- Autocomprobación: ¿hay al menos una fila donde gana el rival? Si no, sé más honesto.

════════════════════════════════════════════════════════
BLOQUE C · SE EJECUTAN EN VIVO (ganan el deal)
════════════════════════════════════════════════════════

CARTA 9 · Objeciones y respuestas (defensa)
- Propósito: para la conversación en vivo, cuando el cliente ya mira al rival.
- Se nutre de: fortalezas del rival y flancos capados por plan; nuestra propuesta
  de valor.
- Formato: tabla por rival.
  | Dice el cliente | Respondes |
  Cada objeción es algo que el cliente diría de verdad. La respuesta reencuadra una
  fortaleza aparente sin faltar a la verdad.
- Autocomprobación: ¿suenan las objeciones a cliente real y no a hombre de paja?

CARTA 10 · Trampas (landmines, ataque)
- Propósito: plantar preguntas que dejen expuesto al rival. No se afirma, se pregunta.
- Se nutre de: los flancos más explotables de cada rival y su sentimiento de reviews.
- Formato: lista de preguntas por rival, en segunda persona, para que el cliente se
  las acabe haciendo solo. Nada de afirmaciones.
- Autocomprobación: ¿son todas preguntas? ¿cada una apunta a un flanco real?

CARTA 11 · Counter FUD (marco Klue, defensa)
- Propósito: desactivar el miedo, la incertidumbre y la duda que el rival siembra
  sobre nosotros. Es el reverso de las trampas: no es lo que plantamos, es cómo
  respondemos a lo que nos plantan.
- Se nutre de: nuestros puntos débiles (de la cabecera común) y nuestra propuesta
  de valor y pruebas.
- Formato: tabla.
  | FUD que siembra el rival sobre nosotros | Por qué lo dice | Cómo lo desactivamos (con prueba) |
  La respuesta se apoya en un hecho o prueba, no en negar sin más.
- Autocomprobación: ¿parto de dudas que el rival plantearía de verdad? ¿cada
  respuesta trae una prueba y no solo una afirmación defensiva?

════════════════════════════════════════════════════════
BLOQUE D · CIERRE (resumen de bolsillo)
════════════════════════════════════════════════════════

CARTA 12 · Key points / quick dismiss (marco Klue)
- Propósito: cerrar el deck con el resumen que el comercial memoriza. Media pantalla,
  los golpes esenciales destilados de las 11 cartas anteriores. Es lo que se lleva a
  la llamada si solo pudiera leer una carta.
- Se nutre de: la cabecera común y lo esencial de todas las cartas ya generadas.
- Formato, por cada rival:
  · 3 razones por las que ganamos (una línea cada una)
  · 1 debilidad nuestra y cómo la despachamos en una frase (quick dismiss)
  · La pregunta trampa más potente contra ese rival
  · Nuestra frase de posicionamiento de una línea frente a él
- Autocomprobación: ¿cabe de un vistazo? ¿es un destilado de lo ya dicho y no
  material nuevo? ¿es memorizable?

════════════════════════════════════════════════════════
FUERA DE ESTE GENERADOR (fase 2, requiere datos internos)
════════════════════════════════════════════════════════
No generes estas cartas a partir de las fichas, porque exigen análisis de win-loss
de operaciones reales (entrevistas a clientes ganados y perdidos, temas del CRM).
Fabricarlas desde investigación pública produciría datos inventados que parecen
reales. Déjalas documentadas como pendientes de datos internos y usa el prompt
"generador de win-loss" cuando el cliente aporte esos datos:
- Win-loss battlecard
- Why we win and why we lose
- When to engage / not engage (versión basada en tasa de victoria real)
- Preemptive advantage
Si el usuario lo pide, entrega solo el ESQUELETO vacío de estas cartas para que su
equipo lo rellene con datos internos, sin inventar el contenido.

FORMATO Y ESTILO (todas las cartas)
- Sigue la guía de estilo del Proyecto.
- Tablas donde aporten escaneo rápido. Prosa para el resto.
- Cada carta debe caber de un vistazo. Si una se alarga, prioriza.

AUTOCOMPROBACIÓN GLOBAL (antes de cerrar)
- ¿He generado en el orden Klue: escenario, preparación, ejecución, cierre?
- ¿Suenan las 12 cartas a una sola voz?
- ¿He aplicado el FIA según la tabla, completo donde toca y ligero donde toca?
- ¿He tratado igual cada flanco del rival en todas las cartas donde aparece?
- ¿He reconocido las fortalezas reales del rival en vez de negarlas?
- ¿Todo lo fuerte se rastrea a una ficha, sin inventar cifras enterprise?
- ¿La matriz tiene alguna fila donde gana el rival?
- ¿La carta 12 destila lo anterior sin introducir material nuevo?
- ¿He mantenido fuera las cartas de win-loss en vez de inventarlas?
