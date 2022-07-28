# Merge-Sort
Proje 2
[16,21,11,8,12,22] -> Merge Sort
[16,21,11] [8,12,22] : Tek eleman kalana kadar ikiye bölme işlemi yapıyoruz.
[16,21] [11] [8,12] [22]
[16] [21] [11] [8] [12] [22] : Tek eleman kaldıktan sonra da sıralı bir şekilde tekrar birleştirme işlemi yapılıyor.
[16,21] [8,11] [12,22]
[8,11,16,21] [12,22]
[8,11,12,16,21,22] : Dizinin son hali bu şekilde oluyor.
Big-O gösterimi:
O(nlogn)
