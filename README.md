# Industria e ingeniería naval · Skills para empleados IA de IAbot.io

Mantenimiento, averías, repuestos, recepción de equipos y documentación técnica de industria y embarcaciones.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Programar mantenimiento preventivo](skills/preventive-maintenance-schedule/SKILL.md) | un empleado de planificación de mantenimiento | Plan por equipo con fundamento, vencimientos y evidencia necesaria. |
| [Analizar averías con evidencias](skills/industrial-failure-analysis/SKILL.md) | un empleado de mejora y fiabilidad | Cronología, árbol de hipótesis y plan de comprobación de acciones. |
| [Priorizar repuestos críticos](skills/spare-parts-criticality/SKILL.md) | un empleado de almacén técnico | Matriz de criticidad, cobertura y propuestas de reposición. |
| [Expediente de recepción de equipos](skills/equipment-acceptance-evidence/SKILL.md) | un empleado de calidad de suministro | Lista de pruebas y documentos con resultados acreditados y desviaciones. |
| [Dossier de mantenimiento de embarcaciones](skills/vessel-maintenance-dossier/SKILL.md) | un empleado de gestión técnica naval | Dossier por sistema con historial, tareas pendientes y referencias técnicas. |
| [Preparar paquetes de reparación naval](skills/shipyard-repair-workpack/SKILL.md) | un empleado de oficina técnica de astillero | Paquete de trabajo y matriz de alcance, exclusiones y evidencias de recepción. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/industrial-engineering-skills --list
npx skills add Iabot-io/industrial-engineering-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Programar mantenimiento preventivo:** «Organiza el mantenimiento de estas máquinas para el próximo trimestre y señala las tareas sin base documental.»
- **Analizar averías con evidencias:** «Prepara un análisis de estas paradas repetidas y define qué datos faltan para validar la causa.»
- **Priorizar repuestos críticos:** «Compara existencias y plazos de estos repuestos y presenta prioridades de revisión sin crear pedidos.»

## Herramientas y límites

Trabaja con documentación del fabricante, inventarios y hojas de cálculo. Los diagnósticos y actuaciones físicas requieren los profesionales y procedimientos autorizados.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [INSST, equipos de trabajo](https://www.insst.es/InshtWeb/Contenidos/Normativa/GuiasTecnicas/Ficheros/equipo1.pdf)
- [Código ISM de la Organización Marítima Internacional](https://wwwcdn.imo.org/localresources/en/KnowledgeCentre/IndexofIMOResolutions/AssemblyDocuments/A.741%2818%29.pdf)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
