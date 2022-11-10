# Event-venue-db
În cadrul acestui proiect am realizat baza de date pentru tema Locații destinate unor evenimente tematice. Compania creată deține o locație pentru închiriat care are ca angajați un organizator, un bucătar, un ajutor de bucătar, trei chelneri, un dj și un fotograf. Clienții se vor programa din timp precizând, pe lângă detaliile personale (CNP, nume, prenume, număr de telefon, eventual e-mail, localitatea în care locuiesc) preferințele lor legate de numărul de invitați, data evenimentului și meniu, care va fi la fel pentru toți invitații. Nu se pot programa două evenimente în aceeași zi. Locația poate primi un număr maxim de 500 de invitați, iar numărul minim este de 30. Compania ține evidența atât a clienților și a furnizorilor(cu nume, adresă, e-mail, număr de telefon și tipul de produse livrate) cât și a angajaților ei (numele și prenumele, numărul de telefon, eventual e-mail, data angajării, postul pe care îl ocupă și experiența în domeniu. Sumele de bani pe care compania le primește de la clienți sunt alcătuite din costul închirierii locației și costul meniului ales, în funcție de numărul de invitați . De asemenea, în cazul furnizorilor, se înregistrează plățile lunare fixe care trebuie efectuate, iar în cazul angajaților se înregistrează salariile acestora, care trebuie să nu fie mai mici de 2000. 

Explicaţii legate de câmpuri, atribute
În tabelul PLĂȚI, sumele corespondente Id_pge (sumele primite de la clienți) sunt calculate după formula (pret_pers (MENIURI) + pret_pers_loc (PROGRAMARI) ) * Nr_invitați (PROGRAMĂRI). 

Constrângeri legate de câmpuri 
1.	Numărul de invitați trebuie să fie cel puțin 30 și cel mult 500.
2.	E-mail-urile trebuie să conțină sintagma „@bde”.
Tabelele ANGAJATI și CLIENTI au Email-ul opțional.
3.	Salariul angajaților trebuie sa fie minim 2000.
