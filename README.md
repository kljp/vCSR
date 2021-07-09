# vCSR
## Virtualized CSR Generator
---
This project supports codes for manipulating a vCSR format of graph data \(CSR format is also available\).

---
Tested operating system
-----
Ubuntu 18.04.5 LTS

---
Tested software
-----
g++ 7.5.0

---
Tested hardware
-----
Intel(R) Xeon(R) CPU E3-1231 v3 @ 3.40GHz

---
Compile
-----
make

---
Execute
-----
./vcsr --input \<\*_mtx\> \[option1\] \[option2\] \[option3\] \[option4\]
- \[option1\]: --virtual \<max\_degree\> 
    - set maximum degree of a vertex to \<max\_degree\>
- \[option2\]: --undirected
    - add reverse edges
- \[option3\]: --sorted
    - sort intra-neighbor lists
- \[option4\]: --verylarge
    - set data type of vertices and edges to 'long long', default='int'

---
Code specification
-----
__vCSR implementation:__
- vcsr.cpp: generate CSR
    - Graph source: https://sparse.tamu.edu/

__Header Provided by https://github.com/iHeartGraph/Enterprise/:__
- wtime.h: get current time for measuring the consumed time

---
Contact
-----
If you have any questions about this project, contact me by one of the followings:
- slashxp@naver.com
- kljp@ajou.ac.kr