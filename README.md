# Biggest-Number-Formation
A cpp program to make largest number from given numbers we are provided with an array of numbers. 

The basic approach for this can be done using stacks, but here we can also arrange the same by using the sorting techniques and swapping methods. Although it can be time taking but it is very helpful for those who avoid doing this using stacks or linked list. We need to arrange them in a way that results the largest value that can be formed. Input Format: First line contains integer T which is number of test case. For each test case, it contains an integer n which is the size of array A[] and next line contains n space separated integers A[i] .  

Constraints: 1&lt;=t&lt;=100 ;1&lt;=m&lt;=100 ;1&lt;=A[i]&lt;=10^5;  

Output Format: Print the largest value. 

Sample Input:  1  4  54 546 548 60  

Sample Output : 6054854654 

Approach to solve the problem : - 1.We will find the largest digit among the elements which is at the end position. 2. We will swap the found element having the largest digit in its front with the first element 3.By fixing the first element we will sort the rest of the arrays in decreasing order. And then make the rearranged decreased elements followed by the first element. 

CONCEPT USED : 1. Swapping concept 2.Sorting 
