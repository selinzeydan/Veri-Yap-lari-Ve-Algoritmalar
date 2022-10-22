# Binary Search Tree Projesi

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root belirlenir. Roottan küçük olanlar sol tarafta büyük olanlar sağ tarafta toplanır.

1.adım: Root:7

2.adım: 5, 7'den küçüktür. 7'nin soluna eklenir.                

             7 
            /
           5
    
3.adım:  1, 5 ve 7'den küçüktür. 5'in soluna eklenir.

             7
            / 
           5
          /
         1
         
4.adım: 8, 7'den büyüktür. 7'nin sağına eklenir.

               7
              / \
             5   8
            /
          1
          
5.adım: 3, 5 ve 7'den küçük olduğundan 5'in soluna, 1'den büyük olduğundan 1'in sağına eklenir. 

              7
             / \
            5   8
           /
          1
           \
             3
            
6.adım: 6, 7'den küçük olduğundan 7'nin soluna, 5'ten büyük olduğundan 5'in sağına eklenir.

               7
              / \
             5   8
            / \
           1   6
           \
             3
            
7.adım: 0; 7, 5 ve 1'den küçüktür. 1'in soluna eklenir.

               7
              / \
             5   8
            / \
           1   6
          / \
         0   3
        
8.adım: 9, 7 ve 8'den büyüktür. 8'in sağına eklenir. 

                7
               / \
              5   8
             / \    \
            1   6    9
           / \
          0   3
         
9.adım: 4, 7 ve 5'ten küçük olduğundan 5'in soluna, 1 ve 3'ten büyük olduğundan 3'ün sağına eklenir.
         
                 7
                / \
               5    8
              / \     \
             1   6     9
            / \
           0   3
                \
                 4
                
10 .adım: 2, 7 ve 5'ten büyük olduğundan 5'in soluna, 1'den büyük olduğundan 1'in sağına ve 3'ten küçük olduğundan 3'in soluna eklenir.

                   7
                  / \
                 5   8
                / \    \
               1   6    9
              / \
             0   3
                 / \
                2    4
                
