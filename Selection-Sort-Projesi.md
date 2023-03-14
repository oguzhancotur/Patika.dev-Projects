
Proje 1 =>>>>>
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Çözüm 1: En küçük elemanı bularak 1. sıradaki ile yer değiştiririz. İlk Hali: [22,27,16,2,18,6].
1. aşama: [2,27,16,22,18,6] olur. Şimdi ise 27 ile 6 yı yer değiştirmeliyiz.
2. aşama: [2,6,16,22,18,27] olmalı. 
3. aşama: [2,6,16,22,18,27] 16 doğru yerde olduğu için ellemiyoruz. 
4. aşama: [2,6,16,18,22,27] 18 ile 22 nin yerini değiştirmeliyiz.

Big-O gösterimi: O(n^2)

18 sayısı ortada olduğundan Average case kapsamına girer.
-----------------------------------------------------------------------------------------------------------------------
Proje 2
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Çözüm 2: 2 sayısını 7 ile yer değiştirmeliyiz. Çünkü en küçük sayı 2.
1. aşama: [2,3,5,8,7,9,4,15,6] olur.
2. aşama: [2,3,5,8,7,9,4,15,6] 3 doğru yerde karışmıyoruz.
3. aşama: [2,3,4,8,7,9,5,15,6] 4 ile 5 sayının yerini değiştirmeliyiz.
4. aşama: [2,3,4,5,7,9,8,15,6] 5 ile 8 sayısının yerini değiştirmeliyiz.
