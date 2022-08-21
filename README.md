# Insertion Sort Projesi

Insertion Sort'da time complexity bütün elemanların üzerinden geçileceği için n olacaktır Big O Notation'ı da buna eşit olur:
    O(n) olarak bu değeri hesaplayabiliriz.
    [22,27,16,2,18,6] bu örnek için Big O Notation değeri O(6) olarak hesaplanabilir.
    Avarage Case'i 3 ya da 4 olarak gösterebiliri.
    Diziyi sıralarsak eğer 18 2. sırada olacaktır. Bu da time complexitymizin O(2) olduğunu gösterir.

[7,3,5,8,2,9,4,15,6] arrayinde 4 değerini arıyorsak eğer, insertion sort ile bütün elemanları sırasıyla kontol etmemiz ve elememiz gerkecektir:
    [7,3,5,8,2,9,4,15,6] 1. adım
    [3,5,8,2,9,4,15,6] 2. adım
    [5,8,2,9,4,15,6] 3. adım
    [8,2,9,4,15,6]  4. adım
    [2,9,4,15,6] 5. adım

# Merge Sort Projesi

[16,21,11,8,12,22] ikinci arrayimizde merge sort yapacaksak eğer time complexitymiz her seferinde arraydeki elemanları ikiye böldüğümüz yani n/2 yaptığımız için logn olacaktır bunu O(logn) olarak gösterebiliriz. Bizim arrayimiz için bu değer O(log6) olacaktır.

    Örnek bir merging süreci şöyle ilerleyebilir:
        [16,21,11,8,12,22] 
    [16,21,11]      [8,12,22]
[16,21][11]             [8] [12,22]
[16] [21] [11]              [8] [12] [22]
[11, 16, 21]                    [8,12,22]
            [8,11,12,16,21,22]

# Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizimizi binary search tree olarak düzenleyecek olursak, bunu şimdilik optimal bir şekilde yapmaya çalışalım, karşımıza şöyle bir şey çıkacaktır;

            5
        3       7   
     2    4    6  8
   1               9

   