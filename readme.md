# Sephora Product Reviews Classification

Questo progetto utilizza un sottoinsieme del dataset ["Sephora Products and Skincare Reviews"](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews) per addestrare un modello di apprendimento automatico in grado di classificare le recensioni dei prodotti Sephora come **raccomandate** (1) o **non raccomandate** (0) in base al contenuto della recensione.

## Descrizione del progetto

Il progetto ha lo scopo di costruire un modello di machine learning, specificamente un modello linguistico, per la classificazione di testo. La variabile target è la colonna `Is_reccomended`, mentre il testo della recensione, contenuto nella colonna `review_text`, rappresenta la variabile predittiva.

### Obiettivo principale

- **Predictive Modeling**: Sviluppare un modello in grado di classificare le recensioni in base al sentiment e altri fattori impliciti indicati nel testo.
- **Applicazioni**: Fornire un tool utile per analizzare rapidamente recensioni dei prodotti e supportare i processi decisionali di marketing.

---

## Struttura del repository

La repository contiene i seguenti file e cartelle principali:

```plaintext
.
├── data/                   # File di dataset utilizzati per l'addestramento e la validazione
│   └── reviews.csv         # Subset del dataset Sephora con le colonne `review_text` e `Is_reccomended`
├── models/                 # Modelli salvati dopo l'addestramento
├── notebooks/              # Jupyter Notebook per esplorazione ed esperimenti
├── src/                    # Codice sorgente del progetto
│   ├── preprocessing.py    # Funzioni per preprocessare i dati
│   ├── training.py         # Script per addestramento del modello
│   └── evaluation.py       # Script per la valutazione delle performance
├── README.md               # Documentazione del progetto
└── requirements.txt        # Dipendenze Python richieste
