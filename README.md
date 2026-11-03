# Ventas y atención al cliente · Skills para empleados IA de IAbot.io

CRM, propuestas, soporte y conocimiento de servicio con seguimiento trazable.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Revisar calidad del CRM](skills/crm-data-hygiene/SKILL.md) | un empleado de operaciones comerciales | Informe de calidad y fichero de cambios propuestos. |
| [Propuestas comerciales desde un briefing](skills/sales-proposal-from-brief/SKILL.md) | un empleado de preparación de ofertas | Propuesta editable, desglose económico y lista de supuestos. |
| [Clasificar solicitudes de soporte](skills/support-request-triage/SKILL.md) | un empleado de soporte al cliente | Registro de casos priorizados y solicitudes de información concreta. |
| [Crear artículos de ayuda comprobables](skills/service-knowledge-article/SKILL.md) | un empleado de conocimiento de soporte | Artículo con síntomas, requisitos, pasos y comprobación final. |
| [Preparar respuestas a reclamaciones](skills/complaint-response-draft/SKILL.md) | un empleado de atención al cliente | Borrador de respuesta y matriz de hechos, evidencias y decisiones. |
| [Preparar reuniones de cuenta](skills/account-meeting-brief/SKILL.md) | un empleado de gestión de clientes | Brief de cuenta, agenda y registro de asuntos pendientes. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/sales-support-skills --list
npx skills add Iabot-io/sales-support-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Revisar calidad del CRM:** «Audita el CRM y prepara propuestas de corrección con referencia a cada registro original.»
- **Propuestas comerciales desde un briefing:** «Redacta una oferta con dos opciones para este briefing y marca las condiciones aún sin aprobar.»
- **Clasificar solicitudes de soporte:** «Clasifica estas solicitudes y prepara la información que necesita cada responsable, sin cerrar casos por intuición.»

## Herramientas y límites

Usa documentos y CRM o correo autorizados. Los borradores y análisis no cambian condiciones comerciales ni envían mensajes fuera del alcance del encargo.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [AEPD](https://www.aepd.es/)
- [Información europea para empresas y consumidores](https://europa.eu/youreurope/business/dealing-with-customers/index_es.htm)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
