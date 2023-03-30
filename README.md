# Objektinis_pirmas_projektas

***v0.5***
+ Pridėtas kodas, kuris naudoja *deque* tipo konteinerį vietoj *vector*.
+ Pridėtas kodas, kuris naudoja *list* tipo konteinerį vietoj *vector*.
+ Pridėtas įvairių programos procesų veikimo laikas, kuris yra matomas apačioje lenetlės pavidalu su *vector*, *deque*, *list* tipo konteineriais.

Vector:

|             	| 1000     	| 10 000   	| 100 000  	| 1 000 000 	| 10 000 000 	|
|-------------	|----------	|----------	|----------	|-----------	|------------	|
| Nuskaitymas 	| 0.006533 	| 0.056995 	| 0.552395 	| 5.49003   	| 55.3696    	|
| Rūšiavimas  	| 0.000112 	| 0.001073 	| 0.012968 	| 0.172484  	| 2.18111    	|
| Grupavimas  	| 0.000183 	| 0.001625 	| 0.019355 	| 0.210891  	| 2.51844    	|

Deque:

|             	| 1000     	| 10 000   	| 100 000  	| 1 000 000 	| 10 000 000 	|
|-------------	|----------	|----------	|----------	|-----------	|------------	|
| Nuskaitymas 	| 0.00664  	| 0.056811 	| 0.554563 	| 5.50413   	| 58.6558    	|
| Rūšiavimas  	| 0.000476 	| 0.005604 	| 0.076834 	| 1.07119   	| 14.0064    	|
| Grupavimas  	| 0.000426 	| 0.003721 	| 0.041214 	| 0.438361  	| 31.0137    	|

List:

|             	| 1000     	| 10 000   	| 100 000  	| 1 000 000 	| 10 000 000 	|
|-------------	|----------	|----------	|----------	|-----------	|------------	|
| Nuskaitymas 	| 0.008188 	| 0.067202 	| 0.656576 	| 6.51919   	| 66.1506    	|
| Rūšiavimas  	| 0.000094 	| 0.001106 	| 0.016726 	| 0.464297  	| 8.88744    	|
| Grupavimas  	| 0.000752 	| 0.007832 	| 0.122866 	| 1.36547   	| 18.1952    	|

***Sistemos parametrai su kuriais buvo pateikti testavimų duomenys***
+ ***CPU:*** AMD Ryzen 5 3600 6-Core Processor, 3600 Mhz, 6 Core(s), 12 Logical Processor(s)
+ ***RAM:*** 16GB
+ ***SSD:*** Kingston SA2000M8 1TB NVMe, (Read/Write) 2,200/2,000MB/s.


<br />
<br />

***v0.4***
+ Pridėta funkcija *gen_file*, kuri generuoja failą su duomenimis.
+ Pridėta funcija *write_to_file*, kuri surūšiuoja duomenis ir priskiria studentą į ***kietiakai.txt*** arba ***vargsiukai.txt*** pagal studneto vidurkį.
+ Pridėtas įvairių programos procesų veikimo laikas, kuris yra matomas apačioje lenetlės pavidalu.


|                     	| 1000     	| 10 000   	| 100 000  	| 1 000 000 	| 10 000 000 	|
|---------------------	|----------	|----------	|----------	|-----------	|------------	|
| Nuskaitymas         	| 0.007238 	| 0.057681 	| 0.57259  	| 5.60828   	| 56.4872    	|
| Rūšiavimas          	| 0.000335 	| 0.003109 	| 0.029556 	| 0.313585  	| 4.03375    	|
| Spausdinimas (kiet) 	| 0.000357 	| 0.00269  	| 0.026719 	| 0.274681  	| 2.66694    	|
| Spausdinimas (varg) 	| 0.000288 	| 0.002639 	| 0.026852 	| 0.266558  	| 2.68626    	|
| Iš viso             	| 0.008218 	| 0.066119 	| 0.655717 	| 6.4631    	| 65.8742    	|

<br />
<br />

***v0.3***

+ Pridėti exception'ai, kurie patikrina ar skaitomas failas nėra tuščias arba neegzistuojantis.
+ Programoje naudojamos funkcijos yra perkeltos į atskirą .cpp failą.
+ **Mylib.h** yra papildytas naudojamų funkcijų antraštėmis ir struktūra.

<br />
<br />

***v0.2***

+  Pridėta funkcija '*bufer_nusk'*, kuri atidaro pasirinktą failą ir perkelia duomenis į buferį iš kurio nuskaito duomenis į struktūrą, apksaičiuoja*'Galutinis (Vid.)'* bei  studento *'Galutinis (Med.)'* pažymius, kuriuos išveda į kitą failą jau surušiuotus pagal vardus.

<br />
<br />

***v0.1*** (su C stiliaus masyvais ir vektoriais)

Su C stiliaus masyvais:
+  Turi struktūrą '*studentas*'.
+  Funkcijoje *'pild'* suvedami duomenys apie namų darbų ir egzamino pažymius. Šioje funkcijoje atliekami galimų įvedimo klaidų šalinimas.
+  Funkcija *'gal'* apskaičiuoja ir grąžina studento *'Galutinis (Vid.)'* pažymį.
+  Funkcija *'med'* apskaičiuoja ir grąžina studento *'Galutinis (Med.)'* pažymį.
+  Funkcija *'spausd'* išveda duomenis.


Su vektoriais:
+  Turi struktūrą '*studentas*'.
+  Funkcijoje *'pild'* suvedami duomenys apie namų darbų ir egzamino pažymius. Šioje funkcijoje atliekami galimų įvedimo klaidų šalinimas. 
+  Funkcija *'spausd'* apskaičiuoja studento *'Galutinis (Vid.)'* bei apskaičiuoja studento *'Galutinis (Med.)'* pažymius. Taip pat išvedami duomenys.
