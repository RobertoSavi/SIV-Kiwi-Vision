# SIG-Kiwi-Vision
A computer vision system able to detect kiwis in images

## Project Structure

```plaintext
SIV-KIWI-VISION/
├── edge_detection_experiments/       # Experiments to perfect the edge detection and A channel masking
│
├── YOLO_detection_experiments/       # Experiments with different YOLO models
│
├── images/                           # The images used to test the project
│
├── main.ipynb                        # Main notebook of the project 
│
├── kiwi_detector_4.pt                # YOLOv8 model fine-tuned on a kiwi_detaset
│
├── kiwi-1.zip                        # Dataset used to fine-tune the model
```


The Notebook relative to the project is main.ipynb


Info:
- Possibili feature: Dimensione, Forma, Colore, Texture, Numero
- Crescita di tipo logaritmico, prima tanto, poi poco.
- La crescita comincia da maggio (impollinazione) e termina a metà ottobre (raccolta).
- Già da settembre la crescita del Kiwi diminuisce notevolmente, di solito aumenta di circa 5% fino alla raccolta.
- La forma del kiwi è un parametro importante, in quanto un kiwi molto ovale è simbolo di un kiwi impollinato bene, che quindi diventerà un ottimo kiwi.
- Il numero dei kiwi è un altro parametro importante, più kiwi ci sono in un albero, minore sarà il nutriente che riceverà ciascun kiwi.
- L'obiettivo è togliere i kiwi impollinati male o che hanno poco potenziale in modo tale che non tolgano nutrimento ai kiwi che probabilmente saranno migliori.
- L'obiettivo non è avere più kiwi, ma kiwi migliori, in quanto vengono venduti meglio e ad un miglior prezzo.
- Il contare i kiwi, e l'identificazione e parametrizzazione delle feature scelte è una task adatta all'image processing, mentre il predire la dimensione finale e un compito adatto all'intelligenza artificiale.