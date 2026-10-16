# Modelamiento de Software - CP1
### SHCE SaludIntegral - Trabajo Final Integrador

*Estudiante:* Armando Sebastian Peliza
*Materia:* Modelamiento de Software
*Docente:* Ing. Guevara

#### 1. Descripción breve del sistema
El sistema SHCE (Sistema Hospitalario de Control de Expedientes) de la clínica SaludIntegral gestiona de forma integral los expedientes clínicos de pacientes, el agendamiento de citas médicas validando identidad y disponibilidad de agenda, y el soporte al proceso asistencial del médico durante la consulta (registro de atención, receta y solicitud/incorporación de exámenes de laboratorio).

#### 2. Relación de diagramas
*Caso de Estudio:* Registrar cita médica
- *Diagrama de Casos de Uso:* Modela los actores (Admisión/Admin, Médico, Paciente, Laboratorio) y las relaciones include/extend. Incluye los casos Consultar disponibilidad y Solicitar exámenes.
- *Diagrama de Secuencia:* Vista temporal de la interacción para registrar cita, con los mensajes recuperarExpedientePorID(), consultarDisponibilidad() y registrarCita().
- *Diagrama de Comunicación:* Vista de colaboración con la misma interacción numerada, validando la trazabilidad con el diagrama de secuencia.

Los tres diagramas son coherentes y trazables entre sí.
