# Historias de Usuario Principales (MVP)

1. **Crear partido** (Alta)
   - **Como** capitán
   - **Quiero** crear un partido indicando fecha, horario, lugar y costo
   - **Para** organizar el encuentro semanal del equipo
   - **Criterios de aceptación**:
     - Se debe poder ingresar fecha, hora y ubicación
     - Se debe poder definir el costo del partido
     - El partido queda visible para todos los miembros del equipo
     - Se envía una notificación automática a los jugadores

2. **Confirmar asistencia** (Alta)
   - **Como** jugador
   - **Quiero** indicar si asistiré al partido
   - **Para** que el capitán tenga control de los participantes
   - **Criterios de aceptación**:
     - Estados disponibles: CONFIRMADO / NO ASISTE / PENDIENTE
     - El estado puede modificarse
     - El cambio se refleja en tiempo real para el equipo
     - *Consideración UI:* Acción simple, ojalá en un solo toque.

3. **Confirmar pago** (Alta)
   - **Como** jugador
   - **Quiero** registrar mi pago adjuntando comprobante
   - **Para** confirmar mi participación en el partido
   - **Criterios de aceptación**:
     - Se puede marcar como pagado
     - Se puede adjuntar comprobante (imagen o archivo)
     - El estado cambia a PAGADO
     - El capitán puede visualizar el comprobante
