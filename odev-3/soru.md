# Soru
1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız?

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap
1.  Başlangıç: [7,5,1,8,3,6,0,9,4,2]
    Root : 7
    Step One: '7' Root Yerleştirildi.
    Step Two: 5, 7'den küçük solun yerleşir.
    Step Three: 1, 5'den küçük solun yerleşir.
    Step Four: 8, 5'den büyük sağına yerleşir.
    Step Five: 3, 1'den büyük. 1'in sağın yerlşir.
    Step Six: 6, 3'den büyük sağına yerleşir.
    Step Seven: 0, 3'den küçük solun yerleşir.
    Step Eight: 9, 8'den büyük sağına yerleşir.
    Step Ten: 4, 6'dan küçük solun yerleşir.
    Step Eleven: 2, 4'den küçük solun yerleşir.


    Binary Search Tree
    --

                7
               / \
              5   8
             /   / \
            1   8   9
             \     /
              3   9
             / \
            0   6
               /
              4
             /
            2
