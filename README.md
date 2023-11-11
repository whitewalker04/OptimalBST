# OptimalBST
This program create the optimal binary search tree for the given ordered keys and the number of times each key is searched.
The program is written using C++ language.

# INPUTS
Read a txt file as the first line will have the nnumber of elements (integer). Thereafter each line represents the number of times each element is searched (integer, this can be treated as probability).

5
10
30
20
20
40

# OUTPUT
The program will output the dynamic programming table (both values and roots).
It should also output a optimal binary search tree (see below).

Dynamic Programming Table representing cost(C[i][j]): 
000    010    050    090    150    250    
000    000    030    070    120    220    
000    000    000    020    060    140    
000    000    000    000    020    080    
000    000    000    000    000    040    
000    000    000    000    000    000    



Dynamic Programming Table representing roots(R[i][j]): 
00    01    02    02    02    03    
00    00    02    02    03    03    
00    00    00    03    03    04    
00    00    00    00    04    05    
00    00    00    00    00    05    
00    00    00    00    00    00    

Optimal Binary Search Tree: 
3
    2
        1
            -
            -
        -
    5
        4
            -
            -
        -





