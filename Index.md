# Curso de Arquitectura Hexagonal

1. Introducción a la Arquitectura Hexagonal

   • 1.1 Concepto de Arquitectura Hexagonal
   • 1.2 Orígenes y Motivación
   • 1.3 Ventajas y Desventajas
   • 1.4 Comparación con otras arquitecturas (Clean, Onion, Monolíticas)

2. Fundamentos de la Arquitectura Hexagonal

   • 2.1 Conceptos de Dominio y Aplicación
   • 2.2 Separación de Capas: Dominio, Aplicación y Adaptadores
      . 2.2.1 Componentes Clave en la Capa de Dominio
      . 2.2.2 Consistencia interna: Invariantes
   • 2.3 Puertos y Adaptadores: Definición y Rol
   • 2.4 Inversión de Dependencias

3. El Núcleo del Dominio

   • 3.1 Creación del Núcleo del Dominio: Principios y Prácticas
   • 3.2 Entidades y Agregados
   • 3.3 Servicios de Dominio
   • 3.4 Value Objects y sus Ventajas
   • 3.5 Invariantes y Reglas de Negocio

4. Aplicación y Lógica de Negocio

   • 4.1 Servicios de Aplicación
   • 4.2 Casos de Uso: Definición y Estructura
   • 4.3 Gestión de Transacciones en la Capa de Aplicación
   • 4.4 Patrón de Orquestación y Coreografía en Casos de Uso

5. Puertos y Adaptadores

   • 5.1 Puertos: Definición y Ejemplos
   • 5.1.1 Puertos Primarios (Inbound)
   • 5.1.2 Puertos Secundarios (Outbound)
   • 5.2 Adaptadores Primarios: Interfaces de Entrada
   • 5.2.1 API REST y Controladores
   • 5.2.2 Interfaces de Usuario
   • 5.2.3 Otros tipos de adaptadores primarios
   • 5.3 Adaptadores Secundarios: Conexiones Externas
   • 5.3.1 Repositorios y Bases de Datos
   • 5.3.2 Servicios Externos (APIs, colas de mensajes)
   • 5.3.3 Adaptadores de Infraestructura (File System, Configuración)

6. Pruebas en Arquitectura Hexagonal

   • 6.1 Principios de Testing en Arquitectura Hexagonal
   • 6.2 Pruebas de Unidad y Aislamiento de Dependencias
   • 6.3 Pruebas de Integración en Adaptadores
   • 6.4 Pruebas de Aceptación y Mocking de Puertos
   • 6.5 End-to-End Testing (E2E) en Arquitecturas Hexagonales

7. Patrones de Diseño en Arquitectura Hexagonal

   • 7.1 Patrón de Repositorio
   • 7.2 Patrón de Servicio
   • 7.3 Patrón de Fabricación (Factories)
   • 7.4 Patrón de Observador en Eventos de Dominio
   • 7.5 Aplicación de DDD (Domain-Driven Design) en Arquitectura Hexagonal

8. Gestión de Dependencias y Organización del Código

   • 8.1 Organización de Módulos y Paquetes
   • 8.2 Inversión de Control (IoC) y Contenedores de Inyección de Dependencias
   • 8.3 Principios SOLID en Arquitectura Hexagonal
   • 8.4 Evitando Dependencias Cíclicas
   • 8.5 Configuración y Carga de Dependencias

9. Implementación en Proyectos Reales

   • 9.1 Diseño y Estrategia de Migración a Arquitectura Hexagonal
   • 9.2 Integración con Arquitecturas de Microservicios
   • 9.3 Despliegue y Operación de Aplicaciones Hexagonales
   • 9.4 Consideraciones de Rendimiento y Escalabilidad

10. Ejemplos Prácticos y Estudios de Caso

    • 10.1 Creación de una API REST en Arquitectura Hexagonal
    • 10.2 Integración con un Sistema de Mensajería (RabbitMQ, Kafka)
    • 10.3 Ejemplo de Aplicación Completa con Repositorios y Casos de Uso
    • 10.4 Ejemplos de Refactorización a Arquitectura Hexagonal

11. Desafíos y Buenas Prácticas

    • 11.1 Desafíos Comunes y Cómo Superarlos
    • 11.2 Buenas Prácticas de Mantenimiento
    • 11.3 Gestión de Cambios en el Dominio
    • 11.4 Evolución y Expansión de Arquitecturas Hexagonales

12. Recursos Adicionales y Avance Profesional

    • 12.1 Lecturas y Recursos Recomendados
    • 12.2 Frameworks y Herramientas para Arquitectura Hexagonal
    • 12.3 Community Building y Desarrollo Profesional en Arquitectura Hexagonal

Este índice proporciona una estructura completa para aprender todos los conceptos esenciales y avanzados de la arquitectura hexagonal, con un enfoque equilibrado en teoría y práctica.
