# Contratos de API Principales

- `POST /api/partidos`: Crea un partido. Body: `{ fecha, horario, lugar, costo, equipo_id }`.
- `GET /api/partidos/proximo`: Devuelve los detalles del próximo partido con la lista de convocados y sus estados.
- `PUT /api/partidos/{partido_id}/asistencias/{usuario_id}`: Actualiza el estado de asistencia.
- `POST /api/partidos/{partido_id}/pagos/{usuario_id}`: Adjunta comprobante y marca como pagado.
