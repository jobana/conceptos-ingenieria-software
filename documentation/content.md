Eje 1: Marcos y Metodologías 🗺️

Definición: Enfoques estructurados para gestionar el ciclo de vida del desarrollo de software, abarcando desde la planificación hasta la entrega y el mantenimiento.

Agile (Filosofía): Conjunto de valores y principios que priorizan a los individuos, el software funcional, la colaboración con el cliente y la respuesta al cambio sobre procesos rígidos y documentación exhaustiva.

Scrum: Marco de trabajo para gestionar proyectos complejos de forma iterativa, utilizando ciclos fijos llamados Sprints, con roles y eventos definidos para fomentar la inspección y adaptación.

Kanban: Método visual para gestionar el flujo de trabajo. Se enfoca en limitar el trabajo en progreso (WIP) para identificar cuellos de botella y maximizar la eficiencia en la entrega.

XP (Extreme Programming): Metodología centrada en la calidad técnica y la excelencia en la programación a través de prácticas como el Desarrollo Guiado por Pruebas (TDD) y la Programación en Pares.

Scrumban: Un modelo híbrido que utiliza la estructura prescriptiva de Scrum (roles, reuniones) con la flexibilidad del sistema de flujo de Kanban para gestionar el trabajo.

Lean: Filosofía originada en la manufactura, enfocada en maximizar el valor para el cliente eliminando sistemáticamente el desperdicio (actividades que no agregan valor).

RAMA: Metodologías Predictivas (Planificación)

Definición: Enfoques secuenciales donde la planificación se realiza de forma exhaustiva al inicio del proyecto, con el objetivo de seguir un plan predefinido.

Cascada (Waterfall): Modelo secuencial donde cada fase (requisitos, diseño, implementación, etc.) debe completarse antes de iniciar la siguiente. Es poco flexible a los cambios.

PMI / PMBOK: Un estándar para la gestión de proyectos que describe un conjunto de procesos y áreas de conocimiento (alcance, tiempo, costo, etc.) considerados buenas prácticas. No es una metodología, sino una guía.

PRINCE2 (PRojects IN Controlled Environments): Metodología de gestión de proyectos orientada a procesos, con un fuerte enfoque en la justificación del negocio, la organización y el control del proyecto por fases.

RAMA: Gestión y Mejora de Procesos

Definición: Disciplinas enfocadas en optimizar los procesos de negocio y desarrollo para mejorar la calidad y la eficiencia.

Six Sigma: Metodología basada en datos para eliminar defectos en cualquier proceso. Su objetivo es alcanzar un nivel de calidad de 99.99966% de productos libres de defectos.

Cadena Crítica (CCPM): Método de gestión de proyectos que se enfoca en los recursos necesarios para ejecutar las tareas y utiliza "buffers" de tiempo para proteger la fecha de finalización del proyecto contra la incertidumbre.


Eje 2: Arquitectura de Software 🏛️
NODO CENTRAL: ARQUITECTURA DE SOFTWARE

Definición: Es el "plano" estructural de una aplicación que define cómo funciona por dentro.

RAMA: Patrones Arquitectónicos

Definición: Son soluciones probadas para problemas comunes de diseño.

Monolito: Toda la aplicación en un solo bloque.

Cliente-Servidor: Separa la interfaz de usuario (cliente) del procesamiento de datos (servidor).

SOA: Conjunto de servicios de negocio que colaboran entre sí.

Microservicios: La aplicación se divide en pequeños servicios independientes.

Hexagonal: Aísla la lógica de negocio de la tecnología externa (BD, UI).

DDD: Modela el software para que refleje fielmente el negocio.

RAMA: Marcos de Arquitectura

Definición: Son guías y reglas estandarizadas para diseñar y gobernar la arquitectura.

TOGAF: Un método paso a paso para desarrollar y gestionar la arquitectura a nivel empresarial.

Zachman Framework: Una matriz para clasificar y asegurar que todos los aspectos de la arquitectura (qué, cómo, quién, dónde...) estén cubiertos.

C4 Model: Un modelo para visualizar la arquitectura de software en 4 niveles de detalle (Contexto, Contenedores, Componentes y Código).

RAMA: Atributos de Calidad

Definición: Miden "qué tan bien" funciona el software.

Escalabilidad: Capacidad de crecer y manejar más usuarios.

Rendimiento: Rapidez y eficiencia de la aplicación.

Disponibilidad: Garantía de que el sistema esté siempre en línea.

Mantenibilidad: Facilidad para corregir errores o hacer cambios.

Seguridad: Capacidad de defenderse contra ataques.

Eje 3: Ciberseguridad en el Desarrollo 🛡️
NODO CENTRAL: CIBERSEGURIDAD (DEVSECOPS)

Definición: Integrar la seguridad en todo el proceso de creación de software.

RAMA: Amenazas y Vulnerabilidades

Definición: Son los fallos y riesgos que pueden ser explotados por atacantes.

Inyección de Código: Engañar a la aplicación para que ejecute código malicioso.

Pérdida de Autenticación: Fallos que permiten a un atacante robar la identidad de un usuario.

Cross-Site Scripting (XSS): Inyectar scripts maliciosos en una web para que afecten a otros usuarios.

Componentes Vulnerables: Usar librerías de terceros con fallos de seguridad conocidos.

Configuraciones Incorrectas: Dejar ajustes por defecto que son inseguros.

RAMA: Prácticas de Seguridad ("Shift-Left")

Definición: Aplicar la seguridad desde el inicio del desarrollo, no al final.

SAST: Analizar el código fuente para encontrar fallos antes de ejecutarlo.

DAST: Probar la aplicación en funcionamiento para detectar vulnerabilidades.

SCA: Revisar las librerías externas para encontrar fallos conocidos.

Pentesting: Simular un hackeo para descubrir debilidades.