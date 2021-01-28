# Face-to-BMI

In questo progetto viene allenata una CNN (FaceNet) su un dataset di immagini con valore di targhet il BMI.

## Data source
Per ottenere il dataset si può utilizzare il (notebook)[] dove viene effettuato un web scraping del sito https://compareceleb.com/. Le immagini scaricate vengono poi ritagliate per ottenere solamente il viso. La maggior parte delle immagini ha dimensione 500x500 ma sono presenti anche immagini di dimensioni inferiori.

Il dataset contiene 3 categorie:
* 0, con BMI minore di 22
* 1, con BMI compreso tra 22 e 25
* 2, con BMI superiore a 25

Viene infine diviso in train, validation e test set. 

## Risultati

