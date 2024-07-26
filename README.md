# Patika Veri Yapıları ve Algoritmalar Dersi Selection Sort Projesi
Patika Veri Yapıları ve Algoritmalar Dersi Selection Sort Projesi

## Selection Sort Aşamaları

Başlangıç Dizisi: [22, 27, 16, 2, 18, 6]

1. Adım: [2, 27, 16, 22, 18, 6] (2 en küçük eleman olarak seçilir ve ilk sıradaki 22 ile yer değiştirilir)
2. Adım: [2, 6, 16, 22, 18, 27] (6 en küçük eleman olarak seçilir ve ikinci sıradaki 27 ile yer değiştirilir)
3. Adım: [2, 6, 16, 22, 18, 27] (16 en küçük eleman olarak seçilir ve yerinde kalır)
4. Adım: [2, 6, 16, 18, 22, 27] (18 en küçük eleman olarak seçilir ve dördüncü sıradaki 22 ile yer değiştirilir)
5. Adım: [2, 6, 16, 18, 22, 27] (22 en küçük eleman olarak seçilir ve yerinde kalır)
6. Adım: [2, 6, 16, 18, 22, 27] (27 en küçük eleman olarak seçilir ve yerinde kalır)

Dizi sıralandıktan sonra [2, 6, 16, 18, 22, 27] haline gelir.

## Big-O Gösterimi

Selection Sort algoritmasının en kötü, en iyi ve ortalama durumdaki zaman karmaşıklığı O(n^2)'dir.

## Time Complexity ve 18 Sayısının Durumu

Dizi sıralandıktan sonra [2, 6, 16, 18, 22, 27] haline gelir. Bu durumda, 18 sayısı ortada yer almaktadır. Dolayısıyla:

- Average case: Aradığımız sayının ortada olması

18 sayısı average case kapsamına girer.

## Selection Sort İlk 4 Adım

Başlangıç Dizisi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

1. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] (2 en küçük eleman olarak seçilir ve ilk sıradaki 7 ile yer değiştirilir)
2. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] (3 zaten ikinci sırada ve doğru yerde)
3. Adım: [2, 3, 4, 8, 7, 9, 5, 15, 6] (4 üçüncü sıraya yerleştirilir, 5 ile yer değiştirilir)
4. Adım: [2, 3, 4, 5, 7, 9, 8, 15, 6] (5 dördüncü sıraya yerleştirilir, 8 ile yer değiştirilir)

Bu adımlardan sonra dizinin durumu [2, 3, 4, 5, 7, 9, 8, 15, 6] olacaktır.
