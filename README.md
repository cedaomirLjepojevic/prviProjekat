# prviProjekat


Pozdrav,

Napravljena je ASP.NET MVC Aplikacija korisnjenjem CRUD operacije, za sada, projekat ima samo jednu klasu 'Employee'
Ovo je samo test!

Prvi i osnovni korak, radi povezivanja sa bazom podataka jeste da da se preko NuGet-a, skine paket pod imenom 'Pomelo.EntityFrameworkCore.MySql'
Drugi korak jeste da se u Program.cs fajlu, kada se kreira projekat i kada se dodaju odredjeni paketi,
promeni jedan deo koda da bi se povezalo sa bazom preko localhost/phpmyadmin.

CRUD (Create Read Update Delete) Operacije: 

1. Na linku https://localhost:7132/Employee/Create
mogu da se kreiraju novi zaposleni
samo se vratite na prvi link i videcete zaposlenog koji ste kreirali -> Create

2. Na linku https://localhost:7132/Employee/
sam napravio listu gde se ispisuju svi Zaposleni 'Employees' -> Read

3. U glavnoj listi imate 'Edit' i 'Delete' da se Update-uje odredjen zaposleni koga birate   -> Update

4. Imate i opciju 'Delete' da izbrisete zaposlenog iz liste   -> Delete
