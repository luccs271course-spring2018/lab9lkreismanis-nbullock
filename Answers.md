# Answers
## by Larisa Kreismanis & Nathan Bullock

1. Try using a TreeMap and a HashMap instead of MyHashMap.
    1. a. Are the resulting word frequencies any different?
    - No, the resulting word frequencies are not any different.
    2. b. Is the time performance any different? If so, how would you rank the three implementations (in increasing order of time complexity)?
    - MyHashMap had more efficient time perfomace than HashMap. Ranking the three implemetaions, MyHashMap is most effiecient followed by HashMap and Tree Map.

2. How are % and Math.floorMod different? Which works more reliably for computing a hash table index?
- % and Math.floorMod are different by % simply returning the remainder of an expression, while .floorMod divides the expression and then maps the number to the nearest lower integer. .floorMod works more reliably for computing a hash table index.

3. What is the time complexity of MyHashMap.size(), and how could you make it much more efficient?
- The time complexity of MyHashMap.size() is O(n). You could make it much more efficient by enabling a change in size.

4. How does this implementation compare to one where you would directly use your linked Node class from the earlier assignment? Answer briefly in terms of ease of implementation, correctness, reliability, and performance.
- In terms of implementation, correctness, reliability, and performance, MyHashMap has the greatest implementation and performance with relatively good correctness and reliabilty.  HashMap has good correctness and reliability, with lesser implementation and performance. 
