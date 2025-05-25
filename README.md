🧪 Grupa B — Kolokvijum: Sistem za upravljanje događajima

Baza: eventmanager
Tabele: users, events, attendees
Funkcionalnosti:

    index.php

        Forma za login

        Link: Registruj se

    register.php

        Polja: username, password, email, rola (admin/user, radio), telefon (nije obavezno), checkbox: prihvati pravila

        Validacije: kao kod Grupe A

    events.php

        Prikaz svih događaja

        CRUD samo za ADMIN-a

        User može: Prijavi se, Pogledaj detalje

        Pretraga po lokaciji i datumu

    insert_event.php

        Forma: Naziv, Opis, Lokacija, Datum, Privatan događaj (checkbox)

    edit_event.php

    report_event.php

        Admin klikom generiše CSV sa prijavljenima po događaju

    logout.php

    Sesije

🧪 Grupa C — Kolokvijum: Aplikacija za upravljanje bibliotekama

Baza: biblioteka
Tabele: users, books, borrowings
Funkcionalnosti:

    index.php

        Login forma + dugme za registraciju

    register.php

        username, password, email, rola (radio: bibliotekar/čitalac), checkbox: prihvati pravila

    books.php

        Prikaz svih knjiga

        Pretraga po naslovu i autoru

        Dropdown: filtriranje po žanru

        CRUD:

            Bibliotekar: Dodaj, Izmijeni, Obriši

            Čitalac: Zaduži knjigu

    insert_book.php / edit_book.php

        Polja: naslov, autor, žanr, dostupnost (checkbox)

    borrow.php

        Čitalac može zadužiti knjigu ako je dostupna

    logout.php

    Sesije

🧪 Grupa D — Kolokvijum: Sistem za upravljanje zaposlenima

Baza: firma
Tabele: users, employees, departments
Funkcionalnosti:

    index.php

        Login forma, link za registraciju

    register.php

        ime, prezime, username, password, rola (admin/HR/radnik - radio), email, checkbox: uslovi

    employees.php

        Prikaz zaposlenih

        Pretraga po imenu i odjeljenju (dropdown)

        CRUD:

            Admin i HR mogu sve

            Radnik može samo pregledati sebe

    insert_employee.php / edit_employee.php

        Forma: ime, prezime, pozicija, odjeljenje (dropdown iz tabele departments), checkbox: aktivan

    logout.php

    Sesije

Ako želiš, mogu ti odmah generisati:

    SQL skripte

    Strukturu foldera za svaki kolokvijum

    Primjer frontenda (HTML/CSS)

    Backend kod (PHP + MySQL)

Samo mi reci s kojom grupom želiš da počnemo.
