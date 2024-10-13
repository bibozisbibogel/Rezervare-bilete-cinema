# Instructiuni Proiect "Rezervare bilete cinema" <br/>

# Programul o sa aiba urmatoarele functii: 


 1. Crearea unui cont pe platforma sau inregistrarea in contul personal ( Log In / Sign Up ) -> functiile "signup" si "login" <br/>
 2. Optiunea de a alege un film dintr-o multime predefinita -> caracteristica a functii "reservation" <br/>
 3. Optiunea de a alege ora la care sa vizionezi filmul -> caracteristica a functii "reservation" <br/>
 4. Optiunea de a alege sala ( multimea locurilor dintr-o sala este prestabilita) -> caracteristica a functii "reservation" <br/>
 5. Optiunea de a alege locul sau chiar locurile ( alegerea unui loc care este deja ocupat va face programul sa afiseze " EROARE! LOC DEJA OCUPAT! " si ne va trimite inapoi la alegerea locului) -> caracteristica a functii  "reservation" <br/>
 6. Optiunea de a vizualiza rezervarile facute ( rezervari personale) -> functia "my_reservations" <br/>
 7. Optiunea de a anula o rezervare facuta ( rezervari personale) -> functia "cancel_reservation" <br/>
 8. Optiunea de a ne deconecta de pe platforma ( numai daca suntem deja logati) -> functia "logout" (utilizarea comenzii fara a fi logat va duce la o eroare, afisata prin mesajul "EROARE! LIPSA CONT!") <br/>
 9. Optiunea de a vedea lista cu preturile biletelor -> functia "show_prices" <br/>
 10. Optiunea de a plati online rezervarea cu un card personal -> functia pay <br/>
 11. Optiunea de a vedea lista filmelor disponibile -> functia "show_movies" <br/>
# Exemple de comenzi posibile:

1. signup - crearea unui cont personal care consta intr-un nume si-o parola <br/>
2. login - conectarea in contul personal introducand numele si parola <br/>
3. show_movies - optiunea de a vizualiza lista filmelor care sunt difuzate in ziua respectiva <br/>
4. reservation - optiunea de a face rezervare ( o comanda mai complexa pe care o vom explica separat) <br/>
5. my_reservations - optiunea de a observa rezervarile facute <br/>
6. cancel_reservation -> optiunea de a anula o rezervare facuta <br/>
7. logout -> optiunea de a ne deconecta de la platforma <br/>
8. show_prices -> optiunea de a vizualiza lista preturilor biletelor <br/>
9. pay -> optiunea de a plati pentru rezervare <br/>

# Functia reservation:

Aplicarea functii fara a fi conectat pe platforma va duce la afisarea mesajului " EROARE! LIPSA CONT! "
Introducerea functiei dupa ce ne-am conectat va duce la urmatorul proces: 

comenzi introduse:               |                consola: <br/>
reservation                      |                Ce film ati dori sa vizionati? <br/>
filmul_K                         |                filmul_K este disponibil la orele: (afisarea orelor) <br/>
ora_K                            |                In ce sala doriti sa vizionati filmul? <br/>
sala_K                           |                Ce loc(uri) doriti sa rezervati? <br/>
locul_K                          |             (varianta in care locul nu este rezervat) Sunteti atat de aproape! Rezervarea dumneavoastra costa "Y" lei! /   (varianta in care locul 
      este deja rezervat) "EROARE! LOC DEJA OCUPAT!" <br/>

# La finalul functii reservation o sa trebuiasca sa platim pentru rezervarea noastra, asa ca este nevoie de functia "pay" <br/>

Aplicarea functii "pay" ne va obliga sa introducem datele cardului pentru a putea finaliza plata rezervarii <br/>

comenzi introduse:              |      consola: <br/>
pay                             |     Va rugam, introduceti-va datele cardului pentru a va putea finaliza rezervarea! <br/>
fullcardname_K                  |     Codul cardului dumneavoastra: <br/>
fullcardnumbers_K               |     CVV-ul dumneavoastra: <br/>
fullcvvnumbers_K                |     (varianta in care avem bani) Felicitari! Plata a fost realizata cu succes! / (varianta in care nu avem bani) "EROARE! FONDURI INSUFICIENTE!" <br/>
