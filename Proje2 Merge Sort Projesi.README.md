# Proje2 Merge Sort Projesi 
[Patika.dev](www.patika.dev)

patika.dev veri yapıları ve algoritmalar eğitimi proje2

Dizi1 = [16, 21, 11, 8, 12, 22]
Dizi1 Merge Sort türüne göre sıralama aşamaları:

1.aşama: Dizi1 ikiye bölünür. [16, 21, 11] ve [8, 12, 22]

2.aşama: ikiye bölünen parçalarda tekrar ikiye bölünür. [16] ve  [21, 11] ve [8, 12] ve [22]

3.aşama: bu ikili ve tekli gruplar kendi içlerinde sıralanır. [16] ve  [11, 21] ve [8, 12] ve [22]

4.aşama: birleştirme aşamlarına geçiş yapılır. iki grup birşleştirilirken en baştaki sayılara bakılır en küçük olanı başa yazarız daha sonra 2. sıra ile diğer dizinin 1. sırası tekrar karşılaştırılır. bu ta ki en son elemana gelene kadar yapılır.
[11, 16, 21] ve [8, 12, 22]

5.aşama: 4.aşama son kalan iki grup için de tekrarlanır. [8, 11, 12, 16, 21, 22]

Big O gösterimi = O(nlogn) 

It's wrtitten by Gaye Aksu.
