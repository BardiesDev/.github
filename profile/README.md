# Bardies

**Bardies construye una plataforma flexible para organizar, automatizar y explotar los datos internos de una empresa sin depender de desarrollos a medida para cada nuevo proceso.**

Nuestra idea es sencilla: cada empresa trabaja de forma distinta, pero casi todas necesitan lo mismo en el fondo: modelar su información, relacionarla, verla en tablas y dashboards, generar reportes, automatizar tareas y conectar datos externos. Bardies reúne todo eso en un ecosistema modular.

## Qué hacemos

Bardies es una plataforma de gestión empresarial configurable. Permite crear modelos de datos propios, gestionar objetos dinámicos, definir relaciones entre ellos y construir vistas útiles para el día a día del negocio.

Con Bardies, una organización puede:

- Crear tipos de objeto adaptados a su actividad: clientes, proyectos, incidencias, oportunidades, empleados, activos o cualquier entidad propia.
- Gestionar datos dinámicos sin tener que cambiar el código por cada nuevo modelo.
- Relacionar entidades entre sí para construir estructuras más ricas.
- Crear tablas personalizadas y vistas combinadas.
- Generar dashboards con KPIs, gráficos y widgets configurables.
- Preparar reportes y plantillas reutilizables.
- Automatizar disparadores, notificaciones y acciones programadas.
- Integrar fuentes de datos externas o internas con trazabilidad.

## Nuestro enfoque

Creemos en software de empresa que sea flexible, mantenible y comprensible. Bardies está pensado como una base sobre la que construir procesos reales sin encerrar al usuario en una estructura fija.

Trabajamos con una arquitectura modular basada en servicios independientes:

- **Frontend principal**: interfaz web para usuarios, administradores y equipos operativos.
- **Landing pública**: página de presentación y entrada al producto.
- **Core backend**: API principal para empresas, usuarios, tipos, objetos, relaciones, tablas, reportes y filtros.
- **Gateway**: punto de entrada seguro para la comunicación entre frontend y servicios.
- **Automation**: motor de disparadores, notificaciones y ejecuciones programadas.
- **Integrator**: módulo de integración, ingesta y sincronización de datos.

## Tecnología

El stack combina tecnologías modernas y conocidas:

- **Vue 3**, **Vite**, **Pinia** y **Vue Router** en frontend.
- **Spring Boot**, **Java 17**, **Spring Data JPA** y **PostgreSQL** en backend.
- **Keycloak** para autenticación y control de acceso.
- **Docker** para levantar el entorno de forma reproducible.
- **Chart.js**, layouts configurables y componentes propios para dashboards y reportes.

## Para quién es Bardies

Bardies está orientado a equipos que necesitan adaptar su software a sus procesos, no al revés:

- Pymes que quieren centralizar operaciones y datos.
- Equipos que gestionan procesos internos cambiantes.
- Consultoras o departamentos que necesitan crear herramientas internas rápido.
- Organizaciones que quieren dashboards, automatizaciones e integraciones sin construir todo desde cero.

## Repositorios

Esta organización contiene los diferentes servicios que forman el ecosistema Bardies. Cada repositorio incluye su propio README con instrucciones de instalación, configuración y ejecución local.

## Estado

Bardies está en desarrollo activo. El foco actual está en consolidar la experiencia de producto, mejorar la estabilidad del frontend, reforzar la arquitectura de servicios y preparar el despliegue cloud de la plataforma.

---

**Bardies: datos flexibles, procesos conectados y herramientas internas hechas a medida de cada empresa.**
