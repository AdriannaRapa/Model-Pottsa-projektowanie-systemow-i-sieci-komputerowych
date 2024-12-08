# 🧑‍💻 Model Pottsa
Projekt realizowany w ramach przedmiotu Projektowanie systemów i sieci komputerowych na kierunku Inżynieria i Analiza Danych. Celem projektu jest implementacja Modelu Pottsa w języku Python, który pozwala na symulację układów spinów na siatkach z uwzględnieniem różnych parametrów fizycznych.

## 📋 Opis projektu
Model Pottsa jest rozszerzeniem modelu Isinga i służy do opisu układów spinów w fizyce statystycznej. Projekt implementuje ten model w języku Python, spełniając następujące wymagania:
* Generowanie siatki spinów o stałym stanie początkowym 🧩:
   * Każda symulacja zaczyna się od zdefiniowanego stanu początkowego.
* Struktura siatki za pomocą tablicy sąsiedztwa 🌐:
   * Definiuje sąsiedztwo dla każdego spinu w siatce.
* Zmiany niezależne od prawdopodobieństwa 🔄:
   * Funkcja wprowadzająca zmiany w spinach nie zależy od prawdopodobieństwa.
* Dodanie wartości zewnętrznej ⚡:
   * Zbadanie wpływu zewnętrznych parametrów na symulację.
* Obliczanie wartości Hamiltonianu 💡:
   * W każdym kroku symulacji obliczana jest wartość Hamiltonianu, który determinuje energię układu.
* Zbadanie wpływu wartości Hamiltonianu na symulację 📊:
   * Analiza, jak zmiana energii układu wpływa na zachowanie spinów.
* Prezentacja wykresu liczebności stanów 📈:
   * Wizualizacja wyników symulacji, przedstawiająca zmiany stanów w każdym kroku.

## 🛠️ Technologie
* Język programowania: Python
* Biblioteki: NumPy, Matplotlib
