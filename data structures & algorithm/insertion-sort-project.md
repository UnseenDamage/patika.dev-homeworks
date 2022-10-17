# [22, 27, 16, 2, 18, 6] --> Insertion Sort

[2,27,16,22,18,6] --> 22 sayısı dizinin elemanları ile karşılaştırılır ve en küçük olan 2 ile yer değişir.
[2,6,16,22,18,27] --> 27 sayısı dizinin elemanları ile karşılaştırılır ve kendinden küçük olan 6 ile yer değişir.
[2,6,16,22,18,27] --> 16 sayısı dizinin elemanları ile karşılaştırılır ve yer değiştirmez.
[2,6,16,18,22,27] --> 22 sayısı dizinin elemanları ile karşılaştırılır ve kendinden küçük olan 18 ile yer değişir.
[2,6,16,18,22,27] --> 22 sayısı dizinin elemanları ile karşılaştırılır ve yer değiştirmez.
[2,6,16,18,22,27] --> 27 sayısı dizide karşılaştırılıcak eleman kalmadığı için yer değiştirmez.

## Big-O gösterimini yazınız.

O(n²)

## Time Complexity:

Average case: n²
Worst case: n²
Best case: n

## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case.

# [7, 3, 5, 8, 2, 9, 4, 15, 6] --> Insertion Sort

[2,3,5,8,7,9,4,15,6] --> 7 sayısı dizinin elemanları ile karşılaştırılır ve en küçük olan 2 ile yer değişir.
[2,3,5,8,7,9,4,15,6] --> 3 sayısı dizinin elemanları ile karşılaştırılır ve yer değiştirmez.
[2,3,4,8,7,9,5,15,6] --> 5 sayısı dizinin elemanları ile karşılaştırılır ve kendinden küçük olan 4 ile yer değişir.
[2,3,4,5,7,9,8,15,6] --> 8 sayısı dizinin elemanları ile karşılaştırılır ve kendinden küçük olan 5 ile yer değişir.
[2,3,4,5,6,9,8,15,7] --> 7 sayısı dizinin elemanları ile karşılaştırılır ve kendinden küçük olan 6 ile yer değişir.
[2,3,4,5,6,7,8,15,9] --> 9 sayısı dizinin elemanları ile karşılaştırılır ve kendinden küçük olan 7 ile yer değişir.
[2,3,4,5,6,7,8,15,9] --> 8 sayısı dizinin elemanları ile karşılaştırılır ve yer değiştirmez.
[2,3,4,5,6,7,8,9,15] --> 15 sayısı dizinin elemanları ile karşılaştırılır ve kendinden küçük olan 9 ile yer değişir.
[2,3,4,5,6,7,8,9,15] --> 15 sayısı dizide karşılaştırılıcak eleman kalmadığı için yer değiştirmez.
