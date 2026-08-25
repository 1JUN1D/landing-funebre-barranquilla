# Sitelinks (Vínculos a sitios) — Campaña Flores Barranquilla

**URL base:** `https://lashadasfloristeria.dondeseria.com/landing-pages/flores-barranquilla.html`

Los seis anclajes ya están implementados en la landing. `#2` y `#3` además dejan el catálogo **filtrado** al abrir, no solo desplazado.

---

## Los 6 sitelinks — listos para copiar y pegar

### 1 · Ver Catálogo Completo
- **Texto del vínculo:** `Ver Catálogo Completo`
- **Descripción 1:** `Rosas y girasoles frescos del día`
- **Descripción 2:** `Precios visibles, pide por WhatsApp`
- **URL final:** `https://lashadasfloristeria.dondeseria.com/landing-pages/flores-barranquilla.html#1`
- *Cae en:* el catálogo, con los 30 arreglos.

### 2 · Arreglos con Rosas
- **Texto del vínculo:** `Arreglos con Rosas`
- **Descripción 1:** `Rojas, rosadas, blancas y fucsia`
- **Descripción 2:** `Armados a mano el día del envío`
- **URL final:** `https://lashadasfloristeria.dondeseria.com/landing-pages/flores-barranquilla.html#2`
- *Cae en:* el catálogo **ya filtrado en Rosas** (29 arreglos).

### 3 · Arreglos con Girasoles
- **Texto del vínculo:** `Arreglos con Girasoles`
- **Descripción 1:** `Girasoles frescos de temporada`
- **Descripción 2:** `Solos o combinados con rosas`
- **URL final:** `https://lashadasfloristeria.dondeseria.com/landing-pages/flores-barranquilla.html#3`
- *Cae en:* el catálogo **ya filtrado en Girasoles** (11 arreglos).

### 4 · Envío el Mismo Día
- **Texto del vínculo:** `Envío el Mismo Día`
- **Descripción 1:** `Pides hoy y entregamos hoy`
- **Descripción 2:** `Cubrimos toda Barranquilla`
- **URL final:** `https://lashadasfloristeria.dondeseria.com/landing-pages/flores-barranquilla.html#4`
- *Cae en:* "Cómo funciona" — pasos del pedido, flores y zonas de cobertura.

### 5 · Ocasiones para Regalar
- **Texto del vínculo:** `Ocasiones para Regalar`
- **Descripción 1:** `Cumpleaños, aniversario, grados`
- **Descripción 2:** `Tarjeta con tu mensaje incluida`
- **URL final:** `https://lashadasfloristeria.dondeseria.com/landing-pages/flores-barranquilla.html#5`
- *Cae en:* la sección de ocasiones.

### 6 · Preguntas Frecuentes
- **Texto del vínculo:** `Preguntas Frecuentes`
- **Descripción 1:** `Cómo pedir, pagos y coberturas`
- **Descripción 2:** `Te enviamos foto antes de salir`
- **URL final:** `https://lashadasfloristeria.dondeseria.com/landing-pages/flores-barranquilla.html#6`
- *Cae en:* el FAQ desplegable.

---

## Tabla resumen (para carga masiva)

| # | Texto del vínculo | Descripción 1 | Descripción 2 | URL final |
|---|---|---|---|---|
| 1 | Ver Catálogo Completo | Rosas y girasoles frescos del día | Precios visibles, pide por WhatsApp | `…flores-barranquilla.html#1` |
| 2 | Arreglos con Rosas | Rojas, rosadas, blancas y fucsia | Armados a mano el día del envío | `…flores-barranquilla.html#2` |
| 3 | Arreglos con Girasoles | Girasoles frescos de temporada | Solos o combinados con rosas | `…flores-barranquilla.html#3` |
| 4 | Envío el Mismo Día | Pides hoy y entregamos hoy | Cubrimos toda Barranquilla | `…flores-barranquilla.html#4` |
| 5 | Ocasiones para Regalar | Cumpleaños, aniversario, grados | Tarjeta con tu mensaje incluida | `…flores-barranquilla.html#5` |
| 6 | Preguntas Frecuentes | Cómo pedir, pagos y coberturas | Te enviamos foto antes de salir | `…flores-barranquilla.html#6` |

Todos los textos caben en los límites de Google Ads: vínculo ≤ 25 caracteres, cada descripción ≤ 35.

---

## Notas de implementación

- **Nivel:** créalos a nivel de **campaña** (no de grupo). Con un solo grupo de anuncios da igual el resultado, pero deja la cuenta ordenada si mañana agregas grupos.
- **Cuántos se muestran:** Google elige entre 2 y 6 según dispositivo y posición. En móvil casi siempre muestra 2 o 4, por eso los dos primeros son los de mayor intención de compra.
- **Orden recomendado:** el que ves arriba. Catálogo y Rosas primero porque son los que más se muestran.
- **Anclajes y conversión:** el `#` no interfiere con el tag de conversión ni con el pop-up, que sigue saliendo a los 5 segundos también en las visitas con anclaje.
- **Se cambió el canonical de `http://` a `https://`** en esta landing, junto con la `og:url` y la `og:image`. Estaban apuntando a `http` y eso genera aviso de URL no coincidente en Ads y de contenido duplicado en Search.
- **Antes de activar:** carga cada una de las seis URLs en el navegador y confirma que caen donde deben. Si el hosting redirige `https` a `http` o agrega `www`, ajusta las URL finales a la forma exacta que quede después del redirect — Ads penaliza los saltos innecesarios.

---

## Un apunte sobre la numeración

`#1`, `#2`, `#3` funcionan y no hay razón técnica para cambiarlos. Pero si más adelante reordenas los sitelinks, los números dejan de decir nada y toca abrir la página para saber qué es cada uno. Anclajes con nombre (`#catalogo`, `#rosas`, `#girasoles`, `#envios`, `#ocasiones`, `#preguntas`) se leen solos en los informes de Ads y en Analytics.

Los dejé numéricos porque así los pediste, y los dos esquemas pueden convivir: si quieres, agrego los nombrados sin tocar los números y usas los que prefieras.
