# Insertion-Sort

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


[22,27,16,2,18,6] -> [2,27,16,22,18,6] -> [2,6,16,22,18,27] -> [2,6,16,22,18,27] -> [2,6,16,18,22,27]
Big-O gösterimi -> O(n^2)
Time Complexity: Worst Case

[7,3,5,8,2,9,4,15,6]  Selection Sort'a göre;
1- [2,3,5,8,7,9,4,15,6]
2- [2,3,5,8,7,9,4,15,6] (3, 2'den sonra en küçük olduğu için değişmeyecek)
3- [2,3,4,8,7,9,5,15,6]
4- [2,3,4,5,7,9,8,15,6]

