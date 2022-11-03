# Kodluyoruz-Insertion-Sort-Projesi
Insertion Sort Proje Ödevi
 
 ## Proje 1 - Ödev 1  
 
[22,27,16,2,18,6] -> Insertion Sort

a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.  

b) Big-O gösterimini yazınız.  

c) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.  

d) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.  

## Çözüm

a)  
   [22, 27, 16, 2, 18, 6] n  
   [2, 27, 16, 22, 18, 6] n-1  
   [2, 6, 16, 22, 18, 27] n-2  
   [2, 6, 16, 18, 22, 27] n-3  
   
b)   
   Big O   
   n + (n-1) + (n-2) + (n-3) + ... + 1 = n2  

c)  
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

d)  
18 (Average Case kapsamına girer)  
   



## Proje 1 - Ödev 2  

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.  

1- [2, 3, 5, 8, 7, 9, 4, 15, 6]  
2- [2, 3, 4, 8, 7, 9, 5, 15, 6]  
3- [2, 3, 4, 5, 7, 9, 8, 15, 6]  
4- [2, 3, 4, 5, 6, 9, 8, 15, 7]






