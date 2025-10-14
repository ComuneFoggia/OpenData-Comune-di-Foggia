# Dataset: Elenco Morti Foggia - Residenti

## Descrizione
Questo dataset contiene i dati relativi agli atti di morte registrati dal Comune di Foggia nel corso del 2024, riferiti a cittadini **residenti**.  
Il dataset è stato sottoposto a un accurato processo di pre-processing e arricchimento per favorirne la pubblicazione come Open Data.

---

## Struttura del Dataset

| Colonna                 | Descrizione                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| Numero                  | Numero progressivo dell'atto (ID univoco)                                   |
| Sesso                   | Sesso del defunto (M = Maschio, F = Femmina)                                |
| Comune di Nascita       | Comune di nascita del defunto                                                |
| Sigla Comune di Nascita | Sigla della provincia del comune di nascita                                 |
| Data Nascita            | Data di nascita del defunto (formato AAAA-MM-GG)                            |
| Comune di Morte         | Comune in cui è avvenuto il decesso                                         |
| Sigla Comune di Morte   | Sigla della provincia del comune di morte                                   |
| Data Morte              | Data in cui è avvenuto il decesso                                           |
| Ora Morte               | Orario del decesso (formato HH:MM)                                          |
| Data Atto               | Data di registrazione dell’atto di morte                                    |
| Comune di Residenza     | Comune di residenza del defunto                                             |
| Sigla Residenza         | Sigla della provincia del comune di residenza                               |
| Giorno Morte            | Giorno della settimana in cui è avvenuto il decesso (es. Lunedì, Martedì)  |
| Anno Morte              | Anno in cui è avvenuto il decesso                                           |
| Mese Morte              | Mese (valore numerico) in cui è avvenuto il decesso                         |
| Eta Morte               | Età del defunto al momento del decesso (in anni, se disponibile)            |

--

## Periodo di Riferimento
**Anno 2024**

## Fonte
**Comune di Foggia**

## Formato File
- Tipo: CSV (Comma-Separated Values)
- Separatore: `,`
- Encoding: UTF-8
- Compatibilità: Excel, Google Sheets, Python (pandas), R

---

## Licenza
**CC BY 4.0 – Creative Commons Attribution 4.0 International**

È consentito:
- Utilizzare il dataset
- Condividerlo e modificarlo
- Adattarlo anche per fini commerciali  
A condizione di citare la fonte: *Comune di Foggia*

---

## Finalità e Applicazioni
Il dataset può essere utilizzato per:
- Analisi demografiche e statistiche locali
- Valutazioni stagionali e settimanali delle morti
- Progetti di ricerca in ambito sociologico
- Applicazioni di data visualization e open government
