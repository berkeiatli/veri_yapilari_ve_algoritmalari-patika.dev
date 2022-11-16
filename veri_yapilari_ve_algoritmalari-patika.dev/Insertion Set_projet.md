
[22,27,16,2,18,6] dizisi için -> Insertion Sort aşamaları:

1.aşama : dizinin elemanlarından en küçük olan en başa gelir ve en baştaki ile yer değiştirir. Yani [2,27,16,22,18,6] olur.<hr>
2.aşama : 2'den sonra en küçük eleman 6 olduğu için 6 yı 2'den hemen sonra en başa yazıyoruz. Yani [2,6,16,22,18,27]
3.aşama : 6'dan sonra en küçük eleman 16 dır ve sıralanmış bir haldedir. O halde 16'dan sonraki en küçük rakam olan 18 i sıralamak için 16'dan sonra en başa yazalım. Yani [2,6,16,18,22,27] olur ve dizi sıralanmıştır. 


Big-O gösterimi :

 [22,27,16,2,18,6] dizisi n elemanlı ve her adımda bir eksiği kadar işlem yapıyoruz. O halde n*(n-1)*(n-2)*....1= n*(n+1)/2 olduğundan ve dominant olan n^2 olduğundan O(n^2) olur. 


 18 sayısı sıralanmış dizide orta sıralarda yer aldığı için "Average Case" kapsamına girer.

 ----------------------------------------------

 [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

 1.adım : dizinin elemanlarından en küçük olan 2 sayısı en başa gelir ve yerdeğiştirilir. Yani [2,3,5,8,7,9,4,15,6] olur.
 2.adım : aynı mantığı bu adımda da uygularsak 2 den sonra dizide en küçük sayı 3 dür ve sıralanmış bir haldedir , ondan sonraki en küçük sayı olan 4 için yapalım. Yani [2,3,4,8,7,9,5,15,6]
 3.adım : 2,3,4 den sonra dizide yer alan en küçük eleman 5'dir. Onun için yaptığımızda dizimiz [2,3,4,5,7,9,8,15,6]
 4.adım : 2,3,4,5 sıralı bir halde. 6 için aynı yöntem uygulanırsa [2,3,4,5,6,9,8,15,7] şeklinde olur. 
 .... 
 
