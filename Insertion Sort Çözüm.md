# Insertion Sort Çözüm

[22,27,16,2,18,6] -> Insertion Sort

## Dizinin sort türüne göre aşamalar;

1.Adım [2|,27,16,22,18,6] // 2, 22 ile yer değiştirlerek dizinin en başına alınır(ilk haline n denirse, bu adım n-1 olacaktır).

2.Adım [2,6|,16,22,18,27] // 6, 27 ile yer değiştirlerek dizinin ikinci sırasına alınır(n-2).

3.Adım [2,6,16|,18,22,27] // 16 yerinde olduğu için dokunulmaz ve 18, 22 ile yer değiştirilerek sıralı dizi elde edilir ve işlem tamamlanır(n-3).

## Dizinin Big-O gösterimi 

Worst Case:O(n²)

Avarage Case: Worst case ve best case senaryolarının ortalaması alındığında O(n²) olarak bulunur.

Best Case:O(n)

## Time Complexity

Dizimiz bu hali avarage case'dir.

Worst Case: [27,22,18,16,6,2]

Best Case: [2,6,16,18,22,27]

## 18 Sayısının case kapsamı

Dizinin sıralanmış hali [2,6,16,18,22,27] şeklindedir. Bu durumda 18 sayısı ortada yer alır ve avarage case olarak adlandırılır.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

[2|,3,5,8,7,9,4,15,6] n-1

[2,3|,5,8,7,9,4,15,6] n-2

[2,3,4|,8,7,9,5,15,6] n-3

[2,3,4,5|,7,9,8,15,6] n-4

www.patika.dev
