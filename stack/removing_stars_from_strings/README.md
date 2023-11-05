# Intuition

In approaching this problem, let's start by considering how we can construct an algorithm that removes letters based on the number of stars we are moving.

We begin by traversing the string. For each character encountered, we append it to the stack. When we come across a star, we want to remove a character from the stack.

Since a stack follows the Last-In, First-Out (LIFO) principle, this allows us to efficiently keep track of the last element added. Therefore, when we encounter a star, we can pop the top element from the stack.

After processing all the characters, we return the elements in the stack as a string, which will give us the desired output. The use of a stack in this approach simplifies the process of tracking and modifying the output based on the number of stars encountered.
