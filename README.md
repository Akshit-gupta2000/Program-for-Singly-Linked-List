# Singly Linked List
A singly liked list (SLL) has one link per node. It has two parts, one part contains data and other contains address of next node. The structure of a node in a SLL is given as in C:
struct node
{
    int data;
    struct node *next;
};
# Doubly Linked List
Doubly linked list is a complex type of linked list in which a node contains a pointer to the previous as well as the next node in the sequence. Therefore, in a doubly linked list, a node consists of three parts: node data, pointer to the next node in sequence (next pointer) , pointer to the previous node (previous pointer).In c its initialized as:
struct node   
{  
    struct node *prev;   
    int data;  
    struct node *next;   
}   
# Circular Linked List
Circular Linked List is a variation of Linked list in which the first element points to the last element and the last element points to the first element. Both Singly Linked List and Doubly Linked List can be made into a circular linked list.
