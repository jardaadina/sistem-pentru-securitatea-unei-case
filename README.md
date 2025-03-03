# sistem-pentru-securitatea-unei-case
Acest proiect implementează un sistem de alarmă inteligent pentru o casă cu două camere. Sistemul este capabil să detecteze activitatea din interior și să reacționeze în funcție de modul de securitate setat de utilizator.

Funcționalități

Trei moduri de operare:
Inactiv – sistemul ignoră senzorii.
Acasă – monitorizează ușa și geamurile.
Plecat – monitorizează toți senzorii.

Senzori pentru:
Mișcare în fiecare cameră.
Deschidere geam în fiecare cameră.
Deschidere ușă principală.
Cod PIN de 4 cifre pentru schimbarea modului.
Întârziere de 15 secunde la activarea modului „Plecat” pentru a permite utilizatorului să părăsească locuința.
Sistem de alarmă sonoră în cazul detectării unei intruziuni.

Cum funcționează?
La pornire, sistemul este inactiv.
Introduci codul PIN pentru a schimba modul.
Dacă alegi modul Acasă, alarma se declanșează doar dacă se deschide un geam sau ușa principală.
Dacă alegi modul Plecat, alarma monitorizează toți senzorii și se declanșează la orice activitate suspectă.
Dacă vrei să dezactivezi sistemul, introduci codul PIN și selectezi modul Inactiv.

Implementare
Dezvoltat folosind Logisim.
Utilizează circuit digital cu:
Numărător de 15 secunde pentru întârziere.
Registru pentru memorarea codului PIN.
Comparator pe 4 biți pentru validarea codului.
Multiplexor pentru afișare pe Seven Segment Display.
Circuit 7447 pentru afișarea numerelor hexadecimale.

Posibile îmbunătățiri
Utilizarea unei memorii RAM pentru stocarea codului PIN în locul registrelor.
Adăugarea unei conexiuni wireless pentru control de la distanță.
Integrarea unui sistem de notificare pe telefon.
