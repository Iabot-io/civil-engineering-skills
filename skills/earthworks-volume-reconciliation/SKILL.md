---
name: earthworks-volume-reconciliation
description: Revisar diferencias entre cubicaciones y documentar sus superficies, límites y criterios. En IAbot.io, asígnala a un empleado de mediciones de obra civil y aporta los modelos o perfiles comparados, límites, unidades y cubicaciones previas.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Ingeniería civil e infraestructuras
---

# Reconciliar cubicaciones de tierras

## Uso en IAbot.io

Asigna esta skill a **un empleado de mediciones de obra civil** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta los modelos o perfiles comparados, límites, unidades y cubicaciones previas.

**Ejemplo de encargo:** «Compara estas dos cubicaciones y explica qué parte de la diferencia procede de límites o superficies distintos.»

**Resultado a revisar:** Reconciliación de volúmenes por zona con método, diferencias y pendientes.

## Cuándo usarla y qué necesita

Revisar diferencias entre cubicaciones y documentar sus superficies, límites y criterios

Trabaja con los modelos o perfiles comparados, límites, unidades y cubicaciones previas. Usa hojas de cálculo y visor de planos; los trabajos espaciales necesitan QGIS o una herramienta SIG compatible y sus sistemas de referencia correctamente definidos.

## Procedimiento

1. Identifica las superficies inicial y final, sus fechas, versiones, unidades y dominio de comparación.
2. Separa zonas de desmonte y terraplén; comprueba si se usan volúmenes geométricos o factores de esponjamiento y compactación.
3. Recalcula o revisa las diferencias por perfiles, malla o TIN con el mismo método y límites cuando existan herramientas disponibles.
4. Descompón diferencias atribuibles a cobertura, interpolación, perfiles faltantes y factores; conserva lo que no se puede explicar.
5. Presenta un cuadro por zona y una conciliación entre los totales de origen y los revisados.

## Comprobación del resultado

- Ambos conjuntos usan una referencia vertical comparable.
- Los factores físicos no se han aplicado dos veces.
- Se conserva el signo y significado de desmonte y terraplén.

## Entrega

Reconciliación de volúmenes por zona con método, diferencias y pendientes.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Documentación de QGIS](https://docs.qgis.org/latest/en/docs/user_manual/working_with_projections/working_with_projections.html)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
