# R-Calibracion-Modelos-Rating-Bayesiano

## Descripción

Implementación práctica de la metodología propuesta por Serenelli & Delfau (2023) para la estimación objetiva de probabilidades de incumplimiento (PD) en sistemas de calificación crediticia ordenados, aplicando enfoques bayesianos no informativos.

## Objetivos

- Implementar el método de Jeffreys Prior para estimación de PDs ordenadas
- Desarrollar simulación Monte Carlo con restricciones de monotonicidad
- Resolver el problema de calibración en carteras de bajo default
- Proporcionar una alternativa objetiva a los métodos subjetivos tradicionales

## Metodología

- Prior de Jeffreys multivariado
- Transformación: `PD = cos(θ)²` donde `θ ∈ [0, π/2]`
- Restricción: `PD₁ < PD₂ < ... < PD₉` (para 9 ratings)
- Simulación Monte Carlo
- Estimación final de PDs por rating

## Aplicaciones

- Calibración de modelos de rating interno (IRB)
- Estimación de PDs en carteras de bajo default
- Validación de escalas de calificación ordenadas
- Cumplimiento regulatorio (Basilea)

## Autores

-Chantres Arrieta Nikole
- Corona López José Luis
- Popoca Rivas Brayan Nain

## Referencia

- Serenelli, G. F., & Delfau, E. (2023). Estimation of Probabilities for Ordered Sets and Application to Calibration of Rating Models. Universidad del CEMA.

