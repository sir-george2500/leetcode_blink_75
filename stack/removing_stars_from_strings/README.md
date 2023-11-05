# Intuition

In approaching this problem, let's start by considering how we can construct an algorithm that removes letters based on the number of stars we are moving.

We begin by traversing the string. For each character encountered, we append it to the stack. When we come across a star, we want to remove a character from the stack.

Since a stack follows the Last-In, First-Out (LIFO) principle, this allows us to efficiently keep track of the last element added. Therefore, when we encounter a star, we can pop the top element from the stack.

After processing all the characters, we return the elements in the stack as a string, which will give us the desired output. The use of a stack in this approach simplifies the process of tracking and modifying the output based on the number of stars encountered.


# Time Complexity 
Since we have to go over every  element in the string  the time compleity for such algo is 0(n)

and since the to total time complexity for stack O(1) for append and pop 

our algorithm will run in 0(n) time 


Space Complexity assumming we have O(n) string we will have to use a space of O(n)
