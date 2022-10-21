# Insertion Sort Projesi
### [22,27,16,2,18,6] -> Insertion Sort

#### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- [22,27,16,2,18,6] Başlangıç
- [2,27,16,22,18,6] En küçük sayı 2 olduğundan dolayı 2 ve 22 yer değiştirdi.
- [2,6,16,22,18,27] 2 haricinde en küçük sayı 6'dır. 6 ve 27 yer değiştirdi.
- [2,6,16,18,22,27] 18 ve 22 yer değiştirdi.

#### 2. Big-O gösterimini yazınız.

   O(n^2)
 
#### 3. Time Complexity
- Average case: Aradığımız sayının ortada olması.
- Worst case: Aradığımız sayının sonda olması.
- Best case: Aradığımız sayının dizinin en başında olması.
  
#### 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[2,6,16,18,22,27]
- Aradığımız sayı başta veya sonda olmadığından best veya worst case'e girmez. Bu nedenle Avarage Case kapsamındadır.

#### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
- [2,3,5,8,7,9,4,15,6] 2 ile 7 sayısı yer değiştirdi
- [2,3,4,8,7,9,5,15,6] 5 ile 4 sayısı yer değiştirdi
- [2,3,4,5,7,9,8,15,6] 8 ile 5 sayısı yer değiştirdi
- [2,3,4,5,6,9,8,15,7] 6 ile 7 sayısı yer değiştirdi
