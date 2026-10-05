<!-- ELUCENIA technical documentation · superficie-corporal · en · no clinical/professional/rights approval -->

# Body surface area and BMI

[conditions, sources and permissions](https://elucenia.org/en/tools/superficie-corporal)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Weight

`peso`

kg · range: 2–350

### Height

`altura`

cm · range: 40–240

## Method edition

Mosteller 1987 √(cm×kg/3600); DuBois 1916 coefficient 0.007184, powers 0.425/0.725; separate BMI

## Documented formula

Mosteller: BSA (m²) = √(height \[cm\] × weight \[kg\] ÷ 3600)

DuBois: BSA (m²) = 0.007184 × weight0.425 × height0.725

BMI = weight ÷ height² (m)

## Limits and population

Enter height in cm and weight in kg; the result is an estimated body surface area in m², distinct from BMI. Mosteller and Du Bois are different equations, not direct surface measurements. The cited 2012 ASCO guideline addresses cytotoxic chemotherapy dosing in obese adults with cancer and does not cover novel targeted agents of that edition. Calculating surface area does not define a dose, a surface-area cap or an indication: the decision must follow the specific protocol and medicine, without deriving universal limits from that reference.

## References

- [Mosteller RD. Simplified calculation of body-surface area. N Engl J Med, 1987.](https://doi.org/10.1056/NEJM198710223171717)

- [Griggs JJ et al. Appropriate chemotherapy dosing for obese adult patients with cancer: American Society of Clinical Oncology clinical practice guideline. J Clin Oncol, 2012.](https://doi.org/10.1200/JCO.2011.39.9436)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
