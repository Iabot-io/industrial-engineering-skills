---
name: preventive-maintenance-schedule
description: Preparar un plan de mantenimiento a partir de frecuencias y condiciones documentadas. En IAbot.io, asígnala a un empleado de planificación de mantenimiento y aporta el inventario, manuales, contadores de uso y partes históricos.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Industria e ingeniería naval
---

# Programar mantenimiento preventivo

## Uso en IAbot.io

Asigna esta skill a **un empleado de planificación de mantenimiento** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta el inventario, manuales, contadores de uso y partes históricos.

**Ejemplo de encargo:** «Organiza el mantenimiento de estas máquinas para el próximo trimestre y señala las tareas sin base documental.»

**Resultado a revisar:** Plan por equipo con fundamento, vencimientos y evidencia necesaria.

## Cuándo usarla y qué necesita

Preparar un plan de mantenimiento a partir de frecuencias y condiciones documentadas

Trabaja con el inventario, manuales, contadores de uso y partes históricos. Trabaja con documentación del fabricante, inventarios y hojas de cálculo. Los diagnósticos y actuaciones físicas requieren los profesionales y procedimientos autorizados.

## Procedimiento

1. Relaciona activo, modelo y serie con el manual correcto y las modificaciones de la instalación.
2. Extrae tareas, competencias, frecuencias e intervalos de uso de fuentes vigentes; conserva advertencias del fabricante.
3. Calcula vencimientos por calendario y contador por separado, sin inventar una última actuación cuando falta registro.
4. Agrupa tareas compatibles con ventanas de parada aportadas y señala los conflictos de recursos.
5. Prepara órdenes propuestas con requisitos previos y criterio de cierre; no ordenes una intervención física desde esta planificación.

## Comprobación del resultado

- Cada frecuencia tiene fuente y criterio de aplicación.
- Las tareas sobre equipos modificados reciben revisión específica.
- El plan conserva las medidas de seguridad del procedimiento del equipo.

## Entrega

Plan por equipo con fundamento, vencimientos y evidencia necesaria.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [INSST, equipos de trabajo](https://www.insst.es/InshtWeb/Contenidos/Normativa/GuiasTecnicas/Ficheros/equipo1.pdf)
- [Código ISM de la Organización Marítima Internacional](https://wwwcdn.imo.org/localresources/en/KnowledgeCentre/IndexofIMOResolutions/AssemblyDocuments/A.741%2818%29.pdf)
