# OOD Detection via Neural Collapse: A NECO-based Study on MNIST

Questo repository contiene l'implementazione e l'analisi sperimentale di **NECO** (Neural Collapse based OOD detection), applicata a scala ridotta utilizzando il dataset **MNIST**. L'obiettivo del progetto è verificare come le proprietà geometriche del *Neural Collapse* possano essere sfruttate per identificare campioni Out-of-Distribution (OOD).

## 📌 Panoramica del Progetto
Il lavoro si ispira al paper:
> *NECO: Neural Collapse Based Out-of-Distribution Detection* (ICLR 2024).

Mentre il paper originale si concentra su architetture a larga scala (come i Vision Transformers), questo elaborato esplora l'efficacia del metodo su una **CNN custom** addestrata su MNIST, analizzando la separazione tra dati In-Distribution (ID) e dati OOD attraverso la proiezione nello spazio delle componenti principali (PCA) costruito a partire dai dati ID.

