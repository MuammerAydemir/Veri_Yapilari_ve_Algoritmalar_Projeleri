# Veri_Yapilari_ve_Algoritmalar_Projeleri
Selection Sort Projesi, Merge Sort Projesi ve Binary Sort Projesleri

## Selection Sort Projesi

``[22,27,16,2,18,6]`` -> Insertion Sort

* [22|27,16,2,18,6] 1.Aşama
* [22,27|16,2,18,6] 2.Aşama 
* [16,22,27|2,18,6] 3.Aşama
* [2,16,22,27|18,6] 4.Aşama
* [2,16,18,22,27|6] 5.Aşama
* [2,6,16,18,22,27|] 6.Aşama 

### Big O Gösterimi
``[2,6,16,18,22,27]`` -> Q(n^2)

### Time Complexity

Seçilen sayı = 18
Avarage case kapsamına girer.

#### Diğer Sıralama
``[7,3,5,8,2,9,4,15,6] `` -> İlk Dört adımı:

* [7|3,5,8,2,9,4,15,6]
* [3,7|5,8,2,9,4,15,6]
* [3,5,7|8,2,9,4,15,6]
* [3,5,7,8|2,9,4,15,6]

