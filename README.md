# Skijalište — provera uslova za rad staza

Studentski projekat iz predmeta **Razvoj višeslojnog softvera**. Aplikacija služi za unos i pregled skijaških staza i proveru da li vremenski uslovi dozvoljavaju njihov rad.

## Šta projekat sadrži

Projekat je organizovan u sloj podataka, sloj poslovne logike, web servis i ASP.NET MVC korisnički interfejs. Za čuvanje podataka koristi SQL Server, a ograničenja vezana za vremenske uslove čitaju se preko servisa iz spoljne konfiguracije.

Korisnik može da se prijavi, pregleda i unese staze, kao i da izvrši proveru staze. Na osnovu unetih uslova i podešenih ograničenja aplikacija prikazuje odluku da li je staza otvorena ili zatvorena.

## Preuzimanje i pokretanje

Izvorni projekat nalazi se u arhivi `BojanMercaRVS.rar`. Preuzeti i raspakovati arhivu, otvoriti Visual Studio rešenje, podesiti konekciju sa SQL Server bazom i adresu servisa za vremenske uslove, pa pokrenuti servis i MVC aplikaciju.

Projekat je izrađen za **.NET Framework 4.8**. Lokalna podešavanja baze i servisa treba prilagoditi računaru na kojem se pokreće.
