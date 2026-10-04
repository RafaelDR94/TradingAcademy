# Documentation Workflow

## Objetivo

Hacer del repositorio la fuente auditable del proceso educativo.

## Al iniciar una clase

1. Leer `progress/PROGRESS.md`.
2. Revisar `progress/skills-matrix.md`.
3. Identificar la sesion curricular activa.
4. Abrir o crear el acta de clase.
5. Seleccionar preguntas de recuperacion de debilidades activas.

## Durante la clase

Registrar solo evidencia relevante:

- respuestas;
- calculos;
- decisiones;
- errores;
- correcciones;
- capturas referenciadas;
- practica de plataforma;
- mini examen.

No llenar el historial con transcripcion completa del chat.

## Al cerrar la clase

Actualizar:

- archivo de clase;
- estado curricular;
- PROGRESS.md;
- skills-matrix.md;
- evaluacion;
- CHANGELOG.md solo si cambio una regla, spec o version.

## Examenes

Cada evaluacion debe guardar:

- fecha;
- alcance;
- preguntas;
- respuestas del alumno;
- rubrica;
- puntaje;
- errores;
- decision de avance;
- acciones de recuperacion.

## Estrategia

Cada cambio de estrategia debe crear una nueva version o corte documental. Nunca reescribir retrospectivamente reglas de una muestra ya ejecutada.

## Commits

Convenciones sugeridas:

- `docs: record class ...`
- `progress: update mastery after class ...`
- `assessment: record checkpoint ...`
- `strategy: freeze v1 ...`
- `journal: record demo trade ...`
- `spec: refine progression rule ...`

## Fuente de verdad

El chat ensena; el repositorio conserva evidencia y reglas. Si existe conflicto, las specs versionadas del repositorio deben revisarse explicitamente antes de cambiar el proceso.
