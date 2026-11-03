---
name: spare-parts-criticality
description: Clasificar necesidades de repuestos usando impacto, cobertura y reposición documentados. En IAbot.io, asígnala a un empleado de almacén técnico y aporta inventario, equipos servidos, consumos, plazos y criterios de criticidad.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Industria e ingeniería naval
---

# Priorizar repuestos críticos

## Uso en IAbot.io

Asigna esta skill a **un empleado de almacén técnico** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta inventario, equipos servidos, consumos, plazos y criterios de criticidad.

**Ejemplo de encargo:** «Compara existencias y plazos de estos repuestos y presenta prioridades de revisión sin crear pedidos.»

**Resultado a revisar:** Matriz de criticidad, cobertura y propuestas de reposición.

## Cuándo usarla y qué necesita

Clasificar necesidades de repuestos usando impacto, cobertura y reposición documentados

Trabaja con inventario, equipos servidos, consumos, plazos y criterios de criticidad. Trabaja con documentación del fabricante, inventarios y hojas de cálculo. Los diagnósticos y actuaciones físicas requieren los profesionales y procedimientos autorizados.

## Procedimiento

1. Normaliza referencias manteniendo equivalencias aprobadas, unidad de compra y equipos compatibles.
2. Calcula existencias utilizables separando reservas, material dañado y unidades pendientes de recepción.
3. Relaciona plazo real de suministro, consumo observado e impacto del equipo con los criterios acordados.
4. Muestra sensibilidad a consumos o plazos inciertos; no conviertas ausencia de averías en ausencia de riesgo.
5. Prepara prioridades y alternativas aprobadas, dejando la decisión de compra al circuito existente.

## Comprobación del resultado

- No se sustituyen referencias por similitud de nombre.
- Unidades de consumo y compra son compatibles.
- El nivel recomendado puede reconstruirse desde los datos y criterios.

## Entrega

Matriz de criticidad, cobertura y propuestas de reposición.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [INSST, equipos de trabajo](https://www.insst.es/InshtWeb/Contenidos/Normativa/GuiasTecnicas/Ficheros/equipo1.pdf)
- [Código ISM de la Organización Marítima Internacional](https://wwwcdn.imo.org/localresources/en/KnowledgeCentre/IndexofIMOResolutions/AssemblyDocuments/A.741%2818%29.pdf)
