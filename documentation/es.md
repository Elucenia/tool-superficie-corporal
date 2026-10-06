<!-- ELUCENIA technical documentation · superficie-corporal · es · no clinical/professional/rights approval -->

# Superficie corporal e IMC

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/superficie-corporal)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Peso

`peso`

kg · intervalo: 2–350

### Estatura

`altura`

cm · intervalo: 40–240

## Edición del método

Mosteller 1987 √(cm×kg/3600); DuBois 1916 coeficiente 0,007184, potencias 0,425/0,725; IMC separado

## Fórmula documentada

Mosteller: SC (m²) = √(altura \[cm\] × peso \[kg\] ÷ 3600)

DuBois: SC (m²) = 0,007184 × peso0,425 × altura0,725

IMC = peso ÷ altura² (m)

## Límites y población

Introduzca altura en cm y peso en kg; el resultado es una estimación de superficie corporal en m², distinta del IMC. Mosteller y Du Bois son ecuaciones diferentes, no mediciones directas de la superficie. La guía ASCO 2012 citada trata de dosis de quimioterapia citotóxica en adultos obesos con cáncer y no abarca nuevos agentes dirigidos de esa edición. Calcular la superficie no define dosis, límite máximo de superficie ni indicación: la decisión debe seguir el protocolo y medicamento específicos, sin deducir límites universales de esa referencia.

## Referencias

- [Mosteller RD. Simplified calculation of body-surface area. N Engl J Med, 1987.](https://doi.org/10.1056/NEJM198710223171717)

- [Griggs JJ et al. Appropriate chemotherapy dosing for obese adult patients with cancer: American Society of Clinical Oncology clinical practice guideline. J Clin Oncol, 2012.](https://doi.org/10.1200/JCO.2011.39.9436)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

IMC 24,2 kg/m²: normopeso

| Detalles del resultado | |
| --- | --- |
| DuBois | 1,81 m² |
| IMC | 24,2 kg/m² |


### 2

IMC 19,5 kg/m²: normopeso

| Detalles del resultado | |
| --- | --- |
| DuBois | 1,50 m² |
| IMC | 19,5 kg/m² |

