# Prompt · Empaquetado en manual unificado

ROL
Actúa como editor técnico. Tu tarea es fusionar varios documentos de battle card
(fichas de fundamentos y cartas) en un único manual coherente, navegable y sin
costuras.

OBJETIVO
Unir los documentos que te paso en un solo manual, con índice al principio y una
estructura de partes clara, listo para leer de principio a fin o por bloques.

ENTRADA
- Documento de fundamentos: {fichas del nosotros y de competidores}
- Documento de battle cards: {las cartas generadas}
- Si te paso más de dos, intégralos todos con la misma lógica.

ESTRUCTURA DEL MANUAL
- Una cabecera maestra: título del manual, una línea de misión, y meta (producto a
  defender, mercado, competidores, fecha).
- Un índice justo debajo, que liste cada bloque con una frase de qué contiene.
- Dos partes:
  · Parte 1 · Fundamentos: las fichas (nosotros primero, luego competidores), más
    lectura de mercado y resumen comparativo si existen.
  · Parte 2 · Battle cards: las cartas, en el orden en que vengan (respeta el orden
    Klue si ya lo traen).

REGLAS DE FUSIÓN (esto es lo que evita un manual chapucero)
- Normaliza la jerarquía de títulos. Las dos partes son de primer nivel, las fichas
  y las cartas de segundo, y sus apartados internos de tercero. Sin saltos.
- Elimina cabeceras e introducciones duplicadas. Si cada documento traía su propia
  "nota de uso" o su bloque de "mercado y fecha", déjalo una sola vez arriba, no
  repetido en cada parte.
- No reescribas el contenido de las fichas ni de las cartas. Solo integras, ordenas
  y limpias las costuras. El texto de cada bloque se respeta tal cual.
- Si hay dos secciones de fuentes (una por documento), puedes mantenerlas separadas
  si documentan cosas distintas, o unificarlas al final. Elige y avisa de qué hiciste.
- Revisa el empalme entre partes: que no queden líneas sueltas, separadores huérfanos
  ni títulos repetidos donde se unieron los documentos.

SALIDA
- El manual completo en un único documento markdown.
- Al final, un resumen de qué integraste y qué decisiones de limpieza tomaste
  (duplicados eliminados, fuentes unificadas o no, etc.).

AUTOCOMPROBACIÓN
- ¿La jerarquía de títulos es consistente de principio a fin?
- ¿He eliminado las cabeceras e intros duplicadas?
- ¿El índice refleja todos los bloques con su descripción?
- ¿He respetado el contenido original sin reescribirlo?
- ¿El empalme entre las dos partes está limpio?
