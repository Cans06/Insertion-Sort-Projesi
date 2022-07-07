# Insertion Sort Projesi

## Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

## Insertion Sort türüne göre aşamalar
Dizinin ilk elemanından başlayarak tüm elemanların karşılaştırılmasıyla dizi küçükten büyüğe doğru bir sıralama işlemi gerçekleştirilecektir.
İlk aşama olarak dizinin ilk elemanı 22 bir sağında ki eleman ile karşılaştırılır,
-22<27 bu işlem 22'den küçük bir eleman bulunana kadar devam eder.
22<16 bu durumda 16 ile 22 yer değiştirir.
[16,22,27,2,18,6]
[2,16,22,27,18,6]
[2,16,18,22,27,6]
[2,6,16,18,22,27]

## Big-O gösterimini yazınız.
n=6;

Best case = O(n) 
Average case = O(n^2)
Worst case = O(n^2)

## Time Complexity
Average case: Dizinin büyük ölçekte sıralı gelmesi durumu,
Worst case: Tüm dizi elemanlarının gezilmesi durumu, 
Best case: Dizinin sıralı gelmesi durumu.

## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizinin Sıralanmış Hali ;
[2,6,16,18,22,27]
18 sayısının ortada olmasından ötürü Avarege case kapsamına girer.



