Proje 1
[22,27,16,2,18,6] -> Insertion Sort

=> Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Cevap: Dizinin ikinci elemanı başlangıç elemanı olarak seçilir.  22,[27],16,2,18,6
Daha sonra 27 ile 22 kıyas edilir. 27 > 22 olduğu için herhangi bir değişiklik yapılmaz.
Şimdi de üçüncü eleman olan 16 ile 27 kontrol edilir. 16 < 27 olduğu için 27 ve 16 yer değişir. Tekrar 16 ve 22 karşılaştırılır ve 16<22 olduğu için 22 ve 16 yer değişir.
16,22,27,2,18,6
Sıra 4. elemandadır. 2<27 , 2<22 ve 2<16 bu yüzden yer değiştirmeler sonucu 2 başa gelir. 
2,16,22,27,18,6
Sıra 5. eleman 18 de. 18<27 , 18<22 bu yüzden 18 ikisiyle de yer değişir.
2,16,18,22,27,6
Son eleman 6, en baştaki eleman hariç hepsinden küçüktür. 2. sıraya kadar kayar ve sort biter.
2,6,16,18,22,27
=> Big-O gösterimini yazınız.
Cevap: 0+1+2+3+4…..+n-1 = [n*(n-1)]/2   :  n^2 O(n^2)
=> Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
Cevap: Sıralandıktan sonra 18 ortada olur. Average case kapsamına girer.

=>[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1. adım:İlk indeksden başlarız ve dizideki en küçük sayıyı buluruz. 5. eleman 2 en küçük sayıdır. İlk indeksde ki sayıyla 2 yi yer değişiriz.
2,3,5,8,7,9,4,15,6
2. adım: Bir sonraki indekse gideriz. O indeks ve ondan sonraki indekslerde ki sayılara bakılır, en küçük sayı 3 dür. Bir değişiklik olmaz.
3. adım: Sonraki indeks yani 5 e gelinir. 5 ve sonrasındaki sayılara bakılır. En küçük sayı 4 dür. 5 ve 4 yer değişir.
2,3,4,8,7,9,5,15,6
4. adım: 8 sayısının olduğu indexe sıra gelir. 8 den itibaren 5 en küçüktür. 5 ve 8 yer değişir. 
2,3,4,5,7,9,8,6

