# proje1
Selection Sort proje ödevi
İRFAN AYAZ 
Proje 1 
A- [22,27,16,2,18,6] Insertion sort aşamaları
1-	Dizinin en baştan sıralamaya bakıldı 22, 27 ten küçük sıralama doğru. Değişiklik yapılmadı
2-	 27 ve 16 ya bakıldı ve 16 yanlış. 16 sıralamada 27’den ve 22’den küçük. En başa alınır. Ve sıralama bu şekildedir.   
[16,22,27,2,18,6]
3-	 27 ve 2’ye bakıldı. 2 sırasıyla hepsinden küçük ve en başa kadar geldi. 
[2,16,22,27,18,6]
4-	27 ve 18’e bakıldı. 18 sırasıyla 27 ve 22’den küçük ama 16’ dan büyük olduğundan 16’ın sağına yerleştirildi.
[2,16,18,22,27,6]
5-	27 ve 6’ay bakıldı. 6 sırasıyla 27, 22, 18, 16,’dan en küçük ama 2’ den büyük olduğundan 2’nin sağına yerleştirildi.
[2,6,16,18,22,27,]  Bitti!

Big O Notation’u n*(n+1)/2 olduğundan O(n^2) dir.

18 sayısı sonda olduğundan Time Complexity Worst case’dir.

B- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını.

1-	Dizinin en küçük elemanını bul ve en baştaki sayı ile değiştir.
[2,3,5,8,7,9,4,15,6] 2,7
2-	Dizinin 2. en küçük elemanını 3 ve yerinde. Dokunma! Sıradakine geç
[2,3,5,8,7,9,4,15,6] 3
3-	Dizinin 3. en küçük elemanını bul ve 3.sıradaki sayı ile değiştir.
4-	[2,3,4,8,7,9,5,15,6] 4,5
5-	Dizinin 4. en küçük elemanını bul ve 4.sıradaki sayı ile değiştir.
[2,3,4,5,7,9,8,15,6]5,8
6-	Dizinin 5. en küçük elemanını bul ve 5.sıradaki sayı ile değiştir.
[2,3,4,5,6,9,8,15,7] 6,7
7-	Dizinin 6. en küçük elemanını bul ve 6.sıradaki sayı ile değiştir.
[2,3,4,5,6,7,8,15,9]7,9
8-	Dizinin 7. en küçük elemanını 8 ve yerinde. Dokunma! Sıradakine geç
[2,3,4,5,6,7,8,15,9]
9-	Dizinin 8. en küçük elemanını bul ve 8.sıradaki sayı ile değiştir.
[2,3,4,5,6,7,8,9,15]
Bitti!
