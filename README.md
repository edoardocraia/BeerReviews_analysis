# BeerReviews_analysis

Progetto sviluppato per il corso **Sistemi Intelligenti per Internet** presso l'Università degli Studi di Roma "La Sapienza".  
L'obiettivo è analizzare e comprendere le recensioni di birre attraverso tecniche di analisi del sentiment, algoritmi di ranking e ricerca sociale.

## Struttura del progetto

Il repository è organizzato nei seguenti moduli:

- **`Sentiment_Analysis/`**: Contiene notebook e script per l'analisi del sentiment delle recensioni, utilizzando tecniche di NLP e modelli di machine learning.
- **`PageRank_Analysis/`**: Implementa l'algoritmo PageRank per determinare l'importanza relativa delle birre in base a metriche derivate dalle recensioni.
- **`SocialSearch_Analysis/`**: Esplora metodi di ricerca sociale per identificare birre simili o correlate, basandosi su comportamenti e preferenze degli utenti.
- **`.idea/`**: File di configurazione dell'ambiente di sviluppo (IntelliJ/PyCharm).

## Tecnologie e strumenti utilizzati

- **Linguaggio**: Python 3.x
- **Notebook**: Jupyter Notebook
- **Librerie principali**:
  - `pandas`, `numpy` per la manipolazione dei dati
  - `scikit-learn` per il machine learning
  - `nltk`, `spaCy` per il Natural Language Processing
  - `networkx` per l'analisi di grafi
  - `matplotlib`, `seaborn` per la visualizzazione dei dati

## Dataset

Il progetto utilizza un dataset di recensioni di birre, contenente informazioni quali:
- Nome della birra
- Recensione testuale
- Valutazioni numeriche (es. aroma, gusto, aspetto)
- Informazioni sull'utente (es. ID, preferenze)

> **Nota**: Il dataset completo non è incluso nel repository per motivi di spazio e privacy.
