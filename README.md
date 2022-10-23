# patika_dev_merge_sort_Proje_2

[Patika.dev](https://www.patika.dev/) Merge sort 2. projedir

### [16,21,11,8,12,22] -> Merge Sort

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Dizi ilk hali ->  [16,21,11,8,12,22] 

Listeyi ikiye bölüyoruz  ->  [16,21,11]  [8,12,22] 

daha da küçük listelere bölüyoruz. -> [16,21]  [11]  [8]  [12,22]

ve tek olarak ayırıyoruz -> [16] [21]  [11]    [8]  [12] [22]

ikilileri sıralayarak birleştiriyoruz -> [16,21] [11]  [8] [12,22]

üçlü olarak sıralı bir biçimde birleştiriyoruz -> [11,16,21]  [8,12,22]

son olarak yüm listeyi küçükten büyüğe olacak şekilde birleştiriyoruz -> [8,11,12,16,21,22]

### Big-O gösterimini yazınız.

Her işlemde, O(n) kadar kompleks ile uğraşıyoruz ve uğraşmamız gereken boyut yarıya indiği için de logn kere işlem yapıyoruz. yani Big-O O(nlogn)'dir.
