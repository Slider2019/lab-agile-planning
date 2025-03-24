---
name: User story
about: Este template es para User Stories
title: ''
labels: ''
assignees: ''

---

1. ¿Qué es una Historia de Usuario?
Representa una parte del valor empresarial que un equipo puede entregar en un corto tiempo.

Va más allá de un "requisito" tradicional, ya que incluye:

¿Para quién es? (rol: cliente, administrador, director de marketing, etc.).

¿Qué necesitan? (funcionalidad concreta).

¿Por qué lo necesitan? (objetivo y valor empresarial).

Ejemplo:

Como gerente de marketing, necesito una lista de correos de clientes para notificar promociones.

2. Partes de una Buena Historia de Usuario
Descripción del valor:

Rol + Necesidad + Beneficio empresarial (ej: aumentar ventas mediante promociones).

Suposiciones y detalles:

Información técnica relevante (ej: "usar base de datos relacional" o "clientes deben haber optado por promociones").

Criterios de Aceptación (Definición de "Terminado"):

Escrito en sintaxis Gherkin (Given-When-Then):

Ejemplo:

Dado 100 clientes en la base de datos y 90 han optado por promociones,

Cuando se solicita la lista de correos,

Entonces se muestran 90 correos.

3. Importancia de los Criterios de Aceptación
Evitan malentendidos al definir qué se considera completado.

Son comprobables y medibles, usando ejemplos claros.

Permiten alineación entre desarrolladores y stakeholders (ej: el gerente de marketing valida que solo se incluyan correos opt-in).

4. Acrónimo INVEST para Historias Bien Formadas
Independientes: Minimizar dependencias con otras historias.

Negociables: Flexibilidad en cómo implementar la funcionalidad.

Valuables: Deben aportar valor claro al negocio/usuario.

Estimables: Tamaño y complejidad deben permitir estimación realista.

Small (Pequeñas): Completables en un sprint (1-2 semanas).

Testables: Verificables mediante criterios objetivos.

5. Epics: Cuándo y Cómo Usarlos
Definición: Historias demasiado grandes para un sprint, que deben dividirse en sub-historias.

Ejemplo: "Mejorar sistema de notificaciones" podría ser un Epic que incluye:

Historia 1: Crear base de datos de correos.

Historia 2: Diseñar plantillas de promociones.

Uso:

Inician como ideas grandes en el backlog.

Se refinan progresivamente en historias más pequeñas y priorizables.

6. Conclusiones Clave
Las historias de usuario capturan quién, qué y por qué para alinear al equipo con el valor empresarial.

Los criterios de aceptación (Gherkin) y el INVEST aseguran claridad y calidad.

Los Epics ayudan a gestionar proyectos complejos, dividiéndolos en partes accionables.
