# Progress Dashboard

## Estado general

- Fecha de inicio: 2026-10-01
- Diagnóstico inicial: **33/100**
- Semana actual: **1**
- Sesión curricular actual: **3 — Lotes, valor por pip, margen y apalancamiento**
- Entorno: **demo**
- Dinero real: **LOCKED**
- Estrategia actual: **sin versión operativa**
- Próximo checkpoint: **Checkpoint 1**

## Conceptos con evidencia positiva

- Interpretación base/cotizada.
- BUY gana si el par sube; SELL gana si baja.
- Cálculo básico de pips.
- Relación lote ↔ tamaño nominal.
- Aproximación EUR/USD:
  - 0.01 lot ≈ 1,000 EUR.
  - 0.10 lot ≈ 10,000 EUR.
  - 1.00 lot ≈ 100,000 EUR.
- PnL básico por pip.
- Margen aproximado = valor nominal / apalancamiento.
- Equity = saldo + PnL flotante.
- Margen libre = equity - margen usado.
- Nivel de margen = equity / margen usado × 100.

## Temas en refuerzo

- BUY usa Ask; SELL usa Bid.
- Diferencia entre margen y pérdida máxima.
- Lectura de spread en plataforma.
- Diferencia entre saldo y equity.
- Interpretación de margen libre bajo.
- Conversión entre puntos y pips en cotización de 5 decimales.

## Evidencia reciente

Ejercicios correctos:

- 0.10 lot = 10,000 EUR.
- 10,000 EUR × 1.1250 = 11,250 USD nominales.
- 11,250 / 50 = 225 USD de margen aproximado.
- 18 pips a 1 USD/pip = +18 USD PnL.
- 25 pips en contra = -25 USD PnL.
- Saldo 5,000, PnL -25 → equity 4,975.
- Equity 4,975, margen 225 → margen libre 4,750.
- Nivel de margen ≈ 2,211.11%.
- Equity 4,600, margen 1,000 → 460%.
- Equity 2,000, margen 1,000 → 200%.

## Error reciente

En un ejercicio se mezcló el valor nominal previo con el saldo de cuenta y se respondió 10,975 en lugar de 4,975. Se corrigió correctamente después.

## Siguiente objetivo

Completar la lectura práctica de cuenta en MT5 y luego entrar a la sesión 4: tipos de orden, Stop Loss, Take Profit y ejecución.

## Clase de refuerzo adicional — 2026-10-08

**Tema:** estructura de mercado, soporte/resistencia, rupturas y cambio de polaridad. Es un adelanto de los contenidos de semana 2; **no** reemplaza la finalizacion de la semana 1.

**Evidencia positiva:** identifica estructura alcista cuando maximos y minimos suben (92→97 y 84→88); reconoce estructura bajista en secuencias claras; en el refuerzo distinguio un soporte que pasa a resistencia (nivel 40). Durante el repaso previo identifico BUY al Ask y explico el calculo teorico del margen 225 USD para 0.10 lote EUR/USD a 1.1250, apalancamiento 1:50.

**Errores a reforzar:** confundio spread con margen inicialmente; en secuencias mixtas (maximos 80→76, minimos 70→73) clasifico erradamente como bajista; en el primer ejercicio de ruptura/retest de 54 identifico el soporte anterior pero omitio que funcionaba como resistencia despues del retest. Necesito apoyo visual y una segunda explicacion en varias preguntas.

**Mini examen:** 1 incorrecta, 1 correcta y 1 parcial. Ejercicio adicional de recuperacion correcto luego de explicacion. No cumple aun evidencia suficiente para 80% independiente. **Estado: REINFORCEMENT**, no MASTERED.

**Preferencia didactica:** dibujar una grafica en cada pregunta de lectura de mercado.

**Proxima accion:** prueba nueva de reconocimiento sin guia (maximos/minimos mixtos, ruptura, cambio de polaridad), y completar tareas de mecanica pendientes de sesion 3 (lectura MT5) antes de sesion 4 (ordenes, SL, TP). La sesion curricular formal permanece en 3. Entorno solo demo.

