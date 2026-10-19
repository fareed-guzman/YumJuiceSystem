# Yum Juice System

Sistema de gestión operativa desarrollado para el emprendimiento Yum Juice, orientado a la gestión de personal y horarios, inventario, proveedores, mantenimiento de equipos y ventas, mediante la aplicación de estructuras de datos y algoritmos en Java.

## Integrantes del Equipo
* Fareed Guzmán
* Iveth Castro
* Zaskia Sunta

## Módulos del Sistema

| Módulo | Responsable |
|---|---|
| 1. Gestión del personal y horarios | Iveth Castro |
| 2. Control de inventario | Fareed Guzmán |
| 3. Gestión de proveedores y abastecimiento | Zaskia Sunta |
| 4. Gestión del mantenimiento de equipos | Iveth Castro |
| 5. Registro y análisis de ventas | Fareed Guzmán |

## Alternativa Seleccionada

Asignación dinámica de personal mediante prioridades, usando `PriorityQueue`, `HashMap` y `ArrayList`. Permite atender primero los turnos que requieren cobertura ante ausencias imprevistas, buscar trabajadores disponibles y proponer reasignaciones que la gerente debe revisar.

## Estructura del Proyecto
El código fuente se organiza bajo el estándar de paquetes de Java:
- `src/com/yumjuice/models/`: Clases de dominio y entidades del negocio.
- `src/com/yumjuice/controllers/`: Clases gestoras y lógica operacional.
- `src/com/yumjuice/structures/`: Implementación de estructuras de datos dinámicas (PriorityQueue).
- `src/com/yumjuice/main/`: Clase de entrada (`com.yumjuice.main.Main`) para la ejecución del sistema.
- `docs/`: Documentación técnica y diagramas UML de respaldo.

## Estado del Proyecto

- **Progreso 1:** formulación del problema, módulos, UML, alternativas, selección de la solución y repositorio inicial.

## Documentación

- [Informe técnico (PDF)](docs/Avance_Proyecto_Programacion_P1.pdf)
- [Diagrama UML preliminar](docs/UML.md)

## Instrucciones para Ejecutar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/fareed-guzman/YumJuiceSystem.git
2. Abrir la carpeta `YumJuiceSystem` en IntelliJ IDEA.
3. Verificar que el proyecto use un JDK instalado (se recomienda JDK 17 o superior).
4. Ejecutar la clase `com.yumjuice.main.Main`.
