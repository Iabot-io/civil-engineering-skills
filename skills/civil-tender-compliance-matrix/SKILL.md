---
name: civil-tender-compliance-matrix
description: Relacionar requisitos técnicos de una licitación de ingeniería civil con evidencias de la oferta. En IAbot.io, asígnala a un empleado de preparación de ofertas técnicas y aporta los pliegos, anexos, aclaraciones oficiales y propuesta técnica.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Ingeniería civil e infraestructuras
---

# Matriz técnica de licitación de obra civil

## Uso en IAbot.io

Asigna esta skill a **un empleado de preparación de ofertas técnicas** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta los pliegos, anexos, aclaraciones oficiales y propuesta técnica.

**Ejemplo de encargo:** «Revisa los pliegos y crea una matriz de lo que debe contener la memoria técnica, con páginas y carencias.»

**Resultado a revisar:** Matriz de requisitos técnicos y pendientes de la oferta.

## Cuándo usarla y qué necesita

Relacionar requisitos técnicos de una licitación de ingeniería civil con evidencias de la oferta

Trabaja con los pliegos, anexos, aclaraciones oficiales y propuesta técnica. Usa hojas de cálculo y visor de planos; los trabajos espaciales necesitan QGIS o una herramienta SIG compatible y sus sistemas de referencia correctamente definidos.

## Procedimiento

1. Fija expediente, versión de pliegos y aclaraciones oficiales; separa requisitos obligatorios y criterios evaluables.
2. Extrae entregables, límites de formato y evidencias exigidas citando apartado y página.
3. Relaciona cada requisito con una sección real de la oferta y conserva las ausencias.
4. Comprueba incoherencias entre programa, medios, mediciones y metodología; no inventes equipos o experiencia.
5. Prepara una lista de cierre de oferta sin estimar puntuaciones como si fueran las de la mesa evaluadora.

## Comprobación del resultado

- Se incorporan las aclaraciones publicadas que modifican requisitos.
- Los requisitos obligatorios se distinguen de recomendaciones.
- No se declara presentada una oferta por tener preparado el documento.

## Entrega

Matriz de requisitos técnicos y pendientes de la oferta.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Documentación de QGIS](https://docs.qgis.org/latest/en/docs/user_manual/working_with_projections/working_with_projections.html)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
