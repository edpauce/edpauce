# Edson Palomino

**Sostenibilidad · IA aplicada · Organización**

Ingeniero industrial y auditor líder ISO en Arequipa, Perú. Llevo más de 15 años en sistemas de
gestión, seguridad y medio ambiente, en minería, energía, construcción y servicios. Desde 2025
construyo con agentes de IA las herramientas que mi propio trabajo necesitaba.

No vengo del software, vengo de la auditoría. Por eso lo que construyo se parece a un sistema de
gestión: las reglas están escritas en código, cada cambio cita su evidencia y nada se cierra por
adivinar.

## Lo que se puede ver

**[control-financiero-wat](https://github.com/edpauce/control-financiero-wat)** — el núcleo
determinista de un agente que lleva el control financiero mensual de dos empresas: un gate de
escritura con siete checks, sellos de integridad sobre los meses cerrados, una compuerta que
valida cada fuente antes de calcular y el cruce de detracciones (SPOT) factura por factura.
Python, 188 tests, datos ficticios.

**[registro-campo-offline](https://github.com/edpauce/registro-campo-offline)** — app web
instalable para registrar mediciones hídricas en campo donde no hay señal: guarda primero en el
equipo, abre sin conexión y genera el Excel en el propio teléfono. JavaScript sin dependencias,
[demo en vivo](https://edpauce.github.io/registro-campo-offline/), datos ficticios.

**[iso-agents](https://github.com/edpauce/iso-agents)** — servidor MCP que redacta los documentos
de un sistema de gestión ISO cláusula por cláusula (Anexo SL): parte de los Word del cliente,
entrega .docx con fidelidad exacta y deja visible cada cambio. TypeScript, licencia MIT. Es el
módulo de documentación de Normia.

## En lo que trabajo

Repos privados, en desarrollo.

| Proyecto | Qué es | Con qué |
|---|---|---|
| **Huellia** | Plataforma multiempresa de huella de carbono e hídrica, alineada a NTP-ISO 14064-1, ISO 14046 y Huella de Carbono Perú (MINAM). | TypeScript · Next.js · Prisma |
| **Normia** | Copiloto para sistemas de gestión ISO: matriz IPERC para ISO 45001, módulo de calidad para ISO 9001 y documentación cláusula por cláusula (ese módulo es público: iso-agents). | TypeScript · Python · Claude API |
| **Matriz legal SSOMA** | Captura las normas del diario oficial, las clasifica por sector y mantiene una base de obligaciones con trazabilidad. | Python |
| **Control financiero** | El sistema completo del que sale el repo público: más de 36,000 líneas de Python y 480 tests. | Python |

## Cómo trabajo

- El modelo decide y orquesta; el código determinista ejecuta.
- Las reglas de seguridad no van en el prompt: van en código que el agente no puede saltarse.
- Sin evidencia citada, un dato no cambia de estado.
- Cada test nombra el caso que lo motivó.

## Formación

- Auditor Líder ISO 9001 e ISO 45001 (ERCA) · ISO 14001 (CQI/IRCA)
- Programa de gases de efecto invernadero y huella de carbono (SGS Academy, 2025) · cursos de los Estándares GRI (GRI Academy, 2026)
- Ingeniero Industrial · egresado de la Maestría en Medio Ambiente y Sistemas Integrados de Gestión (UNSA)

---

*English version: [README.md](README.md)*
