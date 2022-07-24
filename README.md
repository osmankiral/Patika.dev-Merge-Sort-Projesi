# Patika.dev-Merge-Sort-Projesi

[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.

Çözüm:

1.
1- [16,21,11,8,12,22] dizisi ikiye bölünür.

2- [16,21,11] - [8,12,22]

3- [16,21] - [11] ve [8,12] - [22]

4- [16] [21] - [11] ve [8] [12] - [22] birer parçaya ayırdığımız veriler küçükten büyüğe kendi grupları arasında birleştirilir.

5- [11,16,21] ve [8,12,22] en son iki grup da bir araya getirilir.

6- [8,11,12,16,21,22]

2.
Worst Case: O(nlogn)

Average Case: O(nlogn)

Best Case: O(nlogn)


www.patika.dev
