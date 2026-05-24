# AGENTS.md — AstroLuz Shopify DropCOD

## Rol del agente

Actúa como desarrollador senior especializado en Shopify Themes, Liquid, JSON templates, sections, snippets, CSS responsive y JavaScript vanilla.

Tu misión es transformar el theme actual de Shopify en una tienda tipo **one-product store** profesional para **AstroLuz™ Proyector Galaxia Astronauta**, optimizada para conversión en celular y preparada para un modelo **DropCOD**.

---

## Contexto del negocio

La tienda se llama **AstroLuz**.

Producto principal:

**AstroLuz™ Proyector Galaxia Astronauta**

Modelo de negocio:

- Cliente entra a la tienda.
- Ve el producto.
- Hace el pedido online.
- El pedido se confirma por WhatsApp.
- El producto se despacha mediante Dropi/DropCOD.
- El cliente paga al recibir.

Mensaje comercial principal:

> Transforma tu habitación en una galaxia en segundos.

Submensaje:

> Proyector LED decorativo con efecto nebulosa, estrellas y control remoto. Ideal para habitaciones, setups, escritorios y regalos.

CTA principal:

> Pedir ahora

Microcopy de confianza:

> Paga al recibir • Confirmación por WhatsApp • Envío en Colombia

---

## Referencia visual y técnica

Existe un archivo de referencia llamado algo similar a:

`skyracer360_com.html`

Ese archivo es una referencia de estructura y experiencia de tienda one-product. Úsalo únicamente para observar patrones de conversión, jerarquía visual y composición general.

### Patrones observados en la referencia

- Tienda Shopify en español.
- Theme tipo Shrine PRO / one-product.
- Tipografía estilo Poppins.
- Header simple con logo, búsqueda y carrito.
- Redirección o enfoque directo hacia página de producto.
- Página centrada en un producto destacado.
- Galería de imágenes grande.
- Rating visual editable.
- Título fuerte del producto.
- Precio visible.
- Selector de variantes.
- Selector de cantidad.
- Botón principal de compra.
- Drawer cart / carrito lateral.
- Subtotal visible.
- Badges de métodos de pago.
- Formulario de contacto.
- Footer simple.
- Diseño orientado a conversión.

### Restricción crítica

No copiar literalmente:

- Código.
- HTML.
- CSS.
- JavaScript.
- Clases.
- Assets.
- Imágenes.
- Textos.
- Marca.
- Estructura pixel-perfect.
- Claims comerciales.
- Temporizadores engañosos.
- Reseñas falsas.

Crear una implementación original para AstroLuz, inspirada solo en la lógica de conversión.

---

## Objetivo de diseño

La tienda debe sentirse como una marca real y confiable, no como una tienda genérica de dropshipping.

Prioridades:

1. Mobile-first.
2. Primer pantallazo claro.
3. Producto protagonista.
4. CTA visible.
5. Confianza inmediata.
6. Pago contra entrega claro.
7. Diseño limpio y moderno.
8. Carga rápida.
9. Textos cortos y escaneables.
10. Compatibilidad con Shopify Theme Editor.

---

## Dirección visual recomendada

Estética:

- Espacial.
- Moderna.
- Premium accesible.
- Oscura con acentos luminosos.
- Visualmente alineada con luces, galaxias y ambiente nocturno.

Paleta sugerida:

- Fondo principal: negro espacial / azul muy oscuro.
- Fondos secundarios: blanco o gris muy claro para bloques de confianza.
- Acentos: violeta, azul eléctrico, cian o degradados tipo nebulosa.
- Botón principal: alto contraste.
- Texto: muy legible, sin exceso de efectos.

Tipografía:

- Usar la fuente del theme si ya está configurada.
- Si el theme permite configurar Poppins desde ajustes, usar Poppins o una fuente sans-serif moderna equivalente.
- No importar fuentes externas de forma pesada sin necesidad.

---

## Estructura obligatoria de la landing

### 1. Announcement bar / barra superior

Debe ser editable desde Shopify Theme Editor.

Texto sugerido:

> Oferta de lanzamiento • Paga al recibir • Envío en Colombia

Reglas:

- Debe ser compacta.
- Debe verse bien en mobile.
- No usar urgencia falsa.

---

### 2. Header minimalista

Debe incluir:

- Logo o texto de marca AstroLuz.
- Menú simple.
- Icono de búsqueda solo si el theme ya lo soporta.
- Icono de carrito.
- Buen comportamiento responsive.

Reglas:

- No sobrecargar el header.
- En mobile, priorizar logo + carrito + menú.
- Mantener funcionalidades nativas del theme.

---

### 3. Hero / sección principal de producto

Debe mostrar en el primer pantallazo mobile:

- Imagen o galería principal del producto.
- Título fuerte.
- Subtítulo breve.
- Precio usando objetos nativos de Shopify.
- CTA visible.
- Mensajes de confianza.

Contenido recomendado:

Título:

> Transforma tu habitación en una galaxia en segundos

Subtítulo:

> Proyector LED decorativo con efecto nebulosa, estrellas y control remoto.

CTA:

> Pedir ahora

Microcopy:

> Paga al recibir • Confirmación por WhatsApp • Envío en Colombia

Reglas:

- Usar el producto dinámico de Shopify.
- No hardcodear precio si Shopify ya lo gestiona.
- No romper variantes, cantidad ni formulario de producto.
- El botón debe hacer scroll al formulario o usar el formulario nativo de producto.

---

### 4. Barra de confianza

Crear cards compactas:

- Pago contra entrega.
- Confirmación por WhatsApp.
- Envío en Colombia.
- Garantía del proveedor.

Reglas:

- Debe verse como soporte operativo real.
- No usar claims absolutos tipo “100% garantizado” si no está respaldado.

---

### 5. Problema / solución

Problema:

> Tu habitación se siente aburrida o sin ambiente.

Solución:

> AstroLuz™ transforma cualquier espacio con un efecto galaxia relajante en segundos.

Reglas:

- Texto breve.
- Diseño visual.
- Evitar párrafos largos.

---

### 6. Beneficios del producto

Usar cards visuales:

- Efecto nebulosa y estrellas.
- Control remoto.
- Cabeza ajustable.
- Ideal para habitación o regalo.
- Fácil de usar.

Reglas:

- No mencionar Bluetooth, control por voz o altavoz si el proveedor no lo confirmó.
- Cada beneficio debe ser claro y real.

---

### 7. Cómo funciona

Sección en 4 pasos:

1. Haces tu pedido online.
2. Confirmamos por WhatsApp.
3. Recibes en casa.
4. Pagas al recibir.

Reglas:

- Esta sección es fundamental para DropCOD.
- Debe aparecer antes del FAQ.
- Debe reforzar confianza.

---

### 8. Qué incluye

Mostrar una lista limpia:

- Proyector astronauta.
- Control remoto.
- Cable de alimentación.
- Empaque del producto.
- Manual solo si el proveedor lo confirma.

Reglas:

- No prometer accesorios no confirmados.
- Dejar los textos editables desde el editor si es posible.

---

### 9. Garantía y confianza

Texto base:

> Tu pedido se confirma por WhatsApp antes del envío. Si el producto llega con alguna novedad, debe reportarse dentro del plazo indicado por el proveedor.

Reglas:

- No prometer garantía absoluta.
- No inventar políticas de devolución.
- Mantener coherencia con las reglas reales de Dropi/proveedor.

---

### 10. FAQ

Crear sección editable con preguntas frecuentes:

- ¿Cuándo pago?
- ¿Cuánto tarda el envío?
- ¿Dónde entregan?
- ¿Qué incluye el producto?
- ¿Tiene garantía?
- ¿Cómo confirmo mi pedido?

Respuestas sugeridas:

**¿Cuándo pago?**

Pagas al recibir tu producto, después de confirmar tu pedido por WhatsApp.

**¿Cuánto tarda el envío?**

El tiempo puede variar según ciudad, disponibilidad y cobertura logística.

**¿Dónde entregan?**

La tienda está orientada a Colombia. La cobertura final depende de Dropi/proveedor.

**¿Qué incluye el producto?**

Incluye proyector astronauta, control remoto, cable de alimentación y empaque del producto.

**¿Tiene garantía?**

Tiene garantía según las condiciones del proveedor. Si llega con alguna novedad, debe reportarse dentro del plazo indicado.

**¿Cómo confirmo mi pedido?**

Después de hacer el pedido, te contactamos por WhatsApp para validar tus datos antes del envío.

---

### 11. CTA final

Texto:

> Dale a tu habitación un ambiente único con AstroLuz™.

Botón:

> Pedir ahora y pagar al recibir

---

### 12. Carrito

Mantener carrito nativo del theme.

Si existe drawer cart:

- Mantenerlo.
- Mejorar textos al español si están mal.
- Mostrar subtotal.
- Mantener botón de checkout.
- No alterar lógica nativa.
- No usar temporizador falso de reserva.

Si el theme ya tiene un timer de carrito, convertirlo en texto honesto o desactivarlo si parece engañoso.

Texto recomendado:

> Revisa tu pedido antes de finalizar.

Evitar:

> Tu carrito se eliminará en 5 minutos.

---

## Archivos que se pueden tocar

Antes de modificar, revisar la estructura real del theme.

Archivos probables:

- `templates/product.json`
- `templates/index.json`
- `sections/main-product.liquid`
- `sections/featured-product.liquid`
- `sections/header.liquid`
- `sections/footer.liquid`
- `sections/cart-drawer.liquid`
- `snippets/price.liquid`
- `snippets/product-form.liquid`
- `assets/base.css`
- `assets/theme.css`
- `assets/component-product.css`
- `assets/custom.css` si existe

Preferir crear archivos nuevos antes que modificar demasiado código core:

- `sections/astroluz-hero.liquid`
- `sections/astroluz-trust-bar.liquid`
- `sections/astroluz-benefits.liquid`
- `sections/astroluz-how-it-works.liquid`
- `sections/astroluz-included.liquid`
- `sections/astroluz-faq.liquid`
- `sections/astroluz-final-cta.liquid`
- `assets/astroluz.css`

No tocar:

- Checkout.
- Pagos.
- Apps.
- Integraciones Dropi.
- Scripts de terceros sin necesidad.
- Código de tracking.

---

## Reglas técnicas estrictas

- Mobile-first.
- Mantener compatibilidad con Shopify Theme Editor.
- Usar schemas en las sections.
- Hacer textos editables desde settings cuando sea posible.
- Usar Liquid nativo.
- Usar `product`, `section.settings`, `block.settings` correctamente.
- Usar filtros de Shopify para precios.
- No hardcodear precios si existen en Shopify.
- No usar librerías externas pesadas.
- Usar JavaScript vanilla solo cuando sea estrictamente necesario.
- Mantener accesibilidad básica: labels, alt text, botones reales, foco visible.
- No romper formularios nativos de producto.
- No romper variantes.
- No romper inventario.
- No romper carrito.
- No romper checkout.
- No agregar reseñas falsas.
- No agregar temporizadores falsos.
- No agregar escasez falsa.
- No agregar logos de pagos que no estén habilitados.
- No usar assets de otras tiendas.

---

## Plan de implementación por fases

### Fase 1 — Diagnóstico

Antes de escribir código:

1. Revisar estructura del theme.
2. Identificar theme base.
3. Identificar archivos de producto.
4. Identificar carrito.
5. Identificar header/footer.
6. Proponer archivos a modificar.
7. Explicar riesgos.

No modificar nada en esta fase.

---

### Fase 2 — Base visual mobile-first

Implementar:

- Announcement bar.
- Header limpio si es necesario.
- Hero principal.
- Barra de confianza.
- Sección “Cómo funciona”.

No tocar:

- Checkout.
- Apps.
- Bundles.
- Upsells.
- Popups.

---

### Fase 3 — Secciones de conversión

Implementar:

- Problema / solución.
- Beneficios.
- Qué incluye.
- Garantía y confianza.
- FAQ.
- CTA final.

---

### Fase 4 — Pulido de producto

Revisar:

- Galería.
- Precio.
- Variantes.
- Cantidad.
- Botón de compra.
- Mensajes debajo del CTA.
- Espaciados mobile.

---

### Fase 5 — Carrito y confianza

Solo si el theme lo permite sin riesgo:

- Mejorar drawer cart.
- Mantener subtotal.
- Mantener checkout nativo.
- Añadir texto honesto de revisión del pedido.
- Quitar urgencia falsa.

---

### Fase 6 — Auditoría final

Validar:

- `shopify theme dev` compila.
- No hay errores en consola.
- Mobile se ve bien.
- CTA funciona.
- Variantes funcionan.
- Quantity selector funciona.
- Add to cart funciona.
- Cart drawer funciona.
- Checkout sigue funcionando.
- Textos son editables desde Shopify Theme Editor.
- No hay claims falsos.

---

## Criterios de éxito

La página queda bien si:

- En menos de 3 segundos se entiende qué vende.
- En menos de 3 segundos se entiende que se paga al recibir.
- El producto se ve como protagonista.
- La marca se siente confiable.
- El primer pantallazo mobile tiene promesa, producto, CTA y confianza.
- No parece copia de otra tienda.
- No parece una tienda improvisada.
- No rompe funciones nativas de Shopify.

---

## Primer prompt recomendado para Codex

Lee este `AGENTS.md` y revisa el theme actual.

No escribas código todavía.

Primero dime:

1. Qué theme parece estar usando mi tienda.
2. Qué archivos controlan la página de producto.
3. Qué archivos controlan header, footer y carrito.
4. Qué secciones nuevas conviene crear para AstroLuz.
5. Qué archivos tocarías y cuáles no.
6. Qué riesgos técnicos ves.
7. Plan de implementación por fases.

Después espera mi aprobación.

---

## Prompt de implementación fase 1

Implementa solo la Fase 1 visual de AstroLuz:

- Announcement bar.
- Hero principal mobile-first.
- Barra de confianza.
- Sección “Cómo funciona”.

Reglas:

- No toques checkout.
- No toques pagos.
- No toques apps.
- No inventes reseñas.
- No uses temporizadores falsos.
- No copies código del archivo de referencia.
- Usa una implementación original.
- Mantén todo editable desde Shopify Theme Editor cuando sea posible.
- Al terminar, dime qué archivos modificaste y por qué.

---

## Prompt de auditoría final

Actúa como auditor de conversión mobile y revisa tu implementación.

Evalúa:

1. ¿El primer pantallazo explica qué vende AstroLuz?
2. ¿Se entiende que el cliente paga al recibir?
3. ¿El diseño transmite confianza?
4. ¿Hay demasiado texto?
5. ¿El CTA está visible y claro?
6. ¿La página parece marca real o tienda genérica?
7. ¿Hay claims falsos o riesgosos?
8. ¿El código mantiene compatibilidad con Shopify Theme Editor?
9. ¿Se rompió alguna función nativa?
10. ¿Qué mejorarías sin tocar checkout?

No hagas cambios todavía. Primero entrega el diagnóstico.
