Contexto
Durante el desarrollo del proyecto Eco-Track, el equipo debía integrar una API de mapas dentro de una aplicación web utilizada para el seguimiento de actividades ambientales. El trabajo se desarrolló en un entorno remoto utilizando metodologías ágiles, comunicación principalmente asincrónica y herramientas como Slack, Jira, GitHub y Notion.
Al acercarse el cierre del Sprint apareció un inconveniente que bloqueó parte del desarrollo y obligó al equipo a coordinar la resolución sin afectar el cronograma general del proyecto.

Problema
Durante la integración de la API comenzó a producirse un error HTTP 403 (Forbidden) al intentar autenticar las solicitudes.
El inconveniente impedía avanzar con las pruebas funcionales y afectaba directamente la implementación del módulo de mapas.
Después de las primeras verificaciones se comprobó que la documentación utilizada estaba desactualizada respecto a los cambios recientes realizados en el sistema de autenticación.

Acciones realizadas
Para resolver el incidente se siguió un proceso estructurado basado en buenas prácticas de documentación y comunicación técnica.
Investigación
Revisión de los registros (logs) del servicio.
Comparación entre la documentación disponible y la implementación actual.
Validación del comportamiento en el entorno de pruebas.
Reproducción del error por diferentes integrantes del equipo.
Comunicación
Se documentó el problema mediante:
Ticket actualizado en Jira.
Comentarios técnicos estructurados.
Capturas de pantalla del error.
Video explicativo mediante Loom para evitar reuniones innecesarias.
Actualizaciones de estado en Slack utilizando comunicación asincrónica.
Post-mortem constructivo
Luego de resolver el incidente se realizó un análisis enfocado en el aprendizaje y no en la búsqueda de responsables.
Se identificaron las siguientes oportunidades de mejora:
Mantener actualizada la documentación técnica.
Revisar periódicamente los procedimientos de autenticación.
Incorporar validaciones automáticas durante la integración continua.
Mejorar la comunicación entre Backend y QA durante el Sprint.

Aprendizajes
Este incidente permitió reforzar varias prácticas importantes para el trabajo colaborativo.
La documentación actualizada evita bloqueos innecesario
La comunicación asincrónica reduce reuniones y mejora la trazabilidad.
Los comentarios claros en tickets facilitan el trabajo entre distintos equipos.
Los post-mortems orientados al aprendizaje fortalecen la mejora continua.
El feedback respetuoso acelera la resolución de problemas y mejora el clima de trabajo.
Como resultado, el equipo incorporó nuevas plantillas para documentación técnica y una revisión periódica de la documentación antes de comenzar cada Sprint.
  
Update conclusion

Improve feedback reflection

docs: improve lessons learned section
