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
   Program now takes significantly longer to run

   Calling program with 20 has program 6/20 adopted by init
      Also of note, process 20 finished before process 19
   
   Calling program with 40 has program /40 adopted by init
      Program would not run more than 28 processes, but 8/28 adopted
   
   Calling program with 60 has program /60 adopted by init
      Program would not run more than 28 processes, but 17/28 adopted
   
   Calling program with 80 has program /80 adopted by init
      Program would not run more than 28 processes, but 13/28 adopted
   
   Calling program with 99 has program /99 adopted by init
      Program would not run more than 28 processes, but 10/28 adopted
   
   On average, the program seems to be adopted by init approximately more than 50% of the time, but code would not run for more than 28 processes
   
5.
   Calling with 1 2 3 leads to one process being printed twice with the same values printed for each
   Calling with 1 5 10 causes program to take a long time to print each line, but each line is a copy
   Calling with 2 5 1 causes two processes to be printed 5 times
   Calling with 10 6 1 leads program to print 10 processes 6 times, but they do not print in the same order each time
   
6.
   Adding wait system call before final fprint f leads to each i value being printed together k times
   Calling with n=100 still only yields 28 processes
   
7.
   Program run with values 5 6 1 respectively, when program is called, all processes are grouped together, but are still copies of each still
