# Liga El Dorado

App de la liga de fútbol Liga El Dorado: partidos, equipos y compra de boletas.

## Prototipo

Prototipo navegable en HTML, con modo claro y oscuro (datos de ejemplo):

**https://cristiancrea.github.io/liga-el-dorado/**

Para cambiar entre modo claro y oscuro usa el selector **Apariencia** del panel lateral (en computador) o de la pantalla **Perfil** (en el celular). También puedes abrir el prototipo directo en modo oscuro agregando `#oscuro` al final del enlace.

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

### Pantallas en modo oscuro

Todas las pantallas tienen versión oscura en la sección *Liga el dorado* de la página *Mockup*. Usan el modo **Dark** de la colección de variables *Tokens*; los valores del modo oscuro del prototipo HTML son los mismos.

| Pantalla | Figma |
|---|---|
| Próximos encuentros | [42:1827](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=42-1827) |
| Equipo · Info del club | [42:1846](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=42-1846) |
| Equipo · Próximos partidos | [43:1380](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=43-1380) |
| Compra · 1 Selección de boletas | [43:1411](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=43-1411) |
| Compra · 2 Datos y pago | [43:1429](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=43-1429) |
| Compra · 3 Confirmación | [43:1463](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=43-1463) |
| Partido · Resumen | [43:1509](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=43-1509) |
| Partido · Alineaciones | [43:1572](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=43-1572) |
| Siguiendo | [43:1663](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=43-1663) |
| Perfil | [43:1674](https://www.figma.com/design/O72IfV29ZUupkthYAASwE7/Liga-el-dorado?node-id=43-1674) |

## Estructura

| Archivo | Uso |
|---|---|
| `index.html` | Página de entrada; redirige al prototipo. |
| `prototipo/index.html` | Prototipo completo, listo para abrir en el navegador. |
| `prototipo/app.html` | El mismo prototipo sin la envoltura `<html>`, usado para publicarlo como artifact de Claude. |

Para verlo sin internet, descarga el repositorio y abre `prototipo/index.html` en el navegador.
