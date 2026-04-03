# Proyecto_spa
Sistema de Gestión de Citas para Spa

Descripción
Aplicación desarrollada en C# consola que permite gestionar las citas de un spa, incluyendo registro, consulta y cancelación de citas con validación de horarios.

Objetivo
Organizar la gestión de citas del spa evitando conflictos de horario y permitiendo una administración básica de clientes y servicios.

Tecnologías utilizadas
- Lenguaje: C#
- Tipo de aplicación: Consola
- Estructuras utilizadas: List<T>

Funcionalidades actuales (Entrega 1)
- Registrar cita
- Validar horario repetido
- Mostrar citas
- Cancelar cita

 Funcionalidades actuales (Entrega 2)

Concurrencia:
Se implemento concurrencia mediante el uso de hilos (Threads), simulando varios usuarios intentando registrar citas al mismo tiempo.

Esto permite evidenciar problemas de acceso concurrente a la memoria compartida.

Sincronización:
Se implementó sincronización utilizando lock para proteger la lista compartida de citas:

lock (bloqueo)
{
    citas.Add(nueva);
}

Esto evita:
Duplicación de horarios
Inconsistencias en los datos
Errores por acceso simultáneo
  
Cómo ejecutar el proyecto:
1. Descargar el repositorio.
2. Abrir el proyecto en Visual Studio.
3. Ejecutar el programa.
4. En la consola aparece el menú del sistema:

===== SISTEMA SPA =====
1.Registrar cita
2.Ver citas
3.Cancelar cita
4.Salir

5. Seleccionar una opción ingresando el número correcto.
   
Autores:
Manuela Rodriguez
Lizeth Velez
Jeronimo Mejia
