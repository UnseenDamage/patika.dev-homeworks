# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree

```
root = 7 olarak alalım.

Eğer dizinin ilk elemanını referans alacak olursak 7 "root" olur. Dizinin diğer elemanları root a kıyasla tree ye yerleştirilir.

[7, "5", 1, 8, 3, 6, 0, 9, 4, 2] --> 5, 7'den küçük oluğu için 7'nin sol tarafına yerleştirilecek

[7, 5, "1", 8, 3, 6, 0, 9, 4, 2] --> 1, 7'den küçük ve 5'den küçük olduğu için 5'in sol tarafına yerleştirilecek.

[7, 5, 1, "8", 3, 6, 0, 9, 4, 2] --> 8, 7'den büyük olduğu için 7'nin sağ tarafına yerleştirilecek.

[7, 5, 1, 8, "3", 6, 0, 9, 4, 2] --> 3, 7'den küçük ve 1'den büyük olduğu için 1'in sağ tarafına yerleştirilecek.

[7, 5, 1, 8, 3, 6, "0", 9, 4, 2] --> 0, 7'den ve 1'den küçük olduğu için 1'in sol tarafına yerleştirilecek.

[7, 5, 1, 8, 3, 6, 0, "9", 4, 2] --> 9, 7'den ve 8'den büyük olduğu için 8'nin sağ tarafına yerleştirilecek.

[7, 5, 1, 8, 3, 6, 0, 9, "4", 2] --> 4, 7'den küçük ve 3'den büyük olduğu için 3'ün sağ tarafına yerleştirilecek.

[7, 5, 1, 8, 3, 6, 0, 9, 4, "2"] --> 2, 7'den ve 3'den küçük olduğu için 3'in sol tarafına yerleştirilecek.

Eğer Binary Search Tree yapısı oluşturacak olursak aşağıdaki gibi bir yapı elde ederiz:

        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
     / \
    2   4
```
