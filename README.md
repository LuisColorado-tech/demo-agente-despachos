# Demo — Agente de consultas para despachos de abogados

`demo-despachos.html` · autocontenido, cero dependencias · **ábrelo con doble clic**.

Para qué existe: cuando un despacho conteste a uno de los 18 correos y pida ver algo, esto es lo
que se manda. Sin esto, el correo promete y no cumple.

## Qué demuestra (y qué no)

**Sí:**
- Contesta las consultas que se repiten con la información del despacho (8 fichas de ejemplo:
  divorcio, pensión, herencia, despido, urgencia, honorarios, documentos, ubicación).
- Clasifica por **área** y **urgencia**: si detecta amenazas o violencia, pasa a persona al instante
  y marca la urgencia en rojo.
- Recoge **nombre y teléfono** de lo que el cliente escribe.
- Rellena la **ficha que recibe el abogado**: área, urgencia, cliente, nombre, teléfono, cita
  propuesta y un resumen de una línea.
- Pasa a una persona cuando la consulta no está en la base.

**No:**
- No hay LLM ni WhatsApp conectado: la recuperación es por coincidencia de palabras clave y las
  respuestas están escritas a mano. Está dicho en la propia página ("Nota honesta").
- El despacho (Ferrer & Asociados) y las tarifas son ficticios.

**Por qué es honesto decirlo:** el despacho va a probarlo. Si la demo se vende como "IA en vivo" y
luego se cae, se pierde el cliente y la reputación. Como muestra de comportamiento y de la ficha,
funciona igual.

## Cómo se usa en la venta

1. Cuando un despacho responda: *"te mando la demo de cómo quedaría"*.
2. Enviar el enlace (o el archivo, si prefiere abrirlo sin instalar nada).
3. Ofrecer el alcance por escrito con las 3 tarifas del despacho real ya cargadas: ahí se ve la
   diferencia entre la demo y su caso.

## Para publicarla (pendiente de decisión de Luis)

Necesita URL pública para mandarla por correo. Opciones:
- **GitHub Pages** (`LuisColorado-tech/demo-despachos` → `luiscolorado-tech.github.io/demo-despachos`):
  gratis, verificable, y suma al perfil de GitHub.
- Cloudflare Pages / Netlify: también gratis, requiere cuenta y token.

## Verificación hecha

Renderizada con Chrome headless a 1280×1010 y revisada con visión: conversación completa, ficha con
todos los campos, cita marcada como **propuesta** (no confirmada), sin globos cortados.
Captura: `captura.png`.
