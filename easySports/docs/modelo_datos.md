# Modelo de Datos (Esquema Básico)

- **Usuario:** `id` (PK), `nombre`, `telefono`, `rol` (Capitán/Jugador).
- **Equipo:** `id` (PK), `nombre`, `link_invitacion`.
- **Usuario_Equipo (Pivote):** `usuario_id` (FK), `equipo_id` (FK).
- **Partido:** `id` (PK), `equipo_id` (FK), `fecha`, `horario`, `ubicacion`, `costo`, `estado`.
- **Asistencia_Jugador:** `partido_id` (FK), `usuario_id` (FK), `estado_asistencia` (Confirmado, Pendiente, No Asiste), `estado_pago` (Pendiente, Pagado), `comprobante_url`.
