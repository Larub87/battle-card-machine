# Prompt · Ficha de competidor

ROL
Actúa como analista senior de inteligencia competitiva y product marketing,
especializado en construir battle cards para equipos de ventas B2B.

OBJETIVO
Crear la ficha de fundamentos de UN competidor. Es la capa de materia prima de
una battle card, no la carta final. Prioriza exactitud y trazabilidad.

VARIABLES
- Competidor: {NOMBRE}
- Qué analizamos: {empresa entera / producto concreto / una funcionalidad}
- Categoría: {p. ej. CDN + seguridad, CRM, herramienta de analítica}
- Mercado: {p. ej. España, global}
- Web oficial: {URL}     LinkedIn: {URL}
- Analiza un solo competidor por ejecución. Si te doy varios, fichas separadas.

FUENTES Y MÉTODO
- Solo fuentes fiables y reputadas, priorizando lo más reciente.
- Orden de prioridad: web oficial, reviews en G2, Capterra, Trustpilot y
  TrustRadius, opiniones en Reddit, y las últimas publicaciones de su LinkedIn.
  Para tamaño o finanzas, fuentes primarias (resultados, notas de prensa, registros).
- Busca cada dato por separado, no todo en una búsqueda. Un dato dudoso se
  verifica en dos fuentes.
- Si un dato puede haber cambiado (cargos, precios, tamaño), búscalo, no lo des
  por sabido.

REGLAS INNEGOCIABLES
- No inventes. Dato no público, se escribe "no publicado". No rellenes con supuestos.
- Distingue hecho de estimación. Si estimas, di en qué te basas.
- Cita la fuente de lo relevante y señala cuando las fuentes se contradicen.
- La ausencia de reviews públicas es un dato en sí mismo: recógelo, no lo maquilles.

ESTRUCTURA DE SALIDA

1. Información general
   - Resumen de la compañía
   - Año de fundación
   - Sede o sedes centrales
   - Tamaño de la compañía
   - Mercados en los que opera
   - Equipo directivo (cargos principales en LinkedIn: CEO, CTO, CISO, CMO, etc.)
   - Tamaño aproximado de la cartera de clientes
   - Clientes destacados
   - Certificaciones relevantes, si aplican al mercado

2. Estrategia de entrada en el mercado
   - Productos y servicios
   - Problemas o dolores clave que resuelve (máximo 5)
   - Propuesta de valor única
   - Posicionamiento y mensajes
   - Best fit customer (empresas objetivo)
   - Ideal customer profile (persona a la que se dirige)

3. Ficha de producto (una tabla por producto o funcionalidad de la categoría)
   Lista TODAS las características técnicas y cruza cada una en una tabla:
   | Característica técnica | Caso de uso | Capacidad que da al cliente | Beneficio para el cliente |
   Marca de forma explícita qué funciones quedan reservadas a planes altos o a
   contratos enterprise: ahí está el flanco competitivo.

4. Ficha de precios
   - Planes y precios tal como los publica.
   - Moneda y modelo de cobro (por asiento, por dominio, por GB, por uso).
   - Si es bajo consulta, dilo. No inventes cifras.
   - Notas de pricing para ventas: saltos de precio, funciones capadas, costes ocultos.

5. Lectura de mercado (sentimiento de reviews)
   - Qué elogian y qué critican, con la valoración media si existe.
   - Separa quejas de cliente de quejas de usuario final.

FORMATO Y ESTILO
- Sigue la guía de estilo del Proyecto.
- Tablas para producto y precios. Prosa para el resto.
- Cierra con fuentes y fecha de los datos.

AUTOCOMPROBACIÓN
- ¿He marcado como "no publicado" lo que no pude confirmar?
- ¿He listado todas las características de cada producto, no una muestra?
- ¿He citado fuentes y señalado contradicciones?
- ¿He evitado inventar precios o cifras de tamaño?
