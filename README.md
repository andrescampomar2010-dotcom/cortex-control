# Córtex de Control

**ES** · Simulador interactivo de un orquestador de agentes de IA para una empresa comercial. Una sala de operaciones con estética de base subterránea en neón: diez agentes (NODO al mando, ÍRIS, TESELA, PLUMA, KAIRÓS, ÁBACO, PRISMA, ARCHIVO, FARO y CENTINELA) repartidos en ocho departamentos, cada uno con su sala que se enciende al trabajar, y ningún borrador (contacto, oferta, contrato, reunión, informe o parche de seguridad) sale sin la aprobación humana de PUENTE.

**EN** · Interactive simulation of an AI-agent orchestrator for a commercial company. A neon underground operations room: ten agents across eight departments led by NODO, each with its own room that lights up while it works, and no draft (first contact, quote, contract, meeting, report or security patch) leaves without human approval through PUENTE.

## Qué hace / What it does

- 14 vistas: planta de la base, organigrama, canal, encargos, aprobaciones, CRM, informes, decisiones, seguridad, costes de IA, hitos, avisos, actividad y ajustes.
- Pipeline completo: nuevo → cualificado → oferta → revisión → aprobada → enviada → ganada/perdida.
- Consola de órdenes al director: NODO reparte cada encargo entre los agentes y lo negocia contigo por el canal.
- Canal interno por departamentos: los agentes se pasan el trabajo y puedes hablar con cada uno.
- Agentes con cola de tareas, niveles y experiencia; cada sala muestra su trabajo en vivo.
- Borradores en 6 idiomas (ES, EN, FR, IT, PT, DE) con plantillas locales.
- Motor de política comercial: margen mínimo, descuento máximo, límite de crédito y riesgo (ÁBACO devuelve lo que incumple).
- Comparador de decisiones (contratar, subcontratar o automatizar) con puntuación ponderada de ÁBACO y PRISMA.
- Panel de costes de IA: consultas, tokens estimados y horas ahorradas, con supuestos editables.
- Informe de seguridad de referencia (avisos públicos GHSA/CVE) con preparación de aviso de parche.
- Hitos, avisos, atajos de teclado, registro de actividad, métricas de operación, exportación CSV.
- Persistencia local en el navegador. Datos de ejemplo ficticios marcados como EJEMPLO.

## Cómo probarlo / Run it

Abre `index.html` en un navegador. Sin build, sin dependencias externas (solo fuentes de Google Fonts).

Pensado originalmente como artefacto de Claude con IA, CRM compartido y Gmail conectados; fuera de ese entorno detecta las capacidades disponibles y degrada con honestidad a modo local (plantillas y reglas locales), indicándolo en Ajustes.

## Stack

HTML + CSS + JavaScript en un solo archivo. Sin frameworks.

## Licencia / License

MIT
