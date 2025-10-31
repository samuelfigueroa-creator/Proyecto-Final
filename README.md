# Proyecto-Final
Diagrama de clases : https://github.com/samuelfigueroa-creator/Proyecto-Final/blob/main/DiagramaClases%20(2).pdf
💧 Sistema de Control Automático de Llenado de Tanque de 3 Niveles
¡Bienvenidos al proyecto Sistema de Control Automático de Llenado de Tanque de 3 Niveles!
Este sistema permite automatizar el llenado de un tanque de agua mediante sensores de nivel y control inteligente a través de una interfaz web conectada a Adafruit IO, integrando el uso del microcontrolador ESP32.
Nuestro objetivo es crear una solución eficiente, confiable y práctica para el control de sistemas de bombeo y almacenamiento de agua, combinando hardware, software e Internet de las Cosas (IoT).

🧠 Descripción del Proyecto
El sistema está diseñado para controlar de forma automática y manual el llenado de un tanque, utilizando tres sensores de nivel (bajo, medio y alto) que detectan la cantidad de agua disponible.
Cuando el nivel baja del punto mínimo, la bomba se activa automáticamente hasta alcanzar el nivel máximo, momento en el cual se detiene para evitar desbordamientos.
Además, el usuario puede monitorear el estado del tanque y activar/desactivar la bomba manualmente desde una interfaz en Adafruit IO, que permite enviar y recibir datos en tiempo real a través del protocolo MQTT.

🎯 Objetivo General
Desarrollar un sistema automatizado de control de llenado de tanque basado en ESP32 con conectividad IoT (Adafruit IO), que opere en modo manual o automático para optimizar el uso de agua y energía.

🎯 Objetivos Específicos


Diseñar el hardware del sistema de control de llenado.


Implementar tres sensores de nivel para la detección de niveles bajo, medio y alto.


Programar la lógica de control de la bomba mediante ESP32.


Establecer comunicación con Adafruit IO utilizando MQTT.


Crear un dashboard para monitoreo remoto del tanque y la bomba.


Documentar el desarrollo con diagramas, historias de usuario y casos de uso.



👥 Integrantes del Equipo
NombreRolResponsabilidadSamuel FigueroaLíder del Proyecto / Programador IoTCoordinación general, desarrollo del código y pruebas de integración.Sara Lucía AriasDiseñadora / Encargada de PruebasDiseño de diagramas, documentación visual y validación de funcionamiento.Leiner RodríguezEnsamblador / Pruebas de HardwareMontaje físico del sistema, verificación de sensores y actuadores.Sebastián HerreraDocumentación / Soporte TécnicoElaboración de documentos técnicos y registro de resultados.

🕐 Planificación y Reuniones
🗓️ Inicio del proyecto: 10 de septiembre de 2025
🗓️ Entrega final: 5 de diciembre de 2025
💬 Reuniones semanales: Todos los jueves (seguimiento de avances)
🧑‍🏫 Sesiones de trabajo en clase: Todos los viernes

🧩 Fases del Proyecto
FaseFechaActividades principales1. Análisis y Requerimientos10 - 20 septiembreLevantamiento de requerimientos, historias de usuario, casos de uso.2. Diseño del Sistema21 sep - 5 octDiagramas UML, planificación del hardware y diseño de la lógica de control.3. Ensamble y Pruebas Iniciales6 - 20 octMontaje del circuito, pruebas de sensores y relé.4. Desarrollo del Código21 oct - 15 novProgramación del ESP32, integración con Adafruit IO.5. Pruebas y Validación16 - 30 novPruebas integrales, depuración del código y ajustes finales.6. Entrega Final y Presentación1 - 5 dicDocumentación completa, video demostrativo y entrega final.

🚀 Tecnologías y Herramientas
TipoTecnología / HerramientaMicrocontroladorESP32Lenguaje de programaciónC / Arduino (PlatformIO)IDEVisual Studio Code con extensión PlatformIOComunicación IoTMQTT - Adafruit IOSensoresSensores de nivel (flotador o ultrasónico)ActuadorBomba de agua + módulo reléControl manualBotón físico / Dashboard Adafruit IOControl remotoDashboard Adafruit IOControl de versionesGit / GitHubDiagramasDraw.io / LucidchartDocumentaciónMarkdown / PDF

📜 Historias de Usuario Iniciales
HU-01:
Como usuario, quiero encender o apagar manualmente la bomba desde el panel web, para controlar el llenado del tanque a mi gusto.
HU-02:
Como usuario, quiero que la bomba se encienda automáticamente cuando el nivel del tanque esté bajo y se apague al estar lleno, para optimizar el uso de agua.
HU-03:
Como administrador, quiero visualizar en tiempo real el nivel del tanque y el estado de la bomba, para monitorear el sistema.
HU-04:
Como usuario, quiero recibir alertas si alguno de los sensores de nivel falla, para realizar mantenimiento oportuno.
HU-05:
Como usuario, quiero alternar entre modo automático y manual desde el dashboard, para tener control total del sistema.

⚙️ Roles del Equipo según Metodología Scrum
RolNombreFunciones🧭 Product Owner (PO)Samuel FigueroaDefine los requerimientos, valida las entregas y supervisa el desarrollo.⚙️ Scrum Master (SM)Sara Lucía AriasCoordina reuniones y garantiza el cumplimiento de la metodología Scrum.💻 Development Team (Dev Team)Leiner Rodríguez y Sebastián HerreraDesarrollan, prueban y documentan el sistema físico y lógico.

✅ Definition of Ready (DoR)
Una historia está lista para desarrollarse cuando:


Tiene una descripción clara en formato “Como [rol], quiero [acción], para [beneficio]”.


Se definieron los criterios de aceptación.


Está priorizada en el tablero del proyecto.


No depende de otra historia pendiente.



🧩 Definition of Done (DoD)
Una historia está completamente terminada cuando:


El código fue implementado y probado en el ESP32.


La funcionalidad fue verificada en Adafruit IO.


Se realizaron commit y push correctos en GitHub.


Se actualizó la documentación.


El equipo aprobó la historia tras revisión.



🧱 Estructura de Issues y Tareas del Proyecto
Fase 1: Análisis y Diseño


TASK-01: Identificación de requerimientos.


TASK-02: Elaboración de casos de uso.


TASK-03: Diseño del diagrama de flujo y de clases.


TASK-04: Documentación inicial del proyecto.


Fase 2: Desarrollo del Sistema


HU-01: Control manual desde Adafruit IO.


HU-02: Control automático según nivel de tanque.


HU-03: Notificación de fallos en sensores.


TECH-01: Programación del ESP32.


TECH-02: Integración con Adafruit IO mediante MQTT.


TECH-03: Calibración de sensores de nivel.


Fase 3: Pruebas y Entrega


TEST-01: Pruebas de hardware (bomba, relé, sensores).


TEST-02: Validación de conexión IoT.


TEST-03: Ajustes finales y presentación del sistema.



📊 Estado Actual del Proyecto
🔹 Código base: Implementado parcialmente en Visual Studio Code con PlatformIO. Se cuenta con la lectura de sensores y control básico de relé para la bomba.
🔹 Comunicación IoT: Configuración inicial del protocolo MQTT con Adafruit IO en proceso de pruebas.
🔹 Hardware: Montaje funcional del circuito con ESP32, relé y sensores de nivel.
🔹 Documentación: Historias de usuario, tareas y roles definidos; se avanza en los diagramas de flujo y clases.
🔹 Próximos pasos:


Probar comunicación completa con Adafruit IO.


Implementar la lógica de cambio entre modo manual y automático.


Diseñar el dashboard IoT y realizar pruebas integradas.



🔗 Enlaces Importantes
🧩 Casos de Uso: /Documentos/Analisis/CasosDeUso.pdf
📘 Diagrama de Estados: /Documentos/Diseño/DiagramaDeEstados.drawio
🧠 Diagrama de Clases: /Documentos/Analisis/DiagramaDeClases.drawio
🔌 Código Fuente: /Aplicacion/
🧾 Historias de Usuario: /Documentos/Analisis/HistoriasDeUsuario.pdf

