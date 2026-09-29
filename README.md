# Liga El Dorado

App de la liga de fútbol Liga El Dorado: partidos, equipos y compra de boletas.

## Prototipo

Prototipo navegable en HTML (solo modo claro, datos de ejemplo):

**https://cristiancrea.github.io/liga-el-dorado/**

Pantallas incluidas:

- **Inicio**: próximos encuentros de la liga.
- **Detalle de partido**: pestañas *Resumen* (compra de boleta, últimos 5 enfrentamientos, fecha, hora, estadio y transmisión) y *Alineaciones* (alineaciones probables, expulsados y lesionados).
- **Equipo**: pestañas *Info del club* (temporada, historia, nómina) y *Próximos partidos*.
- **Compra de boletas**: selección de zona y cantidad, datos y pago, confirmación con código QR.
- **Siguiendo** y **Perfil**: secciones vacías por ahora.

El prototipo no tiene servidor ni base de datos: los datos están dentro del archivo y el pago es simulado.

## Diseño

Las pantallas, los componentes y las variables de color (modo claro y oscuro) están en Figma:
[Liga El Dorado en Figma](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado)

## Estructura

| Archivo | Uso |
|---|---|
| `index.html` | Página de entrada; redirige al prototipo. |
| `prototipo/index.html` | Prototipo completo, listo para abrir en el navegador. |
| `prototipo/app.html` | El mismo prototipo sin la envoltura `<html>`, usado para publicarlo como artifact de Claude. |

Para verlo sin internet, descarga el repositorio y abre `prototipo/index.html` en el navegador.
