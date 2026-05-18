 Sistema de Gestión de Citas para Spa

# Descripción del proyecto

Este proyecto consiste en una aplicación de consola desarrollada en C# para la gestión de citas de un spa.  
El sistema permite registrar, visualizar y cancelar citas, además de simular múltiples usuarios accediendo al sistema al mismo tiempo mediante concurrencia.

El proyecto fue desarrollado progresivamente en tres entregas, integrando conceptos fundamentales de Sistemas Operativos como:

- Concurrencia
- Hilos (Threads)
- Sincronización
- Sección crítica
- Memoria compartida
- Monitoreo de recursos

# Objetivo

Desarrollar un sistema que permita gestionar citas de un spa evitando conflictos de horario y aplicando conceptos de sistemas operativos para controlar accesos concurrentes a recursos compartidos.

# Tecnologías utilizadas

- Lenguaje: C#
- Plataforma: .NET
- Aplicación de consola
- Thread
- lock
- List<T
- Stopwatch
- `GC.GetTotalMemory()

# Evolución del proyecto

# Entrega 1 – Sistema base

En la primera entrega se desarrolló la estructura principal del sistema.

# Funcionalidades implementadas

- Registrar citas
- Mostrar citas
- Cancelar citas
- Validación de horarios repetidos
- Menú interactivo

# Entrega 2 – Concurrencia y sincronización

En la segunda entrega se implementó concurrencia real mediante múltiples hilos.

# Características agregadas

- Uso de Threads
- Simulación de múltiples usuarios
- Sincronización con lock
- Protección de memoria compartida
- Validación concurrente de horarios

# Problema técnico resuelto

Múltiples usuarios podían intentar registrar citas al mismo tiempo, generando conflictos sobre la lista compartida de citas.

La solución implementada fue el uso de sincronización mediante lock.

# Entrega 3 – Sistema completo

En la entrega final se integraron conceptos avanzados de sistemas operativos y monitoreo de recursos.

# Mejoras finales

- Monitoreo de tiempo de ejecución
- Medición de uso de memoria
- Organización modular del código
- Explicación técnica de concurrencia
- Evidencia funcional del sistema

# Conceptos de Sistemas Operativos aplicados

# Threads (Hilos)

El sistema utiliza múltiples hilos para simular usuarios accediendo al sistema al mismo tiempo.

Ejemplo:

csharp
Thread t1 = new Thread(() => SimularCita("Ana", "10:00"));


Autores:
- Manuela Rodriguez
- Lizeth Velez
- Jeronimo Mejia
