# Progetto ML: previsione dell'affidabilità creditizia per il rilascio della carta di credito 💳

Il progetto consiste nella realizzazione di un modello di machine learning per stimare l'affidabilità creditizia di un cliente.  

Si hanno a disposizione i dati anonomizzati di clienti che hanno già ottenuto la carta di credito e lo stato del loro debito mensile, contenuti nel file `application_record.csv`. I clienti che chiedono il rilascio della carta di credito sono contenuti nel file `credit_record.csv`.

Vengono svolti i seguenti punti:
* Analisi esplorativa dei dataset
* Definizione e creazione di una variabile target
* Inner join dei dataset per ottenere il dataset finale
* Visualizzazione grafici relativi al dataset ottenuto
* Preprocessing dati con `scikit-learn`
* Oversampling con tecnica SMOTE
* Modellazione
  *   Regressione logistica
  *   Albero decisionale
  *   Random Forest
  *   Rete neurale
*   Interpretabilità dei risultati
  * Se ad un cliente viene negata la carta di credito, il team deve essere in grado di fornirgli una motivazione.
