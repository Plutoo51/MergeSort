# MergeSort
MergeSort
[Patika.dev](https://www.patika.dev/tr)

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Diziyi ikiye bölüyoruz ve bölünen dizileri tek eleman kalana kadar tekrar ikiye bölüyoruz.

[16,21,11]--[8,12,22]

[16,21]--[11]--[8]--[12,22]

[16]--[21]--[11]--[8]--[12]--[22]

Sıralı dizi elde etmek için birleştiriyoruz.

[16,21]--[11]--[8]--[12,22]
[11,16,21]--[8,12,22]
[8,11,12,16,21,22]

Big-O --> O(n*logn)
