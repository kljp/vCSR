# vCSR
## Virtualized CSR generator
---
This project supports codes for manipulating a vCSR format of graph data \(including CSR format also\).

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
GTX970

---
Compile
-----
make

---
Execute
-----
./vcsr \<\*_mtx\> \[option1\] \[option2\]
    - \[option1\] --virtual \<max\_degree\> : set maximum degree of a vertex
    - \[option2\] --undirected : add reverse edges

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