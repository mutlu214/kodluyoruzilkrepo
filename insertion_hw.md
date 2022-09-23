# INSERTION SORT HW (ALGORİTMALAR 1. PROJE)

## SORU 1

### [22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### CEVAP 1

> **insertion sort aşamaları**
>
>> [2,27,16,22,18,6]
>
>> [2,6,16,22,18,27]
>
>> [2,6,16,18,22,27]

> **Big-O notation**
> 
>> Big-O (n²)

> **Time Complexity**
>> Average case: O(n²)
>> 
>> Worst Case : O(n²)
>> 
>> Best Case : O(n)

> **18 sayısı hangi case kapsamına girer?**
>
>>18 sayısı **average case** kapsamına girer

### SORU 2

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### CEVAP 2

>[7,3,5,8,2,9,4,15,6]
>[2,3,5,8,7,9,4,15,6]
>[2,3,5,8,7,9,4,15,6]
>[2,3,4,8,7,9,5,15,6]
>[2,3,4,5,7,9,8,15,6]