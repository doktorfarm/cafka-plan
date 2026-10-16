# Cafka — plan firmy i prognoza

Interaktywny plan dla dwóch osób uruchamiających markę kawy. Zawiera pięć kroków: współpraca z palarnią i budżet, opłacalność sprzedaży, forma firmy, zadania do startu oraz źródła.

## Jak korzystać

1. Wybierz wariant współpracy z palarnią i wpisz budżet.
2. Wprowadź liczbę zamówień, cenę paczki 250 g i koszt kawy.
3. Sprawdź koszty, wynik oraz podpowiedzi „Co dalej?”.
4. Ustal z księgowym formę firmy, podatki i składki. Wpisane kwoty są przykładowe.
5. Kliknij „Pobierz prognozę PDF”, aby zapisać aktualny scenariusz.

Zapisane ustawienia pozostają w przeglądarce użytkownika. Każda osoba ma własny scenariusz; strona nie synchronizuje danych między osobami. Ten sam scenariusz można przekazać w PDF. Nie publikuj własnych danych finansowych w plikach repozytorium.

## Uruchomienie

Strona jest statyczna, bez instalacji zależności i bez serwera aplikacyjnego. Otwórz `index.html` razem z plikiem `jspdf.umd.min.js` w tym samym folderze.

GitHub Pages: w **Settings → Pages** wybierz **Deploy from a branch**, gałąź **main**, folder **/ (root)**. Plik `.nojekyll` wyłącza przetwarzanie Jekyll.

## Zakres i źródła

Przepisy i źródła sprawdzono 16.10.2026. Linki do MF, ZUS, UOKiK oraz badań 2025–2026 są w aplikacji. Ceny palarni, koszty reklamy i liczby zamówień są edytowalnymi założeniami, a nie danymi rzeczywistymi Cafki ani stawkami urzędowymi.

Model nie zastępuje rozliczenia księgowego. Obejmuje skalę PIT i klasyczny CIT; zdrowotna jest uproszczonym szacunkiem. Wynik nie jest stanem konta. Budżet początkowy nie zwiększa automatycznie zysku.

## Eksport PDF i licencje zależności

PDF powstaje lokalnie w przeglądarce z aktualnych danych. Zawiera polskie znaki, budżet, prognozę miesięczną, założenia i opis ograniczeń.

- jsPDF 4.2.1: licencja MIT, plik `jsPDF-LICENSE.txt`.
- Font Ubuntu używany w PDF: Ubuntu Font Licence, plik `Ubuntu-FONT-LICENSE.txt`.

Strona nie wymaga kluczy API ani danych logowania.
