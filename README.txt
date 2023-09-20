LOC - 18+104 = 122 linije koda ukupno

Calculator.java

2 - Zapa�anje: Kori��enje stati�ke promenljive "finalResult" mo�e dovesti do problema u vi�enitnom okru�enju i ote�ati testiranje. Treba razmotriti alternativne na�ine za rukovanje rezultatom.
5-22 - Zapa�anje: Unutar klase "Operations" definisani su stati�ki simboli za operacije. Ovo mo�e biti korisno za �itljivost, ali treba obratiti pa�nju na to da se operacije ve� koriste kao karakteri u kodu. Treba li ovo dvostruko definisanje?
24 - Zapa�anje: Konstruktor klase "Operations" je privatni i ne koristi se. Nema potrebe za definisanjem privatnog konstruktora u ovoj situaciji.
26-33 - Zapa�anje: Metoda "ToString" klase "Operations" vra�a string sa svim operacijama, ali nije jasno za�to bi ovo bilo korisno. Mo�da bi trebalo razmotriti promjenu naziva metode kako bi se izbjegla zabuna.
36 - Zapa�anje: Ova metoda "Run" samo poziva "evaluateExpression" i mo�e biti nepotrebna. Mo�da bi se mogla eliminisati i pozivati "evaluateExpression" direktno.
39-60 - Zapa�anje: Metoda "evaluateExpression" sadr�i mnogo kompleksne logike za analizu izraza. Ovo mo�e biti te�ko odr�avati i testirati. Treba razmotriti razbijanje ovog djela koda na manje funkcije radi pobolj�anja �itljivosti i odr�avanja.
67-75 - Zapa�anje: Kod za razdvajanje brojeva iz izraza i operacija je komplikovan i te�ak za �itanje. Treba razmotriti bolje metode za razdvajanje i analizu izraza.
78-100 - Zapa�anje: Metoda "Calculate" tako�e sadr�i dosta kompleksne logike za izvr�avanje ra�unskih operacija. Ovo bi se tako�e moglo razdvojiti i pojednostaviti kako bi se pobolj�ala �itljivost i odr�avanje.



Start.java

5 - Zapa�anje: Varijabla "expression" bi trebala imati opisno ime kako bi se jasno razumjela njena svrha, npr. "inputExpression" ili sli�no.
8 - Zapa�anje: Klasa "Scanner" se koristi za unos sa tastature, ali nakon �to se unese izraz, vi�e se ne �eka novi unos unutar petlje. Ovo mo�e izazvati nepravilno pona�anje programa. Treba razmisliti o postavljanju skeniranja unutar petlje kako bi se �ekao novi unos nakon svake iteracije.
9 - Zapa�anje: Trenutna implementacija ne uzima novi unos unutar petlje. Treba dodati skeniranje unutar petlje kako bi se omogu�ila interaktivnost sa korisnikom i unos novih izraza.
