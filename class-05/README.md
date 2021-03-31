# Linked Lists

**Linked Lists:** are basically multiple nodes where every node can lead to the **next** node by pointing at the the **next** node.

There are two types of linked lists, **singly** (where each node points at the next one) and **doubly** (where each node points at the previous one and the next one).

There are three important parameters in linked lists **head** (the first node), **current** (the node that we are currently looking at), and **next** (the next node to the current one).

Accessing singly linked lists can be done by using `while` loop, so for example if we want to check for a value in a linked list we would start at the head since we can't go back and the while loop will check for the value in each loop if the value for the current loop is **null**, then return false since we reached the end of the linked list, if not, then check if the current value equals the value that we are looking for.