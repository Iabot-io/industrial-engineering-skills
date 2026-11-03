---
name: industrial-failure-analysis
description: Estructurar el análisis de una avería distinguiendo síntomas, hipótesis, causas verificadas y acciones. En IAbot.io, asígnala a un empleado de mejora y fiabilidad y aporta los partes de avería, registros, condiciones de operación y acciones realizadas.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Industria e ingeniería naval
---

# Analizar averías con evidencias

## Uso en IAbot.io

Asigna esta skill a **un empleado de mejora y fiabilidad** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta los partes de avería, registros, condiciones de operación y acciones realizadas.

**Ejemplo de encargo:** «Prepara un análisis de estas paradas repetidas y define qué datos faltan para validar la causa.»

**Resultado a revisar:** Cronología, árbol de hipótesis y plan de comprobación de acciones.

## Cuándo usarla y qué necesita

Estructurar el análisis de una avería distinguiendo síntomas, hipótesis, causas verificadas y acciones

Trabaja con los partes de avería, registros, condiciones de operación y acciones realizadas. Trabaja con documentación del fabricante, inventarios y hojas de cálculo. Los diagnósticos y actuaciones físicas requieren los profesionales y procedimientos autorizados.

## Procedimiento

1. Reconstruye la secuencia antes, durante y después del fallo con tiempos, mediciones y cambios recientes.
2. Separa síntoma de mecanismo e hipótesis causal; enlaza cada hipótesis con evidencia a favor y en contra.
3. Identifica medidas de contención ya autorizadas y no las confundas con solución definitiva.
4. Propón comprobaciones seguras al responsable competente y define qué resultado refutaría cada hipótesis.
5. Relaciona acciones correctivas con causas verificadas y criterio medible de eficacia.

## Comprobación del resultado

- No se declara causa raíz por frecuencia o correlación solamente.
- Las pruebas propuestas no eluden protecciones ni procedimientos de seguridad.
- Las acciones tienen responsable, fecha y evidencia de eficacia.

## Entrega

Cronología, árbol de hipótesis y plan de comprobación de acciones.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [INSST, equipos de trabajo](https://www.insst.es/InshtWeb/Contenidos/Normativa/GuiasTecnicas/Ficheros/equipo1.pdf)
- [Código ISM de la Organización Marítima Internacional](https://wwwcdn.imo.org/localresources/en/KnowledgeCentre/IndexofIMOResolutions/AssemblyDocuments/A.741%2818%29.pdf)
