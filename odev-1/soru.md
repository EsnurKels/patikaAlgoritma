# Soru
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız?

2. Big-O gösterimini yazınız?

3. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

    a. Average case: Aradığımız sayının ortada olması.

    b. Worst case: Aradığımız sayının sonda olması.

    c. Best case: Aradığımız sayının dizinin en başında olması.



4. [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız?

## Cevap

1.  Step One: [22,27,16,2,18,6] --> Başlangıç durumu

    Step Two: [22,27,16,2,18,6] --> 2

    Step Three: [16,22,27,2,18,6] --> 16 doğru konuma yerleştirildi.

    Step Four: [2,16,22,27,18,6] --> 2 doğru konuma yerleştirildi.

    Step Five: [2,16,18,22,27,6] --> 18 doğru konuma yerleştirildi.

    Step Six: [2,6,16,18,22,27] --> 6 doğru konuma yerleştirildi.

2. Big-O --> O(n^2)

3. Average Case uyar.

4.  Başlangıç: [7,3,5,8,2,9,4,15,6]

    Step One: [2,3,5,8,7,9,4,15,6] --> 2 en küçük, 7 ile yer değiştirir.

    Step Two: [2,3,5,8,7,9,4,15,6] --> 3 en küçük yerinde kalır.

    Step Three: [2,3,4,8,7,9,5,15,6] --> 4 en küçük, 5 ile yer değiştirir.

    Step Four: [2,3,4,5,7,9,8,15,6] --> 5 en küçük, 8 ile yer değiştirir.

    -- Devamı --

    Step Five: [2,3,4,5,6,9,8,15,7] --> 6 en küçük, 7 ile yer değiştirir.

    Step Six: [2,3,4,5,6,7,8,15,9] --> 7 en küçük, 9 ile yer değiştirir.

    Step Seven: [2,3,4,5,6,7,8,15,9] --> 8 en küçük yerinde kalır.

    Step Eigth: [2,3,4,5,6,7,8,9,15] --> 9 en küçük, 15 ile yer değiştirir.