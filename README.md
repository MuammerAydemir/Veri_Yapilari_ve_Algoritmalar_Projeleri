# Veri_Yapilari_ve_Algoritmalar_Projeleri
Selection Sort Projesi, Merge Sort Projesi ve Binary Sort Projesleri
***
## Selection Sort Projesi

``[22,27,16,2,18,6]`` -> Insertion Sort
```
1. [22|27,16,2,18,6] 
2. [22,27|16,2,18,6]  
3. [16,22,27|2,18,6] 
4. [2,16,22,27|18,6] 
5. [2,16,18,22,27|6] 
6. [2,6,16,18,22,27|] 
```
#### Big O Gösterimi
``[2,6,16,18,22,27]`` -> Q(n^2)

#### Time Complexity
>[2,6,16,18,22,27]

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? (Yazınız)
- Avarage case kapsamına girer.

#### Diğer Sıralama
``[7,3,5,8,2,9,4,15,6] `` -> İlk Dört adımı:
```
1. [7|3,5,8,2,9,4,15,6]
2. [3,7|5,8,2,9,4,15,6]
3. [3,5,7|8,2,9,4,15,6]
4. [3,5,7,8|2,9,4,15,6]
```
***
## Merge Sort Projesi

``[16,21,11,8,12,22]`` -> Merge Sort
```
1. [16,21,11] - [8,12,22]
2. [16] - [21,11] - [8,12] - [22]
3. [16] - [21] - [11] - [8] - [12] - [22]
4. [16] - [11,21] - [8,12] - [22]
5. [11,16,21] - [8,12,22]
6. [8,11,12,16,21,22]
```
#### Big O Gösterimi
``[8,11,12,16,21,22]`` -> Q(n*logn)
***

## Binary Sort Projesi

``[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]`` dizisinin Binary-Search-Tree aşamalarını yazınız.
```
1) root 3'dir. root'un sağında 5 bulunur. Solunda 1 bulunur.
2) root 1'dir. root'un sağında 8 bulunur. Solunda 0 bulunur.
3) root 8'dir. root'un sağında 9 bulunur. Solu boştur.
4) root 5'dir. root'un sağında 6 bulunur. Solunda 2 bulunur.
5) root 2'dir. root'un sağında 7 bulunur. Solunda 4 bulunur.
```