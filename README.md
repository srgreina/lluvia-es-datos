# lluvia-es-datos

Datos abiertos de lluvia en España (AEMET): horario, diario y mensual. Fase actual: provincia de Málaga.

Generado automáticamente por [`lluvia-es-app`](https://github.com/srgreina/lluvia-es-app). No editar a mano.

Fuente: © AEMET (AEMET OpenData), uso permitido citando a AEMET como autora.

## Contenido
- `estaciones.json`: catálogo de estaciones usadas.
- `municipios.json`: municipios con centroide.
- `municipio_estacion.json`: estación más cercana de cada municipio, con distancia en km y aviso de dato orientativo.
- `latest.json`: últimas 24 h por estación (serie horaria y acumulados 1 h / 6 h / 24 h).
- `horario/AAAA/MM.parquet`: histórico horario (`estacion`, `fecha_utc`, `prec_mm`, `origen`).

Unidades: precipitación en mm (= l/m²). Fechas en UTC.
