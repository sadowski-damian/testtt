
Interfejs obsługiwany jest przez konsolę – użytkownik wprowadza dane przez `Scanner`.

---

## 💰 System opłat

Opłaty są obliczane na podstawie dnia tygodnia oraz typu pojazdu:

- **Dni robocze:** 2.30 zł/godzina,
- **Weekend:** 4.30 zł/godzina,
- **Samochody z więcej niż 8 miejscami:** dopłata 5 zł,
- **Ciężarówki z dużą wysokością i niską ładownością:** dopłata 100 zł.

---

## ⚠️ Obsługa wyjątków

System obsługuje i wyświetla błędy w przypadkach:
- braku miejsc na parkingu,
- błędnych lub pustych danych wejściowych,
- próby dodania pojazdu o zduplikowanym numerze rejestracyjnym,
- próby wyjazdu nieistniejącego pojazdu.

---

## 🧪 Przykładowe testy manualne

1. Dodaj samochód z poprawnymi danymi.
2. Dodaj motocykl z niepoprawnym typem (`skuter`) – sprawdź komunikat o błędzie.
3. Przesuń czas o kilka godzin i zarejestruj wyjazd – sprawdź naliczoną opłatę.
4. Wygeneruj raport dzienny i sprawdź listę zaparkowanych pojazdów.

---

## 👥 Autorzy

- Damian Sadowski – logika pojazdów i obsługa wyjątków
- Paulina Chojnowska – raporty, historia, struktura systemu
