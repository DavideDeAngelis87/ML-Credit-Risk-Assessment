# Machine Learning for Credit Risk Assessment

## Descrizione del Progetto
Sviluppo di un sistema di **Credit Scoring** per la valutazione automatizzata dell'affidabilità creditizia dei clienti, in modo tale da permettere al team dedicato di comprendere se accettare o meno la richiesta per il rilascio della carta di credito.

L'analisi trasforma i dati storici e demografici dei richiedenti in un indicatore di rischio oggettivo, riducendo la discrezionalità e migliorando la stabilità del portafoglio crediti.

## Workflow Tecnico e Metodologia
Il workflow affronta le sfide tipiche dei dati finanziari:

1. **Exploratory Data Analysis (EDA):** identificazione delle variabili più correlate al rischio di default (es. reddito, durata del prestito, storico dei pagamenti).
2. **Data Cleaning & Pre Processing:** trattamento dei valori mancanti, One Hot Encoding delle variabili categoriche non ordinali e Label Encoding delle variabili binarie.
3. **Handling Class Imbalance:** applicazione di tecniche di bilanciamento per gestire la sproporzione tra clienti "solvibili" e "insolventi", garantendo che il modello sia in grado di riconoscere correttamente i casi critici.
4. **Modellazione Predittiva:** implementazione di algoritmi di classificazione per la valutazione del migliore: Regressione Logistica, SVC, Rete Neurale (MLP Classifier).
5. **Model Evaluation:** utilizzo delle metriche di classificazione per valutare i modelli bilanciando falsi positivi (prestiti sicuri rifiutati) e falsi negativi (prestiti rischiosi concessi).

## Tech Stack
* **Linguaggio:** Python
* **Librerie:** `Scikit-learn`, `Pandas`, `NumPy`.
* **Visualizzazione:** `Seaborn`, `Matplotlib`.

## Valore Strategico
- **Risk Mitigation:** riduzione delle perdite finanziarie attraverso una pre-valutazione accurata dei profili a rischio.
- **Process Automation:** velocizzazione dei tempi di risposta per le richieste di credito tramite lo screening automatico.
- **Informed Decision Making:** supporto ai dipartimenti di risk management con dati quantitativi e modelli validati.

## Struttura del Repository
- `Progetto_Affidabilità_creditizia.ipynb`: notebook contenente l'intero processo di analisi, addestramento e validazione del modello.
- `credit_scoring.csv`: dataset utilizzato per l'analisi
