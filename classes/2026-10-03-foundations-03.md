# Clase — Lotes, PnL, Margen y Apalancamiento

## Objetivo

Conectar tamaño de posición, valor por pip, PnL, margen, equity, margen libre y nivel de margen.

## Plataforma

- MetaTrader 5
- Cuenta demo
- EUR/USD
- M15
- Volumen observado: 0.01 lot

## Conceptos

### Lote

En EUR/USD:

- 0.01 lot ≈ 1,000 EUR.
- 0.10 lot ≈ 10,000 EUR.
- 1.00 lot ≈ 100,000 EUR.

El lote mide tamaño de posición. El pip mide movimiento.

### PnL

PnL = Profit and Loss = ganancia/pérdida.

Ejemplo:

- 0.10 lot ≈ 1 USD/pip.
- +18 pips → +18 USD.
- -25 pips → -25 USD.

### Valor nominal

10,000 EUR a EUR/USD 1.1250:

10,000 × 1.1250 = 11,250 USD.

### Margen

Con apalancamiento 1:50:

11,250 / 50 = 225 USD de margen aproximado.

Margen no significa pérdida máxima.

### Equity

Equity = Saldo + PnL flotante.

Ejemplo:

5,000 - 25 = 4,975 USD.

### Margen libre

Margen libre = Equity - Margen usado.

4,975 - 225 = 4,750 USD.

### Nivel de margen

Nivel de margen = Equity / Margen usado × 100.

Ejemplos correctos:

- 4,975 / 225 × 100 ≈ 2,211.11%.
- 4,600 / 1,000 × 100 = 460%.
- 2,000 / 1,000 × 100 = 200%.

## Errores observados

- En un ejercicio, se mezcló el valor nominal previo con el saldo de cuenta.
- Se corrigió al recordar que equity parte del saldo, no del tamaño nominal.

## MT5

Se logró:

- conectar correctamente la cuenta demo;
- habilitar Nueva Orden;
- abrir la ventana de orden;
- observar 0.01 lot = 1,000 EUR;
- observar Bid/Ask y spread.

## Checklist

- [x] Explica lote como tamaño.
- [x] Convierte 0.10 lot a 10,000 EUR.
- [x] Calcula valor nominal en USD.
- [x] Calcula margen aproximado.
- [x] Calcula PnL simple.
- [x] Calcula equity.
- [x] Calcula margen libre.
- [x] Calcula nivel de margen.
- [x] Interpreta caída del nivel de margen como mayor presión.
- [ ] Lee saldo/equity/margen/margen libre directamente en MT5.
- [ ] Mini examen formal de 3 preguntas.

## Estado

**IN PROGRESS**

La teoría y los cálculos muestran buen avance. Falta cerrar la práctica directamente en MT5 y registrar mini examen.
