---
name: drainage-design-input-pack
description: Organizar las entradas y supuestos de un estudio de drenaje para su cálculo y revisión técnica. En IAbot.io, asígnala a un empleado de apoyo a proyectos hidráulicos y aporta las cuencas, superficies, datos de lluvia, redes existentes y criterios de diseño.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Ingeniería civil e infraestructuras
---

# Preparar datos para drenaje

## Uso en IAbot.io

Asigna esta skill a **un empleado de apoyo a proyectos hidráulicos** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta las cuencas, superficies, datos de lluvia, redes existentes y criterios de diseño.

**Ejemplo de encargo:** «Prepara el expediente de datos de estas cuencas y señala qué impide realizar todavía el dimensionamiento.»

**Resultado a revisar:** Matriz de entradas, fuentes, unidades y supuestos pendientes de validación.

## Cuándo usarla y qué necesita

Organizar las entradas y supuestos de un estudio de drenaje para su cálculo y revisión técnica

Trabaja con las cuencas, superficies, datos de lluvia, redes existentes y criterios de diseño. Usa hojas de cálculo y visor de planos; los trabajos espaciales necesitan QGIS o una herramienta SIG compatible y sus sistemas de referencia correctamente definidos.

## Procedimiento

1. Delimita el ámbito y enumera cuencas, puntos de vertido, redes y restricciones conocidas.
2. Registra fuente, periodo, localización y unidad de los datos de precipitación; distingue registros observados de parámetros de diseño.
3. Relaciona superficies y usos con los coeficientes aportados por el técnico, conservando su justificación y rango de aplicación.
4. Comprueba continuidad de unidades y cobertura de datos; señala cotas, capacidades o condiciones de contorno ausentes.
5. Prepara las entradas para el método indicado y una lista de decisiones técnicas aún necesarias.

## Comprobación del resultado

- No se ha elegido un periodo de retorno ni coeficiente sin criterio documentado.
- Las áreas y unidades de precipitación no se mezclan.
- Preparar datos no se presenta como cálculo hidráulico aprobado.

## Entrega

Matriz de entradas, fuentes, unidades y supuestos pendientes de validación.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Documentación de QGIS](https://docs.qgis.org/latest/en/docs/user_manual/working_with_projections/working_with_projections.html)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
