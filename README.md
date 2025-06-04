System Parkingowy – Projekt Java
📋 Opis
Projekt przedstawia obiektowy system parkingowy napisany w języku Java, który umożliwia:

rejestrację wjazdów i wyjazdów pojazdów,

kontrolę dostępnych miejsc,

przesuwanie czasu symulacji,

generowanie dziennego raportu,

przegląd historii parkowania.

W projekcie zaimplementowano trzy typy pojazdów:

Samochód osobowy,

Ciężarówka,

Motocykl.

System bazuje na koncepcjach programowania obiektowego takich jak dziedziczenie, polimorfizm i enkapsulacja.

🧩 Struktura klas
Pojazd (abstrakcyjna) – klasa bazowa z informacjami o pojeździe i metodami do obliczania opłat.

Samochod, Ciezarowka, Motocykl – klasy dziedziczące, implementujące zachowanie specyficzne dla typu pojazdu.

RejestrParkowania – klasa przechowująca informacje o czasie wjazdu/wyjazdu oraz opłacie.

SystemParkingowy – główna klasa zarządzająca systemem i logiką aplikacji.

