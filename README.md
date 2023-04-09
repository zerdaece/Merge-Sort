# Merge-Sort
patika_mergesort



[16,21,11,8,12,22] -> Merge Sort
 
 Veri kümesini ikiye ayırıyoruz. Tek eleman kalana kadar devam ediyoruz.
 
 [16,21,11] -- [8,12,22]
 
 [16,21]--[11]--[8]--[12,22]
 
 [16]--[21]---[11]--[8]---[12]--[22]
 
 Burada tek eleman kaldı . Şimdi sayı sıralamasına göre tekrar birleştiriyoruz.

 [16,21]--[8,11]--[12,22]

 [8,11,12,16,21,22]

 Big-O gösterimi O(n*logn)dir.  
