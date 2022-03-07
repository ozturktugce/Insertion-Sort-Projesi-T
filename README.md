# Insertion-Sort-Projesi-T

**Insertion Asamalari**

[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

**Big O gosterimi:** 

n+(n-1)+(n-2)+...+1 = n*(n+1)/2
n^2+n / 2 
dominant deger n^2
O(n^2)

**Time Complexitiy**
**Average case:** Aradimiz sayinin ortada olmasi
**Worst case:** Aradimiz sayinin sonda olmasi
**Best case:** Aradimiz sayinin dizinin en basinda olmasi.

Dizi siralandiktan sonra 18 sayisi;
[2,6,16,**18**,22,27] ortada olacağindan **Average Case** kapsamindadir.

[7,3,5,8,2,9,4,15,6] ==> **Insertion Sort'a gore ilk dort adimi;**
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
