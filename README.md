# Veinte&30 CarWash — Sitio web

Sitio web oficial del lavadero, lubricentro y estación de servicio ANCAP Veinte&30, Punta del Este, Uruguay.

## Estructura del proyecto

```
lavadero_web/
├── index.html          # Estructura de la página (HTML)
├── css/
│   └── styles.css      # Todos los estilos (CSS)
├── js/
│   └── main.js         # Toda la lógica interactiva (JavaScript)
└── README.md           # Este archivo
```

## Secciones del sitio

- **Banner rotativo** de promociones (auto-avanza cada 5 segundos)
- **Hero** con estadísticas del negocio
- **Servicios** de lavado con selector de tipo de vehículo (precios en tiempo real)
- **Reservas** con calendario interactivo — lavadero y lubricentro
- **Suscripciones** por patente con 3 planes
- **Programa de fidelidad** (Rewards) con 4 niveles y canjes
- **Galería** con filtros por categoría y lightbox
- **Cafetería** con menú por pestañas
- **Car Detail** con precios por tratamiento
- **Pista ANCAP** con servicios
- **Sucursales** con horarios y Google Maps
- **Contacto** con formulario
- **Términos y Condiciones** en modal

## Cómo publicarlo en GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `veintey30`).
2. Subí estos tres archivos y la carpeta `css/` y `js/` manteniendo la estructura.
3. Andá a **Settings → Pages**.
4. En "Source" elegí la rama `main` y la carpeta `/ (root)`.
5. Guardá. En unos minutos el sitio queda publicado en:
   `https://TU-USUARIO.github.io/veintey30/`

## Cómo editar los datos

Casi todo el contenido editable (precios, servicios, planes, menú, galería) está definido como **objetos y arrays al inicio de `js/main.js`**. Para cambiar precios o agregar servicios, editá esos objetos sin tocar el resto del código.

Para cambiar los **colores de marca**, editá las variables CSS al inicio de `css/styles.css` (bloque `:root`).

## Pendientes antes de publicar

- [ ] Reemplazar los números de WhatsApp de contacto (actualmente placeholder)
- [ ] Cargar fotos reales en la galería
- [ ] Verificar precios actualizados de todos los servicios
- [ ] Confirmar horarios reales de cada sucursal
- [ ] Agregar datos reales de promociones vigentes

## Tecnología

HTML5 + CSS3 + JavaScript puro (sin frameworks ni dependencias, salvo Google Fonts). Totalmente responsive y listo para PWA.

---

© 2026 Veinte&30 · STI Ltda. · RUT 100062160016
