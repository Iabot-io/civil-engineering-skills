# Ingeniería civil e infraestructuras · Skills para empleados IA de IAbot.io

Preparación y revisión de información topográfica, mediciones e inspecciones para equipos de ingeniería civil.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Revisar datos topográficos de entrada](skills/civil-survey-input-audit/SKILL.md) | un empleado de apoyo topográfico | Informe de entrada topográfica con incidencias y puntos de control. |
| [Reconciliar cubicaciones de tierras](skills/earthworks-volume-reconciliation/SKILL.md) | un empleado de mediciones de obra civil | Reconciliación de volúmenes por zona con método, diferencias y pendientes. |
| [Preparar datos para drenaje](skills/drainage-design-input-pack/SKILL.md) | un empleado de apoyo a proyectos hidráulicos | Matriz de entradas, fuentes, unidades y supuestos pendientes de validación. |
| [Informe de inspección de viales](skills/road-inspection-report/SKILL.md) | un empleado de documentación de infraestructuras | Informe por tramo y registro geolocalizado de observaciones. |
| [Plan documental de mantenimiento de infraestructuras](skills/infrastructure-maintenance-register/SKILL.md) | un empleado de gestión de activos públicos | Registro por activo con tareas, vencimientos, evidencias y excepciones. |
| [Matriz técnica de licitación de obra civil](skills/civil-tender-compliance-matrix/SKILL.md) | un empleado de preparación de ofertas técnicas | Matriz de requisitos técnicos y pendientes de la oferta. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/civil-engineering-skills --list
npx skills add Iabot-io/civil-engineering-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Revisar datos topográficos de entrada:** «Revisa este CSV topográfico y su memoria; identifica puntos duplicados, cotas incoherentes y metadatos que faltan.»
- **Reconciliar cubicaciones de tierras:** «Compara estas dos cubicaciones y explica qué parte de la diferencia procede de límites o superficies distintos.»
- **Preparar datos para drenaje:** «Prepara el expediente de datos de estas cuencas y señala qué impide realizar todavía el dimensionamiento.»

## Herramientas y límites

Usa hojas de cálculo y visor de planos; los trabajos espaciales necesitan QGIS o una herramienta SIG compatible y sus sistemas de referencia correctamente definidos.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [Documentación de QGIS](https://docs.qgis.org/latest/en/docs/user_manual/working_with_projections/working_with_projections.html)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
