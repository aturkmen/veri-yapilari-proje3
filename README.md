
# Binary Search Tree

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız:
- ilk elemanı root olarak al: 7
- sonraki eleman 5 < root (7) sola yerleştir.

--7  
-/  
5
- sonraki eleman 1 < root (7) sola yerleştir.
  - 1 < 5 sola yerleştir.
  
----7  
---/  
--5  
-/  
1
- sonraki eleman 8 > root (7) sağa yerleştir.

----7  
---/-\  
--5---8  
-/  
1
- sonraki eleman 3 < root (7) sola yerleştir.
  - 3 < 5 sola yerleştir.
  - 3 > 1 sağa yerleştir.
  
----7  
---/-\  
--5---8  
-/  
1  
-\  
--3

- sonraki eleman 6 < root (7) sola yerleştir.
-- 6 > 5 sağa yerleştir.
-- 6 < 8 sola yerleştir.

----7  
---/-\  
--5---8  
-/---/  
1---6  
-\  
--3
- sonraki eleman 0 < root (7) sola yerleştir.
  - 0 < 5 sola yerleştir.
  - 0 < 1 sola yerleştir.

------7  
-----/-\  
----5---8  
---/---/  
--1---6  
-/-\  
0---3
- sonraki eleman 9 > root (7) sağa yerleştir.
  - 9 > 8 sağa yerleştir.
  
------7  
-----/-\  
----5---8  
---/---/-\  
--1---6---9  
-/-\  
0---3
- sonraki eleman 4 < root (7) sola yerleştir.
  - 4 < 5 sola yerleştir.
  - 4 > 1 sağa yerleştir.
  - 4 > 3 sağa yerleştir.
  
------7  
-----/-\  
----5---8  
---/---/-\  
--1---6---9  
-/-\  
0---3  
------\  
-------4
- sonraki eleman 2 < root (7) sola yerleştir.
  - 2 < 5 sola yerleştir.
  - 2 > 1 sağa yerleştir.
  - 2 < 3 sola yerleştir.
 
------7  
-----/-\  
----5---8  
---/---/-\  
--1---6---9  
-/-\  
0---3  
----/-\  
---2---4
