# (16,21,11,8,12,22) Merge Sorting
- Aşama 1: Dizi 2 eşit parçaya bölünür.
Sol parça: [16, 21, 11]
Sağ parça: [8, 12, 22]

Aşama 2: Her iki parça da aynı işleme tabi tutulur.
Sol parça: [16] (zaten sıralı)
Sağ parça: [21] (zaten sıralı)

Aşama 3: İki sıralı parça birleştirilir.
Birleştirilmiş parça: [16, 21]

Aşama 4: Sol parça [11] ve sağ parça [8] birleştirilir.
Birleştirilmiş parça: [8, 11]

Aşama 5: Sol parça [8, 11] ve sağ parça [12] birleştirilir.
Birleştirilmiş parça: [8, 11, 12]

Aşama 6: Sol parça [16, 21] ve sağ parça [8, 11, 12] birleştirilir.
Birleştirilmiş parça: [8, 11, 12, 16, 21]

Aşama 7: Sağ parça [22] (zaten sıralı) olarak kalır.

Aşama 8: Sol parça [8, 11, 12, 16, 21] ve sağ parça [22] birleştirilir.
Birleştirilmiş parça (sıralı dizi): [8, 11, 12, 16, 21, 22]

Sonuç olarak, verilen dizi Merge Sort algoritması kullanılarak sıralandı ve sıralı sonuç [8, 11, 12, 16, 21, 22] elde edildi.

Merge Sort'un Big-O gösterimi O(n log n) dir.
