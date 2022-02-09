# migneco.1
Project 1 cs4760

1. Calling the program with 1 yields 1 process with child id 0
   Calling the program with 2 yields 2 processes, both parent and child increment by 1
   Calling the program with 4 yields similare results to 2, but with 4 processes
   Calling the program with 16 increments the child ID, but parent ID occasionally takes value 1
   Calling the program with 64 increments the child ID, but parent ID occasionally takes value 1

2.

   PID: 9549 --> PID:1 --> PID:32078 --> PID:32079

3.
   Calling program with 20 has program 5/20 adopted by init
   Calling program with 40 has program 11/40 adopted by init
   Calling program with 60 has program 20/60 adopted by init
   Calling program with 80 has program 21/80 adopted by init
   Calling program with 99 has program 26/99 adopted by init
   
   On average, the program seems to be adopted by init approximately around 25% of the time
   
4.
   Calling program with 20 has program /20 adopted by init
   Calling program with 40 has program /40 adopted by init
   Calling program with 60 has program /60 adopted by init
   Calling program with 80 has program /80 adopted by init
   Calling program with 99 has program /99 adopted by init
   
   On average, the program seems to be adopted by init approximately around % of the time
   
