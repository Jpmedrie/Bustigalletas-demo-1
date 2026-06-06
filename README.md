# 🍪 Bustigalletas — Landing Page

Landing page premium para **Bustigalletas**, marca artesanal de galletas rellenas con sede en **Mérida, Yucatán, México**.

---

## ✅ Características implementadas

| Sección | Estado |
|---|---|
| Navbar fijo con transición scroll | ✅ |
| Menú hamburger para móvil | ✅ |
| Hero 100vh con overlay + grain texture artesanal | ✅ |
| Trust Bar fondo chocolate #2B1204, números #C56E23, 64px con barra decorativa | ✅ |
| Menú-estilo galería de 6 productos (filas horizontales, foto + contenido) | ✅ |
| Sección "Cómo funciona tu pedido" (4 pasos) | ✅ |
| Pedidos especiales (2 columnas) | ✅ |
| Testimonios con carrusel automático | ✅ |
| CTA Final | ✅ |
| Footer 3 columnas con logo forzado a blanco (filter) | ✅ |
| Botón flotante WhatsApp con pulso | ✅ |
| Popup catálogo full-screen (grid 2 col, sticky footer) | ✅ |
| Animaciones reveal on-scroll (IntersectionObserver) | ✅ |
| Reducción de movimiento (`prefers-reduced-motion`) | ✅ |
| Responsive: desktop / tablet / móvil | ✅ |
| Fallbacks elegantes si imágenes no cargan | ✅ |
| Títulos de sección con barra decorativa naranja 60px | ✅ |
| Tags de sección con barra vertical | en lugar de emoji | ✅ |
| Zero console errors | ✅ |

---

## 🔄 Cambios aplicados en esta versión

### CHANGE 1 — Trust Bar colors
- Fondo: `#9CD8E9` → `#2B1204` (chocolate profundo)
- Números: `→ #C56E23` (naranja Bustigalletas)
- Etiquetas: `→ rgba(255,255,255,0.75)` (blanco suave)

### CHANGE 2 — Products: menu-style layout
- Eliminada la grid de tarjetas 3 columnas
- Nueva lista estilo menú de restaurante premium
- Cada fila: foto 140×140px (rounded-xl) + nombre Playfair 22px + descripción + badge + link "Pedir →"
- Hover: fondo `#FDF6EE` con transición 0.2s
- Max-width 760px centrado
- CTA "Ver catálogo completo y pedir" debajo de la lista

### CHANGE 3 — Popup catálogo full-screen
- Overlay `rgba(43,18,4,0.85)` + `backdrop-filter: blur(4px)`
- Modal: bg `#FDF6EE`, max-width 720px, max-height 85vh, border-radius 20px
- Animación: scale 0.95→1 + opacity 0→1, 0.25s ease-out
- Header: logo + H2 "Nuestro catálogo" + subtexto + divider naranja
- Grid 2 columnas (1 en móvil) de 6 tarjetas de producto
- Cada tarjeta: imagen 160px, nombre, descripción, badge, precio, botón WhatsApp
- Footer sticky: mezclar sabores → WhatsApp
- Cierra con botón ×, click en overlay, tecla ESC

### CHANGE 4 — Visual style refinements
- **4a Hero grain**: overlay de textura noise SVG al 3% de opacidad
- **4b Section titles**: barra decorativa 60×3px `#C56E23` debajo de cada h2
- **4c Typography tags**: reemplazados emojis con barra vertical `|` en naranja
- **4d Footer logo**: `filter: brightness(0) invert(1)` → logo siempre blanco
- **4e Trust Bar numbers**: 64px con barra decorativa naranja bajo cada cifra

---

## 📁 Estructura del proyecto

```
index.html                        ← Archivo único (CSS + JS inline)
Logo sin fondo.png                ← Logo de la marca
Hero.jpg                          ← Imagen de fondo del hero
Brownie_rellena.jpg               ← Foto producto 1
Chispas_chocolate_partida.jpg     ← Foto producto 2
Red_Velvet_relleno_queso_crema_2.jpg ← Foto producto 3
Evento_especial.jpg               ← Foto pedidos especiales
README.md                         ← Este archivo
```

> Los productos 4 (Oreo V), 5 (Lotus) y 6 (Rosquita de fresa) usan gradientes de color como placeholder hasta que se suban sus fotos reales.

---

## 🚀 Siguiente pasos recomendados

1. **Subir fotos de Oreo V, Lotus y Rosquita** — nombrarlas `Oreo_V.jpg`, `Lotus_choco_blanco.jpg`, `Rosquita_fresa.jpg` y reemplazar los gradientes.
2. **Añadir precios reales** — sustituir "Consultar precio" en el popup por los precios actuales.
3. **Google Analytics / Meta Pixel** — añadir snippet en el `<head>` para medir visitas y conversiones.
4. **Open Graph tags** — imagen social y metadata para compartir en redes sociales.
5. **Dominio propio** — conectar `bustigalletas.com` o similar en la pestaña Publish.

---

## 🌐 Despliegue

Para publicar la página ve a la pestaña **Publish** y haz clic en el botón de despliegue. El sitio quedará disponible en la URL asignada.

---

## 📞 Contacto en la página

- **WhatsApp**: https://wa.me/529991369402
- **Entregas**: Martes y jueves, Mérida, Yucatán, México
