PROJECT 1.1 

[22,27,16,2,18,6] -> Insertion Sort 
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. 
Big-O gösterimini yazınız. 
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız 

1.Average case: Aradığımız sayının ortada olması 
2.Worst case: Aradığımız sayının sonda olması 
3.Best case: Aradığımız sayının dizinin en başında olması. 

 
Answers 1: 

![alt text](https://github.com/mr0kocaman/Kodluyoruz_BaslangicSeviyesi_BackEnd_Patikasi/blob/main/image-1.png)

(n) + (n - 1) + (n - 2) + (n - 3) + 1  
= [n * (n+1)]/2  
= n^2/2 + n/2 
==> Big - O gösterimi; O(n^2)  
#Big - O gösteriminde n'nin kuvvetine odaklandığımızdan geri kalanı işlemi etkilemez  

Dizinin son sıralanışı [2,6,16,18,22,27] şeklindedir. 
2   --> Lower 
18 --> Middle      }    Sonuç olarak 18 sayısı dizinin avarage  case ini verir. 
27 --> Higher  

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. 

![alt text](https://github.com/mr0kocaman/Kodluyoruz_BaslangicSeviyesi_BackEnd_Patikasi/blob/main/image.png)

