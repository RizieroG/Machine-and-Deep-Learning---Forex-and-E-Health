:point_right: Machine and Deep-Learning to Forex and E-Health :point_left:


Salve, sono uno studente di ingegneria informatica, condivido qui i miei progetti creati per la tesi di laurea. Sono in cerca di suggerimenti per il miglioramento degli stessi, o semplicemente spero che possano essere d'aiuto a qualcuno.
All'interno delle cartelle troverete tutti progetti svolti su Google Colab, organizzati in due cartelle: una per l'applicazione dei metodi di regressione Lineare, Polinomiale, Lasso e Ridge; l'altra cartella è dedicata invece per l'applicazione della rete neurale LSTM.
Per entrambi i casi di studio sono state applicate tutte le tecniche di regressione e reti LSTM con lo scopo di comparare le diverse tecniche e capire quale fosse la più efficace. All'interno dei codici ".ipynb" troverete tutto il necessario per: gestire e modificare correttamente il dataset (preso da Kaggle o messo a disposizione da terzi), creazione dei dataset di training/testing/validation, creazione del modello lineare/lasso/ridge/polinomiale/LSTM pronto per l'allenamento, allenamento della macchina, predizione, calcolo dell'errore commesso e grafico per il confronto tra predizione-valore vero.
Il caso di studio del Forex riguarda la coppia EUR/USD e la sua valutazione nel tempo. Lo scopo è: dato diversi input (o anche solo il valore di chiusura) capire se la macchina è capace di prevedere i prossimi valori di chiusura. Nel caso della rete LSTM vengono utilizzati gli ultimi 15 elementi come look back.
Per il caso di studio della glicemia ci basiamo sul valore di ISIG e Boli per prevedere il livello di glucosio nel sangue. Lo scopo è sempre quello di creare una macchina capace di prevedere i prossimi valori di glucosio a partire dai due input precedentemente accennati.
Per provare il codice basterà scaricare il file ".ipynb" e provarlo in un ambiente adatto (ad esempio Google Colab).
Spero che questi progetti possano servire a qualcuno o essere semplicemente d'ispirazione per un progetto più ampio.

-----#

English Version:


Hi, I am a student of computer engineering, I share here my projects that I made for the thesis. I am finding for advices to improve these projects, or I hope that them can help someone in theirs.
Inside of the folders you will find all the projects written by Google Colab, they are organized in two folders: the first folder is dedicated to the applications of the regression models such as: Linear, Ridge, Lasso and Polynomial; the second folder is dedicated to the application of the LSTM neural network.
For both case studies I used all the methods previously mentioned (regression and also LSTM) and aim is to compare them and find out the most efficient. Inside of the codes ".ipynb" you will find: management and modification the datasets (taken from kaggle or made available by third parties), creation of the training/testing/validation datasets, creation of the linear/polynomial/lasso/ridge/LSTM model ready for training, fit the models, prediction of values, computation of loss and plot the real values against predicted values.
The first case study is about the Forex, more precisely the pair EUR/USD and his history evalutation. The aim is: I take several (or just one) inputs and we try to understand if the model is able to predict the next closing values of EUR/USD. With the neural network LSTM I use a look back of 15 elements, you can try with other values.
The second case study is about the e-health, more precisely the prediction of blood glucose level. So in this second case I use the ISIG and Bolus values as inputs and the output is the blood glucose level. The aim is the same of the previous case, so we try to create a model that is able to predict the future blood glucose level values.
You can try the codes, just download the files ".ipynb" and open them inside of Google Colab, for example.
Again, I hope that these projects can help someone or just that can be an inspiration for bigger projects.
