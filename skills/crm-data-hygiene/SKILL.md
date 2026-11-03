---
name: crm-data-hygiene
description: Detectar duplicados y registros comerciales incompletos sin fusionarlos automáticamente. En IAbot.io, asígnala a un empleado de operaciones comerciales y aporta exportación del CRM, reglas de campos y etapas comerciales.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Ventas y atención al cliente
---

# Revisar calidad del CRM

## Uso en IAbot.io

Asigna esta skill a **un empleado de operaciones comerciales** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta exportación del CRM, reglas de campos y etapas comerciales.

**Ejemplo de encargo:** «Audita el CRM y prepara propuestas de corrección con referencia a cada registro original.»

**Resultado a revisar:** Informe de calidad y fichero de cambios propuestos.

## Cuándo usarla y qué necesita

Detectar duplicados y registros comerciales incompletos sin fusionarlos automáticamente

Trabaja con exportación del CRM, reglas de campos y etapas comerciales. Usa documentos y CRM o correo autorizados. Los borradores y análisis no cambian condiciones comerciales ni envían mensajes fuera del alcance del encargo.

## Procedimiento

1. Identifica entidades, claves, propietarios y etapas válidas del CRM.
2. Detecta campos ausentes, formatos inválidos y relaciones incoherentes.
3. Agrupa candidatos duplicados conservando evidencias y diferencias, sin asumir identidad por un nombre.
4. Prepara cambios con valor actual, propuesto y criterio, respetando preferencias de contacto.
5. Entrega revisión y reversión por identificador antes de cualquier escritura autorizada.

## Comprobación del resultado

- No se fusionan personas o empresas sin evidencia suficiente.
- Las etapas propuestas pertenecen al proceso real.
- Los datos sensibles no se amplían mediante inferencias.

## Entrega

Informe de calidad y fichero de cambios propuestos.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [AEPD](https://www.aepd.es/)
- [Información europea para empresas y consumidores](https://europa.eu/youreurope/business/dealing-with-customers/index_es.htm)
