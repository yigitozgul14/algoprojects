Verilen dizi [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] için Binary Search Tree (BST) oluşturulması ve aşamaları şu şekildedir:

Aşama 1: Dizinin ilk elemanı olan 7, BST'nin kök düğümüdür.
BST: [7]

Aşama 2: 5, 7'nin sol çocuğu olacaktır çünkü 5, 7'den küçüktür.
BST:

markdown
Copy code
    7
   /
  5
Aşama 3: 1, 7'nin solundaki 5'in sol çocuğu olacaktır çünkü 1, 5'ten küçüktür.
BST:

markdown
Copy code
    7
   /
  5
 /
1
Aşama 4: 8, 7'nin sağ çocuğu olacaktır çünkü 8, 7'den büyüktür.
BST:

markdown
Copy code
    7
   / \
  5   8
 / 
1
Aşama 5: 3, 5'in sağ çocuğu olacaktır çünkü 3, 5'ten büyüktür.
BST:

markdown
Copy code
    7
   / \
  5   8
 / \
1   3
Aşama 6: 6, 5'in sağındaki 3'ün sol çocuğu olacaktır çünkü 6, 3'ten büyüktür.
BST:

markdown
Copy code
    7
   / \
  5   8
 / \
1   3
     \
      6
Aşama 7: 0, 1'in sol çocuğu olacaktır çünkü 0, 1'den küçüktür.
BST:

markdown
Copy code
    7
   / \
  5   8
 / \
1   3
   / \
  0   6
Aşama 8: 9, 8'in sağ çocuğu olacaktır çünkü 9, 8'den büyüktür.
BST:

markdown
Copy code
    7
   / \
  5   8
 / \   \
1   3   9
   / \
  0   6
Aşama 9: 4, 3'ün sağ çocuğu olacaktır çünkü 4, 3'ten büyüktür.
BST:

markdown
Copy code
    7
   / \
  5   8
 / \   \
1   3   9
   / \
  0   6
     /
    4
Aşama 10: 2, 3'ün sol çocuğu olacaktır çünkü 2, 3'ten küçüktür.
BST:

markdown
Copy code
    7
   / \
  5   8
 / \   \
1   3   9
   / \
  0   6
 / 
