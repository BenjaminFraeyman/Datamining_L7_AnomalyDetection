# Datamining_L7_AnomalyDetection

Je hebt voor practicum 7 van Datamining een rode code gekregen. Hieronder de feedback per gedeelte:

Imbalance classification: 1ste vraag: goed, terminologie kan wel wat beter. 2de vraag: De recall ging wel omhoog (58.97 % naar 90.38 %). Antwoord is niet goed. 3de vraag: resultaat, antwoord en plot zijn niet correct.

Wind turbine anomaly detection: De anomaly detection is niet correct. De 3 sigma regel moest je toepassen op het residue van de hold out set. Niet op de voorspelling van de hold out set. Plots zijn ook niet correct.

Clustering-based anomaly detection: Perfect, maar code sharing met Kevin L. Notebook voerde eerst niet goed uit, je voegde Dataframe.show() toe, show() bestaat niet op de  DataFrame klasse. Je code werkt niet zo efficiënt maar juiste resultaten.

Matrix Profile: Je hebt znorm_eucl niet geimplementeerd volgens de gegeven formule. 
