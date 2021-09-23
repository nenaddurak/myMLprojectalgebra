# myMLprojectalgebra

Projekt: Airline Passenger Satisfaction

U ovom projektu bavit ćemo se problemom predviđanja zadovoljstva putnika neke avionske kompanije. 

Opis

Radi se o binarnom klasifikacijskom problemu u kojem traženo zadovoljstvo može biti jedno od: neutral or dissatisfied (neutralni ili nezadovoljni) ili satisfied (zadovoljni). Koristit ćemo skup podataka pronađen na Kaggleu (Airline Passenger Satisfaction) koji sadrži oko 130 000 redova podataka raspoređenih na 24 značajki. Dataset sadrži kategorične i kontinuirane značajke pa smo kategorične encodali na različite načine onako kako se činilo ispravno(one hot encoding) te smo proveli čišćenje podataka od nedostajućih vrijednosti, tj. popunili smo ih novim vrijednostima.

Konstruirali smo najbolji mogući model za dan skup podataka koristeći metode nadziranog učenja. 
Koristili smo pet  modela za binarnu klasifikaciju, to jest: Random Forest, Logističku regresiju, naivnog Bayesa, KNN i XGBoost. 
Cijeli kod pisan je u Pythonu, te smo raznim metodama za odabir značajki odabrali one najutjecajnije tako da model ostane precizan, ali i postane efikasniji.
Koristili smo nekoliko načina za evaluaciju modela, a medu njima i roc auc metriku koja dobro funkcionira na relativno balansiranom skupu podataka po pitanju target varijable.
Naš konačan rezultat je da najbolji rezultat u najkračem vremenu postiže Random Forest model sa oko 96% točnosti.  

Prije početka

Zahtijevi

Za izvođenje ovog projekta potrebno nam je računalo, u našem slučaju s instaliranim OS Win 10, stabilna Internet veza, korištenje nekog od Internet browser-a, otvaranje stranice https://colab.research.google.com 

Pokretanje programa

Nakon što smo pristupili stranici https://colab.research.google.com otvaramo file ProjectML.ipynb

Autor

Nenad Đurak - dnenad@racunarstvo.hr


Verzija

Verzija 1.0

Licenca

Ovaj program licenciran je pod imenom Nenad Đurak Licenca.

