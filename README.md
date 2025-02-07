# patikaDev
patikaDev  Insertion Sort Proje 


[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Adım Adım Insertion Sort Uygulaması
1. Adım
İlk eleman (22) zaten tek başına sıralı kabul edilir.
➡ [22, 27, 16, 2, 18, 6]

2. Adım
27 zaten 22'den büyük olduğu için yer değiştirme yok.
➡ [22, 27, 16, 2, 18, 6] 

3. Adım
16, 27 ve 22 ile karşılaştırılır. 16, 27 ve 22'den küçük olduğu için sola kaydırılır.
➡ [16, 22, 27, 2, 18, 6]

5. Adım
2, 27, 22 ve 16 ile karşılaştırılır. Hepsinden küçük olduğu için en başa gelir.
➡ [2, 16, 22, 27, 18, 6] 

6. Adım
18, 27, 22 ve 16 ile karşılaştırılır. 18, 27 ve 22'den küçük, 16'dan büyük olduğu için 16 ile 22 arasına yerleşir.
➡ [2, 16, 18, 22, 27, 6] 

7. Adım
6, 27, 22, 18, 16 ve 2 ile karşılaştırılır. 6, 16, 18, 22, 27'den küçük ama 2'den büyük olduğu için ikinci sıraya yerleşir.
➡ [2, 6, 16, 18, 22, 27]


Big-O gösterimini yazınız.
Dizinin sıralama sürecine baktığımızda, her elemanın yerine yerleşmesi için diğer elemanları kaydırması gerektiğini görüyoruz.
Dizimiz karışık bir sıra içerdiğinden, ortalama ve en kötü durum senaryoları geçerlidir ve bu durumda Big-O: O(n²) olur.




Orijinal Dizi: [22, 27, 16, 2, 18, 6]
Sıralı Hali: [2, 6, 16, 18, 22, 27]

Şimdi, 18 sayısının dizideki konumunu inceleyelim:

Sıralı dizide 18 üçüncü sırada (ortada) bulunuyor.
Average Case (Ortalama Durum): Aradığımız sayının ortada olmasıdır.
Cevap: 18 sayısı "Average Case" kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
