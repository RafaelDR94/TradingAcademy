# Strategy Lab

## Hipótesis inicial

**Trend + Pullback + Confirmation**

No se considera estrategia rentable. Es un vehículo de aprendizaje hasta que exista evidencia.

## Marco inicial

- Mercado: un solo par líquido, inicialmente EUR/USD.
- Contexto: 1H.
- Entrada: 15m.
- Tendencia: swings claros.
- Evento: pullback a zona relevante.
- Confirmación: rechazo claro o ruptura de microestructura definida.
- Invalidación: punto que niega la tesis.
- Salida de laboratorio: regla fija por versión.

## Playbook obligatorio

1. Hipótesis.
2. Mercado.
3. Horario.
4. Contexto válido.
5. Contexto inválido.
6. Setup.
7. Trigger.
8. Stop/invalidation.
9. Salida.
10. Riesgo simulado.
11. No-trade.
12. Ejemplos válidos.
13. Ejemplos inválidos.
14. Versión y fecha.

## Backtest

Secuencia:

1. Congelar reglas.
2. Piloto de 20 trades.
3. Resolver ambigüedades y crear nueva versión si aplica.
4. Muestra principal significativa.
5. Separar muestra de evaluación.
6. Forward test/demo.

Métricas: expectancy, R, drawdown, profit factor, win rate contextual, rachas, costos y calidad de ejecución.
