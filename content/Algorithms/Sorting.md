### 1. **Sortowanie bąbelkowe (Bubble Sort)**

- **Opis**: Prosty algorytm polegający na wielokrotnym przechodzeniu przez listę i zamienianiu miejscami sąsiednich elementów, jeśli są w złej kolejności.
- **Złożoność czasowa**:
    - Najlepszy przypadek: O(n)
    - Średni przypadek: O(n²)
    - Najgorszy przypadek: O(n²)
- **Złożoność pamięciowa**: O(1)
- **Stabilność**: Tak
- **Zastosowanie**: Rzadko stosowane w praktyce ze względu na niską wydajność, głównie w celach edukacyjnych.

### 2. **Sortowanie przez wybieranie (Selection Sort)**

- **Opis**: Algorytm polegający na iteracyjnym wybieraniu najmniejszego (lub największego) elementu z nieposortowanej części listy i przenoszeniu go na początek (lub koniec) listy.
- **Złożoność czasowa**:
    - Najlepszy przypadek: O(n²)
    - Średni przypadek: O(n²)
    - Najgorszy przypadek: O(n²)
- **Złożoność pamięciowa**: O(1)
- **Stabilność**: Nie
- **Zastosowanie**: Niezbyt efektywne dla dużych zbiorów danych; może być użyteczne, gdy liczba zamian musi być minimalna.

### 3. **Sortowanie przez wstawianie (Insertion Sort)**

- **Opis**: Algorytm polegający na budowaniu posortowanej listy poprzez iteracyjne wstawianie kolejnych elementów w odpowiednie miejsce w już posortowanej części listy.
- **Złożoność czasowa**:
    - Najlepszy przypadek: O(n)
    - Średni przypadek: O(n²)
    - Najgorszy przypadek: O(n²)
- **Złożoność pamięciowa**: O(1)
- **Stabilność**: Tak
- **Zastosowanie**: Efektywne dla małych lub częściowo posortowanych zbiorów danych.

### 4. **Sortowanie przez scalanie (Merge Sort)**

- **Opis**: Algorytm oparty na strategii "dziel i zwyciężaj", polegający na dzieleniu listy na mniejsze podlisty, sortowaniu ich rekurencyjnie, a następnie scalaniu w jedną posortowaną listę.
- **Złożoność czasowa**:
    - Najlepszy przypadek: O(n log n)
    - Średni przypadek: O(n log n)
    - Najgorszy przypadek: O(n log n)
- **Złożoność pamięciowa**: O(n)
- **Stabilność**: Tak
- **Zastosowanie**: Dobry wybór dla dużych zbiorów danych, zwłaszcza gdy stabilność sortowania jest istotna.

### 5. **Sortowanie szybkie (Quick Sort)**

- **Opis**: Algorytm "dziel i zwyciężaj", który wybiera element (pivot) i dzieli listę na dwie części: mniejsze i większe od pivota, a następnie sortuje te części rekurencyjnie.
- **Złożoność czasowa**:
    - Najlepszy przypadek: O(n log n)
    - Średni przypadek: O(n log n)
    - Najgorszy przypadek: O(n²)
- **Złożoność pamięciowa**: O(log n)
- **Stabilność**: Nie
- **Zastosowanie**: Często stosowany w praktyce ze względu na dobrą wydajność średnią; jednak należy uważać na najgorszy przypadek.

### 6. **Sortowanie kopcowe (Heap Sort)**

- **Opis**: Algorytm oparty na strukturze danych zwanej kopcem (heap), który pozwala na efektywne znajdowanie największego (lub najmniejszego) elementu i jego usuwanie, co umożliwia posortowanie listy.
- **Złożoność czasowa**:
    - Najlepszy przypadek: O(n log n)
    - Średni przypadek: O(n log n)