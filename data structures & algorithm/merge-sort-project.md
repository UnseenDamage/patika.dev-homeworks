# [16, 21, 11, 8, 12, 22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. <br><br>

[16,21,11],[8,12,22] --> Dizi ikiye bölündü. <br>
[16,21],[11],[8,12],[22] --> İkiye bölünmüş dizi tekrardan ikiye bölündü. <br>
[16],[21],[11],[8],[12],[22] --> Dizi 6 adet tekli grup haline geldi. <br>
[16],[11,21],[8,12],[22] --> Gruplar ikili gruplara dönüştürüldü ve grup içerisinde en küçük olan başa alındı. <br>
[11,16,21],[8,12,22] --> Gruplar üçlü gruplara dönüştürüldü ve grup içerisinde en küçük olan başa alındı. <br>
[8,11,12,16,21,22] --> Gruplar birleştirildi ve en küçük olan başa alınacak şekilde sıralandı.

## Big-O gösterimini yazınız.

O(nlogn)
