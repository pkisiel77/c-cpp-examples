**Temat: Wprowadzenie do C++ i struktura programu**

Język C++ to język ogólnego przeznaczenia, który pozwala na pisanie bardzo wydajnego kodu. Każdy program w C++ ma określoną strukturę. Poniżej znajduje się najprostszy przykład:

```cpp
#include <iostream> // Biblioteka do obsługi wejścia/wyjścia

int main() { // Główna funkcja programu
    std::cout << "Witaj w nauce C++!" << std::endl; // Wypisanie tekstu
    return 0; // Zakończenie programu
}

```

**Kluczowe elementy:**

1. `#include <iostream>` – Dołączamy nagłówek, który pozwala nam używać `std::cout` (wypisywanie na ekran).
2. `int main()` – To "serce" programu. Wykonywanie kodu zawsze zaczyna się od tej funkcji.
3. `std::cout` – Obiekt służący do wyświetlania danych.
4. `;` (średnik) – Każda instrukcja w C++ musi kończyć się średnikiem.

**Zadania:** 

- Spróbuj zmienić tekst wewnątrz cudzysłowu na swoje imię i uruchom program.
