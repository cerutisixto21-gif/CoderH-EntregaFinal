# Triage y Respuesta Automatizada de Consultas — ADC

**Curso:** IA Automation Avanzada — Coder House  
**Alumno:** Sixto  
**Entrega:** Proyecto Final

## Descripción

Sistema de triage automatizado de consultas por email para el software ADC, orientado a nutricionistas. Cuando llega un email, n8n lo clasifica con IA, consulta una base de conocimiento (RAG), solicita aprobación humana en Slack, envía la respuesta por Gmail y registra la trazabilidad en Airtable.

**Stack:** n8n · Airtable · Groq · Gmail · Slack

## Entregables

- [Entregable 1 — Diagrama de Arquitectura](./Entregable%201%20-%20Diagrama%20de%20Arquitectura%20-%20ADC.pdf)
- [Entregable 2 — Manual Operativo de Datos](./Entregable%202%20-%20Manual%20Operativo%20de%20Datos%20-%20ADC.pdf)
- [Entregable 3 — Matriz de Costos](./Entregable%203%20-%20Matriz%20de%20Costos%20-%20ADC.pdf)
- [Entregable 4 — Seguridad y Resiliencia](./Entregable%204%20-%20Seguridad%20y%20Resiliencia%20-%20ADC.pdf)
- [Entregable 5 — Dashboard de Control](./Entregable%205%20-%20Dashboard%20de%20Control%20-%20ADC.pdf)

## Workflow de n8n

[JSON exportado del workflow](./Triage_y_Respuesta_Automatizada_de_Consultas_ADC.json), listo para importar en n8n.

## Evidencias de ejecución

- [Ejecución n8n #116 exitosa](./01-ejecucion-116-exitosa.jpg)
- [Aprobación humana en Slack](./03-aprobacion-humana-slack.jpg)
- [Respuesta enviada por Gmail](./02-respuesta-gmail-enviada.jpg)

## Airtable

- [Dashboard público](https://airtable.com/appRVvAowAEEgQAvF/shrjfXrFe32q7KkRJ)
- [Base de datos en modo lectura](https://airtable.com/appRVvAowAEEgQAvF/shrY9ejd6yByPFuiN)

## Video demo

El video demostrará el trigger de Gmail, el procesamiento de n8n y el resultado final. La guía de grabación se incorporará cuando el video esté listo.
