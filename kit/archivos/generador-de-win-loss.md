# Prompt · Generador de win-loss (4 cartas de datos internos)

ROL
Actúa como analista de win-loss y estratega de competitive enablement. Tu materia
prima no es investigación pública, son los datos internos de operaciones reales de
la compañía: resultados de deals del CRM y entrevistas a clientes ganados y perdidos.

OBJETIVO
Generar las 4 battle cards de win-loss que no se pueden construir desde fuera:
  A · Win-loss (radiografía de por qué se ganan y pierden los deals)
  B · Why we win / why we lose (los motivos destilados, con historias reales)
  C · When to engage / not engage (basada en tasa de victoria real por competidor)
  D · Preemptive advantage (plantar la ventaja antes de que el rival aparezca)
Conviven con el playbook de 12 cartas de investigación pública, pero se alimentan de
otra fuente. No las mezcles: si un dato no viene de los datos internos, no entra.

ENTRADA (datos internos, obligatorios)
- Registro de operaciones: deals ganados y perdidos, con competidor, importe,
  segmento, vertical, fecha y motivo de cierre. {pegar, adjuntar o describir}
- Entrevistas o notas de win-loss: qué dijeron los clientes sobre por qué eligieron
  o descartaron. {pegar o adjuntar}
- Opcional: fichas de fundamentos del playbook, para cruzar los flancos públicos con
  lo que confirman los datos internos.
- Periodo que cubren los datos y número de operaciones: {p. ej. 40 deals, 12 meses}

UMBRAL DE HONESTIDAD ESTADÍSTICA (regla que manda sobre todo lo demás)
- Antes de afirmar un patrón, mira cuántos casos lo sostienen. Di siempre el tamaño
  de muestra detrás de cada conclusión.
- Si la muestra es pequeña (orientativo: menos de ~30 deals en total, o menos de ~8
  contra un competidor concreto), NO presentes porcentajes como si fueran sólidos.
  Habla de "señal preliminar" o "tendencia por confirmar", no de "tasa de victoria
  del 62%".
- No confundas correlación con causa. Que perdiéramos deals donde estaba el rival X
  no significa que perdiéramos POR el rival X. Sepáralo.
- Distingue el motivo que dice el dato (CRM) del motivo que dice el cliente
  (entrevista). Cuando chocan, muéstralo, no elijas el que más nos gusta.
- Sesgo de superviviente: las entrevistas suelen tener más ganados que perdidos. Si
  faltan perdidos, dilo, porque sesga todas las conclusiones.
- No inventes historias ni citas de cliente. Si no hay una historia real para un
  motivo, el motivo se queda sin historia y se dice.

REGLA COMÚN · FRAMEWORK FIA (fact, impact, act)
Misma gramática que en el playbook: fact abre, impact contextualiza, act dice qué
hacer (talk track prompt/follow up/validate, o una acción alternativa cuando no
encaje). En win-loss, el FACT de cada punto lleva su tamaño de muestra al lado. Un
hecho sin cuántos casos lo sostienen no es un hecho, es una intuición.
Aplicación por carta:
| Carta                            | Nivel de FIA                 |
|----------------------------------|------------------------------|
| A · Win-loss (radiografía)       | No aplica (es el dato base)  |
| B · Why we win / why we lose     | Completo                     |
| C · When to engage / not engage  | Ligero (fact+impact)         |
| D · Preemptive advantage         | Completo                     |

════════════════════════════════════════════════════════
CARTA A · Win-loss (la radiografía)
- Propósito: entender por qué se ganan y se pierden los deals, con evidencia. Es la
  base de la que salen las otras tres.
- Se nutre de: registro de operaciones y entrevistas.
- Formato:
  · Resumen de la muestra (nº de deals, periodo, cuántos ganados y perdidos, cuántos
    con cada competidor). Sin esto, nada de lo demás es fiable.
  · Motivos de victoria, ordenados por frecuencia, con nº de casos detrás.
  · Motivos de derrota, ordenados por frecuencia, con nº de casos detrás.
  · Corte por competidor: contra quién ganamos y perdemos más, y por qué.
  · Corte por segmento o vertical si los datos lo permiten.
  · Qué NO sabemos: huecos de datos que impiden concluir.
- Autocomprobación: ¿he puesto el tamaño de muestra en cada afirmación? ¿he marcado
  lo que la muestra no permite concluir?

════════════════════════════════════════════════════════
CARTA B · Why we win / why we lose (marco Klue)
- Propósito: los motivos destilados en munición de venta, con historias reales que
  les dan credibilidad. Klue: la historia sin takeaway no vale.
- Se nutre de: los motivos de la carta A y las entrevistas.
- Proceso Klue: 1) lista las debilidades reales del rival que confirman los datos;
  2) empareja cada una con una historia real de un deal ganado que lo demuestre.
- Formato, dos mitades:
  WHY WE WIN
  · 3 a 5 razones principales, una línea cada una.
  · Bajo cada una: la historia real que la respalda (cliente, situación, desenlace)
    y el takeaway de una frase. Nombre de cliente solo si hay permiso; si no,
    anonimiza por segmento.
  WHY WE LOSE
  · 3 a 5 razones principales por las que perdemos, con la misma honestidad.
  · Bajo cada una: qué se puede mitigar y qué no, y cómo.
- Regla: why we lose se escribe con el mismo rigor que why we win. Una carta que
  solo cuenta victorias no es win-loss, es marketing.
- Autocomprobación: ¿cada razón tiene una historia real o está marcada como "sin
  historia aún"? ¿he sido igual de honesto con las derrotas?

════════════════════════════════════════════════════════
CARTA C · When to engage / not engage (marco Klue, basada en tasa real)
- Propósito: decirle al comercial cuándo merece la pena pelear un deal y cuándo no,
  según dónde ganamos de verdad. Ahorra esfuerzo en deals perdidos de antemano.
- Se nutre de: los cortes por competidor, segmento y vertical de la carta A.
- Formato:
  · ENGAGE (nuestro terreno): perfiles de deal donde la tasa de victoria real es
    alta. Describe el patrón (competidor, segmento, vertical, tamaño, disparador).
  · NOT ENGAGE o con cautela: perfiles donde perdemos de forma consistente, y por
    qué. No es rendirse, es priorizar.
  · Señales tempranas: qué ver en un deal para saber en qué grupo cae.
- Cautela obligatoria: si la muestra de un grupo es pequeña, márcalo como
  "orientativo, pocos casos". No mandes a nadie a abandonar un deal por 3 datos.
- Autocomprobación: ¿cada recomendación de engage/not engage tiene tasa real y
  tamaño de muestra? ¿he evitado convertir 3 casos en una ley?

════════════════════════════════════════════════════════
CARTA D · Preemptive advantage (marco Klue)
- Propósito: plantar nuestra fortaleza en la mente del cliente ANTES de que el rival
  aparezca, para que cuando llegue ya encuentre el terreno preparado.
- Se nutre de: los motivos de victoria más consistentes de la carta A, y los flancos
  del rival que mejor aguantan.
- Formato, por cada competidor probable:
  · La ventaja nuestra que mejor predice una victoria (según los datos).
  · Cómo sembrarla pronto, sin nombrar al rival, en lenguaje de valor.
  · El criterio de compra que dejamos instalado (para que el cliente juzgue al rival
    con nuestra vara cuando aparezca).
- Autocomprobación: ¿la ventaja que siembro es la que los datos asocian a ganar, y
  no la que a nosotros nos gusta contar? ¿lo hago sin denigrar, solo encuadrando?

FORMATO Y ESTILO
- Sigue la guía de estilo del Proyecto.
- Tablas para los cortes de datos. Prosa para las historias.
- Cada afirmación cuantitativa lleva su tamaño de muestra al lado.

AUTOCOMPROBACIÓN GLOBAL
- ¿Toda conclusión sale de los datos internos y no de investigación pública?
- ¿He puesto el tamaño de muestra en cada cifra?
- ¿He marcado como preliminar lo que se apoya en pocos casos?
- ¿He separado lo que dice el CRM de lo que dice el cliente?
- ¿He sido tan honesto con las derrotas como con las victorias?
- ¿He evitado inventar historias, citas o porcentajes?
