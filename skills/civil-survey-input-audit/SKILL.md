---
name: civil-survey-input-audit
description: Comprobar integridad, unidades y referencia espacial de un levantamiento antes de usarlo en un proyecto. En IAbot.io, asígnala a un empleado de apoyo topográfico y aporta los puntos, metadatos, unidades, sistema de referencia y levantamiento de control.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Ingeniería civil e infraestructuras
---

# Revisar datos topográficos de entrada

## Uso en IAbot.io

Asigna esta skill a **un empleado de apoyo topográfico** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta los puntos, metadatos, unidades, sistema de referencia y levantamiento de control.

**Ejemplo de encargo:** «Revisa este CSV topográfico y su memoria; identifica puntos duplicados, cotas incoherentes y metadatos que faltan.»

**Resultado a revisar:** Informe de entrada topográfica con incidencias y puntos de control.

## Cuándo usarla y qué necesita

Comprobar integridad, unidades y referencia espacial de un levantamiento antes de usarlo en un proyecto

Trabaja con los puntos, metadatos, unidades, sistema de referencia y levantamiento de control. Usa hojas de cálculo y visor de planos; los trabajos espaciales necesitan QGIS o una herramienta SIG compatible y sus sistemas de referencia correctamente definidos.

## Procedimiento

1. Identifica sistema horizontal, referencia vertical, unidades horizontales y verticales, fecha y origen; conserva por separado lo conocido y lo supuesto. La unidad horizontal no acredita la de las cotas.
2. Comprueba columnas, identificadores, valores no numéricos, duplicados y rangos; no elimines puntos anómalos sin dejar una copia.
3. Compara la extensión y puntos de control con el levantamiento; una coincidencia visual de mapa no valida el sistema de referencia.
4. Registra transformaciones propuestas con origen y destino; no asignes otro CRS para aparentar que las coordenadas coinciden.
5. Entrega el conjunto depurado solo con cambios trazables y una lista de cuestiones que debe resolver el responsable del levantamiento.

## Comprobación del resultado

- Se diferencian alturas elipsoidales, ortométricas y cotas locales cuando corresponda.
- Los identificadores originales permiten reconstruir cada corrección.
- Ningún sistema de referencia se ha inferido exclusivamente por apariencia.

## Entrega

Informe de entrada topográfica con incidencias y puntos de control.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Documentación de QGIS](https://docs.qgis.org/latest/en/docs/user_manual/working_with_projections/working_with_projections.html)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
