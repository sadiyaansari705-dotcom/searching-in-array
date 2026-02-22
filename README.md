Count Nodes in a Singly Linked List (C Program)

This project contains a simple C program that demonstrates how to create and traverse a singly linked list and count the total number of nodes.

🧾 Program Description

This program:

Defines a Node structure with:

data (integer)

next pointer

Dynamically allocates memory for 3 nodes using malloc()

Links the nodes together

Traverses the linked list

Counts and prints the total number of nodes

🧠 Concepts Used

Structures in C

Pointers

Dynamic memory allocation (malloc)

Linked List

Traversal using while loop

💻 How the Program Works

Memory is allocated for 3 nodes.

Nodes are linked sequentially.

A temporary pointer is used to traverse the list.

The loop runs until NULL is reached.

The counter increments for each node.

The total node count is displayed.

🚀 How to Run
🔹 Compile the Program
gcc filename.c -o output
🔹 Run the Program
./output

(For Windows)

output.exe
📤 Sample Output
Total nodes = 3
📂 Project Structure
📁 linked-list-node-count
 ├── main.c
 └── README.md
⚠️ Note

This example manually creates 3 nodes.

Data values are not assigned in this program.

Memory is not freed using free() (can be added for better practice).

🔧 Possible Improvements

Take node values as user input

Create nodes dynamically using loops

Add proper memory deallocation using free()

Implement insertion and deletion operations

👨‍💻 Author

⭐ A more advanced version with user input

⭐ Version with proper memory deallocation
