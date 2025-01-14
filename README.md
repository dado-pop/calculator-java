-PRVI ZADATAK:
Nad kodom koji se nalazi u navedenom repozitorijumu trebalo je izračunati sledeću metriku:
LOC (za kompletan projekat, odnosno za sve fajlove zbirno)
Uz pomoć alata CLOC dobio sam rezultat 148

-DRUGI ZADATAK: 
Statička analiza koda urađena je pomoću SonarLint ekstenzije VSC-a
U nastavku su zapažanja:

- File Calculator.java – 1 : Premesti ovaj fajl u imenovani paket.
- File Calculator.java – 4 : Dodaj privatni konstruktor da sakriješ implicitni javni.
- File Calculator.java – 18 : Preimenuj metodu "ToString" da izbegneš nesporazum/sukob sa metodom "toString" definisanom u nadklasi "java.lang.Object".
- File Calculator.java – 70 : Odmah vrati ovu izraz umesto da ga dodeljuješ privremenoj promenljivoj "textResult".
- File Calculator.java – 183 : Ukloni ovaj suvišni skok.
