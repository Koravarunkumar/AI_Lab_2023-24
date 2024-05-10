# Ex.No: 6   Logic Programming – Factorial of number   
### DATE:                                                                            
### REGISTER NUMBER : 212221060299
### AIM: 
To  write  a logic program  to solve Towers of Hanoi problem  using SWI-PROLOG. 
### Algorithm:
1. Start the program
2.  Write a rules for finding solution of Towers of Hanoi in SWI-PROLOG.
3.  a )	If only one disk  => Move disk from X to Y.
4.  b)	If Number of disk greater than 0 then
5.        i)	Move  N-1 disks from X to Z.
6.        ii)	Move  Nth disk from X to Y
7.        iii)	Move  N-1 disks from Y to X.
8. Run the program  to find answer of  query.

### Program:
Program:
move(1,X,Y,) :-
write('Move top disk from '), write(X), write(' to '), write(Y), nl. move(N,X,Y,Z) :- N>1, M is N-1, move(M,X,Z,Y), move(1,X,Y,), move(M,Z,Y,X).


### Output:

![316235230-aa53abcb-161a-4239-9c44-cf4c09bdb009](https://github.com/Koravarunkumar/AI_Lab_2023-24/assets/164622370/f1798e75-3547-4282-a844-3f199bc7ad73)




### Result:
Thus the solution of Towers of Hanoi problem was found by logic programming.
