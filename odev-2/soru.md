# Soru
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız?
2. Big-O gösterimini yazınız?

## Cevap
1.  Başlangıç: [16,21,11,8,12,22]
    Step One: [16,21,11] - [8,12,22] --> 2 gruba ayrılır.
    Step Two: [11,16,21] - [8,12,22] --> 2 grupta sıralanır.
    Step Three: [8,11,12,16,21,22] --> 2 Grup birleştirilir ve yeniden sıralanır.
2. Big-O: O(n log n)