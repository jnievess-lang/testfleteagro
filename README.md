# FleteAgro

Cotizador y simulador de fletes para productoras agrícolas. Es un solo archivo, `index.html`, sin dependencias: ábrelo en el navegador.

- **Vehículo**: pick-up, camión ligero, mediano, pesado, tractocamión o refrigerado. Capacidad, velocidad, tarifa por km y rendimiento se pueden editar.
- **Carga**: producto, toneladas y presentación. Calcula los viajes necesarios y el aprovechamiento de la unidad.
- **Ruta**: origen, destino, distancia, paradas intermedias y hora de salida.
- **Costos**: moneda, diésel, maniobras, peajes, IVA y retorno en vacío.
- **Simulación**: el vehículo (o el convoy) recorre la ruta en el mapa con hora simulada, kilómetros, velocidad, paradas y bitácora.
- **Historial**: los fletes generados se guardan en el navegador (localStorage) para volver a simularlos.
