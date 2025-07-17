# LINKEDLIST-IMPLEMENTATION
*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: ADI BAIS
*INTERN ID*: CT04DG2170
*DOMAIN*: C PROGRAMMING
*DURATION*: 4 WEEKS
*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:

The provided C program demonstrates a simple and interactive implementation of a singly linked list, allowing users to insert, delete, and traverse elements using a menu-driven interface. This type of data structure is fundamental in computer science, and this program effectively showcases how it works using dynamic memory allocation and pointer manipulation in the C language.

At the heart of the program is a user-defined structure called Node, which contains two members: an int to hold the data and a pointer to the next node in the list. A global pointer head is used to keep track of the first node in the list, and it is initially set to NULL to indicate an empty list.

The insert() function is responsible for adding a new node to the end of the list. It dynamically allocates memory using malloc() and initializes the new node with the given value. If the list is empty (i.e., head is NULL), the new node becomes the head. Otherwise, the function traverses the list to find the last node and links the new node to it. This showcases how linked lists grow dynamically and do not require contiguous memory allocation like arrays.

The deleteNode() function removes a node with a specific value from the list. It handles three main cases: the list is empty, the node to be deleted is the head node, or the node is somewhere in the middle or end. The function carefully adjusts pointers to unlink the node from the list and frees the memory to prevent memory leaks. If the value is not found, it reports that to the user. This function highlights how deletion works in a linked list by changing only the necessary pointers without needing to shift elements.

The traverse() function simply walks through the list from the head to the end, printing out each element followed by an arrow (->) to visually represent the links between nodes. If the list is empty, it informs the user accordingly. This is a helpful way to verify the structure and contents of the list at any point during execution.

The main() function provides a user-friendly interface using a do-while loop that repeatedly shows a menu with four options: Insert, Delete, Traverse, and Exit. Depending on the user’s choice, the corresponding function is called. The input is taken using scanf() for both menu selection and data input, allowing the user to perform multiple operations in one session until they choose to exit.

The program includes basic error handling. For instance, it checks if malloc() returns NULL during insertion and notifies the user if memory allocation fails. It also gracefully handles attempts to delete from or traverse an empty list.

Overall, this singly linked list program is an excellent beginner-level demonstration of dynamic data structures in C. It covers core operations with clear logic and simple input handling, making it ideal for learning how linked lists operate at a low level. With some enhancements—such as inserting at a specific position, reversing the list, or counting nodes—it can be expanded into a more powerful data structure utility

*OUTPUT*:
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/9253f9fd-84a3-4fce-8211-0d14128b9da9" />
