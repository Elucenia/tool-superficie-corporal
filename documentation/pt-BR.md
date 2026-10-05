<!-- ELUCENIA technical documentation · superficie-corporal · pt-BR · no clinical/professional/rights approval -->

# Superfície corporal e IMC

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/superficie-corporal)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Peso

`peso`

kg · intervalo: 2–350

### Altura

`altura`

cm · intervalo: 40–240

## Edição do método

Mosteller 1987 sqrt(cm×kg/3600); Du Bois 1916 coeficiente 0,007184/potências 0,425/0,725; IMCseparado

## Fórmula documentada

Mosteller: SC (m²) = √(altura \[cm\] × peso \[kg\] ÷ 3600)

DuBois: SC (m²) = 0,007184 × peso0,425 × altura0,725

IMC = peso ÷ altura² (m)

## Limites e população

Informe altura em cm e peso em kg; o resultado é uma estimativa de superfície corporal em m², distinta do IMC. Mosteller e Du Bois são equações diferentes, não medidas diretas da superfície. A diretriz ASCO 2012 citada trata de doses de quimioterapia citotóxica em adultos obesos com câncer e não abrange novos agentes alvo daquela edição. Calcular a superfície não define dose, teto de superfície ou indicação: a decisão deve seguir o protocolo e o medicamento específicos, sem deduzir limites universais dessa referência.

## Referências

- [Mosteller RD. Simplified calculation of body-surface area. N Engl J Med, 1987.](https://doi.org/10.1056/NEJM198710223171717)

- [Griggs JJ et al. Appropriate chemotherapy dosing for obese adult patients with cancer: American Society of Clinical Oncology clinical practice guideline. J Clin Oncol, 2012.](https://doi.org/10.1200/JCO.2011.39.9436)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
