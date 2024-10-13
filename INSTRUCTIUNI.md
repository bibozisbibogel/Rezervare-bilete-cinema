# Programul o sa aiba urmatoarele functii:



 1. Crearea unui cont pe platforma sau inregistrarea in contul personal ( Log In / Sign Up ) -> functiile "signup" si "login"
 2. Optiunea de a alege un film dintr-o multime predefinita -> caracteristica a functii "reservation"
 3. Optiunea de a alege ora la care sa vizionezi filmul -> caracteristica a functii "reservation"
 4. Optiunea de a alege sala ( multimea locurilor dintr-o sala este prestabilita) -> caracteristica a functii "reservation"
 5. Optiunea de a alege locul sau chiar locurile ( alegerea unui loc care este deja ocupat va face programul sa afiseze " EROARE! LOC DEJA OCUPAT! " si ne va trimite inapoi la alegerea locului) -> caracteristica a functii "reservation"
 6. Optiunea de a vizualiza rezervarile facute ( rezervari personale) -> functia "my_reservations"
 7. Optiunea de a anula o rezervare facuta ( rezervari personale) -> functia "cancel_reservation"
 8. Optiunea de a ne deconecta de pe platforma ( numai daca suntem deja logati) -> functia "logout" (utilizarea comenzii fara a fi logat va duce la o eroare, afisata prin mesajul "EROARE! LIPSA CONT!")
 


# Exemple de comenzi posibile:

1. signup - crearea unui cont personal care consta intr-un nume si-o parola
2. login - conectarea in contul personal introducand numele si parola
3. movie - optiunea de a vizualiza lista filmelor care sunt difuzate in ziua respectiva
4. reservation - optiunea de a face rezervare ( o comanda mai complexa pe care o vom explica separat)
5. my_reservations - optiunea de a observa rezervarile facute 
6. cancel_reservation -> optiunea de a anula o rezervare facuta
7. logout -> optiunea de a ne deconecta de la platforma

# Functia reservation:

Aplicarea functiei fara a fi conectat pe platforma va duce la afisarea mesajului " EROARE! LIPSA CONT! "
Introducerea functiei dupa ce ne-am conectat va duce la urmatorul proces: 

comenzi introduse:               |                consola: <br/>
reservation                      |                Ce film ati dori sa vizionati? <br/>
filmul_K                         |                filmul_K este disponibil la orele: (afisarea orelor) <br/>
ora_K                            |                In ce sala doriti sa vizionati filmul? <br/>
sala_K                           |                Ce loc(uri) doriti sa rezervati? <br/>
locul_K                          |             (varianta in care locul nu este rezervat) Succes! Rezervarea dumneavoastra a fost creata cu succes! /   (varianta in care locul este deja rezervat) "EROARE! LOC DEJA OCUPAT!" <br/>
