# insertionSort/PROJE1



[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]

[16,22,27,2,18,6]

[2,16,22,27,18,6]

[2,16,18,22,27,6]

[2,6,16,18,22,27]

## Time Complexity: 
* Average case: Aradığımız sayının ortada olması
   ```
  [2,6,16,18,22,27]
  16-18
   ```
* Worst case: Aradığımız sayının sonda olması
   ```
   27
  ```
* Best case: Aradığımız sayının dizinin en başında olması.
   ```
    2
   ```
## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
   ```
   average case
   ```

## Big-O gösterimi:
  ```
  O(n^2)
  ```

---


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


 ```
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
```
