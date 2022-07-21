# Merge Sort Çözüm

### [16,21,11,8,12,22] Dizinin merge sort türünde aşamaları;

Dizi tek elemana kadar 2'li gruplara bölünerek ilerlenir(Orjinal dizilim ile ilerlenmiştir). Tek eleman kalıncaya kadar bölüm işlemi devam eder. Bölme işlemi tamamlandıktan sonra dizi kendi aralarında sıralanarak aynı şekilde birleştirilir. Bu işlem sıralanmış dizi elde edene kadar aşağıdaki gibi devam eder.

1. [16,21,11,8,12,22]

2. [16,21,11] || [8,12,22]

3. [16] | [21,11] || [8,12] [22]

4. [16] | [21] | [11] || [8] | [12] | [22]

5. [16] | [11,21] || [8,12] [22]

6. [11,16,21] || [8,12,22]

7. [8,11,12,16,21,22]


### [16,21,11,8,12,22] Dizinin Big-O gösterimi;

Merge sort için time complexity her koşul için nlogn şeklindedir. Bundan dolayı Big-O gösterimi O(nlogn) şeklindedir. Bizim dizimiz için bu değer =(6*log6)'dır.

www.patika.dev