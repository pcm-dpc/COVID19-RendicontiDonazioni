<img src="assets/images/dpc-logo-covid19.png" alt="DPC COVID-19 Rendiconti donazioni" data-canonical-src="assets/images/dpc-logo-covid19.png" width="400" />

# Dati rendiconti COVID-19

Fin dall’inizio dell’emergenza epidemiologica legata al virus Covid-19, lo slancio solidale è stato molto forte e partecipato. Per questo motivo il Dipartimento della Protezione Civile ha aperto tre conti correnti bancari per raccolte specifiche:<br>
- C/C 66387: nel quale sono confluite le donazioni finalizzate all’acquisto di dispositivi di protezione individuali (DPI), apparecchiature per respirazione, presidi medici ospedalieri, vaccini e servizio di trasporto DPI. La cifra raccolta è pari a € 173.517.036,19;
- C/C 66401: nel quale sono state versate donazioni finalizzate da due donatori a specifici progetti. La cifra raccolta è pari a € 89.481.600,00;
- C/C 66432: relativo alla campagna promossa da un donatore con l’obiettivo di sostenere i familiari dei medici, degli infermieri, degli operatori sanitari e dei soggetti con mansioni di supporto e assistenza ai sanitari deceduti a causa del contagio da Covid-19, contratto nell’esercizio delle proprie funzioni. La cifra raccolta è pari a € 12.728.498,70.

## Struttura del repository
```
UKR-2022/
├── data/
│   ├── csv
│   │   ├── DPC-EmeCovid19-CC66387-rendiconto.csv
│   │   ├── DPC-EmeCovid19-CC66401-rendiconto.csv
│   │   ├── DPC-EmeCovid19-CC66432-rendiconto.csv
│   ├── json
│   │   ├── DPC-EmeCovid19-CC66387-rendiconto.json
│   │   ├── DPC-EmeCovid19-CC66401-rendiconto.json
│   │   ├── DPC-EmeCovid19-CC66432-rendiconto.json
│   ├── odt
│   │   ├── DPC-EmeCovid19-CC66387-rendiconto.odt
│   │   ├── DPC-EmeCovid19-CC66401-rendiconto.odt
│   │   ├── DPC-EmeCovid19-CC66432-rendiconto.odt
│   ├── pdf
│   │   ├── DPC-EmeCovid19-CC66387-rendiconto.pdf
│   │   ├── DPC-EmeCovid19-CC66401-rendiconto.pdf
│   │   ├── DPC-EmeCovid19-CC66432-rendiconto.pdf
├── assets/
│   ├── images
```

## Dataset

|Nome campo<br>Field name|Descrizione<br>Description|Formato<br>Format|Esempio<br>Example|
|-|-|-|-|
|**data**|Data operazione|Date<br>YYYY-MM-DD<br>ISO 8601|2020-04-14|
|**operazione**|Tipo operazione|Stringa|entrata / uscita|
|**descrizione_documento**|Descrizione e/o documento|Stringa|Lorem ipsum|
|**importo**|Importo operazione|Decimal|100.50|
|**note**|Note operazione|Stringa|Lorem ipsum|

## Licenza

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)<br>
[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/COVID-19-Rendiconti/blob/master/LICENSE)
