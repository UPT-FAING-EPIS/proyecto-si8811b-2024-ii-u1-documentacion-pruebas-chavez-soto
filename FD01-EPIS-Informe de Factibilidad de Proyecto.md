# Informe de Factibilidad

## Sistema de Control de Asistencia de Estudiantes

### Versión 1.0

## 1. Descripción del Proyecto

### 1.1 Nombre del proyecto
Desarrollo de una aplicación web y móvil para el control de asistencia de estudiantes

### 1.2 Duración del proyecto
7 semanas

### 1.3 Descripción
El proyecto consiste en el desarrollo de un sistema integral para el control de asistencia de estudiantes, que incluye una aplicación web para uso de los docentes y una aplicación móvil para los estudiantes. La aplicación web permitirá a los docentes realizar un seguimiento de la asistencia de los alumnos mediante reportes en forma de tablas y gráficos. Por otro lado, la aplicación móvil notificará a los estudiantes sobre la cantidad de inasistencias que tienen acumuladas.

Este sistema es de gran importancia ya que permitirá un seguimiento más eficiente y en tiempo real de la asistencia de los estudiantes, facilitando la labor de los docentes y promoviendo la responsabilidad de los alumnos al mantenerlos informados sobre sus inasistencias.

### 1.4 Objetivos

#### 1.4.1 Objetivo general
Desarrollar e implementar un sistema de control de asistencia de estudiantes que mejore la eficiencia en el seguimiento de la asistencia y promueva la responsabilidad de los alumnos.

#### 1.4.2 Objetivos Específicos
1. Diseñar y desarrollar una aplicación web para el registro y seguimiento de asistencia por parte de los docentes.
2. Crear una aplicación móvil que notifique a los estudiantes sobre sus inasistencias acumuladas.
3. Implementar un sistema de reportes en forma de tablas y gráficos para facilitar el análisis de la asistencia.
4. Establecer una infraestructura en la nube utilizando Azure y Terraform para garantizar la escalabilidad y disponibilidad del sistema.

## 2. Riesgos
- Dificultades en la integración entre la aplicación web y móvil.
- Posibles problemas de rendimiento al manejar grandes volúmenes de datos de asistencia.
- Resistencia al cambio por parte de algunos docentes o estudiantes.
- Problemas de seguridad en el manejo de datos sensibles de los estudiantes.
- Dificultades en la implementación de la infraestructura en Azure utilizando Terraform.

## 3. Análisis de la Situación actual

### 3.1 Planteamiento del problema
Actualmente, el control de asistencia de estudiantes se realiza de manera manual o utilizando sistemas obsoletos, lo que resulta en procesos ineficientes y propensos a errores. Los docentes invierten mucho tiempo en el registro y seguimiento de la asistencia, y los estudiantes no tienen un medio fácil para consultar sus inasistencias acumuladas. Esto puede llevar a problemas académicos y administrativos.

### 3.2 Consideraciones de hardware y software

#### Hardware:
- Servidores en la nube de Azure para hospedar la aplicación web y la API.
- Dispositivos móviles (smartphones) para la aplicación móvil de los estudiantes.
- Computadoras o tablets para que los docentes accedan a la aplicación web.

#### Software:
- Frontend Web: JavaScript y JSON
- Frontend Móvil: Desarrollo en MAUI
- Backend: Node.js y Go
- Infraestructura: Terraform para la gestión de recursos en Azure
- Base de datos: [Especificar el tipo de base de datos a utilizar]
- Servicios en la nube: Azure (Resource Group, Storage Account, Blob Storage)

## 4. Estudio de Factibilidad

### 4.1 Factibilidad Técnica
El proyecto es técnicamente factible debido a:
- La disponibilidad de tecnologías maduras para el desarrollo web (JavaScript) y móvil (MAUI).
- La existencia de frameworks robustos para el backend (Node.js y Go).
- La posibilidad de utilizar servicios en la nube de Azure para garantizar la escalabilidad y disponibilidad.
- El uso de Terraform para la gestión de la infraestructura, lo que facilita el despliegue y mantenimiento.

### 4.2 Factibilidad económica
[Aquí se deberían incluir los costos estimados del proyecto, incluyendo desarrollo, infraestructura, y mantenimiento. También se debería comparar con los beneficios económicos esperados.]

### 4.3 Factibilidad Operativa
El sistema propuesto mejorará significativamente la eficiencia en el control de asistencia. Los docentes podrán acceder fácilmente a los reportes de asistencia, y los estudiantes recibirán notificaciones automáticas sobre sus inasistencias. La interfaz intuitiva de ambas aplicaciones facilitará su adopción por parte de los usuarios.

### 4.4 Factibilidad Legal
[Aquí se debería incluir información sobre las leyes y regulaciones relevantes relacionadas con el manejo de datos de estudiantes y la protección de la privacidad.]

### 4.5 Factibilidad Social
El proyecto tendrá un impacto social positivo al promover la responsabilidad de los estudiantes y facilitar la labor de los docentes. Además, proporcionará datos valiosos para la toma de decisiones educativas.

### 4.6 Factibilidad Ambiental
Al ser un sistema digital, reducirá el uso de papel asociado con los métodos tradicionales de control de asistencia, contribuyendo así a la sostenibilidad ambiental.

## 5. Análisis Financiero
[Aquí se debería incluir un análisis detallado de los costos y beneficios financieros del proyecto, incluyendo el cálculo del ROI, VAN y TIR.]

## 6. Conclusiones
Basándonos en el análisis de factibilidad realizado, podemos concluir que el proyecto de desarrollo de una aplicación web y móvil para el control de asistencia de estudiantes es viable y factible. Los beneficios en términos de eficiencia, acceso a la información y promoción de la responsabilidad estudiantil superan los costos y riesgos asociados. 

La combinación de tecnologías modernas para el desarrollo web y móvil, junto con la infraestructura en la nube de Azure gestionada por Terraform, proporciona una base sólida para la implementación exitosa del sistema. Se recomienda proceder con el desarrollo del proyecto, prestando especial atención a la seguridad de los datos y la facilidad de uso para garantizar una adopción exitosa por parte de docentes y estudiantes.
