---
name: vessel-maintenance-dossier
description: Consolidar mantenimiento de buques y embarcaciones con historial, vencimientos y evidencias. En IAbot.io, asígnala a un empleado de gestión técnica naval y aporta el inventario del buque, manuales, registros y programa de mantenimiento aprobado.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Industria e ingeniería naval
---

# Dossier de mantenimiento de embarcaciones

## Uso en IAbot.io

Asigna esta skill a **un empleado de gestión técnica naval** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta el inventario del buque, manuales, registros y programa de mantenimiento aprobado.

**Ejemplo de encargo:** «Organiza el dossier de mantenimiento de esta embarcación y señala registros incompletos por sistema.»

**Resultado a revisar:** Dossier por sistema con historial, tareas pendientes y referencias técnicas.

## Cuándo usarla y qué necesita

Consolidar mantenimiento de buques y embarcaciones con historial, vencimientos y evidencias

Trabaja con el inventario del buque, manuales, registros y programa de mantenimiento aprobado. Trabaja con documentación del fabricante, inventarios y hojas de cálculo. Los diagnósticos y actuaciones físicas requieren los profesionales y procedimientos autorizados.

## Procedimiento

1. Fija la identidad de la embarcación y la configuración de máquinas, equipos y sistemas de seguridad.
2. Relaciona manuales y programa aprobado con horas, ciclos e inspecciones registradas.
3. Detecta vencimientos y lagunas conservando por separado requisitos de bandera, clase, fabricante y operador.
4. Documenta averías, reparaciones y repuestos asociados sin declarar resuelto un defecto por la existencia de una orden.
5. Entrega pendientes y evidencias al responsable técnico; conserva su decisión sobre operación y aptitud del buque.

## Comprobación del resultado

- Los registros se asocian al equipo y periodo correctos.
- No se extrapolan reglas de una bandera o tipo de buque a otro.
- No se certifica navegabilidad ni se autoriza una operación.

## Entrega

Dossier por sistema con historial, tareas pendientes y referencias técnicas.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [INSST, equipos de trabajo](https://www.insst.es/InshtWeb/Contenidos/Normativa/GuiasTecnicas/Ficheros/equipo1.pdf)
- [Código ISM de la Organización Marítima Internacional](https://wwwcdn.imo.org/localresources/en/KnowledgeCentre/IndexofIMOResolutions/AssemblyDocuments/A.741%2818%29.pdf)
