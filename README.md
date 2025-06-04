# 🚗 System Parkingowy – Projekt Java

## 📋 Opis

Projekt przedstawia **obiektowy system parkingowy** napisany w języku **Java**, który umożliwia:

- rejestrację wjazdów i wyjazdów pojazdów,
- kontrolę dostępnych miejsc,
- przesuwanie czasu symulacji,
- generowanie dziennego raportu,
- przegląd historii parkowania.

W projekcie zaimplementowano trzy typy pojazdów:

- **Samochód osobowy**
- **Ciężarówka**
- **Motocykl**

System bazuje na koncepcjach **programowania obiektowego** takich jak:
- dziedziczenie,
- polimorfizm,
- enkapsulacja.

---

## 🧩 Struktura klas

- **`Pojazd`** *(abstrakcyjna)* – klasa bazowa zawierająca dane pojazdu i metody do obliczania opłat.
- **`Samochod`**, **`Ciezarowka`**, **`Motocykl`** – klasy dziedziczące po `Pojazd`, zawierające specyficzne cechy i zasady naliczania opłat.
- **`RejestrParkowania`** – klasa przechowująca dane o czasie wjazdu, wyjazdu i naliczonej opłacie dla danego pojazdu.
- **`SystemParkingowy`** – główna klasa aplikacji odpowiedzialna za logikę, obsługę danych i komunikację z użytkownikiem przez konsolę.

---

## ✅ Przykładowe funkcje programu

- Obsługa wielu typów pojazdów i ich parametrów
- Walidacja danych wejściowych i obsługa wyjątków
- Dynamiczne przesuwanie czasu w symulacji
- Raportowanie stanu parkingu
- Historia zaparkowanych i wyjechanych pojazdów

---

## 👨‍💻 Autorzy

- **Damian Sadowski** – logika pojazdów, obsługa wjazdu/wyjazdu, wyjątki
- **Paulina Chojnowska** – raporty, historia pojazdów, dostępność, struktura danych
