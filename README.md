# Córtex de Control

**ES** · Simulador interactivo de un orquestador de agentes de IA para un pipeline comercial. Una base neuronal en sección transversal: cada agente (ÍRIS, NODO, TESELA, ÁBACO, ARCHIVO, CENTINELA, PUENTE) tiene su sala, se enciende al trabajar y ningún borrador (contacto, oferta, seguimiento, parche de seguridad) sale sin aprobación humana.

**EN** · Interactive simulation of an AI-agent orchestrator for a sales pipeline. A cross-section of a neural base: each agent has its own room that lights up while it works, and no draft (first contact, quote, follow-up, security patch) leaves without human approval.

## Qué hace / What it does

- Pipeline completo: nuevo → cualificado → oferta → revisión → aprobada → enviada → ganada/perdida.
- Agentes con cola de tareas, niveles y experiencia; cada sala muestra su trabajo en vivo.
- Borradores en 6 idiomas (ES, EN, FR, IT, PT, DE) con plantillas locales.
- Motor de política comercial: margen mínimo, descuento máximo, límite de crédito y riesgo (ÁBACO devuelve lo que incumple).
- Bandeja de aprobación humana (PUENTE): aprobar, rechazar, rehacer o pedir cambios.
- Informe de seguridad de referencia (avisos públicos GHSA/CVE) con preparación de aviso de parche.
- Consola de órdenes a NODO, atajos de teclado, registro de actividad, métricas de operación, exportación CSV.
- Persistencia local en el navegador. Datos de ejemplo ficticios marcados como EJEMPLO.

## Cómo probarlo / Run it

Abre `index.html` en un navegador. Sin build, sin dependencias externas (solo fuentes de Google Fonts).

Pensado originalmente como artefacto de Claude con IA, CRM compartido y Gmail conectados; fuera de ese entorno detecta las capacidades disponibles y degrada con honestidad a modo local (plantillas y reglas locales), indicándolo en Ajustes.

## Stack

HTML + CSS + JavaScript en un solo archivo. Sin frameworks.

## Licencia / License

MIT
