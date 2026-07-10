## Decisión metodológica: ¿usar todos los centros o uno solo?

El repositorio original incluye información de cuatro instituciones:

| Centro | Registros aproximados |
|---|---:|
| Cleveland Clinic Foundation | 303 |
| Hungarian Institute of Cardiology | 294 |
| University Hospital de Zúrich | 123 |
| V.A. Medical Center de Long Beach | 200 |

Aunque podría parecer conveniente unir todos los registros, las cuatro bases no son completamente comparables. Presentan diferencias en la composición de las muestras, en la proporción de pacientes con enfermedad y, especialmente, en la cantidad de datos faltantes.

Algunas variables relevantes, como la cantidad de vasos principales observados por fluoroscopía (`ca`) y el resultado de talasemia (`thal`), se encuentran casi completas en Cleveland, pero presentan una gran cantidad de valores faltantes en otros centros. Además, ciertas bases corresponden a poblaciones clínicas muy particulares. Por ejemplo, la base de Long Beach proviene de un hospital de veteranos y contiene una proporción muy elevada de pacientes masculinos.

Por estos motivos, mezclar los cuatro centros podría introducir sesgos y hacer que algunas relaciones reflejen diferencias entre instituciones más que asociaciones clínicas entre variables.
El dataset elegido fue el de Cleveland.
