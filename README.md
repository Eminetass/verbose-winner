#veriYapıları-selectionİnsertion 
insertion-selection short ve ilgili kavramları örneklerle açıklanır.<br>
<br>
******[22,27,16,2,18,6] -> insertion sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması <br>
Worst case: Aradığımız sayının sonda olması <br>
Best case: Aradığımız sayının dizinin en başında olması. <br>

     [22,27,16,2,18,6]  ilk elemanı grup kabul eder diğer elemalarla karşılatırarak dizini sıralar. 
 [22|27,16,2,18,6]
 [6,22|27,16,2,18]
 [6,18,22|27,16,2]
 [6,18,22,27|16,2]
 [2,6,18,22,27|16]
 [2,6,16,18,22,27]
18 saysının time complexty average case dir.
big-O notasyonu O(n^2) dir.


*******[7,3,5,8,2,9,4,15,6] -> selection sort

[7,3,5,8,2,9,4,15,6] selection sort için dizini adım adım küçükten büyüğe sıralanır
[2,3,5,8,7,9,4,15,6] 
[2,3,4,8,7,9,5,15,6] 
[2,3,4,5,7,9,8,15,6] 
[2,3,4,5,6,9,8,15,7] 
[2,3,4,5,6,7,8,15,9]
[2,3,4,5,6,7,8,9,15] 













