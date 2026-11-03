---
name: infrastructure-maintenance-register
description: Convertir requisitos de mantenimiento en un registro de tareas e inspecciones trazable por activo. En IAbot.io, asígnala a un empleado de gestión de activos públicos y aporta el inventario, manuales, inspecciones y criterios de mantenimiento aprobados.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Ingeniería civil e infraestructuras
---

# Plan documental de mantenimiento de infraestructuras

## Uso en IAbot.io

Asigna esta skill a **un empleado de gestión de activos públicos** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta el inventario, manuales, inspecciones y criterios de mantenimiento aprobados.

**Ejemplo de encargo:** «Prepara el calendario documental de estos activos utilizando solo las frecuencias aprobadas.»

**Resultado a revisar:** Registro por activo con tareas, vencimientos, evidencias y excepciones.

## Cuándo usarla y qué necesita

Convertir requisitos de mantenimiento en un registro de tareas e inspecciones trazable por activo

Trabaja con el inventario, manuales, inspecciones y criterios de mantenimiento aprobados. Usa hojas de cálculo y visor de planos; los trabajos espaciales necesitan QGIS o una herramienta SIG compatible y sus sistemas de referencia correctamente definidos.

## Procedimiento

1. Normaliza el inventario manteniendo códigos, ubicación, titularidad y estado conocido.
2. Extrae tareas y frecuencias de manuales, contratos o plan aprobado; diferencia tiempo, uso y condición.
3. Calcula próximos vencimientos desde la última actuación válida, mostrando registros inexistentes y fechas contradictorias.
4. Relaciona tareas con recursos y dependencias sin asignar automáticamente trabajos para los que falte autorización.
5. Define qué evidencia cierra cada actuación y conserva las excepciones para revisión del responsable.

## Comprobación del resultado

- No se inventan periodicidades para activos sin documentación.
- Los vencimientos consideran el criterio de calendario o uso correcto.
- Cada cierre enlaza al acta o parte correspondiente.

## Entrega

Registro por activo con tareas, vencimientos, evidencias y excepciones.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Documentación de QGIS](https://docs.qgis.org/latest/en/docs/user_manual/working_with_projections/working_with_projections.html)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
