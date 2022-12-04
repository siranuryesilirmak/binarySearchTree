# Binary Search Tree

**soru:**
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

**cevap:**

1 --> 7 > 5 => 5 , 7'nin soluna

2 --> 7 > 1 , 5 > 1 => 1 , 5'in soluna

3 --> 7 < 8 => 8 , 7'nin sağına

4 --> 7 > 3 , 5 > 3 , 1 < 3 => 3 , 1'in sağına

5 --> 7 > 6 , 5 < 6 => 6 , 5'in sağına

6 --> 7 > 0 , 5 > 0 , 1 > 0 => 0 , 1'in soluna

7 --> 7 < 9 , 8 < 9 => 9 , 8'in sağına

8 --> 7 > 4 , 5 > 4 , 1 < 4 , 3 < 4 => 4 , 3'ün sağına

9 --> 7 > 2 , 5 > 2 , 1 < 2 , 3 < 2 => 2 , 3'ün soluna yazılır.

