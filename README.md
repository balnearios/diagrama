# diagrama
flowchart LR
    A(Inicio) --> B{Planificación}
    B --> C(Definición del problema)
    B --> D(Objetivos)
    B --> E(Plan de acción)
    B --> F(Plan de control)
    B --> G{Ejecución}
    G --> H(Asignación de recursos)
    G --> I(Formación de equipos)
    G --> J(Ejecución de tareas)
    G --> K{Control}
    K -- Sí --> J
    K -- No --> L(Fin)
