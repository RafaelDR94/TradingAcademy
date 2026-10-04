# Trading Academy

Repositorio de trabajo para convertir el aprendizaje de trading en un proceso **trazable, evaluable y versionado**.

> Objetivo central: construir competencia real mediante sesiones de 30 minutos, evaluación continua, gestión de riesgo, estrategia versionada, backtesting y práctica en demo antes de considerar dinero real.

## Principios

- Progresión por dominio, no por calendario.
- Separar calidad de decisión de PnL.
- Riesgo, apalancamiento y position sizing son prerrequisitos.
- Toda estrategia debe existir como hipótesis, reglas versionadas y evidencia antes de usarse como sistema.
- Demo/replay/backtest antes de dinero real.
- Cada clase deja evidencia: checklist, práctica, evaluación y siguiente paso.
- El repositorio es el registro operativo del programa; el chat es el entorno de enseñanza.

## Estructura

- `specs/` — reglas del sistema de aprendizaje, evaluación, progresión y documentación.
- `curriculum/` — plan de 40 sesiones y estado de cada una.
- `classes/` — acta detallada de cada clase, con checklist y evidencia.
- `assessments/` — diagnóstico, mini exámenes, checkpoints y examen final.
- `progress/` — estado actual, matriz de habilidades y próximos objetivos.
- `journal/` — esquema y plantillas para operaciones y prácticas.
- `strategy/` — laboratorio de estrategia, playbooks y versiones.
- `CHANGELOG.md` — cambios relevantes del sistema/documentación.

## Estado inicial

- Diagnóstico: **33/100**.
- Ruta actual: **Semana 1 — Mecánica de mercado y riesgo básico**.
- Foco actual: lotes, valor por pip, margen, apalancamiento y lectura de cuenta en MT5.
- Entorno de ejecución: **demo**.
- Dinero real: **bloqueado** hasta cumplir los criterios de salida definidos en `specs/progression-policy.md`.

## Flujo de una clase

1. Recuperación activa.
2. Concepto nuevo.
3. Práctica.
4. Mini examen.
5. Cierre y actualización del repositorio.

La definición detallada está en `specs/session-spec.md`.

## Convención de estado

- `NOT STARTED` — aún no trabajado.
- `IN PROGRESS` — material iniciado, falta evidencia.
- `EVIDENCE PENDING` — contenido practicado, falta evaluación suficiente.
- `MASTERED` — alcanzó el criterio de dominio definido.
- `REINFORCEMENT` — requiere práctica dirigida antes de avanzar en temas dependientes.

## Regla de documentación

Al terminar una clase se actualizan, como mínimo:

1. El archivo de la sesión en `classes/`.
2. `progress/PROGRESS.md`.
3. `progress/skills-matrix.md`.
4. El registro de evaluación correspondiente.
5. `CHANGELOG.md` si cambió el sistema, una regla o una versión de estrategia.

Esto evita que el progreso dependa de memoria conversacional y convierte el curso en un historial auditable.
