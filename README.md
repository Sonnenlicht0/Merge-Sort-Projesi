# Merge-Sort-Projesi
Patika.dev  Merge projesi için açtığım proje 

https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje

[16,21,11,8,12,22] -> Merge Sort

-> Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
-> Big-O gösterimini yazınız.

Çözüm

-> [16,21,11,8,12,22]
   [16,21,11] ; [8,12,22]
   [16,21] ; [11] ; [8,12] ; [22]
   [16] ; [21] ; [11] ; [8] ; [12] ; [22]
   [16,21] ; [8,11] ; [12,22]
   [8,11,12,16,21,22]
  
-> O(nlogn) --> O(6log6)
