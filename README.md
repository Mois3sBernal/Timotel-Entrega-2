# Hospedaje El Timotel

Sitio web de reservas del Hospedaje El Timotel (Sahagún, Córdoba).
Proyecto de Diseño Web - Universidad de Córdob

## Estructura
- `index.html`, `habitaciones.html`, `habitacion.html`, `servicios.html`, `informacion.html`, `contacto.html`, `reservar.html`
- `css/styles.css`: estilos de todo el sitio
- `js/utils.js`: funciones compartidas (fetch, loaders, errores, localStorage, validación)
- `js/inicio.js`, `habitaciones.js`, `habitacion.js`, `servicios.js`, `reservar.js`, `contacto.js`: un módulo por página
- `data/habitaciones.json`, `data/servicios.json`: datos que se consumen con fetch
- `img/`: fotos

## Avance 2 (JavaScript)
- DOM y eventos: submit, click, input y change, con `event.preventDefault()`.
- Fetch con async/await, manejo de errores 404 y 500 con try/catch, loaders y mensajes de error.
- localStorage: reservas (crear, editar, eliminar) y mensajes de contacto en formato JSON.
- Validaciones en tiempo real con bordes y mensajes en línea.
