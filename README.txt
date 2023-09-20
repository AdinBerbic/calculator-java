LOC - 18+104 = 122 linije koda ukupno

Calculator.java

2 - Zapažanje: Korišæenje statièke promenljive "finalResult" može dovesti do problema u višenitnom okruženju i otežati testiranje. Treba razmotriti alternativne naèine za rukovanje rezultatom.
5-22 - Zapažanje: Unutar klase "Operations" definisani su statièki simboli za operacije. Ovo može biti korisno za èitljivost, ali treba obratiti pažnju na to da se operacije veæ koriste kao karakteri u kodu. Treba li ovo dvostruko definisanje?
24 - Zapažanje: Konstruktor klase "Operations" je privatni i ne koristi se. Nema potrebe za definisanjem privatnog konstruktora u ovoj situaciji.
26-33 - Zapažanje: Metoda "ToString" klase "Operations" vraæa string sa svim operacijama, ali nije jasno zašto bi ovo bilo korisno. Možda bi trebalo razmotriti promjenu naziva metode kako bi se izbjegla zabuna.
36 - Zapažanje: Ova metoda "Run" samo poziva "evaluateExpression" i može biti nepotrebna. Možda bi se mogla eliminisati i pozivati "evaluateExpression" direktno.
39-60 - Zapažanje: Metoda "evaluateExpression" sadrži mnogo kompleksne logike za analizu izraza. Ovo može biti teško održavati i testirati. Treba razmotriti razbijanje ovog djela koda na manje funkcije radi poboljšanja èitljivosti i održavanja.
67-75 - Zapažanje: Kod za razdvajanje brojeva iz izraza i operacija je komplikovan i težak za èitanje. Treba razmotriti bolje metode za razdvajanje i analizu izraza.
78-100 - Zapažanje: Metoda "Calculate" takoðe sadrži dosta kompleksne logike za izvršavanje raèunskih operacija. Ovo bi se takoðe moglo razdvojiti i pojednostaviti kako bi se poboljšala èitljivost i održavanje.



Start.java

5 - Zapažanje: Varijabla "expression" bi trebala imati opisno ime kako bi se jasno razumjela njena svrha, npr. "inputExpression" ili slièno.
8 - Zapažanje: Klasa "Scanner" se koristi za unos sa tastature, ali nakon što se unese izraz, više se ne èeka novi unos unutar petlje. Ovo može izazvati nepravilno ponašanje programa. Treba razmisliti o postavljanju skeniranja unutar petlje kako bi se èekao novi unos nakon svake iteracije.
9 - Zapažanje: Trenutna implementacija ne uzima novi unos unutar petlje. Treba dodati skeniranje unutar petlje kako bi se omoguæila interaktivnost sa korisnikom i unos novih izraza.
