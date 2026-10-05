<!-- ELUCENIA technical documentation · superficie-corporal · it · no clinical/professional/rights approval -->

# Superficie corporea e IMC

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/superficie-corporal)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Peso

`peso`

kg · intervallo: 2–350

### Altezza

`altura`

cm · intervallo: 40–240

## Edizione del metodo

Mosteller 1987 √(cm×kg/3600); DuBois 1916 coefficiente 0,007184, potenze 0,425/0,725; BMI separato

## Formula documentata

Mosteller: SC (m²) = √(altezza \[cm\] × peso \[kg\] ÷ 3600)

DuBois: SC (m²) = 0,007184 × peso0,425 × altezza0,725

BMI = peso ÷ altezza² (m)

## Limiti e popolazione

Inserisci altezza in cm e peso in kg; il risultato è una stima della superficie corporea in m², distinta dall’IMC. Mosteller e Du Bois sono equazioni diverse, non misure dirette della superficie. La linea guida ASCO 2012 citata riguarda le dosi di chemioterapia citotossica negli adulti obesi con cancro e non comprende i nuovi agenti mirati di quell’edizione. Calcolare la superficie non definisce dose, tetto di superficie o indicazione: la decisione deve seguire il protocollo e il farmaco specifici, senza dedurre limiti universali da tale riferimento.

## Riferimenti

- [Mosteller RD. Simplified calculation of body-surface area. N Engl J Med, 1987.](https://doi.org/10.1056/NEJM198710223171717)

- [Griggs JJ et al. Appropriate chemotherapy dosing for obese adult patients with cancer: American Society of Clinical Oncology clinical practice guideline. J Clin Oncol, 2012.](https://doi.org/10.1200/JCO.2011.39.9436)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
