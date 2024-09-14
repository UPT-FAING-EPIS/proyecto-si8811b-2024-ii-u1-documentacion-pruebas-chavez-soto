# Requerimientos Funcionales y No Funcionales

### Requerimientos del Sistema

#### Requerimientos Funcionales

1. Aplicación Web (para docentes):
   - RF1: Permitir a los docentes iniciar sesión de forma segura.
   - RF2: Permitir a los docentes registrar la asistencia de los estudiantes para cada clase.
   - RF3: Generar reportes de asistencia en forma de tablas y gráficos.
   - RF4: Permitir la visualización de tendencias de asistencia por estudiante, clase o período.
   - RF5: Permitir a los docentes modificar registros de asistencia pasados en caso de errores.
   - RF6: Proporcionar una función de búsqueda para encontrar rápidamente estudiantes o clases específicas.
   - RF7: Permitir la exportación de reportes de asistencia en formatos comunes (PDF, Excel).

2. Aplicación Móvil (para estudiantes):
   - RF8: Permitir a los estudiantes iniciar sesión de forma segura.
   - RF9: Mostrar el resumen de asistencia del estudiante para cada clase.
   - RF10: Enviar notificaciones push a los estudiantes sobre su cantidad de inasistencias.
   - RF11: Permitir a los estudiantes ver un calendario con sus días de asistencia e inasistencia.
   - RF12: Proporcionar una función para que los estudiantes puedan justificar sus inasistencias.

3. Backend:
   - RF13: Implementar una API RESTful para la comunicación entre el frontend y el backend.
   - RF14: Gestionar la autenticación y autorización de usuarios (docentes y estudiantes).
   - RF15: Procesar y almacenar los datos de asistencia en tiempo real.
   - RF16: Generar y enviar notificaciones automáticas basadas en reglas predefinidas.
   - RF17: Proporcionar endpoints para la generación de reportes y análisis de datos.

#### Requerimientos No Funcionales

1. Rendimiento:
   - RNF1: El sistema debe ser capaz de manejar al menos 1000 usuarios concurrentes sin degradación significativa del rendimiento.
   - RNF2: El tiempo de respuesta para las operaciones comunes (como registro de asistencia o consulta) debe ser inferior a 2 segundos.

2. Seguridad:
   - RNF3: Todas las comunicaciones deben estar encriptadas utilizando HTTPS.
   - RNF4: Las contraseñas de los usuarios deben almacenarse de forma segura utilizando algoritmos de hash modernos.
   - RNF5: El sistema debe implementar protección contra ataques comunes (SQL injection, XSS, CSRF).

3. Disponibilidad:
   - RNF6: El sistema debe estar disponible al menos el 99.9% del tiempo (menos de 9 horas de inactividad al año).

4. Escalabilidad:
   - RNF7: La arquitectura debe permitir escalar horizontalmente para manejar un aumento en la carga de usuarios.

5. Usabilidad:
   - RNF8: La interfaz de usuario debe ser intuitiva y requerir un mínimo de entrenamiento para su uso.
   - RNF9: La aplicación móvil debe ser compatible con las últimas versiones de iOS y Android.

6. Mantenibilidad:
   - RNF10: El código debe seguir las mejores prácticas de desarrollo y estar bien documentado.
   - RNF11: Deben implementarse pruebas automatizadas con una cobertura mínima del 80%.

7. Compatibilidad:
   - RNF12: La aplicación web debe ser compatible con las últimas versiones de los navegadores más comunes (Chrome, Firefox, Safari, Edge).

8. Cumplimiento:
   - RNF13: El sistema debe cumplir con las regulaciones de protección de datos aplicables (por ejemplo, GDPR si es aplicable).

9. Recuperación ante desastres:
   - RNF14: Debe implementarse un sistema de respaldo y recuperación que permita la restauración completa de los datos en menos de 4 horas.
