# Patika.dev Linkim
https://app.patika.dev/elifnazliboke

# Binary Search Tree Projesi

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Root 7'dir. 5<7 olduğundan 5, root'un solunda bulunur.

		 7
		/
           5
					 
					 
1<7 olduğundan 1, root'un soluna gider. 1<5 olduğu için de 1, 5'in soluna gider.

		  7
		 /
            5
           /
          1
					
					
8>7 olduğundan 8, root'un sağına gider.

		   7
		 /   \
            5     8
           /
          1
					
					
3<7 olduğundan 3, root'un soluna gider. 3<5 olduğundan 3, 5'in sağına gider. 3>1 olduğu için de 3, 1'in sağına gider.

		   7
		 /   \
            5     8
           /
          1
	       \
	        3
					

6<7 olduğundan 6, root'un soluna gider. 6>5 olduğundan 6, 5'in sağına gider.

		   7
		 /   \
            5     8
           / \
          1   6
	       \
	        3
					
					
0<7 olduğundan 0, root'un soluna gider. 0<5 olduğundan 0, 5'in soluna gider. 0<1 olduğun için de 0, 1'in soluna gider.

		   7
		 /   \
            5     8
           / \
          1   6
	     / \
	    0   3
					
