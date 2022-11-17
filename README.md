VERİ YAPILARI VE ALGORİTMALAR
Selection Sort Projesi
# Proje-1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. 
1. [22,27,16,2,18,6]		(n)
2. [2,27,16,22,18,6]		(n-1)
3. [2,6,16,22,18,27]		(n-2)
4. [2,6,16,18,22,27]		(1)

Detaylı açıklaması aşağıdaki gibidir.
Soldaki sayıdan başlanarak en küçük eleman bulunana kadar tüm elemanlar taranır. 
2 elemanı 22 elemanı ile yer değiştirir.  Dizinin son hali [2,27,16,22,18,6] şeklindedir.
2'den sonraki en küçük elemanı bulmak için aynı tarama 2'den sonrası için tekrarlanır.
6 elemanı 27 elemanı ile yer değiştirir. Dizinin son hali [2,6,16,22,18,27] şeklindedir.
6'dan sonraki en küçük elemanı bulmak için tarama 6'dan sonrası için tekrarlanır.
16 elemanı daha küçük bir eleman bulunmadığı için yerinde kalır. Dizinin son hali [2,6,16,22,18,27] şeklindedir.
16'dan sonraki en küçük elemanı bulmak için tarama 16'dan sonrası için tekrarlanır.
18 elemanı 22 elemanı ile yer değiştirir. Dizinin son hali [2,6,16,18,22,27] şeklindedir.
18'den sonraki en küçük elemanı bulmak için tarama 18'den sonrası için tekrarlanır.
22 elemanı 27 elemanından küçük olduğu için yerinde kalır ve işlem sonlanır. Dizinin son hali [2,6,16,18,22,27] şeklindedir.

Big-O gösterimini yazınız.

Big O : O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması

Worst case: Aradığımız sayının sonda olması

Best case: Aradığımız sayının dizinin en başında olması.

[2,6,16,18,22,27] dizi sıralandığında 18 sayısı ortada kaldığı için Avarage Case olur.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. [7,3,5,8,2,9,4,15,6]		(n)
2. [2,3,5,8,7,9,4,15,6]		(n-1)
3. [2,3,4,8,7,9,5,15,6]		(n-2)
4. [2,3,4,5,7,9,8,15,6]		(n-3)

www.patika.dev
