# FleteAgro

Cotizador y simulador de fletes para productoras agrícolas sobre rutas reales. Es un solo archivo, `index.html`: ábrelo en el navegador con conexión a internet (o publícalo, por ejemplo, con GitHub Pages).

- **Vehículo**: pick-up, camión ligero, mediano, pesado, tractocamión o refrigerado. Capacidad, velocidad, tarifa por km y rendimiento se pueden editar.
- **Carga**: producto, toneladas y presentación. Calcula los viajes necesarios y el aprovechamiento de la unidad.
- **Ruta**: origen, destino y paradas se escriben libremente y se eligen entre sugerencias de lugares reales. La ruta se traza por carretera y la distancia sale de esa ruta.
- **Costos**: moneda, diésel, maniobras, peajes, IVA y retorno en vacío.
- **Simulación**: el vehículo (o el convoy) avanza sobre el mapa real con hora simulada, kilómetros, velocidad, paradas y bitácora.
- **Historial**: los fletes generados se guardan en el navegador (localStorage) para volver a simularlos.

## Servicios externos (gratuitos, sin clave)

| Uso | Servicio |
| --- | --- |
| Mapa | [Leaflet](https://leafletjs.com/) con mosaicos estándar de [OpenStreetMap](https://www.openstreetmap.org/copyright) |
| Sugerencias de lugares | [Photon](https://photon.komoot.io/) (komoot) |
| Rutas por carretera | [OSRM](https://project-osrm.org/) (servidor de demostración; respaldo: routing.openstreetmap.de) |

Estos servidores públicos tienen límites de uso razonable. Para uso intensivo o comercial conviene contratar un proveedor o montar servidores propios de Photon y OSRM y cambiar las URL `GEOCODER` y `ROUTERS` en el script.
