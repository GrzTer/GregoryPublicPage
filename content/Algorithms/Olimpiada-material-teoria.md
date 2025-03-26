# Olimpiada Programistyczna Finał Etap-Teoria (20zadań/20min)
### 1. **Algorytmy sortujące**
   - **Bubble Sort**
   - **Quick Sort**
     - Złożoność czasowa w najlepszym, średnim i najgorszym przypadku
     - Optymalizacja algorytmu
   - **Insertion Sort**
   - **Selection Sort**
   - **Merge Sort**
     - Złożoność i zastosowanie algorytmu "dziel i zwyciężaj"
   - **Heap Sort**
     - Zastosowanie kopca do implementacji algorytmu

### 2. **Algorytmy grafowe**
   - **Dijkstra**: znajdowanie najkrótszej ścieżki w grafie z dodatnimi wagami
   - **Bellman-Ford**: znajdowanie najkrótszej ścieżki z uwzględnieniem ujemnych wag
   - **Kruskal** i **Prim**: algorytmy do znajdowania minimalnego drzewa rozpinającego
   - **Floyd-Warshall**: algorytm do obliczania najkrótszych ścieżek pomiędzy wszystkimi parami w grafie

### 3. **Struktury danych**
   - **Stos**: Przechowywanie danych w kolejności LIFO, zastosowanie w algorytmach rekurencyjnych
   - **Kolejka**: Kolejność FIFO, użycie w algorytmach BFS (przeszukiwanie wszerz)
   - **Drzewo binarne**: Zastosowanie w wyszukiwaniach i sortowaniu (np. BST – Binary Search Tree)
   - **Tablica haszująca**: Wyszukiwanie, dodawanie i usuwanie elementów w czasie średnim O(1)
   - **Kopiec binarny**: Użycie w implementacjach kolejek priorytetowych

### 4. **Dynamiczne programowanie**
   - Technika rozwiązywania problemów, które mogą być rozbite na mniejsze podproblemy.
   - Przykłady problemów: problem plecakowy, problem najdłuższej wspólnej podsekwencji, problem sumy podzbiorów.

### 5. **Rekursja**
   - Zrozumienie zasad wywołań rekurencyjnych i podstawowych algorytmów rekurencyjnych
   - Sposób działania, przykłady (np. obliczanie silni, fibonacciego)

### 6. **Algorytmy zachłanne**
   - **Algorytm Kruskala i Prim'a**: do znajdowania minimalnego drzewa rozpinającego
   - **Algorytm Dijkstry**: znajdowanie najkrótszej ścieżki w grafie
   - Kompresja danych: **Algorytm Huffmana**

### 7. **Złożoność obliczeniowa**
   - **Big-O Notation**: Jak analizować złożoność czasową algorytmów (O(n), O(n log n), O(n²))
   - Zrozumienie, jak złożoność algorytmu wpływa na czas jego działania w zależności od wielkości danych wejściowych.

### 8. **Optymalizacja kodu**
   - **Refaktoryzacja kodu**: Poprawa jakości kodu bez zmiany jego zewnętrznego zachowania
   - **Dead Code Elimination**: Usuwanie nieużywanego kodu
   - **Inlining**: Optymalizacja polegająca na rozwijaniu wywołań funkcji bezpośrednio w miejscu wywołania

### 9. **Wzorce projektowe**
   - Przykłady popularnych wzorców projektowych (np. Singleton, Factory, Observer)

### 10. **Zarządzanie pamięcią**
   - **Garbage Collection**: Automatyczne zarządzanie pamięcią w nowoczesnych językach programowania
   - **Manual Memory Management**: Zarządzanie pamięcią w językach takich jak C, C++

### 11. **Analiza danych**
   - Umiejętność analizy i przetwarzania danych w różnych formach (tablice, listy, grafy)
   - **Algorytmy wyszukiwania** (np. binary search, wyszukiwanie w grafach)

---

Zalecane materiały do nauki:
1. **Książki**:
   - "Introduction to Algorithms" (Cormen, Leiserson, Rivest, Stein)
   - "Algorithm Design Manual" (Skiena)
2. **Online Resources**:
   - Strony internetowe z zadaniami i ćwiczeniami, takie jak:
     - LeetCode
     - HackerRank
     - Codeforces
     - GeeksforGeeks
3. **Ćwiczenia praktyczne**:
   - Implementowanie algorytmów z wybranych tematów
   - Rozwiązywanie zadań algorytmicznych w czasie rzeczywistym

---

1. **Algorytmy sortujące**
   - **Bubble Sort**: Prosty algorytm sortowania polegający na wielokrotnym przechodzeniu przez listę i zamianie miejscami sąsiednich elementów, jeśli są w złej kolejności.
   - **Quick Sort**: Algorytm sortowania typu "dziel i zwyciężaj", wybierający element zwany pivotem i dzielący listę na dwie części, sortując je rekurencyjnie.
   - **Insertion Sort**: Sortuje listę poprzez iteracyjne wstawianie każdego elementu na odpowiednie miejsce w już posortowanej części listy.
   - **Selection Sort**: Algorytm sortowania polegający na wielokrotnym wybieraniu najmniejszego elementu z nieposortowanej części listy i przenoszeniu go na początek.
   - **Merge Sort**: Sortowanie polegające na dzieleniu listy na mniejsze podlisty, sortowaniu ich i scalaniu w jedną posortowaną listę.
   - **Heap Sort**: Wykorzystuje strukturę kopca do efektywnego sortowania poprzez wielokrotne usuwanie największego elementu i odbudowywanie kopca.

1. **Algorytmy grafowe**
   - **Dijkstra**: Służy do znajdowania najkrótszych ścieżek w grafie z dodatnimi wagami krawędzi.
   - **Bellman-Ford**: Algorytm do znajdowania najkrótszych ścieżek, który obsługuje grafy z ujemnymi wagami krawędzi.
   - **Kruskal i Prim**: Algorytmy służące do znajdowania minimalnego drzewa rozpinającego w grafie.
   - **Floyd-Warshall**: Algorytm obliczający najkrótsze ścieżki pomiędzy wszystkimi parami wierzchołków w grafie.

1. **Struktury danych**
   - **Stos**: Struktura danych działająca na zasadzie LIFO (Last In, First Out), używana m.in. w implementacji rekurencji.
   - **Kolejka**: Struktura danych działająca na zasadzie FIFO (First In, First Out), stosowana w algorytmach takich jak BFS.
   - **Drzewo binarne**: Struktura danych składająca się z węzłów, gdzie każdy węzeł ma co najwyżej dwóch potomków, używana m.in. w wyszukiwaniach i sortowaniu.
   - **Tablica haszująca**: Struktura danych umożliwiająca szybkie wyszukiwanie, dodawanie i usuwanie elementów poprzez funkcję haszującą.
   - **Kopiec binarny**: Specjalne drzewo binarne, które spełnia warunek kopca, używane w implementacjach kolejek priorytetowych.

1. **Dynamiczne programowanie**
   - Technika rozwiązywania problemów poprzez dzielenie ich na mniejsze podproblemy i przechowywanie wyników tych podproblemów, aby uniknąć ich wielokrotnego rozwiązywania.
   - Przykłady zastosowań: problem plecakowy, problem najdłuższej wspólnej podsekwencji, obliczanie liczb Fibonacciego.

1. **Rekursja**
   - Technika programowania, w której funkcja wywołuje sama siebie w celu rozwiązania mniejszej instancji tego samego problemu.
   - Przykłady: obliczanie silni (n!), ciągu Fibonacciego, przeszukiwanie drzew i grafów.

1. **Algorytmy zachłanne**
   - Podejście polegające na podejmowaniu lokalnie optymalnych wyborów w nadziei na globalnie optymalne rozwiązanie.
   - Przykłady: algorytmy znajdowania minimalnego drzewa rozpinającego (Kruskal, Prim), algorytm Dijkstry do znajdowania najkrótszej ścieżki.

1. **Złożoność obliczeniowa**
   - Analiza efektywności algorytmów pod względem zużycia zasobów, takich jak czas i pamięć.
   - Notacja Big-O: O(n), O(n log n), O(n²) – opisuje, jak czas działania algorytmu rośnie wraz ze wzrostem wielkości danych wejściowych.

1. **Optymalizacja kodu**
   - Proces modyfikacji kodu w celu poprawy jego wydajności, czytelności lub zużycia pamięci, bez zmiany jego funkcjonalności.
   - Techniki: refaktoryzacja, eliminacja martwego kodu, inlining funkcji.

1. **Wzorce projektowe**
   - Sprawdzone rozwiązania dla typowych problemów projektowych w oprogramowaniu.
   - Przykłady: Singleton (zapewnienie istnienia jednej instancji klasy), Factory 

---

### 1. **Algorytmy sortujące**

- **Quick Sort**: Zrozumienie złożoności czasowej w najlepszym, średnim i najgorszym przypadku oraz optymalizacji.
- **Merge Sort**: Nauka zasadności podejścia "dziel i zwyciężaj", złożoności czasowej oraz przypadków użycia.
- **Heap Sort**: Skupienie na wykorzystaniu kopców w algorytmach sortujących oraz ich zastosowanie w kolejkach priorytetowych.

### 2. **Algorytmy grafowe**

- **Algorytm Dijkstry**: Zastosowanie algorytmu do znajdowania najkrótszej ścieżki w grafach z dodatnimi wagami krawędzi.
- **Bellman-Ford**: Zrozumienie, jak ten algorytm radzi sobie z grafami zawierającymi ujemne wagi krawędzi.
- **Algorytmy Kruskala i Prima**: Wykorzystywane do znajdowania minimalnego drzewa rozpinającego w grafie. Należy poznać oba algorytmy i przypadki ich zastosowań.

### 3. **Struktury danych**

- **Stos**: Wykorzystywany do operacji LIFO (Last In, First Out), rekurencji oraz backtrackingu.
- **Kolejka**: Działa na zasadzie FIFO (First In, First Out), używana w algorytmach takich jak BFS (przeszukiwanie wszerz).
- **Drzewo binarne**: Struktura danych używana do efektywnego wyszukiwania, wstawiania i usuwania elementów (np. BST – Binary Search Tree).
- **Tablica haszująca**: Umożliwia wyszukiwanie, dodawanie i usuwanie elementów w czasie średnim O(1).
- **Kopiec binarny**: Struktura wykorzystywana w implementacjach kolejek priorytetowych.

### 4. **Dynamiczne programowanie**

- Nauka rozwiązywania problemów, które mogą być rozbite na mniejsze podproblemy, które są rozwiązywane i przechowywane dla ponownego użycia.
- Przykłady problemów: problem plecakowy, najdłuższa wspólna podsekwencja, obliczanie liczb Fibonacciego.

### 5. **Rekursja**

- Zrozumienie, jak działa rekursja jest kluczowe do rozwiązywania problemów rekurencyjnych, takich jak obliczanie silni, ciąg Fibonacciego, czy przeszukiwanie drzew i grafów.

### 6. **Algorytmy zachłanne**

- **Algorytmy Kruskala i Prima**: Służą do znajdowania minimalnego drzewa rozpinającego.
- **Algorytm Dijkstry**: Używany do znajdowania najkrótszej ścieżki w grafie.
- **Kodowanie Huffmana**: Wykorzystywane do efektywnej kompresji danych.

### 7. **Analiza złożoności**

- Opanowanie notacji Big-O i analiza złożoności czasowej oraz pamięciowej algorytmów.
- Zrozumienie, jak złożoność algorytmu wpływa na jego wydajność w zależności od rozmiaru danych wejściowych.

### 8. **Optymalizacja kodu**

- Nauka technik takich jak **Dead Code Elimination** oraz **Inlining**.
- Refaktoryzacja kodu, mająca na celu poprawienie wydajności bez zmiany jego zewnętrznego zachowania.

### 9. **Wzorce projektowe**

- Zapoznanie się z popularnymi wzorcami projektowymi, takimi jak **Singleton**, **Factory**, **Observer**.

### 10. **Zarządzanie pamięcią**

- Zrozumienie **Garbage Collection** oraz **Manual Memory Management**, szczególnie w językach takich jak C/C++.

---

### 1. **Algorytmy Sortowania**

- **Quick Sort**: Algorytm sortowania oparty na metodzie dziel i zwyciężaj. Wybiera element zwany pivotelem i dzieli zbiór na dwie części: mniejszą i większą od pivota, a następnie rekurencyjnie sortuje te podzbiory.
- **Merge Sort**: Algorytm sortowania oparty na podejściu dziel i zwyciężaj. Dzieli zbiór na mniejsze części, sortuje je, a następnie scala w jedną posortowaną całość.
- **Heap Sort**: Algorytm sortowania oparty na strukturze kopca. Tworzy kopiec z danych, a następnie wielokrotnie usuwa największy element, przywracając kopiec po każdej operacji.

### 2. **Algorytmy Grafowe**

- **Algorytm Dijkstry**: Służy do znajdowania najkrótszych ścieżek w grafie o nieujemnych wagach krawędzi.
- **Algorytm Bellmana-Forda**: Potrafi obsługiwać grafy z krawędziami o ujemnych wagach i wykrywać ujemne cykle.
- **Algorytmy Kruskala i Prima**: Służą do znajdowania minimalnego drzewa rozpinającego w grafie. Kruskal dodaje krawędzie o najmniejszej wadze, unikając cykli, podczas gdy Prim zaczyna od jednego wierzchołka i rozrasta drzewo, dodając najtańsze krawędzie.
- **A* (A-star)**: Algorytm wyszukiwania najkrótszej ścieżki, który wykorzystuje funkcję heurystyczną do oceny kosztu dotarcia do celu, łącząc koszt dotychczasowy z oszacowaniem kosztu pozostałej drogi.

### 3. **Struktury Danych**

- **Stos (Stack)**: Struktura danych działająca na zasadzie LIFO (Last In, First Out). Umożliwia dodawanie i usuwanie elementów z jednego końca.
- **Kolejka (Queue)**: Struktura danych działająca na zasadzie FIFO (First In, First Out). Elementy są dodawane na końcu i usuwane z początku.
- **Drzewa Binarne**: Struktura danych, w której każdy węzeł ma co najwyżej dwóch potomków. Umożliwiają efektywne operacje wyszukiwania, wstawiania i usuwania.
- **Tablice Haszujące (Hash Tables)**: Struktura danych umożliwiająca szybkie wyszukiwanie, wstawianie i usuwanie elementów poprzez mapowanie kluczy na indeksy tablicy za pomocą funkcji haszującej.
- **Kopiec (Heap)**: Struktura danych będąca specjalnym przypadkiem drzewa binarnego, spełniająca warunek kopca, gdzie dla każdego węzła wartość jest większa (lub mniejsza) od wartości jego potomków. Używana m.in. w algorytmie sortowania kopcowego oraz w implementacji kolejek priorytetowych.

### 4. **Programowanie Dynamiczne**

- Technika rozwiązywania problemów poprzez dzielenie ich na nakładające się podproblemy i zapisywanie wyników tych podproblemów w celu uniknięcia ich wielokrotnego rozwiązywania.
- Przykładowe problemy:
    - **Problem plecakowy**: Określenie, jakie przedmioty zabrać do plecaka, aby zmaksymalizować wartość przy ograniczonej pojemności.
    - **Najdłuższa wspólna podsekwencja (LCS)**: Znalezienie najdłuższej sekwencji, która pojawia się w tej samej kolejności w obu ciągach.
    - **Obliczanie liczb Fibonacciego**: Generowanie ciągu liczb, gdzie każda liczba jest sumą dwóch poprzednich.

### 5. **Rekurencja**

- Technika programowania, w której funkcja wywołuje sama siebie. Ważna jest znajomość przypadków brzegowych oraz zapewnienie, że każde wywołanie zbliża się do tych przypadków, aby uniknąć nieskończonej rekurencji.
- Przykłady zastosowań:
    - Obliczanie silni liczby.
    - Obliczanie n-tej liczby Fibonacciego.
    - Przeszukiwanie drzew i grafów (np. przeszukiwanie wszerz, przeszukiwanie w głąb).

### 6. **Algorytmy Zachłanne**

- Algorytmy podejmujące lokalnie optymalne decyzje w nadziei na globalnie optymalne rozwiązanie.
- Przykładowe zastosowania:
    - **Huffman Coding**: Algorytm kompresji danych, który przypisuje krótsze kody do bardziej prawdopodobnych symboli.
    - **Problem wydawania reszty**: Dobór monet w taki sposób, aby wydać resztę przy użyciu jak najmniejszej liczby monet.

### 7. **Analiza Złożoności Algorytmów**

- Ocena efektywności algorytmu pod względem czasu wykonania i zużycia pamięci.
- Notacja **Big-O**: Służy do opisywania górnej granicy złożoności algorytmu, skupiają