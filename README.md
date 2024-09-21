# Proyecto "Desarrollo de una aplicación web y móvil para el control de asistencia de estudiantes"

## Historias de Usuario para Docentes

### HU-D01: Inicio de sesión
Como docente, quiero poder iniciar sesión en la aplicación web de forma segura, para acceder a las funcionalidades del sistema.

**Criterios de aceptación:**
1. Debe haber un formulario de inicio de sesión con campos para usuario y contraseña.
2. El sistema debe validar las credenciales del usuario.
3. En caso de credenciales incorrectas, se debe mostrar un mensaje de error.
4. Después de un inicio de sesión exitoso, se debe redirigir al docente a su dashboard.

### HU-D02: Registro de asistencia
Como docente, quiero poder registrar la asistencia de los estudiantes para cada clase, para mantener un registro preciso de la participación.

**Criterios de aceptación:**
1. Debe haber una lista de todos los estudiantes inscritos en la clase.
2. Debe ser posible marcar a cada estudiante como presente, ausente o con retraso.
3. Debe ser posible registrar la asistencia para una fecha específica.
4. El sistema debe guardar automáticamente los cambios en tiempo real.

### HU-D03: Generación de reportes
Como docente, quiero poder generar reportes de asistencia en forma de tablas y gráficos, para analizar las tendencias de asistencia.

**Criterios de aceptación:**
1. Debe haber una opción para generar reportes.
2. Los reportes deben poder filtrarse por clase, período de tiempo y estudiante.
3. Los reportes deben presentarse en formato de tabla y gráfico.
4. Debe ser posible exportar los reportes en formatos PDF y Excel.

### HU-D04: Modificación de registros de asistencia
Como docente, quiero poder modificar registros de asistencia pasados, para corregir errores o actualizar información.

**Criterios de aceptación:**
1. Debe haber una opción para ver y editar registros de asistencia pasados.
2. Los cambios deben guardarse y reflejarse inmediatamente en los reportes.
3. Debe quedar un registro de la modificación (quién la hizo y cuándo).

### HU-D05: Visualización de tendencias
Como docente, quiero poder ver tendencias de asistencia por estudiante, clase o período, para identificar patrones y tomar decisiones informadas.

**Criterios de aceptación:**
1. Debe haber una sección de análisis de tendencias.
2. Se deben mostrar gráficos interactivos que ilustren las tendencias de asistencia.
3. Debe ser posible filtrar las tendencias por estudiante, clase y período de tiempo.

## Historias de Usuario para Estudiantes

### HU-E01: Inicio de sesión móvil
Como estudiante, quiero poder iniciar sesión en la aplicación móvil de forma segura, para acceder a mi información de asistencia.

**Criterios de aceptación:**
1. Debe haber un formulario de inicio de sesión con campos para usuario y contraseña.
2. El sistema debe validar las credenciales del usuario.
3. En caso de credenciales incorrectas, se debe mostrar un mensaje de error.
4. Después de un inicio de sesión exitoso, se debe mostrar el dashboard del estudiante.

### HU-E02: Visualización de resumen de asistencia
Como estudiante, quiero poder ver un resumen de mi asistencia para cada clase, para estar al tanto de mi participación.

**Criterios de aceptación:**
1. Debe haber una lista de todas las clases en las que está inscrito el estudiante.
2. Para cada clase, se debe mostrar el número de asistencias, ausencias y retrasos.
3. Debe ser posible ver el porcentaje de asistencia para cada clase.

### HU-E03: Notificaciones de inasistencias
Como estudiante, quiero recibir notificaciones sobre mi cantidad de inasistencias, para estar al tanto de mi situación académica.

**Criterios de aceptación:**
1. La aplicación debe enviar notificaciones push cuando se alcancen ciertos umbrales de inasistencias.
2. Las notificaciones deben ser claras y especificar la clase y el número de inasistencias.
3. Debe ser posible configurar la frecuencia de las notificaciones.

### HU-E04: Visualización de calendario de asistencia
Como estudiante, quiero ver un calendario con mis días de asistencia e inasistencia, para tener una visión general de mi participación en clases.

**Criterios de aceptación:**
1. Debe haber una vista de calendario mensual.
2. Los días de asistencia, inasistencia y retraso deben estar claramente marcados con diferentes colores.
3. Al tocar un día específico, se debe mostrar el detalle de las clases de ese día.

### HU-E05: Justificación de inasistencias
Como estudiante, quiero poder enviar justificaciones por mis inasistencias, para informar a mis docentes sobre las razones de mis ausencias.

**Criterios de aceptación:**
1. Debe haber una opción para justificar una inasistencia específica.
2. Se debe poder adjuntar documentos o imágenes como prueba de la justificación.
3. El sistema debe notificar al docente correspondiente sobre la justificación enviada.
4. El estudiante debe poder ver el estado de sus justificaciones (pendiente, aprobada, rechazada).
