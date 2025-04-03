Zgodnie z regulaminem Olimpiady Innowacji Technicznych w Telekomunikacji i Informatyce, Etap I zawodów III stopnia (blok programistyczny) składa się z testu obejmującego 20 pytań o zwiększonym stopniu trudności, w tym zadania dotyczące tworzenia i analizy rozwiązań teleinformatycznych, modyfikacji kodu informatycznego, stosowania algorytmów programistycznych, analizy danych i struktur oprogramowania.

Na podstawie tych informacji, sporządziłem przykładowe pytania, które mogą pojawić się na tym etapie. Oto 20 przykładowych zadań:

1. **Zadanie 1:** Co to jest algorytm sortowania bąbelkowego i jak działa? Podaj przykład implementacji w Pythonie. 
    - Prosty algorytm sortowania, polega na zasadzie wielokrotnego przechodzenia przez listę elementów, porównania sąsiednich par i zamiany ich miejscami, jeżeli są nieprawidłowo ustawione.
2. **Zadanie 2:** Co to jest algorytm wyszukiwania binarnego? Wyjaśnij, jak działa i podaj jego czas złożoności.
    
3. **Zadanie 3:** Napisz funkcję w Pythonie, która oblicza silnię liczby n.
    
4. **Zadanie 4:** Co to jest drzewo binarne i jak wygląda struktura danych drzewa w C++?
    
5. **Zadanie 5:** W jaki sposób zaimplementowałbyś algorytm Dijkstry w języku Python? Podaj przykład użycia.
    
6. **Zadanie 6:** Wyjaśnij różnicę między typem danych `list` a `tuple` w Pythonie.
    
7. **Zadanie 7:** Zaimplementuj algorytm do obliczania najmniejszego wspólnego dzielnika dwóch liczb.
    
8. **Zadanie 8:** Jakie są główne różnice między językiem C++ a Pythonem? Podaj przykłady użycia zmiennych i funkcji w obu językach.
    
9. **Zadanie 9:** Napisz funkcję w języku Python, która odwraca ciąg znaków.
    
10. **Zadanie 10:** Co to jest hash map w C++? Podaj przykład użycia.
    
11. **Zadanie 11:** Jakie są zalety i wady stosowania struktur danych typu `linked list` w porównaniu do `array`?
    
12. **Zadanie 12:** Napisz funkcję w Pythonie, która liczy, ile razy dany znak występuje w ciągu tekstowym.
    
13. **Zadanie 13:** Jakie są główne różnice między algorytmem BFS (Breadth-First Search) a DFS (Depth-First Search)? Podaj przykład użycia obu algorytmów.
    
14. **Zadanie 14:** Co to jest rekurencja? Podaj przykład funkcji rekurencyjnej w języku Python.
    
15. **Zadanie 15:** Wyjaśnij różnicę między językiem programowania C a C++.
    
16. **Zadanie 16:** Jakie struktury danych można zastosować w problemie znajdowania najkrótszej ścieżki w grafie?
    
17. **Zadanie 17:** Zaimplementuj w Pythonie algorytm do obliczania największego wspólnego dzielnika dwóch liczb przy użyciu algorytmu Euklidesa.
    
18. **Zadanie 18:** Jakie są zalety stosowania algorytmów zachłannych? Podaj przykład zastosowania.
    
19. **Zadanie 19:** Napisz funkcję w Pythonie, która zwraca liczbę słów w podanym tekście.
    
20. **Zadanie 20:** Wyjaśnij, czym jest dynamiczne programowanie i podaj przykład problemu, który można rozwiązać tą metodą.
    

---

Oto zestaw flashcardów, które pomogą Ci przygotować się do Etapu 1 Zawodów III stopnia (blok programistyczny). Każda karta zawiera pytanie z jednej strony i odpowiedź z drugiej strony.

---

**Flashcard 1:**

- **Pytanie:** Co to jest algorytm sortowania bąbelkowego i jak działa?
    
- **Odpowiedź:** Algorytm sortowania bąbelkowego (Bubble Sort) polega na porównywaniu kolejnych elementów w tablicy i ich zamianie miejscami, jeśli są w złej kolejności. Powtarza się to, aż cała tablica zostanie posortowana. Jego złożoność to O(n²).
    

---

**Flashcard 2:**

- **Pytanie:** Co to jest algorytm wyszukiwania binarnego? Wyjaśnij, jak działa i podaj jego czas złożoności.
    
- **Odpowiedź:** Algorytm wyszukiwania binarnego znajduje element w posortowanej tablicy poprzez wielokrotne dzielenie jej na połowy. Złożoność: O(log n).
    

---

**Flashcard 3:**

- **Pytanie:** Napisz funkcję w Pythonie, która oblicza silnię liczby n.
    
- **Odpowiedź:**
    

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```

---

**Flashcard 4:**

- **Pytanie:** Co to jest drzewo binarne i jak wygląda struktura danych drzewa w C++?
    
- **Odpowiedź:** Drzewo binarne to struktura danych, w której każdy węzeł ma maksymalnie dwóch potomków (lewego i prawego). W C++ może wyglądać tak:
    

```cpp
struct Node {
    int data;
    Node* left;
    Node* right;
};
```

---

**Flashcard 5:**

- **Pytanie:** Jak zaimplementowałbyś algorytm Dijkstry w języku Python? Podaj przykład użycia.
    
- **Odpowiedź:**
    

```python
import heapq

def dijkstra(graph, start):
    queue = [(0, start)]
    distances = {start: 0}
    while queue:
        (dist, node) = heapq.heappop(queue)
        for neighbor, weight in graph[node]:
            distance = dist + weight
            if neighbor not in distances or distance < distances[neighbor]:
                distances[neighbor] = distance
                heapq.heappush(queue, (distance, neighbor))
    return distances
```

---

**Flashcard 6:**

- **Pytanie:** Wyjaśnij różnicę między typem danych `list` a `tuple` w Pythonie.
    
- **Odpowiedź:** `list` to typ danych zmienny (można zmieniać jego elementy), a `tuple` to typ danych niemutowalny (po utworzeniu nie można zmieniać jego zawartości).
    

---

**Flashcard 7:**

- **Pytanie:** Zaimplementuj algorytm do obliczania najmniejszego wspólnego dzielnika dwóch liczb.
    
- **Odpowiedź:**
    

```python
def gcd(a, b):
    while b:
        a, b = b, a % b
    return a
```

---

**Flashcard 8:**

- **Pytanie:** Jakie są główne różnice między językiem C++ a Pythonem? Podaj przykłady użycia zmiennych i funkcji w obu językach.
    
- **Odpowiedź:** C++ jest językiem statycznie typowanym, a Python dynamicznie typowanym. W C++ zmienne muszą mieć określony typ, w Pythonie typ jest ustalany w trakcie działania programu.
    

```cpp
// C++
int a = 5;
```

```python
# Python
a = 5
```

---

**Flashcard 9:**

- **Pytanie:** Napisz funkcję w języku Python, która odwraca ciąg znaków.
    
- **Odpowiedź:**
    

```python
def reverse_string(s):
    return s[::-1]
```

---

**Flashcard 10:**

- **Pytanie:** Co to jest hash map w C++? Podaj przykład użycia.
    
- **Odpowiedź:** Hash map (lub unordered_map w C++) to struktura danych, która przechowuje pary klucz-wartość.
    

```cpp
#include <unordered_map>
unordered_map<int, string> map;
map[1] = "one";
map[2] = "two";
```

---

**Flashcard 11:**

- **Pytanie:** Jakie są zalety i wady stosowania struktur danych typu `linked list` w porównaniu do `array`?
    
- **Odpowiedź:** Linked list umożliwia dynamiczne zarządzanie pamięcią i łatwe dodawanie/usuwanie elementów, ale ma wyższy koszt dostępu do elementów. Array pozwala na szybki dostęp do elementów, ale jego rozmiar jest statyczny.
    

---

**Flashcard 12:**

- **Pytanie:** Napisz funkcję w Pythonie, która liczy, ile razy dany znak występuje w ciągu tekstowym.
    
- **Odpowiedź:**
    

```python
def count_char(s, char):
    return s.count(char)
```

---

**Flashcard 13:**

- **Pytanie:** Jakie są główne różnice między algorytmem BFS (Breadth-First Search) a DFS (Depth-First Search)? Podaj przykład użycia obu algorytmów.
    
- **Odpowiedź:** BFS przeszukuje w poziomie, zaczynając od węzła początkowego, natomiast DFS przeszukuje w głąb.  
    Przykład BFS:
    

```python
from collections import deque
def bfs(graph, start):
    queue = deque([start])
    visited = set()
    while queue:
        node = queue.popleft()
        if node not in visited:
            visited.add(node)
            for neighbor in graph[node]:
                queue.append(neighbor)
```

Przykład DFS:

```python
def dfs(graph, start, visited=None):
    if visited is None:
        visited = set()
    visited.add(start)
    for neighbor in graph[start]:
        if neighbor not in visited:
            dfs(graph, neighbor, visited)
```

---

**Flashcard 14:**

- **Pytanie:** Co to jest rekurencja? Podaj przykład funkcji rekurencyjnej w języku Python.
    
- **Odpowiedź:** Rekurencja to technika, w której funkcja wywołuje samą siebie. Przykład:
    

```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)
```

---

**Flashcard 15:**

- **Pytanie:** Wyjaśnij różnicę między językiem programowania C a C++.
    
- **Odpowiedź:** C jest językiem proceduralnym, a C++ jest językiem obiektowym, który wspiera programowanie zorientowane na obiekty (OOP).
    

---

**Flashcard 16:**

- **Pytanie:** Jakie struktury danych można zastosować w problemie znajdowania najkrótszej ścieżki w grafie?
    
- **Odpowiedź:** W problemie najkrótszej ścieżki używa się takich struktur danych jak: macierz sąsiedztwa, lista sąsiedztwa, kopiec (heap) oraz kolejki priorytetowe.
    

---

**Flashcard 17:**

- **Pytanie:** Zaimplementuj w Pythonie algorytm do obliczania największego wspólnego dzielnika dwóch liczb przy użyciu algorytmu Euklidesa.
    
- **Odpowiedź:**
    

```python
def gcd(a, b):
    while b:
        a, b = b, a % b
    return a
```

---

**Flashcard 18:**

- **Pytanie:** Jakie są zalety stosowania algorytmów zachłannych? Podaj przykład zastosowania.
    
- **Odpowiedź:** Algorytmy zachłanne są proste do zaimplementowania i często dają rozwiązanie w krótkim czasie, ale nie zawsze gwarantują optymalne rozwiązanie. Przykład: algorytm wyboru najtańszego połączenia w problemie komiwojażera.
    

---

**Flashcard 19:**

- **Pytanie:** Napisz funkcję w Pythonie, która zwraca liczbę słów w podanym tekście.
    
- **Odpowiedź:**
    

```python
def count_words(text):
    return len(text.split())
```

---

**Flashcard 20:**

- **Pytanie:** Wyjaśnij, czym jest dynamiczne programowanie i podaj przykład problemu, który można rozwiązać tą metodą.
    
- **Odpowiedź:** Dynamiczne programowanie to technika rozwiązywania problemów poprzez dzielenie ich na mniejsze podproblemy, które są rozwiązywane raz i zapisywane. Przykład: problem plecakowy.
    

---

>Sprawdź regulamin i sporządź bazę przykładowych pytań na jego podstawie, ma ona przygotować mnie na Zawody III stopnia z bloku Programistycznego
>
Przygotuj zadania przygotowujące mnie na Zawody III stopnia:
>- Sporządź 20 zadań przykładowych do Etapu I Zawodów III stopnia
  >  
>- Podaj odpowiedzi do tych 20 zadań
>- Sporządź flashcard 'y