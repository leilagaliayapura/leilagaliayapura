graph TD;
  A[Contacto Inicial de Bienvenida] --> B[Verificación de Satisfacción Inicial]
  B --> C{Cliente Satisfecho}
  C -->|Sí| D[Registro de Satisfacción]
  C -->|No| E[Resolución de Incidencias]
  E --> F[Registro de Incidencias]
  F --> G[Resolución de Incidencias]
  G --> B
  D --> H[Encuesta de Satisfacción]
  H --> I[Análisis de Resultados]
