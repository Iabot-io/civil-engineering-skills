---
name: road-inspection-report
description: Consolidar observaciones de viales con localización, evidencia y seguimiento. En IAbot.io, asígnala a un empleado de documentación de infraestructuras y aporta las fichas de visita, fotografías, tramos y sistema de identificación de la carretera.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Ingeniería civil e infraestructuras
---

# Informe de inspección de viales

## Uso en IAbot.io

Asigna esta skill a **un empleado de documentación de infraestructuras** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta las fichas de visita, fotografías, tramos y sistema de identificación de la carretera.

**Ejemplo de encargo:** «Organiza estas fotografías por tramo y prepara un informe de inspección sin inventar causas estructurales.»

**Resultado a revisar:** Informe por tramo y registro geolocalizado de observaciones.

## Cuándo usarla y qué necesita

Consolidar observaciones de viales con localización, evidencia y seguimiento

Trabaja con las fichas de visita, fotografías, tramos y sistema de identificación de la carretera. Usa hojas de cálculo y visor de planos; los trabajos espaciales necesitan QGIS o una herramienta SIG compatible y sus sistemas de referencia correctamente definidos.

## Procedimiento

1. Fija carretera, sentido, tramo, progresiva y fecha de visita; conserva incertidumbre de localización.
2. Describe daños observables y dimensiones realmente medidas; separa firme, drenaje, señalización y elementos de contención.
3. Relaciona cada observación con fotografía y ficha; identifica duplicados y evolución entre visitas comparables.
4. Aplica el criterio de prioridad facilitado por la entidad titular y prepara los avisos urgentes mediante su procedimiento. Envíalos solo si el encargo y los permisos vigentes autorizan esa comunicación; conserva el registro de lo enviado.
5. Redacta el informe distinguiendo observación, hipótesis y necesidad de inspección especializada.

## Comprobación del resultado

- Se identifica el sentido y la referencia de localización.
- Una imagen no se usa para certificar capacidad portante o seguridad.
- Las acciones propuestas tienen responsable y evidencia pendiente.

## Entrega

Informe por tramo y registro geolocalizado de observaciones.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Documentación de QGIS](https://docs.qgis.org/latest/en/docs/user_manual/working_with_projections/working_with_projections.html)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
