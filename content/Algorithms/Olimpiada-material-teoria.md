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

1. **Algorytmy sortujące**
   - **Bubble Sort**: Prosty algorytm sortowania polegający na wielokrotnym przechodzeniu przez listę i zamianie miejscami sąsiednich elementów, jeśli są w złej kolejności.
   - **Quick Sort**: Algorytm sortowania typu "dziel i zwyciężaj", wybierający element zwany pivotem i dzielący listę na dwie części, sortując je rekurencyjnie.
   - **Insertion Sort**: Sortuje listę poprzez iteracyjne wstawianie każdego elementu na odpowiednie miejsce w już posortowanej części listy.
   - **Selection Sort**: Algorytm sortowania polegający na wielokrotnym wybieraniu najmniejszego elementu z nieposortowanej części listy i przenoszeniu go na początek.
   - **Merge Sort**: Sortowanie polegające na dzieleniu listy na mniejsze podlisty, sortowaniu ich i scalaniu w jedną posortowaną listę.
   - **Heap Sort**: Wykorzystuje strukturę kopca do efektywnego sortowania poprzez wielokrotne usuwanie największego elementu i odbudowywanie kopca.

2. **Algorytmy grafowe**
   - **Dijkstra**: Służy do znajdowania najkrótszych ścieżek w grafie z dodatnimi wagami krawędzi.
   - **Bellman-Ford**: Algorytm do znajdowania najkrótszych ścieżek, który obsługuje grafy z ujemnymi wagami krawędzi.
   - **Kruskal i Prim**: Algorytmy służące do znajdowania minimalnego drzewa rozpinającego w grafie.
   - **Floyd-Warshall**: Algorytm obliczający najkrótsze ścieżki pomiędzy wszystkimi parami wierzchołków w grafie.

3. **Struktury danych**
   - **Stos**: Struktura danych działająca na zasadzie LIFO (Last In, First Out), używana m.in. w implementacji rekurencji.
   - **Kolejka**: Struktura danych działająca na zasadzie FIFO (First In, First Out), stosowana w algorytmach takich jak BFS.
   - **Drzewo binarne**: Struktura danych składająca się z węzłów, gdzie każdy węzeł ma co najwyżej dwóch potomków, używana m.in. w wyszukiwaniach i sortowaniu.
   - **Tablica haszująca**: Struktura danych umożliwiająca szybkie wyszukiwanie, dodawanie i usuwanie elementów poprzez funkcję haszującą.
   - **Kopiec binarny**: Specjalne drzewo binarne, które spełnia warunek kopca, używane w implementacjach kolejek priorytetowych.

4. **Dynamiczne programowanie**
   - Technika rozwiązywania problemów poprzez dzielenie ich na mniejsze podproblemy i przechowywanie wyników tych podproblemów, aby uniknąć ich wielokrotnego rozwiązywania.
   - Przykłady zastosowań: problem plecakowy, problem najdłuższej wspólnej podsekwencji, obliczanie liczb Fibonacciego.

5. **Rekursja**
   - Technika programowania, w której funkcja wywołuje sama siebie w celu rozwiązania mniejszej instancji tego samego problemu.
   - Przykłady: obliczanie silni (n!), ciągu Fibonacciego, przeszukiwanie drzew i grafów.

6. **Algorytmy zachłanne**
   - Podejście polegające na podejmowaniu lokalnie optymalnych wyborów w nadziei na globalnie optymalne rozwiązanie.
   - Przykłady: algorytmy znajdowania minimalnego drzewa rozpinającego (Kruskal, Prim), algorytm Dijkstry do znajdowania najkrótszej ścieżki.

7. **Złożoność obliczeniowa**
   - Analiza efektywności algorytmów pod względem zużycia zasobów, takich jak czas i pamięć.
   - Notacja Big-O: O(n), O(n log n), O(n²) – opisuje, jak czas działania algorytmu rośnie wraz ze wzrostem wielkości danych wejściowych.

8. **Optymalizacja kodu**
   - Proces modyfikacji kodu w celu poprawy jego wydajności, czytelności lub zużycia pamięci, bez zmiany jego funkcjonalności.
   - Techniki: refaktoryzacja, eliminacja martwego kodu, inlining funkcji.

9. **Wzorce projektowe**
   - Sprawdzone rozwiązania dla typowych problemów projektowych w oprogramowaniu.
   - Przykłady: Singleton (zapewnienie istnienia jednej instancji klasy), Factory 