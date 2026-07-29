# Environmental Satellite Analysis Portfolio

Portafolio de **15 análisis satelitales reproducibles** orientados a GIS, remote sensing y políticas ambientales y sociales.

## Tecnologías

- Python
- Google Earth Engine
- geemap
- Sentinel-1 y Sentinel-2
- Landsat Collection 2
- CHIRPS
- MODIS
- JRC Global Surface Water
- Dynamic World
- SRTM

## Configuración

1. Crea o selecciona un proyecto de Google Cloud con Earth Engine habilitado.
2. Abre cada notebook en Google Colab.
3. Reemplaza `TU_PROYECTO_GEE` por tu Project ID.
4. Ejecuta las celdas de autenticación.
5. Cambia el área de estudio, las fechas y los parámetros según tu investigación.

```python
import ee
ee.Authenticate()
ee.Initialize(project="TU_PROYECTO_GEE")
```

## Proyectos

| Nº | Notebook | Resultado principal |
|---:|---|---|
| 01 | Sentinel-2 RGB reciente | Mosaico de color verdadero |
| 02 | NDVI | Salud y densidad de vegetación |
| 03 | NDWI/MNDWI | Agua superficial |
| 04 | NBR/dNBR | Severidad de incendios |
| 05 | Cambio de vegetación | Pérdida y ganancia |
| 06 | Dynamic World | Cobertura terrestre |
| 07 | Fragmentación forestal | Núcleo y bordes |
| 08 | Proxy de carbono | Prioridad para inventarios |
| 09 | CHIRPS | Anomalía de precipitación |
| 10 | Landsat LST | Temperatura superficial |
| 11 | NDBI | Expansión urbana |
| 12 | Sentinel-1 | Inundaciones |
| 13 | Presión sobre biodiversidad | Índice multicriterio |
| 14 | Accesibilidad territorial | Distancias a servicios |
| 15 | Tablero territorial | Integración de indicadores |

## Estructura de cada notebook

- Pregunta de análisis
- Fuentes de datos
- Procesamiento
- Mapa interactivo
- Estadísticas básicas
- Exportación opcional
- Interpretación para política pública
- Limitaciones metodológicas

## Territorios sugeridos

- Amazonas: bosques montanos, turismo y biodiversidad
- Loreto: deforestación, carbono y comunidades
- Lima: expansión urbana, humedales e islas de calor
- Apurímac: agua, agricultura y vulnerabilidad climática

## Nota metodológica

Los productos son exploratorios y educativos. No sustituyen inventarios de campo, estudios de riesgo, evaluaciones de impacto ambiental ni verificaciones de carbono.
