PROJECT 1.3 

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. 
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb. 

Answers 3: 

![alt text](https://github.com/mr0kocaman/Kodluyoruz_BaslangicSeviyesi_BackEnd_Patikasi/blob/main/image-3.png)

Step 1: 7 > 5 olduğu için root'un sağında bulunur. (root 5'tir.) 
Step 2: 1 < 5 olduğu için root'un solunda bulunur. (root 5'tir.) 
Step 3: 8 > 5 ve 8 > 7 olduğu için root'un sağında bulunur. (root 7'dir.) 
Step 4: 3 < 5 ve 3 > 1 olduğu için root'un sağında bulunur. (root 1'dir.) 
Step 5: 6 > 5 ve 6 < 7 olduğu için root'un solunda bulunur. (root 7'dir.) 
Step 6: 0 < 5 ve 0 < 1 olduğu için root'un solunda bulunur. (root 1'dir.) 
Step 7: 9 > 5, 9 > 7 ve 9 > 8 olduğu için root'un sağında bulunur. (root 8'dir.) 
Step 8: 4 < 5, 4 > 1 ve 4 > 3 olduğu için root'un sağında bulunur. (root 3'tür.) 
Step 9: 2 < 5, 2 > 1 ve 2 < 3 olduğu için root'un solunda bulunur. (root 3'tür.) 