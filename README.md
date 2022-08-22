
# Algoritma-Odev

Patika.dev Frontend Eğitimi serisinde Insertion Sort, Merge Sort ve Binary Search Tree Ödevleri Toplu Hali

## Proje-1 Insertion Sort

```

Ödev İçeriği

[22,27,16,2,18,6] -> Insertion Sort
1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2- Big-O gösterimini yazınız.
3- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
(Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.)
4- [7,3,5,8,2,9,4,15,6**] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
### 1)
```
- 1.Adım [2,27,16,22,18,6]

- 2.Adım [2,6,16,22,18,27]

- 3.Adım [2,6,16,18,22,27]
```
### 2)
```
Big-0 -> 0(n^2)
```
### 3)
```
[2,6,16,18,22,27]
- 18 Sayısı Average case olur.
```
### 4)
```
- 1.Adım [2,3,5,8,7,9,4,15,6] 
- 2.Adım [2,3,4,8,7,9,5,15,6] 
- 3.Adım [2,3,4,5,7,9,8,15,6] 
- 4.Adım [2,3,4,5,6,9,8,15,7] 
```
 
## Proje-2 Merge Sort Sort

```

Ödev İçeriği

[16,21,11,8,12,22] -> Merge Sort

1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2- Big-O gösterimini yazınız.

```
### 1)
```
1- [16,21,11] - [8,12,22]
2- [16] , [21,11] - [8] , [12,22]
3- [16] , [11,21] - [8] , [12,22]
4- [11,16,21] - [8,12,22]
5- [8,11,12,16,21,22]
```

### 2)
```
O(nlogn) -> O(6log6)
```


## Proje-23 Binary Search Tree Projesi

```

Ödev İçeriği

1- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

```

### 1)
```
- Root 7'dir. 
- 5 < 7 soluna gider.
- 1 < 7 soluna koyacağız fakat 1 < 5 olduğundan onunda soluna gider.
- 8 > 7 sağına koyuyoruz. 
- 3 < 7 sol, 3 < 5 sol, fakat 3 > 1 olduğundan 1'in sağına koyuyoruz.
- 6 < 7 sol ve 6 > 5 olduğundan 5'in sağına koyuyoruz.
- 0 < 7 sol,  0 < 5 sol, 0 < 1 olduğundan 1'in soluna koyuyoruz.
- 9 > 7 sağ, 9 > 8 olduğundan 8'in sağına koyuyoruz.
- 4 < 7 sol, 4 < 5 sol, 4 > 1 sağ ve 4 > 3 olduğundan 3'ün sağına koyuyoruz.
- 2 < 7 sol, 2 < 5 sol, 2 > 1 sağ, 2 < 3 olduğundan 3'ün soluna koyuyoruz.
```
