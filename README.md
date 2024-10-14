# LLM AS SUPPORTING TOOLS FOR BIAS MITIGATION 
Questa repository contiene i dataset sintetici generati dagli esperimenti condotti nell'ambito della tesi intitolata "Mitigazione del Bias nei Dati Attraverso Refactoring Supportato da Large Language Models". 
Gli esperimenti sono stati condotti con l'obiettivo di valutare l'efficacia dei Large Language Models (LLM) nella mitigazione del bias nei dataset, utilizzati per l'addestramento di modelli di machine learning.
Ogni dataset sintetico presente in questa repository è stato generato da un LLM come parte del processo di refactoring dei dati per ridurre i sintomi di unfairness.
I dataset sono stati creati per testare l'efficacia delle tecniche di pre-processing suggerite dall'LLM (ChatGPT-4o).

## STRUTTURA DELLA REPOSITORY
- /fairness-datasets: Folder principale contenente i dataset sintetici in formato CSV, suddivisi in base ai vari esperimenti.
  - /student-performance: Contiene il dataset originale e i sintetici generati dall'LLM per gli esperimenti effettuati sul student-performance dataset.
  - /heart-disease: Contiene il dataset originale e i sintetici generati dall'LLM per gli esperimenti effettuati sul heart-disease dataset.
  - /german-credit: Contiene il dataset originale e i sintetici generati dall'LLM per gli esperimenti effettuati sul german-credit dataset.

