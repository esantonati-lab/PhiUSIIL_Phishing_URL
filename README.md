# Rilevamento URL di Phishing tramite Regressione Logistica
Ginevra Sofia Moro 2086034 Elisa Santonati 2157441
Questo progetto mira a classificare gli URL in "legittimi" o "phishing" utilizzando modelli di classificazione lineare. Il lavoro è stato realizzato per il corso di **Intelligenza Artificiale 2**.
L'obiettivo è dimostrare l'efficacia della Regressione Logistica nell'identificare minacce informatiche basandosi su feature strutturali dell'URL, confrontando un'implementazione manuale (Custom) con lo standard industriale (Scikit-Learn).
Il dataset utilizzato è il **PhiUSIIL Phishing URL Dataset**, reperito dal repository UCI Machine Learning. 
- **Dimensioni:** 235.795 osservazioni.
- **Target:** `label` (0: Legit, 1: Phishing).

Le principali librerie Python utilizzate sono:
* `numpy`: Calcolo vettoriale e implementazione matematica.
* `pandas`: Manipolazione e pulizia dei dati.
* `matplotlib` & `seaborn`: Visualizzazione dati (Dashboard EDA, 3D Plots, Decision Boundary).
* `scipy`: Ottimizzazione numerica (`fmin_tnc`).
* `scikit-learn`: Benchmarking e metriche di valutazione.

# Come eseguire il codice
Per riprodurre i risultati:
1. Clonare la repository: `git clone https://github.com/tuo-username/nome-progetto.git`
2. Assicurarsi di avere installato le dipendenze: `pip install numpy pandas matplotlib seaborn scipy scikit-learn`
3. Aprire il file `Progetto_AI.ipynb` in **Google Colab** o **Jupyter Notebook**.
4. Caricare il file CSV del dataset (seguendo le istruzioni nel notebook) ed eseguire le celle in ordine cronologico.
