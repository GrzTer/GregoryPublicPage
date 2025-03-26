Algorytmy grafowe to zestaw procedur i reguł służących do analizy oraz przetwarzania grafów. Grafy są strukturami danych składającymi się z wierzchołków (ang. vertices) i krawędzi (ang. edges), co pozwala na modelowanie różnorodnych zależności i połączeń w wielu dziedzinach, takich jak matematyka, informatyka czy analiza sieci. 

**Przykładowe algorytmy grafowe:**

1. **Przeszukiwanie wszerz (BFS - Breadth-First Search):**
    
    - **Opis**: Algorytm polegający na przeszukiwaniu grafu, zaczynając od zadanego wierzchołka, a następnie odwiedzaniu wszystkich jego sąsiadów, zanim przejdzie się do sąsiadów tych sąsiadów.
        
    - **Zastosowanie**: Znajdowanie najkrótszych ścieżek w grafach o jednakowych wagach krawędzi oraz analiza spójności grafu. 
        
2. **Przeszukiwanie w głąb (DFS - Depth-First Search):**
    
    - **Opis**: Algorytm polegający na eksploracji grafu poprzez przechodzenie jak najgłębiej wzdłuż gałęzi, zanim nastąpi powrót i sprawdzenie innych możliwości.
        
    - **Zastosowanie**: Odwiedzanie wszystkich wierzchołków w grafie, znajdowanie spójnych składowych oraz rozwiązywanie problemów takich jak detekcja cykli.
        
3. **Algorytm Dijkstry:**
    
    - **Opis**: Służy do znajdowania najkrótszej ścieżki między dwoma wierzchołkami w grafie ważonym, gdzie krawędzie mają przypisane dodatnie wagi.
        
    - **Zastosowanie**: Optymalizacja tras w nawigacji GPS, analiza sieci komunikacyjnych. 
        
4. **Algorytm Kruskala:**
    
    - **Opis**: Służy do znajdowania minimalnego drzewa rozpinającego w grafie ważonym, polegając na dodawaniu krawędzi o najmniejszej wadze, które nie tworzą cykli.
        
    - **Zastosowanie**: Projektowanie sieci, takich jak sieci energetyczne czy telekomunikacyjne, gdzie celem jest minimalizacja kosztów połączeń.
        
5. **Algorytm Prima:**
    
    - **Opis**: Inny sposób znajdowania minimalnego drzewa rozpinającego, polegający na iteracyjnym dodawaniu krawędzi o najmniejszej wadze, które łączą wierzchołek z drzewem rozpinającym.
        
    - **Zastosowanie**: Podobnie jak algorytm Kruskala, stosowany w projektowaniu efektywnych i kosztowo optymalnych sieci.
        
6. **Algorytm Bellmana-Forda:**
    
    - **Opis**: Służy do znajdowania najkrótszych ścieżek w grafie, nawet jeśli krawędzie mają ujemne wagi, pod warunkiem że nie ma cykli o ujemnej sumie wag.
        
    - **Zastosowanie**: Analiza sieci finansowych, gdzie mogą występować ujemne wartości, oraz w sytuacjach wymagających uwzględnienia takich wag.
        
7. **Algorytm Floyda-Warshalla:**
    
    - **Opis**: Umożliwia obliczanie najkrótszych ścieżek pomiędzy wszystkimi parami wierzchołków w grafie.
        
    - **Zastosowanie**: Analiza tras w dużych sieciach, takich jak sieci komputerowe czy transportowe.
        
8. **Sortowanie topologiczne:**
    
    - **Opis**: Porządkuje wierzchołki grafu skierowanego acyklicznego (DAG) w liniową sekwencję, tak aby dla każdej krawędzi (u, v), wierzchołek u pojawiał się przed wierzchołkiem v.
        
    - **Zastosowanie**: Planowanie zadań, analiza zależności między zadaniami, kompilacja kodu źródłowego.
        
9. __Algorytm A_:_*
    
    - **Opis**: Heurystyczny algorytm służący do znajdowania najkrótszej ścieżki w grafie, łączący cechy algorytmu Dijkstry z dodatkowymi informacjami o przewidywanym koszcie dotarcia do celu.
        
    - **Zastosowanie**: Szeroko stosowany w systemach nawigacyjnych, grach komputerowych oraz robotyce do planowania tras.
        
Wybór odpowiedniego algorytmu zależy od specyfiki problemu, takich jak rodzaj grafu (np. skierowany, nieskierowany, ważony), wymagania dotyczące wydajności oraz charakterystyka danych wejściowych.