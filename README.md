Ovaj projekat sadrži API testove za autentifikaciju korisnika. Testovi su napravljeni koristeći Postman, a uključuju kreiranje korisničkog naloga, dobijanje autentifikacionog tokena, i validaciju korisničkih podataka putem GET i POST zahteva.

Koraci u testiranju:
POST /api/register - Kreira korisnički nalog i dobija autentifikacioni token.
GET /api/users/{id} - Proverava podatke o korisniku koristeći dobijeni token.


Uključeni testovi:
Provera uspešne registracije korisnika.
Validacija da je korisnik registrovan i token generisan.
Provera tačnosti korisničkih podataka (ime, prezime) nakon autentifikacije.


Upotreba
Importujte kolekciju u Postman.
Pokrenite testove i pratite rezultate u "Test Results" tabu.


Autor
Nemanja Nikitovic
