# Append-an-element-in-linked-list
Linked List : Append

 

Write a C program to append a node to the Linked List.

 

Define a structure

struct node

{

int data;

struct node * link;

}

 

Include functions

append --- to add data at the end of the linked list.

display --- to display all the data in the linked list.

 

Refer function specifications for further details.

[Note: The stmt. 'Elements in the linked list are' should be in the main function.

 

Input and Output Format:

Refer sample input and output for formatting specifications.

 

Sample Input and Output:

[All text in bold corresponds to input and the rest corresponds to output.]

 

Enter the value

10

Do you want to add another node? Type Yes/No

Yes

Enter the value

17

Do you want to add another node? Type Yes/No

Yes

Enter the value

11

Do you want to add another node? Type Yes/No

Yes

Enter the value

28

Do you want to add another node? Type Yes/No

No

The elements in the linked list are 10 17 11 28

 

Function Definitions:
void append (struct node **, int )
void display (struct node *)
