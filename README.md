# deneme2patika-

Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
• Big-O gösterimini yazınız.
Yukarıdaki dizi için Merge Sort aşamaları şu şekildedir

[7, 3, 5, 8, 2, 9, 4, 15, 6]

[7, 3, 5, 8] [2, 9, 4, 15, 6]

[7, 3] [5, 8] [2, 9] [4, 15, 6]

[7] [3] [5] [8] [2] [9] [4] [15, 6]

[7] [3] [5] [8] [2] [9] [4] [15] [6]

[3, 7] [5, 8] [2, 9] [4, 15] [6]

[3, 5, 7, 8] [2, 4, 9, 15] [6]

[2, 3, 4, 5, 7, 8, 9, 15] [6]

[2, 3, 4, 5, 6, 7, 8, 9, 15]

Merge Sort için Big-O gösterimi O(n log n)'dir.
