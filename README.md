Remove loop in Linked List
MediumAccuracy: 27.66%Submissions: 445K+Points: 4
Get Internship at GfG by submitting your Entries in: Data Science Blogathon

banner
Given a linked list of N nodes such that it may contain a loop.

A loop here means that the last node of the linked list is connected to the node at position X(1-based index). If the linked list does not have any loop, X=0.

Remove the loop from the linked list, if it is present, i.e. unlink the last node which is forming the loop.


Example 1:

Input:
N = 3
value[] = {1,3,4}
X = 2
Output: 1
Explanation: The linked list looks like
1 -> 3 -> 4
     ^    |
     |____|    
A loop is present. If you remove it 
successfully, the answer will be 1. 
