### 1. Wyszukiwanie

- **Przeszukiwanie liniowe (Linear Search):**  
    Sprawdza element po elemencie sekwencyjnie, aż znajdzie szukany element lub przeszuka całą strukturę.
    
- **Wyszukiwanie binarne (Binary Search):**  
    Działa na posortowanych strukturach – porównuje element środkowy i decyduje, którą połowę przeszukać, redukując złożoność do O(log n).
    
- **Wyszukiwanie interpolacyjne (Interpolation Search):**  
    Udoskonalona wersja wyszukiwania binarnego, która szacuje pozycję szukanego elementu na podstawie wartości; efektywne przy równomiernym rozkładzie danych.
    
- **Jump Search:**  
    Przeskakuje elementy w stałych odstępach, a po znalezieniu przedziału wykonuje przeszukiwanie liniowe – przydatne przy posortowanych danych.
    

---

### 2. Sortowanie

- **Bubble Sort:**  
    Porównuje i zamienia sąsiednie elementy, „bąbelkując” największe elementy na koniec; prosty, ale mało wydajny (O(n²)).
    
- **Insertion Sort:**  
    Buduje posortowaną część listy, wstawiając kolejne elementy w odpowiednie miejsce; efektywny dla małych lub częściowo posortowanych danych.
    
- **Selection Sort:**  
    W każdej iteracji wybiera najmniejszy (lub największy) element z nieposortowanej części i umieszcza go na początku; działa w czasie O(n²).
    
- **Merge Sort:**  
    Dzieli listę na mniejsze fragmenty, sortuje je rekurencyjnie, a następnie scala w jedną uporządkowaną całość; gwarantowana złożoność O(n log n).
    
- **Quick Sort:**  
    Wybiera pivot, dzieli listę na elementy mniejsze i większe od pivotu, a następnie sortuje te części – średnia złożoność O(n log n), choć najgorszy przypadek O(n²).
    
- **Heap Sort:**  
    Używa struktury kopca (heap) do uporządkowania elementów; buduje kopiec, a następnie wyciąga elementy jeden po drugim – złożoność O(n log n).
    
- **Counting Sort:**  
    Liczy wystąpienia poszczególnych wartości, a następnie odtwarza uporządkowaną listę; bardzo szybki dla ograniczonego zakresu wartości (O(n+k)).
    
- **Radix Sort:**  
    Sortuje liczby, przetwarzając cyfry od najmniej znaczącej do najbardziej znaczącej, często wykorzystując Counting Sort jako podalgorytm.
    

---

### 3. Algorytmy Grafowe

- **DFS (Depth-First Search):**  
    Przeszukiwanie grafu metodą "w głąb", eksplorujące ścieżki aż do końca, a potem cofające się, by zbadać kolejne.
    
- **BFS (Breadth-First Search):**  
    Przeszukuje graf warstwami – najpierw odwiedza wierzchołki bezpośrednio połączone z punktem startowym, potem kolejne.
    
- **Dijkstra's Algorithm:**  
    Znajduje najkrótsze ścieżki od jednego źródła do wszystkich innych w grafie z nieujemnymi wagami krawędzi.
    
- **Bellman-Ford Algorithm:**  
    Podobny do Dijkstry, ale radzi sobie z ujemnymi wagami; wykrywa też cykle o ujemnej sumie wag.
    
- **Floyd-Warshall Algorithm:**  
    Algorytm dynamiczny, który oblicza najkrótsze ścieżki między wszystkimi parami wierzchołków – prosty do implementacji, ale o złożoności O(n³).
    
- **Kruskal's Algorithm:**  
    Buduje minimalne drzewo rozpinające, wybierając krawędzie w kolejności rosnącej wag i unikając cykli za pomocą struktury zbiorów rozłącznych.
    
- **Prim's Algorithm:**  
    Rozpoczyna od jednego wierzchołka i stopniowo rozszerza drzewo rozpinające, zawsze wybierając najtańszą krawędź wychodzącą z już wybranych wierzchołków.
    
- **A* Algorithm:**  
    Heurystyczny algorytm wyszukiwania najkrótszej ścieżki, łączący koszty dotychczasowe z przewidywanym kosztem do celu, co pozwala na szybsze znalezienie optymalnego rozwiązania.
    

---

### 4. Algorytmy Rekurencyjne

- **Tower of Hanoi:**  
    Klasyczny problem przenoszenia dysków między słupami, demonstrujący zasady rekurencji i strategii dziel i zwyciężaj.
    
- **Permutacje:**  
    Generowanie wszystkich możliwych ustawień elementów zbioru przy użyciu rekurencyjnego podejścia – często wykorzystywane do zadań kombinatorycznych.
    
- **Kombinacje/Backtracking:**  
    Technika generowania kombinacji lub rozwiązywania problemów (np. sudoku) poprzez rekurencyjne wypróbowywanie opcji i wycofywanie się, gdy warunki nie są spełnione.
    

---

### 5. Najbardziej Ogólne (Rekurencyjne przykłady)

- **Fibonacci (rekurencyjnie):**  
    Obliczanie n-tego wyrazu ciągu Fibonacciego przez sumowanie dwóch poprzednich wyrazów; prosta, ale nieefektywna wersja rekurencyjna.
    
- **Silnia (Factorial):**  
    Obliczanie n! przez rekurencyjne mnożenie n razy, gdzie n! = n · (n-1)!, z warunkiem zakończenia dla 0! = 1.
    
- **Konwersja int→binarny i odwracanie:**  
    Rekurencyjne dzielenie liczby całkowitej przez 2, zbieranie reszt (bitów) i ewentualne odwracanie uzyskanego ciągu, aby otrzymać reprezentację binarną.
    
- **Konwersja liczb na rzymskie:**  
    Przekształcanie liczby arabskiej na rzymski zapis poprzez dopasowywanie i odejmowanie wartości symboli rzymskich – implementowany iteracyjnie lub rekurencyjnie.
    
- **Algorytm Euklidesa (rekurencyjnie):**  
    Oblicza największy wspólny dzielnik (NWD) dwóch liczb poprzez rekurencyjne dzielenie i przyjmowanie reszty, aż do uzyskania zera.